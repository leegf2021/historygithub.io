<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<meta name="description" content="你最像历史上的谁的投影？15 道题，5 种历史人格投影，每题附一条可核对的史料注。原创自评，非专业测评。">
<title>你最像历史上的谁的投影？</title>
<style>
:root{
  --bg:#f4efe3;
  --bg2:#faf7ee;
  --card:#fffdf8;
  --ink:#211e19;
  --ink2:#544d43;
  --ink3:#93897b;
  --line:#e5ddcd;
  --line2:#efe8da;
  --accent:#b23a2e;
  --accent-soft:#f7e7e2;
  --soft:#f8f4ea;
  --r:18px;
  --shadow:0 16px 38px -22px rgba(70,55,35,.45);
  --maxw:1080px;
  --serif:"Songti SC","STSong","Noto Serif SC","Source Han Serif SC","SimSun",Georgia,serif;
}
*{box-sizing:border-box;-webkit-tap-highlight-color:transparent}
html{-webkit-text-size-adjust:100%}
body{
  margin:0;background-color:var(--bg);color:var(--ink);
  background-image:radial-gradient(1100px 520px at 50% -180px,#fdfbf5 0%,rgba(253,251,245,0) 72%);
  font-family:-apple-system,BlinkMacSystemFont,"PingFang SC","Hiragino Sans GB","Microsoft YaHei",system-ui,"Segoe UI",sans-serif;
  font-size:16px;line-height:1.75;-webkit-font-smoothing:antialiased;
}
img,svg{max-width:100%;display:block}
button{font-family:inherit;font-size:inherit;color:inherit}
h1,h2,h3,h4{margin:0;letter-spacing:-.01em;line-height:1.3;font-family:var(--serif)}
p{margin:0}
.wrap{max-width:var(--maxw);margin:0 auto;padding:0 20px}

.page{display:none}
.page.active{display:block}

/* ============ 首页（居中单列 · 无插画） ============ */
#page-home{min-height:100dvh;padding:48px 0 44px;display:none}
#page-home.active{display:flex;flex-direction:column;justify-content:center}
.home-copy{width:100%;max-width:640px;margin:0 auto;text-align:center}
.home-copy .kicker{
  display:inline-block;font-size:12.5px;font-weight:700;color:var(--accent);
  background:var(--accent-soft);border-radius:999px;padding:7px 17px;letter-spacing:.2em;
}
.home-copy h1{font-size:34px;font-weight:800;margin:24px 0 0;letter-spacing:.01em;line-height:1.42}
.home-copy h1 em{font-style:normal;color:var(--accent)}
.home-copy .lead{font-size:15.5px;color:var(--ink2);line-height:2.05}
.home-copy .lead b{color:var(--ink);font-weight:600}

.home-rule{display:flex;align-items:center;justify-content:center;gap:11px;margin:26px 0 22px}
.home-rule i{display:block;width:48px;height:1px;background:var(--line)}
.home-rule b{display:block;width:6px;height:6px;border-radius:1px;background:var(--accent);
  opacity:.6;transform:rotate(45deg)}

.facts{display:flex;flex-wrap:wrap;gap:9px;margin:26px 0 0;justify-content:center}
.fact{font-size:13px;color:var(--ink2);background:var(--card);border:1px solid var(--line);border-radius:999px;padding:7px 14px}
.fact b{color:var(--ink);font-weight:700}

.preview{margin-top:30px}
.preview .cap{font-size:11.5px;font-weight:800;letter-spacing:.16em;color:var(--ink3);margin-bottom:12px}
.seals{display:flex;flex-wrap:wrap;gap:9px;justify-content:center}
.seal-chip{display:flex;align-items:center;gap:8px;background:var(--card);border:1px solid var(--line);
  border-radius:12px;padding:7px 12px 7px 8px;font-size:13px;color:var(--ink2)}
.seal-chip i{width:24px;height:24px;border-radius:7px;display:flex;align-items:center;justify-content:center;
  font-family:var(--serif);font-size:14px;font-weight:700;color:#fff;font-style:normal;flex:none}

.cta{display:flex;justify-content:center;margin-top:34px}
.cta .btn{padding:16px 56px;font-size:16.5px;letter-spacing:.08em;border-radius:15px;
  box-shadow:0 16px 32px -16px rgba(33,30,25,.7)}
.home-foot{margin:24px 0 0;font-size:12px;color:var(--ink3);letter-spacing:.06em}
.btn{
  border:none;border-radius:14px;padding:15px 30px;font-size:16px;font-weight:700;
  background:var(--ink);color:#fff;cursor:pointer;letter-spacing:.02em;
  transition:transform .15s ease,opacity .15s ease,box-shadow .15s ease;
  min-height:52px;display:inline-flex;align-items:center;justify-content:center;
}
.btn:hover{opacity:.9}
.btn:active{transform:scale(.975)}
.btn:focus-visible{outline:3px solid var(--accent);outline-offset:2px}
.btn.ghost{background:var(--card);color:var(--ink);border:1.5px solid var(--line)}
.btn.ghost:hover{border-color:var(--ink3)}
.btn:disabled{opacity:.35;cursor:not-allowed;transform:none}

/* ============ 答题页 ============ */
#page-quiz.active{display:flex;flex-direction:column;min-height:100dvh}
.qz-head{position:sticky;top:0;z-index:20;background:rgba(244,239,227,.95);backdrop-filter:blur(10px);
  padding:14px 0 10px;border-bottom:1px solid var(--line2)}
.qz-row{display:flex;justify-content:space-between;align-items:center;gap:12px;margin-bottom:10px}
.qz-row .ttl{font-size:13px;font-weight:700;color:var(--ink2);letter-spacing:.04em;font-family:var(--serif)}
.qz-row .cnt{font-size:12.5px;color:var(--ink3);font-variant-numeric:tabular-nums;white-space:nowrap}
.bar{height:4px;border-radius:3px;background:var(--line);overflow:hidden}
.bar i{display:block;height:100%;width:0;border-radius:3px;background:var(--accent);
  transition:width .38s cubic-bezier(.4,0,.2,1)}

.dots{display:flex;flex-wrap:wrap;gap:4px;margin-top:11px}
.dot{width:20px;height:20px;border-radius:6px;border:1.5px solid var(--line);background:var(--card);
  font-size:10.5px;font-weight:700;color:var(--ink3);cursor:pointer;padding:0;
  display:flex;align-items:center;justify-content:center;transition:all .18s}
.dot:hover{border-color:var(--ink3)}
.dot.done{background:#f2e6dd;border-color:#e0cec1;color:var(--ink2)}
.dot.cur{background:var(--ink);border-color:var(--ink);color:#fff}

.qz-main{flex:1;padding:26px 0 20px}
.qz-tag{display:inline-block;font-size:12px;font-weight:700;color:#fff;background:var(--accent);
  border-radius:8px;padding:5px 13px;letter-spacing:.08em;font-family:var(--serif)}
.qz-q{font-size:21px;font-weight:700;line-height:1.6;margin:16px 0 22px;letter-spacing:.01em}
.opts{display:flex;flex-direction:column;gap:11px}
.opt{
  display:flex;align-items:flex-start;gap:13px;width:100%;text-align:left;
  background:var(--card);border:1.5px solid var(--line);border-radius:15px;
  padding:15px 17px;font-size:15.5px;line-height:1.65;cursor:pointer;
  transition:border-color .18s,background .18s,transform .12s;
}
.opt:hover{border-color:#d9cdba}
.opt:active{transform:scale(.99)}
.opt:focus-visible{outline:3px solid var(--accent);outline-offset:2px}
.opt .mk{flex:none;width:24px;height:24px;border-radius:50%;border:1.5px solid #d3c9b7;
  font-size:12px;font-weight:700;color:var(--ink3);display:flex;align-items:center;justify-content:center;margin-top:2px;
  transition:all .18s}
.opt.sel{border-color:var(--accent);background:#fdf4f1}
.opt.sel .mk{background:var(--accent);border-color:var(--accent);color:#fff}
.opt .tx{flex:1}

.note{margin-top:18px;background:var(--soft);border:1px solid var(--line);border-left:4px solid var(--accent);
  border-radius:12px;padding:15px 18px;display:none}
.note.on{display:block;animation:fadeUp .32s ease}
.note b{display:block;font-size:11px;letter-spacing:.18em;color:var(--accent);font-weight:800;margin-bottom:7px}
.note p{font-size:13.5px;line-height:1.85;color:var(--ink2);font-family:var(--serif)}
@keyframes fadeUp{from{opacity:0;transform:translateY(6px)}to{opacity:1;transform:none}}

.shake{animation:shake .4s ease}
@keyframes shake{
  0%,100%{transform:translateX(0)}
  20%{transform:translateX(-7px)}
  40%{transform:translateX(6px)}
  60%{transform:translateX(-4px)}
  80%{transform:translateX(3px)}
}

.qz-foot{position:sticky;bottom:0;z-index:20;background:rgba(244,239,227,.95);backdrop-filter:blur(10px);
  border-top:1px solid var(--line2);padding:14px 0 calc(14px + env(safe-area-inset-bottom))}
.qz-foot .wrap{display:flex;gap:12px;align-items:center}
.qz-foot .btn{flex:1}
.qz-foot .back{flex:0 0 104px;white-space:nowrap}
@media(max-width:420px){.qz-foot .back{flex:0 0 92px;white-space:nowrap;font-size:14px;padding-left:10px;padding-right:10px}}

/* ============ 结果页 ============ */
#page-result{padding:0 0 64px}
.res-hero{position:relative;overflow:hidden;padding:38px 0 34px;color:#fff}
.res-hero .blob{position:absolute;width:280px;height:280px;border-radius:50%;
  background:rgba(255,255,255,.09);right:-100px;top:-110px}
.res-hero .blob2{position:absolute;width:160px;height:160px;border-radius:50%;
  background:rgba(255,255,255,.07);left:-70px;bottom:-80px}
.res-hero .wrap{position:relative}
.res-seal{position:absolute;right:0;top:4px;width:62px;height:62px;border:2px solid rgba(255,255,255,.72);
  border-radius:12px;display:flex;align-items:center;justify-content:center;
  font-family:var(--serif);font-size:29px;font-weight:700;color:#fff;opacity:.92;letter-spacing:0}
.res-ico{width:52px;height:52px;margin-bottom:16px;opacity:.95}
.res-hero .k{font-size:11px;letter-spacing:.26em;opacity:.86;font-weight:600;margin-bottom:14px}
.res-hero .fill{display:inline-block;font-size:12.5px;font-weight:800;background:rgba(255,255,255,.95);
  border-radius:8px;padding:5px 13px;margin-bottom:14px;letter-spacing:.06em}
.res-hero h1{font-size:30px;font-weight:800;letter-spacing:.01em;line-height:1.35;max-width:520px}
.res-hero .quote{font-size:15.5px;line-height:1.85;opacity:.95;margin-top:14px;max-width:620px;font-family:var(--serif)}

.res-body{padding-top:0}
.blk{background:var(--card);border:1px solid var(--line);border-radius:var(--r);padding:24px 24px;margin-top:16px}
.blk > h3{font-size:13px;font-weight:800;letter-spacing:.16em;color:var(--accent);margin-bottom:16px}

.vs{display:grid;grid-template-columns:1fr;gap:10px;margin-top:-34px;position:relative;z-index:2}
.vs .cell{background:var(--card);border:1px solid var(--line);border-radius:15px;padding:15px 17px;box-shadow:0 10px 26px -20px rgba(70,55,35,.5)}
.vs .cell b{display:block;font-size:10.5px;letter-spacing:.14em;color:var(--ink3);font-weight:800;margin-bottom:5px}
.vs .cell span{font-size:14.5px;color:var(--ink2);line-height:1.7}
.vs .cell.truth{background:#fffdf5;border-color:#e8dcc6}
.vs .cell.truth span{color:var(--ink);font-weight:600}

.bars{display:flex;flex-direction:column;gap:13px}
.brow .bl{display:flex;justify-content:space-between;align-items:baseline;font-size:13.5px;margin-bottom:6px}
.brow .bl b{font-weight:700;font-family:var(--serif)}
.brow .bl span{font-size:12.5px;color:var(--ink3);font-variant-numeric:tabular-nums}
.btrack{height:9px;border-radius:5px;background:var(--line2);overflow:hidden}
.btrack i{display:block;height:100%;border-radius:5px;width:0;transition:width .8s cubic-bezier(.3,0,.2,1)}
.brow.top .bl b{color:var(--accent)}
.combo{margin-top:20px;padding-top:18px;border-top:1px dashed var(--line);font-size:14.5px;color:var(--ink2);line-height:1.9}
.combo b{color:var(--ink);font-weight:700}
.purity{display:inline-block;font-size:11.5px;font-weight:700;color:var(--accent);background:var(--accent-soft);
  border-radius:6px;padding:3px 10px;margin-bottom:10px}

.axes{display:flex;flex-direction:column;gap:20px}
.axis .an{display:flex;justify-content:space-between;align-items:baseline;font-size:13.5px;margin-bottom:9px}
.axis .an b{font-weight:700}
.axis .an span{font-size:12px;color:var(--ink3)}
.ax-track{position:relative;height:26px;border-radius:8px;background:linear-gradient(90deg,var(--line2),#f7f2e6,var(--line2))}
.ax-track::before{content:"";position:absolute;left:50%;top:3px;bottom:3px;width:1px;background:var(--line);opacity:.9}
.ax-track i{position:absolute;top:50%;width:15px;height:15px;border-radius:50%;transform:translate(-50%,-50%);
  border:2.5px solid #fff;box-shadow:0 2px 7px rgba(60,45,30,.3);left:50%;transition:left .7s cubic-bezier(.3,0,.2,1)}
.ax-end{display:flex;justify-content:space-between;font-size:11.5px;color:var(--ink3);margin-top:6px;letter-spacing:.04em}
.axis .tip{font-size:13.5px;color:var(--ink2);line-height:1.8;margin-top:9px}
.axis + .axis{padding-top:4px;border-top:1px dashed var(--line)}

.rows{display:flex;flex-direction:column}
.row{display:flex;gap:14px;padding:14px 0;border-bottom:1px solid var(--line2)}
.row:last-child{border-bottom:none;padding-bottom:0}
.row .lb{flex:none;width:78px;font-size:11.5px;font-weight:800;color:var(--ink3);letter-spacing:.06em;padding-top:4px}
.row .vl{flex:1;font-size:14.5px;line-height:1.85}

.facts-list{counter-reset:f;list-style:none;margin:0;padding:0}
.facts-list li{position:relative;padding:0 0 16px 34px;font-size:14.5px;line-height:1.85;color:var(--ink2)}
.facts-list li:last-child{padding-bottom:0}
.facts-list li::before{counter-increment:f;content:counter(f);
  position:absolute;left:0;top:3px;width:22px;height:22px;border-radius:7px;background:var(--soft);
  border:1px solid var(--line);color:var(--accent);font-size:11.5px;font-weight:800;
  display:flex;align-items:center;justify-content:center}
.facts-list li b{color:var(--ink);font-weight:700}

.adv ol{list-style:none;margin:0;padding:0;counter-reset:adv}
.adv li{position:relative;padding:0 0 18px 40px;font-size:14.5px;line-height:1.85;color:var(--ink2)}
.adv li:last-child{padding-bottom:0}
.adv li::before{
  counter-increment:adv;content:counter(adv);
  position:absolute;left:0;top:1px;width:26px;height:26px;border-radius:9px;
  background:var(--accent-soft);color:var(--accent);font-size:12.5px;font-weight:800;
  display:flex;align-items:center;justify-content:center;
}

.slogan{margin-top:16px;border-radius:var(--r);padding:26px 24px;text-align:center;
  font-size:20px;font-weight:800;line-height:1.6;font-family:var(--serif)}

.rule{margin-top:16px;background:var(--soft);border:1px solid var(--line);border-radius:var(--r);padding:20px 22px}
.rule h3{font-size:12.5px;font-weight:800;letter-spacing:.16em;color:var(--ink2);margin-bottom:12px}
.rule ul{margin:0;padding-left:19px;font-size:13.5px;color:var(--ink2);line-height:1.9}
.rule li::marker{color:var(--accent)}
.rule b{color:var(--ink);font-weight:700}

.acts{display:flex;flex-direction:column;gap:11px;margin-top:22px}
.acts .btn{width:100%}

.disc{margin-top:22px;font-size:12.5px;color:var(--ink3);line-height:1.85;
  background:var(--soft);border:1px solid var(--line);border-radius:14px;padding:16px 18px}
.disc b{color:var(--ink2);font-weight:700}

/* ============ toast & modal ============ */
#toast{position:fixed;left:50%;bottom:104px;transform:translate(-50%,16px);z-index:90;
  background:rgba(33,30,25,.94);color:#fff;font-size:14px;font-weight:600;
  padding:12px 22px;border-radius:12px;opacity:0;pointer-events:none;
  transition:opacity .25s,transform .25s;max-width:88vw;text-align:center}
#toast.on{opacity:1;transform:translate(-50%,0)}

#modal{position:fixed;inset:0;z-index:100;background:rgba(33,30,25,.88);
  display:none;align-items:center;justify-content:center;padding:22px;overflow-y:auto}
#modal.on{display:flex}
#modal .inner{width:100%;max-width:340px;text-align:center;margin:auto}
#modal canvas{width:100%;height:auto;border-radius:16px;display:block;box-shadow:0 24px 60px -16px rgba(0,0,0,.6)}
#modal .tip{color:rgba(255,255,255,.82);font-size:13px;margin-top:16px;line-height:1.7}
#modal .dl{display:inline-block;margin-top:16px;background:#fff;color:#211e19;font-size:14.5px;
  font-weight:700;border-radius:12px;padding:13px 30px;text-decoration:none}
#modal .x{background:none;border:none;color:rgba(255,255,255,.7);font-size:13.5px;
  padding:12px;margin-top:8px;cursor:pointer}

/* ============ desktop ============ */
@media(min-width:880px){
  .home-copy{max-width:700px}
  .home-copy h1{font-size:44px}
  .home-copy .lead{font-size:16px}
  .qz-q{font-size:24px;margin:20px 0 26px}
  .qz-main{padding:38px 0 26px}
  .vs{grid-template-columns:1fr 1fr}
  .res-hero h1{font-size:38px}
  .res-hero .quote{font-size:16.5px}
  .blk{padding:30px 32px}
  .qz-main .wrap,.qz-head .wrap,.qz-foot .wrap{max-width:740px}
  .res-hero .wrap,.res-body .wrap{max-width:780px}
  .acts{flex-direction:row}
  .acts .btn{width:auto;flex:1}
}
</style>
</head>
<body>

<!-- ==================== 首页 ==================== -->
<section id="page-home" class="page active">
  <div class="wrap">
    <div class="home-copy">

      <span class="kicker">历史投影测试</span>

      <h1>你最像历史上的<br><em>谁的投影？</em></h1>

      <div class="home-rule"><i></i><b></b><i></i></div>

      <p class="lead">
        15 道题，问的都是你每天真实会做的选择——从接到一件新任务，到熬夜熬到几点。<br>
        <b>你的答案会投影到 5 种历史人格里的一个。</b><br>
        每题都附一条真实史料注，出处可查。没有标准答案，选你真正会做的那一个，不是你觉得自己「应该做」的那一个。
      </p>

      <div class="facts">
        <span class="fact"><b>15</b> 道题</span>
        <span class="fact"><b>约 4</b> 分钟</span>
        <span class="fact"><b>5</b> 种投影</span>
        <span class="fact">每题附<b>史料注</b></span>
      </div>

      <div class="preview">
        <div class="cap">五 种 投 影</div>
        <div class="seals" id="home-seals"></div>
      </div>

      <div class="cta">
        <button class="btn" id="btn-start">开始测试</button>
      </div>

      <p class="home-foot">原创自评 · 非专业心理诊断</p>

    </div>
  </div>
</section>

<!-- ==================== 答题页 ==================== -->
<section id="page-quiz" class="page">
  <div class="qz-head">
    <div class="wrap">
      <div class="qz-row">
        <span class="ttl">你最像历史上的谁的投影</span>
        <span class="cnt" id="q-count">已答 0 / 15</span>
      </div>
      <div class="bar"><i id="q-bar"></i></div>
      <div class="dots" id="q-dots"></div>
    </div>
  </div>

  <div class="qz-main">
    <div class="wrap">
      <span class="qz-tag" id="q-tag">第 1 问</span>
      <h2 class="qz-q" id="q-text"></h2>
      <div class="opts" id="q-opts"></div>
      <div class="note" id="q-note"><b>史 料 注</b><p id="q-note-text"></p></div>
    </div>
  </div>

  <div class="qz-foot">
    <div class="wrap">
      <button class="btn ghost back" id="btn-prev">上一题</button>
      <button class="btn" id="btn-next">下一题</button>
    </div>
  </div>
</section>

<!-- ==================== 结果页 ==================== -->
<section id="page-result" class="page">
  <div class="res-hero" id="res-hero">
    <div class="blob"></div><div class="blob2"></div>
    <div class="wrap">
      <div class="res-seal" id="res-seal"></div>
      <div class="res-ico" id="res-ico"></div>
      <div class="k" id="res-k">你 的 历 史 投 影</div>
      <div class="fill" id="res-fill"></div>
      <h1 id="res-name"></h1>
      <p class="quote" id="res-quote"></p>
    </div>
  </div>

  <div class="res-body">
    <div class="wrap">

      <div class="vs">
        <div class="cell"><b>别人眼中的你</b><span id="res-illusion"></span></div>
        <div class="cell truth"><b>真实的你</b><span id="res-truth"></span></div>
      </div>

      <div class="blk">
        <h3>成分分析</h3>
        <div class="bars" id="res-bars"></div>
        <div class="combo" id="res-combo"></div>
      </div>

      <div class="blk">
        <h3>三轴位置</h3>
        <div class="axes" id="res-axes"></div>
      </div>

      <div class="blk">
        <h3>具体解释</h3>
        <div class="rows" id="res-rows"></div>
      </div>

      <div class="blk">
        <h3>关于你的投影 · 三件真实的事</h3>
        <ol class="facts-list" id="res-facts"></ol>
      </div>

      <div class="blk adv">
        <h3>行动建议</h3>
        <ol id="res-adv"></ol>
      </div>

      <div class="slogan" id="res-slogan"></div>

      <div class="rule">
        <h3>结 果 是 怎 么 算 出 来 的</h3>
        <ul>
          <li>15 道题，每题的 4 个选项分别对应 5 种投影中的 4 种，一题只记 1 分。</li>
          <li>题目每 5 题为一轮，一轮内 5 种投影各出现 4 次，因此每种投影在全部题目中出现次数完全相同（各 12 次），机会均等。</li>
          <li><b>主投影 = 得分最高的一项</b>。若两项并列，先看第 15 题的作答，再看第 1 题，仍并列则按「谋略 → 内省 → 破局 → 自由 → 自愈」的固定顺序判定——<b>不会随机出结果</b>。</li>
          <li>结果完全由你的答案决定：答案相同，结果一定相同；修改答案后按新答案重新计算，不会累加旧的分数。</li>
        </ul>
      </div>

      <div class="acts">
        <button class="btn" id="btn-share">生成结果图</button>
        <button class="btn ghost" id="btn-review">回看并修改答案</button>
        <button class="btn ghost" id="btn-restart">重新测试</button>
      </div>

      <p class="disc" id="disc">
        <b>关于这个测试：</b>它是一份原创的日常行为自评量表，题目与结果解读均为原创设计，用于自我观察和娱乐参考。
        它不是专业心理测评，也不是历史人物的真实性格测评，不构成任何心理诊断、医疗建议或对人的评价。
        文中引用的史实均注明出处，可自行核对；历史人物本身远比任何标签复杂，请只把结果当作一面镜子，不要当作结论。
      </p>

    </div>
  </div>
</section>

<div id="toast"></div>

<div id="modal">
  <div class="inner">
    <canvas id="card" width="750" height="1000"></canvas>
    <p class="tip">长按图片保存，或点下方按钮下载</p>
    <a class="dl" id="dl" download="历史投影测试结果.png">下载结果图</a><br>
    <button class="x" id="btn-close">关闭</button>
  </div>
</div>

<script>
"use strict";

/* ==================== 五种投影 ==================== */
var ORDER = ['zg','wy','wt','lb','ss'];

var TYPES = {
  zg: {
    name: '诸葛亮 · 把棋盘先看清的人',
    short: '谋略',
    seal: '谋',
    color: '#3e6b8c',
    fill: '投 影 · 谋 略 者',
    quote: '你不是慢，你是要先在心里把整件事走一遍，才肯出手。',
    illusion: '冷静、稳、话少，什么事都能托付给他',
    truth: '你不是不急，你是知道急没有用',
    need: '一个能把混乱理清楚的系统',
    explain: '你处理世界的方式是「先建模型」——把混乱拆成结构，把结构排出顺序，再决定要不要出手。这不是犹豫，而是一种对代价特别敏感的能力：你知道错误的决定要用更多时间去补，所以宁可在前面多花一点。别人看到你在想，其实你已经走过一遍了。',
    highlight: '在别人还在讨论怎么做的时候，你已经在想「它为什么会变成这样」',
    blind: '你容易把「想清楚」当成行动的前提，于是有些机会在你准备完之前就过去了。另外，你很少让别人看见自己的不确定，这会让你显得比实际更疏远。',
    advice: [
      '给每个决定设一个截止时间。你的分析能力早就够了，缺的往往是一个「到此为止」的闹钟——到点就用手上 70% 的信息做决定。',
      '试着说出「我还没想好」，而不是用一个完整的方案掩盖不确定。让身边的人早点知道你在犹豫，他们会比你想象中更有用。',
      '每周留一件「算不出回报」的事去做：见一个不为什么的人、看一部没什么用的电影。你需要练习在不完全掌控的情况下也能安心。'
    ],
    items: '一本可以随时涂改的方格笔记本 · 一支好写的笔',
    itemWhy: '你的安全感来自「可修改」',
    slogan: '先把棋盘看清，再落第一子。',
    keys: ['先谋后动','系统性','可靠'],
    facts: [
      '出山之前，他在隆中「躬耕陇亩」，刘备三顾茅庐才见到他（《三国志·诸葛亮传》）。',
      '陈寿评价他「科教严明，赏罚必信」——后人记住他的，不是奇谋，而是把制度立住了。',
      '《出师表》里那句「受任于败军之际，奉命于危难之间」，是他写给刘禅的自述。'
    ]
  },
  wy: {
    name: '王阳明 · 向内找答案的人',
    short: '内省',
    seal: '心',
    color: '#3f6b54',
    fill: '投 影 · 内 省 者',
    quote: '你不是想太多，你只是不肯骗自己。',
    illusion: '安静、想得深、有点疏离，不太好接近',
    truth: '你在意的事情很小，小到只有你自己知道',
    need: '一份对得起自己的确认',
    explain: '你是先感受到情绪、才处理事情的那种人。这不是软弱，是一种更细的感知力——你能察觉到别人忽略的那点不对劲，也能立刻分辨出一句话是不是真的。代价是你很难糊弄自己，也很难真的把一件事「算了」。',
    highlight: '在没有人看见的地方，你依然选择做对的那件事',
    blind: '你的洞见很多，但常常停在「想明白了」这一步，没有变成行动。另外，你太习惯自我消化，容易让身边的人以为你不需要人。',
    advice: [
      '把「想清楚」升级成「说出来」。对一个人讲一遍你的判断，它才真正成立——你的想法需要一个出口，否则会变成内耗。',
      '给自己设一个行动配额：每天至少做一件小的、别人能看见的事。哪怕只是发一条消息、交一次东西。',
      '少用「我还没准备好」推迟事情。准备好不是开始的前提，而是做完之后才会有的感觉。'
    ],
    items: '一本只写给自己看的手账 · 一支顺手的笔',
    itemWhy: '写给自己的话，不需要交给任何人检查',
    slogan: '答案不在外面，在心里那面镜子上。',
    keys: ['内省','真诚','一致'],
    facts: [
      '正德三年（1508 年）他被贬到贵州龙场做驿丞，环境极苦，在那里「中夜大悟」（《明史·王守仁传》）。',
      '年轻时他和朋友对着庭院里的竹子「格」了七天七夜，什么也没格出来，还病倒了——多年后他承认，道理从来不在竹子身上（《传习录》）。',
      '正德十四年（1519 年）宁王朱宸濠起兵，他手上没有正规军，靠用计与速度，数十日就擒获了对方。'
    ]
  },
  wt: {
    name: '武则天 · 不把规则当回事的人',
    short: '破局',
    seal: '权',
    color: '#b07d2b',
    fill: '投 影 · 破 局 者',
    quote: '你不是爱争，你只是不想让人替你决定。',
    illusion: '有野心、不太好惹、效率极高，让人不敢轻慢',
    truth: '你只是很早就明白——退让换不来尊重',
    need: '一个「我说了算」的位置',
    explain: '你的判断方式是「这样做会有什么结果」，而不是「这样做合不合规矩」。这条路会很辛苦，因为你要同时付两份成本：把事做成的成本，和打破规矩的代价。但你算过这笔账，你觉得值。',
    highlight: '别人说「不可能」的地方，你把它做成了',
    blind: '你习惯把目的藏起来，用「我只是想帮忙」包装自己的野心，久了会累，也会让别人低估你。另外你很难允许自己停下来，容易把人生过成一场不能输的比赛。',
    advice: [
      '把目的直说出来。你不需要用「我只是想帮忙」来降低别人的戒心——清楚地说出你要什么，反而会换来该有的尊重。',
      '给自己配一条「退路」。不是因为你打算退，而是当你知道自己退得起的时候，动作会更稳、更敢下重注。',
      '每周留一次「不为了赢」的对话：不谈事情、不谈进度，只是和人待着。你需要练习在没有目标的时候也不焦虑。'
    ],
    items: '一枚刻着自己名字的印章 · 一支正红色的口红',
    itemWhy: '你的武器是做决定',
    slogan: '路是走出来的，不是选出来的。',
    keys: ['目标感','破格','执行力'],
    facts: [
      '载初元年（690 年）她称帝，改国号为周，是中国历史上唯一的女皇帝。',
      '她在位期间扩大了科举取士，亲自策问贡人于洛城殿，被认为开了殿试、武举的先例。',
      '乾陵前立着一块「无字碑」，碑上不刻一字。为什么无字，后世解读不一——有一种说法是，她把评价留给了后人。'
    ]
  },
  lb: {
    name: '李白 · 不肯被驯服的人',
    short: '自由',
    seal: '逸',
    color: '#7e5fa8',
    fill: '投 影 · 自 由 者',
    quote: '你不是不靠谱，你只是不肯把自己交给一套不属于你的规矩。',
    illusion: '随性、有趣、抓不住，活得比谁都潇洒',
    truth: '你比谁都认真，只是认真的东西跟别人不一样',
    need: '一段不用向任何人解释的时间',
    explain: '你做判断的方式是「感觉对不对」，而不是「合不合算」。这种人在结构化的环境里会显得刺眼，但在需要灵感的场合会发光。你要的从来不是轻松，是真实——一旦一件事让你觉得虚伪，你的身体会比大脑先开始逃。',
    highlight: '在完全没有人要求你的时候，你做出的东西比谁都好',
    blind: '你开始的事情远多于完成的事情，收尾全靠心情。另外你不太擅长表达需要，别人常常以为你什么都不缺。',
    advice: [
      '给你的灵感配一个容器：随手记。别指望脑子记住，也别等「有整块时间」再动手——你永远不会有一整块时间。',
      '主动找一个「专职收尾」的搭子：你负责开始，他负责结束。承认自己需要这个人，比硬撑到底省事得多。',
      '每个月为自己做一件「必须完成」的小事：写完一篇、做完一个、交掉一个。完成感是可以训练的，而它恰好是你最容易缺的东西。'
    ],
    items: '一本随身小册子 · 一支不需要换墨的笔',
    itemWhy: '你的人生常常从「先记下来」开始变清楚',
    slogan: '你不属于任何一把尺子。',
    keys: ['直觉','自由','表达'],
    facts: [
      '二十多岁时他「仗剑去国，辞亲远游」（《上安州裴长史书》），一生没有走科举这条路。',
      '天宝三载（744 年）他与杜甫在洛阳相识、同游梁宋，是中国文学史上最著名的一次相遇。',
      '「天子呼来不上船，自称臣是酒中仙」出自杜甫《饮中八仙歌》——那是杜甫眼里的他。'
    ]
  },
  ss: {
    name: '苏轼 · 什么都能咽下去还能笑的人',
    short: '自愈',
    seal: '味',
    color: '#a85a3c',
    fill: '投 影 · 自 愈 者',
    quote: '你不是没心没肺，你是把苦咽下去，然后还愿意好好吃一顿饭。',
    illusion: '随和、心大、什么都能接受，好像没什么能伤到你',
    truth: '你什么都知道，你只是选择先活下去，再谈别的',
    need: '一段被允许慢慢来的时间',
    explain: '你处理伤害的方式不是对抗，而是转化——把难的那部分一点一点变成日常的一部分。这不是钝感，是一种极高的生存智慧：你比谁都清楚发生了什么，只是你更早明白了，生气解决不了任何事。',
    highlight: '在很差的日子里，你还能把一顿饭认真做好',
    blind: '你太擅长消化，以至于别人以为你不需要安慰。你的「没事」说得太顺口，有时候连自己都骗过去了。',
    advice: [
      '给自己记一份「小确幸清单」：写下这周让你舒服过的三件小事。你的复原力需要一个看得见的抓手，否则会悄悄透支。',
      '别用「没事」结束对话。挑一个人，把真实的感受完整说一次——你值得被安慰，而不是永远当那个安慰别人的人。',
      '把「能忍」升级成「能选」：问问自己，这件事我咽下去是因为它不值得争，还是因为我怕冲突？有些事本来就不必咽。'
    ],
    items: '一口好锅 · 一只顺手的杯子',
    itemWhy: '你的人生常常从「吃顿好的」开始复活',
    slogan: '人间有味是清欢。',
    keys: ['韧性','生活力','松弛'],
    facts: [
      '嘉祐二年（1057 年）他与弟弟苏辙同榜进士及第，那一年的主考官是欧阳修。',
      '元丰三年（1080 年）「乌台诗案」后被贬黄州，他在城东坡地开荒种田，自号「东坡居士」，并写下前后《赤壁赋》。',
      '他被贬到最远的儋州（今海南）时，仍写下「九死南荒吾不恨，兹游奇绝冠平生」（《六月二十日夜渡海》）。'
    ]
  }
};

/* 结果页 hero 上的人格图标（白色剪影） */
var ICONS = {
  zg: '<path d="M24 8c9.4 0 15.6 7.2 15.6 15.4H8.4C8.4 15.2 14.6 8 24 8z" fill="#fff"/><path d="M24 8v15.4M16 23.4l3-15M32 23.4l-3-15" stroke="#fff" stroke-width="1.6" opacity=".45"/><rect x="22" y="23" width="4" height="17" rx="2" fill="#fff" opacity=".7"/><path d="M17 43h14" stroke="#fff" stroke-width="2.6" stroke-linecap="round" opacity=".7"/>',
  wy: '<rect x="15" y="7" width="5" height="34" rx="2.5" fill="#fff" opacity=".55"/><rect x="27" y="12" width="5" height="29" rx="2.5" fill="#fff"/><path d="M15 19h5M15 31h5M27 24h5M27 35h5" stroke="#3f6b54" stroke-width="1.4" opacity=".45"/><path d="M30 15c6-3 9-7 9-12-5 0-8 3-9 8z" fill="#fff" opacity=".8"/>',
  wt: '<rect x="10" y="20" width="28" height="20" rx="4.5" fill="#fff"/><rect x="18" y="11" width="12" height="10" rx="3" fill="#fff" opacity=".62"/><path d="M16 34h16" stroke="#b07d2b" stroke-width="3.2" stroke-linecap="round" opacity=".55"/><path d="M24 26v6" stroke="#b07d2b" stroke-width="3.2" stroke-linecap="round" opacity=".55"/>',
  lb: '<path d="M33 7a16.5 16.5 0 1 0 7.5 25.6A13.5 13.5 0 0 1 33 7z" fill="#fff"/><path d="M10 34h13l-1.8 6h-9.4z" fill="#fff" opacity=".6"/><path d="M11 30.5h11" stroke="#fff" stroke-width="2.4" stroke-linecap="round" opacity=".75"/>',
  ss: '<path d="M24 9c8.2 0 14.6 11.6 15.8 18.4H8.2C9.4 20.6 15.8 9 24 9z" fill="#fff"/><rect x="6" y="27" width="36" height="4.6" rx="2.3" fill="#fff" opacity=".62"/><path d="M30 33v9" stroke="#fff" stroke-width="2.6" stroke-linecap="round" opacity=".7"/>'
};

/* ==================== 15 道题 ==================== */
var QUESTIONS = [
  {
    q: '一件你没做过、但必须由你来做的事，落到了你手上。你的第一反应是——',
    note: '诸葛亮 27 岁之前一直在隆中「躬耕陇亩」，直到刘备三顾茅庐才出山。他给出的《隆中对》把天下形势拆成三块——那不是预言，是推演（《三国志·诸葛亮传》）。',
    o: [
      ['先做起来，边做边摸清它到底是怎么回事','lb'],
      ['先问自己一句：这件事我到底想不想做','wy'],
      ['先想清楚：做完这件事，我能拿到什么','wt'],
      ['先找人聊聊，看看别人是怎么做的','ss']
    ]
  },
  {
    q: '一群人约着周末出门，群消息刷得很快。你在群里是——',
    note: '《宋史·苏轼传》记他在黄州时「与田父野老相从溪谷之间」——一个被贬的官员，和当地农夫老人一起在山谷间游玩。这种能和任何人待在一起的能力，是他一生的护身符。',
    o: [
      ['把时间、地点、路线列清楚，谁负责什么也写明白','zg'],
      ['先想一下那天我到底想不想出门，再回消息','wy'],
      ['直接定地方，说一句「跟我走就行」','wt'],
      ['负责找吃的、串气氛，具体行程随大家','ss']
    ]
  },
  {
    q: '你熬得最深的那个夜晚，通常是在做什么？',
    note: '王阳明年轻时曾和朋友对着庭院里的竹子「格」了七天七夜，想格出竹子的道理，结果什么也没格出来，还病倒了（《传习录》中他本人的回忆）。多年后他承认：道理从来不在竹子身上。',
    o: [
      ['在想一个没想通的问题，不想把它留到明天','zg'],
      ['在写点什么、做点什么，或者纯粹舍不得睡','lb'],
      ['在赶一件必须完成的事，做完之前我不会停','wt'],
      ['在吃东西、看剧、聊天，总之在把白天还给自己','ss']
    ]
  },
  {
    q: '别人替你把决定做了，然后把结果通知你。你会——',
    note: '载初元年（690 年）武则天称帝，改国号为周，是中国历史上唯一的女皇帝。从才人到昭仪、皇后、皇帝，她几乎每一步都越过了当时的规矩。',
    o: [
      ['表面上接受，心里已经在重新算一遍','zg'],
      ['有点不舒服，但很快就不想了','lb'],
      ['会认真想：我为什么这么在意这件事','wy'],
      ['算了，就当多了一个选择，说不定还挺好','ss']
    ]
  },
  {
    q: '你最受不了哪种人？',
    note: '元丰三年（1080 年）「乌台诗案」后，苏轼被贬黄州，人生跌到最低。他在城东的坡地上开荒种田，自号「东坡居士」，也正是在那段时间写出了《念奴娇·赤壁怀古》与前后《赤壁赋》。',
    o: [
      ['明明可以做得更好，却说「差不多就行了」','zg'],
      ['什么都要按规矩来，一点余地都不留','lb'],
      ['嘴上说一套、心里想一套的人','wy'],
      ['遇到事第一句话就是「不可能」的人','wt']
    ]
  },
  {
    q: '你花了很久做的一件事失败了。接下来几天你——',
    note: '正德三年（1508 年）王阳明被贬到贵州龙场，只做了一个小小的驿丞，环境极其艰苦。他在那里「中夜大悟」，后来提出「知行合一」：知是行的开始，行是知的完成（《传习录》）。',
    o: [
      ['难受两天，然后该干嘛干嘛','lb'],
      ['反复回想：这里面是不是有我一直没看见的问题','wy'],
      ['复盘一遍，然后立刻开始下一个','wt'],
      ['找人吃顿饭，边吃边说，说完就轻了','ss']
    ]
  },
  {
    q: '你更希望被人记住的是——',
    note: '《三国志》作者陈寿评价诸葛亮「科教严明，赏罚必信，无恶不惩，无善不显」。他被后人记住的不是奇谋，而是把制度立起来、把事情管住。',
    o: [
      ['那人办事靠谱，交给他的事从没出过岔子','zg'],
      ['那人活得明白，知道自己要什么','wy'],
      ['那人做成了一件别人没做成的事','wt'],
      ['那人很有意思，和他待着不累','ss']
    ]
  },
  {
    q: '一件事你想不通的时候，你会——',
    note: '李白二十多岁时「仗剑去国，辞亲远游」（《上安州裴长史书》），一生没有走科举这条路。杜甫在《饮中八仙歌》里写他：「天子呼来不上船，自称臣是酒中仙。」',
    o: [
      ['找资料、找规律，把它拆成几块看','zg'],
      ['不硬想了，出去走走，答案自己会冒出来','lb'],
      ['先按最可能的那条路做，边走边改','wt'],
      ['先睡一觉、吃顿好的，第二天再说','ss']
    ]
  },
  {
    q: '如果一定要你站到很多人面前说话，你的状态是——',
    note: '天宝三载（744 年）李白与杜甫在洛阳相识，随后同游梁宋。这是中国文学史上最著名的一次相遇：两人相差十一岁，此后杜甫写了十几首诗怀念李白。',
    o: [
      ['准备充分就还好，怕的是自己没想清楚','zg'],
      ['感觉来了我能讲得很好，感觉没来就算了','lb'],
      ['会紧张，但我更在意自己说的是不是真的','wy'],
      ['不太怕，气氛到了我能把大家逗乐','ss']
    ]
  },
  {
    q: '你的手机里，最舍不得删的是——',
    note: '正德十四年（1519 年）宁王朱宸濠起兵，王阳明手上并没有正规军。他用计、用疑兵、用最短的路径，前后不过数十日就擒获了朱宸濠。',
    o: [
      ['各种记录、清单、随手记下的想法','zg'],
      ['一些没什么用但很好看的照片和截图','lb'],
      ['一些深夜写下的话','wy'],
      ['划掉过的待办、做完的事','wt']
    ]
  },
  {
    q: '你身边的朋友，大多是——',
    note: '嘉祐二年（1057 年）苏轼与弟弟苏辙同榜进士及第，那一年的主考官是欧阳修。此后兄弟二人一生聚少离多，他写下大量寄给苏辙的诗，包括「人有悲欢离合，月有阴晴圆缺」（《水调歌头》）。',
    o: [
      ['类型差别很大，什么样的人都有','lb'],
      ['不多，但每一个都能说很深的话','wy'],
      ['能一起做事的，聊得来更好，聊不来也行','wt'],
      ['各种都有，我好像跟谁都聊得来','ss']
    ]
  },
  {
    q: '突然多出一整天空白时间，你会——',
    note: '元丰五年（1082 年）三月，苏轼在黄州沙湖道中遇雨，同行的人都狼狈，他写下《定风波》：「竹杖芒鞋轻胜马，谁怕？一蓑烟雨任平生。」',
    o: [
      ['正好把攒着没处理的事理一理','zg'],
      ['一个人待着，想点平时没空想的事','wy'],
      ['安排一件一直想做但没时间做的事','wt'],
      ['什么也不安排，睡到自然醒，然后随便走走','ss']
    ]
  },
  {
    q: '做成一件事之后，你最先想到的是——',
    note: '李白在《将进酒》里写「人生得意须尽欢，莫使金樽空对月」。他不是不知道前途难料，他是选择在能高兴的时候先高兴。',
    o: [
      ['这次哪一步还能更省力','zg'],
      ['太好了，先庆祝一下','lb'],
      ['下一步可以做更大的','wt'],
      ['想找人分享，谁陪我高兴一下','ss']
    ]
  },
  {
    q: '有人当面否定你，语气还不太客气。你的第一反应——',
    note: '乾陵前立着武则天的「无字碑」，碑上不刻一字。为什么无字，后世解读不一——有一种说法是，她把评价留给了后人。',
    o: [
      ['先判断他说得对不对，对就改','zg'],
      ['有点气，但懒得争，转头就忘','lb'],
      ['先感受到的是情绪，然后才想他说了什么','wy'],
      ['觉得没必要，笑一下把话岔开','ss']
    ]
  },
  {
    q: '你理想中的「好日子」是什么样？',
    note: '苏轼被贬到最远的儋州（今海南）时，仍写下「九死南荒吾不恨，兹游奇绝冠平生」（《六月二十日夜渡海》）。他还写过一句更轻的：「人间有味是清欢。」',
    o: [
      ['该掌控的都掌控住了，一切按计划走','zg'],
      ['自由，不被任何东西绑住','lb'],
      ['心里踏实，做的事对得起自己','wy'],
      ['一直在往上走，每年都比去年更厉害','wt']
    ]
  }
];

/* ==================== 三轴定义 ==================== */
var AXES = [
  {
    name: '决策方式',
    left: '谋定',
    right: '即兴',
    w: { zg:-0.90, wt:-0.50, wy:-0.15, ss:0.40, lb:1.00 },
    tipL: '你几乎是先在心里把整件事演一遍，才肯真正出手的人。',
    tipR: '你做决定主要靠当下的感觉——反复权衡反而会让你做不好。',
    tipM: '你两边都用：遇到大事会先想清楚，日常小事凭感觉。'
  },
  {
    name: '能量方向',
    left: '向内',
    right: '向外',
    w: { wy:-1.00, ss:-0.40, zg:-0.10, lb:0.50, wt:0.90 },
    tipL: '你的力气主要花在内部：把事情想清楚、把自己安顿好，比对外争取更重要。',
    tipR: '你的力气主要朝外：人和事在推着你往前走，你也更擅长在外部的世界里使上劲。',
    tipM: '你内外都开着口：既需要独处，也需要人群。'
  },
  {
    name: '面对规则',
    left: '顺势',
    right: '破局',
    w: { ss:-0.80, wy:-0.40, lb:-0.10, zg:0.35, wt:1.00 },
    tipL: '你更擅长顺着形势走，用巧劲把局面理顺，而不是硬掰。',
    tipR: '你更擅长把规则掀开重写——让你照着别人的路走，你会浑身难受。',
    tipM: '你会看情况：该顺的时候顺，该破的时候你也不怕。'
  }
];

/* ==================== 状态 ==================== */
var S = { idx: 0, answers: new Array(QUESTIONS.length).fill(null) };

function $(id){ return document.getElementById(id); }
var MK = ['A','B','C','D'];

/* 每种投影的满分（= 它在题目中出现的次数，用于校验均等） */
var MAXP = {};
ORDER.forEach(function(k){ MAXP[k] = 0; });
QUESTIONS.forEach(function(q){
  var used = {};
  q.o.forEach(function(o){ MAXP[o[1]] += 1; used[o[1]] = 1; });
});

/* ==================== 首页印章 ==================== */
(function(){
  var box = $('home-seals'), h = '';
  ORDER.forEach(function(k){
    var T = TYPES[k];
    h += '<span class="seal-chip"><i style="background:' + T.color + '">' + T.seal + '</i>' + T.name.split(' · ')[0] + '</span>';
  });
  box.innerHTML = h;
})();

/* ==================== 页面切换 ==================== */
function go(id){
  var pages = document.querySelectorAll('.page');
  for (var i=0;i<pages.length;i++) pages[i].classList.remove('active');
  $(id).classList.add('active');
  window.scrollTo(0,0);
}

/* ==================== toast ==================== */
var toastTimer = null;
function toast(msg){
  var t = $('toast');
  t.textContent = msg;
  t.classList.add('on');
  clearTimeout(toastTimer);
  toastTimer = setTimeout(function(){ t.classList.remove('on'); }, 2200);
}

/* ==================== 答题页 ==================== */
function answeredCount(){
  var n = 0;
  for (var i=0;i<S.answers.length;i++) if (S.answers[i] !== null) n++;
  return n;
}

function renderDots(){
  var box = $('q-dots');
  box.innerHTML = '';
  for (var i=0;i<QUESTIONS.length;i++){
    (function(i){
      var b = document.createElement('button');
      b.className = 'dot' + (S.answers[i] !== null ? ' done' : '') + (i === S.idx ? ' cur' : '');
      b.textContent = (i+1);
      b.title = '第 ' + (i+1) + ' 题' + (S.answers[i] !== null ? '（已答）' : '（未答）');
      b.setAttribute('aria-label', b.title);
      b.onclick = function(){ S.idx = i; renderQuiz(); };
      box.appendChild(b);
    })(i);
  }
}

function renderQuiz(){
  var q = QUESTIONS[S.idx];
  $('q-tag').textContent = '第 ' + (S.idx + 1) + ' 问 / 共 ' + QUESTIONS.length + ' 问';
  $('q-text').textContent = q.q;

  var n = answeredCount();
  $('q-count').textContent = '已答 ' + n + ' / ' + QUESTIONS.length;
  $('q-bar').style.width = (n / QUESTIONS.length * 100) + '%';

  var box = $('q-opts');
  box.innerHTML = '';
  for (var i=0;i<q.o.length;i++){
    (function(i){
      var o = q.o[i];
      var b = document.createElement('button');
      b.className = 'opt' + (S.answers[S.idx] === o[1] ? ' sel' : '');
      b.innerHTML = '<span class="mk">' + MK[i] + '</span><span class="tx"></span>';
      b.querySelector('.tx').textContent = o[0];
      b.onclick = function(){
        S.answers[S.idx] = o[1];
        renderQuiz();
      };
      box.appendChild(b);
    })(i);
  }

  /* 已答时展示该题的史料注（知识点） */
  var note = $('q-note');
  if (S.answers[S.idx] !== null){
    $('q-note-text').textContent = q.note;
    note.classList.add('on');
  } else {
    note.classList.remove('on');
    $('q-note-text').textContent = '';
  }

  $('btn-prev').disabled = (S.idx === 0);
  $('btn-next').textContent = (S.idx === QUESTIONS.length - 1) ? '查看结果' : '下一题';
  renderDots();
}

function shakeOpts(){
  var el = $('q-opts');
  el.classList.remove('shake');
  void el.offsetWidth;
  el.classList.add('shake');
}

function goPrev(){
  if (S.idx === 0){ toast('已经是第一题了'); return; }
  S.idx--;
  renderQuiz();
}

function goNext(){
  if (S.answers[S.idx] === null){
    toast('这一题还没选哦');
    shakeOpts();
    return;
  }
  if (S.idx === QUESTIONS.length - 1){ finish(); return; }
  S.idx++;
  renderQuiz();
}

function finish(){
  var miss = -1, cnt = 0;
  for (var i=0;i<S.answers.length;i++){
    if (S.answers[i] === null){ cnt++; if (miss === -1) miss = i; }
  }
  if (cnt > 0){
    toast('还有 ' + cnt + ' 题没答，已跳到第 ' + (miss + 1) + ' 题');
    S.idx = miss;
    renderQuiz();
    return;
  }
  showResult();
}

/* ==================== 计分：每次按当前答案重算，不累加 ==================== */
function computeScores(){
  var sc = {};
  ORDER.forEach(function(k){ sc[k] = 0; });
  for (var i=0;i<S.answers.length;i++){
    var a = S.answers[i];
    if (a && Object.prototype.hasOwnProperty.call(sc, a)) sc[a] += 1;
  }
  return sc;
}

/* 排名：分数 → 第 15 题 → 第 1 题 → 固定顺序 */
function pickMain(sc){
  var best = -1;
  ORDER.forEach(function(k){ if (sc[k] > best) best = sc[k]; });
  var tied = ORDER.filter(function(k){ return sc[k] === best; });
  if (tied.length === 1) return { main: tied[0], tied: tied, byTie: false };
  var q15 = S.answers[QUESTIONS.length - 1];
  if (q15 && tied.indexOf(q15) >= 0) return { main: q15, tied: tied, byTie: true };
  var q1 = S.answers[0];
  if (q1 && tied.indexOf(q1) >= 0) return { main: q1, tied: tied, byTie: true };
  return { main: tied[0], tied: tied, byTie: true };
}

function rankTypes(sc, main){
  return ORDER.slice().sort(function(a, b){
    if (sc[b] !== sc[a]) return sc[b] - sc[a];
    if (a === main) return -1;
    if (b === main) return 1;
    return ORDER.indexOf(a) - ORDER.indexOf(b);
  });
}

function axisValue(sc, axis){
  var sum = 0;
  ORDER.forEach(function(k){ sum += sc[k] * axis.w[k]; });
  var avg = sum / QUESTIONS.length;
  if (avg > 1) avg = 1;
  if (avg < -1) avg = -1;
  return avg;
}

/* ==================== 结果页 ==================== */
function showResult(){
  var sc = computeScores();
  var pick = pickMain(sc);
  var main = pick.main;
  var ranked = rankTypes(sc, main);
  var second = ranked[1];
  var T = TYPES[main], T2 = TYPES[second];
  var maxScore = sc[main];
  var diff = maxScore - sc[second];

  var purity = diff >= 4 ? '非常突出' : (diff >= 2 ? '比较明显' : (diff >= 1 ? '略有倾向' : '几乎均等'));

  $('res-hero').style.background = 'linear-gradient(150deg,' + T.color + ',' + shade(T.color) + ')';
  $('res-seal').textContent = T.seal;
  $('res-ico').innerHTML = '<svg viewBox="0 0 48 48" aria-hidden="true">' + ICONS[main] + '</svg>';
  $('res-fill').textContent = T.fill;
  $('res-fill').style.color = T.color;
  $('res-name').textContent = T.name;
  $('res-quote').textContent = T.quote;

  $('res-illusion').textContent = T.illusion;
  $('res-truth').textContent = T.truth;

  /* 成分表 */
  var bars = '';
  for (var i=0;i<ranked.length;i++){
    var k = ranked[i], tp = TYPES[k];
    var pct = Math.round(sc[k] / QUESTIONS.length * 100);
    bars += '<div class="brow' + (i === 0 ? ' top' : '') + '">' +
      '<div class="bl"><b>' + tp.short + '（' + TYPES[k].seal + '）</b><span>' + sc[k] + ' 次 · ' + pct + '%</span></div>' +
      '<div class="btrack"><i data-w="' + Math.max(pct, 3) + '" style="background:' + tp.color + '"></i></div>' +
      '</div>';
  }
  $('res-bars').innerHTML = bars;
  var tracks = $('res-bars').querySelectorAll('.btrack i');
  for (var bi=0; bi<tracks.length; bi++){
    (function(el, n){ setTimeout(function(){ el.style.width = el.getAttribute('data-w') + '%'; }, 60 + n * 70); })(tracks[bi], bi);
  }

  /* 组合解读 */
  var combo = '<span class="purity">' + purity + ' · 主投影 ' + T.short + '</span><br>';
  combo += '15 道题里，你选了「' + T.short + '」' + maxScore + ' 次，「' + T2.short + '」' + sc[second] + ' 次' +
           '（平均线是每项 3 次，也就是 20%）。<br>';
  combo += '你的主投影是「' + T.short + '」——' + T.need + '；第二底色是「' + T2.short + '」——' + T2.need + '。';
  if (diff >= 4){
    combo += '两者差距很大，「' + T.short + '」在你身上几乎是决定性的。';
  } else if (diff >= 2){
    combo += '两者有一定差距，但「' + T2.short + '」也常常在你不注意的时候冒出来。';
  } else if (diff >= 1){
    combo += '两者只差一分，你可能常常在两种状态之间来回切换。';
  } else {
    combo += '两者完全打平，你的底色非常均衡，这在 15 道题里并不常见。';
  }
  if (pick.byTie){
    combo += '<br><b>判定说明：</b>你的最高分出现了并列（' + pick.tied.map(function(k){ return TYPES[k].short; }).join(' / ') +
      '），按规则依次比较第 15 题、第 1 题的作答后，判定主投影为「' + T.short + '」。';
  }
  $('res-combo').innerHTML = combo;

  /* 三轴 */
  var axh = '';
  for (var a=0;a<AXES.length;a++){
    var ax = AXES[a];
    var v = axisValue(sc, ax);
    var pos = Math.round((v + 1) / 2 * 100);
    if (pos < 8) pos = 8;
    if (pos > 92) pos = 92;
    var tip = v < -0.3 ? ax.tipL : (v > 0.3 ? ax.tipR : ax.tipM);
    axh += '<div class="axis">' +
      '<div class="an"><b>' + ax.name + '</b><span>' + (v < -0.3 ? '偏 ' + ax.left : (v > 0.3 ? '偏 ' + ax.right : '居 中')) + '</span></div>' +
      '<div class="ax-track"><i data-p="' + pos + '" style="background:' + T.color + '"></i></div>' +
      '<div class="ax-end"><span>' + ax.left + '</span><span>' + ax.right + '</span></div>' +
      '<div class="tip">' + tip + '</div>' +
      '</div>';
  }
  $('res-axes').innerHTML = axh;
  var marks = $('res-axes').querySelectorAll('.ax-track i');
  for (var mi=0; mi<marks.length; mi++){
    (function(el, n){ setTimeout(function(){ el.style.left = el.getAttribute('data-p') + '%'; }, 80 + n * 110); })(marks[mi], mi);
  }

  /* 具体解释 */
  var rows = [
    ['一句话画像', T.quote],
    ['你的核心需要', T.need],
    ['高光时刻', T.highlight],
    ['盲点与风险', T.blind],
    ['三个关键词', T.keys.join(' · ')],
    ['开运小物', T.items + '（' + T.itemWhy + '）']
  ];
  $('res-rows').innerHTML = rows.map(function(){ return '<div class="row"><div class="lb"></div><div class="vl"></div></div>'; }).join('');
  var vls = $('res-rows').querySelectorAll('.vl');
  var lbs = $('res-rows').querySelectorAll('.lb');
  for (var m=0;m<rows.length;m++){ lbs[m].textContent = rows[m][0]; vls[m].textContent = rows[m][1]; }

  /* 三件真实的事 */
  var fh = '';
  for (var f=0; f<T.facts.length; f++) fh += '<li></li>';
  $('res-facts').innerHTML = fh;
  var flis = $('res-facts').querySelectorAll('li');
  for (var f2=0; f2<T.facts.length; f2++) flis[f2].textContent = T.facts[f2];

  /* 行动建议 */
  var ah = '';
  for (var p=0;p<T.advice.length;p++) ah += '<li></li>';
  $('res-adv').innerHTML = ah;
  var lis = $('res-adv').querySelectorAll('li');
  for (var q2=0;q2<T.advice.length;q2++) lis[q2].textContent = T.advice[q2];

  var sl = $('res-slogan');
  sl.textContent = T.slogan;
  sl.style.background = hexA(T.color, .10);
  sl.style.color = T.color;

  go('page-result');
}

/* ==================== 颜色工具 ==================== */
function shade(hex){
  var n = parseInt(hex.slice(1), 16);
  var r = Math.max(0, (n >> 16) - 40);
  var g = Math.max(0, ((n >> 8) & 255) - 36);
  var b = Math.max(0, (n & 255) - 30);
  return '#' + ((1 << 24) + (r << 16) + (g << 8) + b).toString(16).slice(1);
}
function hexA(hex, a){
  var n = parseInt(hex.slice(1), 16);
  return 'rgba(' + (n >> 16) + ',' + ((n >> 8) & 255) + ',' + (n & 255) + ',' + a + ')';
}

/* ==================== 结果图 ==================== */
function rrect(ctx, x, y, w, h, r){
  ctx.beginPath();
  ctx.moveTo(x + r, y);
  ctx.lineTo(x + w - r, y); ctx.quadraticCurveTo(x + w, y, x + w, y + r);
  ctx.lineTo(x + w, y + h - r); ctx.quadraticCurveTo(x + w, y + h, x + w - r, y + h);
  ctx.lineTo(x + r, y + h); ctx.quadraticCurveTo(x, y + h, x, y + h - r);
  ctx.lineTo(x, y + r); ctx.quadraticCurveTo(x, y, x + r, y);
  ctx.closePath();
}
function wrapText(ctx, text, maxW){
  var lines = [], line = '';
  for (var i=0;i<text.length;i++){
    var test = line + text[i];
    if (ctx.measureText(test).width > maxW && line.length > 0){ lines.push(line); line = text[i]; }
    else line = test;
  }
  if (line) lines.push(line);
  return lines;
}
var FONT = '-apple-system,"PingFang SC","Microsoft YaHei",sans-serif';
var FONT_S = '"Songti SC","STSong","SimSun",serif';

function makeCard(){
  var sc = computeScores();
  var pick = pickMain(sc);
  var T = TYPES[pick.main];
  var ranked = rankTypes(sc, pick.main);
  var pct = Math.round(sc[pick.main] / QUESTIONS.length * 100);

  var c = $('card'), x = c.getContext('2d'), W = 750, H = 1000;
  x.clearRect(0, 0, W, H);
  x.fillStyle = '#f4efe3'; x.fillRect(0, 0, W, H);

  var g = x.createLinearGradient(0, 0, W, 440);
  g.addColorStop(0, T.color); g.addColorStop(1, shade(T.color));
  x.fillStyle = g; x.fillRect(0, 0, W, 430);
  x.fillStyle = 'rgba(255,255,255,.11)';
  x.beginPath(); x.arc(690, 400, 200, 0, Math.PI * 2); x.fill();

  /* 印章 */
  x.strokeStyle = 'rgba(255,255,255,.75)'; x.lineWidth = 3;
  rrect(x, 604, 52, 78, 78, 14); x.stroke();
  x.fillStyle = '#fff'; x.font = '700 40px ' + FONT_S;
  x.textAlign = 'center'; x.fillText(T.seal, 643, 104); x.textAlign = 'left';

  x.fillStyle = 'rgba(255,255,255,.86)';
  x.font = '600 20px ' + FONT;
  x.fillText('你 的 历 史 投 影', 56, 84);

  x.font = '800 21px ' + FONT;
  var fw = x.measureText(T.fill).width;
  x.fillStyle = 'rgba(255,255,255,.95)';
  rrect(x, 56, 116, fw + 42, 50, 13); x.fill();
  x.fillStyle = T.color; x.fillText(T.fill, 77, 149);

  x.fillStyle = '#fff';
  x.font = '800 52px ' + FONT_S;
  var nl = wrapText(x, T.name, 620);
  for (var ni=0; ni<Math.min(nl.length,2); ni++) x.fillText(nl[ni], 54, 258 + ni * 66);

  var qy = 258 + Math.min(nl.length,2) * 66 + 16;
  x.fillStyle = 'rgba(255,255,255,.95)';
  x.font = '400 24px ' + FONT_S;
  var ql = wrapText(x, T.quote, 630);
  for (var i=0;i<Math.min(ql.length, 2);i++) x.fillText(ql[i], 56, qy + i * 38);

  /* 成分 */
  var y = 486;
  x.fillStyle = '#93897b'; x.font = '800 16px ' + FONT;
  x.fillText('你 的 成 分 表 · 主 投 影 ' + pct + '%', 56, y);
  y += 34;
  for (var b=0;b<ranked.length;b++){
    var tp = TYPES[ranked[b]];
    var p = Math.round(sc[ranked[b]] / QUESTIONS.length * 100);
    x.fillStyle = '#544d43'; x.font = '600 20px ' + FONT;
    x.fillText(tp.short, 56, y + 6);
    x.fillStyle = '#e5ddcd'; rrect(x, 150, y - 8, 420, 16, 8); x.fill();
    x.fillStyle = tp.color; rrect(x, 150, y - 8, Math.max(420 * p / 100, 12), 16, 8); x.fill();
    x.fillStyle = '#93897b'; x.font = '600 18px ' + FONT;
    x.fillText(p + '%', 588, y + 6);
    y += 38;
  }

  /* 对照 */
  y += 12;
  x.fillStyle = '#93897b'; x.font = '800 16px ' + FONT;
  x.fillText('别人眼中的你', 56, y);
  x.fillText('真实的你', 400, y);
  x.fillStyle = '#544d43'; x.font = '400 21px ' + FONT;
  var a1 = wrapText(x, T.illusion, 300), a2 = wrapText(x, T.truth, 310);
  for (var j=0;j<Math.min(a1.length, 2);j++) x.fillText(a1[j], 56, y + 34 + j * 31);
  for (var k=0;k<Math.min(a2.length, 2);k++) x.fillText(a2[k], 400, y + 34 + k * 31);

  y += 34 + Math.max(Math.min(a1.length,2), Math.min(a2.length,2)) * 31 + 26;
  var rows = [
    ['你的核心需要', T.need],
    ['盲点与风险', T.blind],
    ['开运小物', T.items]
  ];
  for (var m=0;m<rows.length;m++){
    x.fillStyle = '#b3aaa0'; x.font = '800 15px ' + FONT;
    x.fillText(rows[m][0], 56, y);
    x.fillStyle = '#211e19'; x.font = '400 22px ' + FONT;
    var rl = wrapText(x, rows[m][1], 620);
    var use = Math.min(rl.length, 2);
    for (var p2=0;p2<use;p2++) x.fillText(rl[p2], 56, y + 32 + p2 * 31);
    y += 32 + use * 31 + 14;
    if (y > 880) break;
  }

  x.textAlign = 'center';
  x.fillStyle = T.color; x.font = '800 26px ' + FONT_S;
  x.fillText(T.slogan, W / 2, 936);
  x.fillStyle = '#b3aaa0'; x.font = '400 16px ' + FONT;
  x.fillText('你最像历史上的谁的投影 · 15 题 · 5 种投影 · 原创自评', W / 2, 974);
  x.textAlign = 'left';

  $('dl').href = c.toDataURL('image/png');
  $('modal').classList.add('on');
}

/* ==================== 事件绑定 ==================== */
$('btn-start').onclick = function(){
  S.idx = 0;
  S.answers = new Array(QUESTIONS.length).fill(null);
  go('page-quiz');
  renderQuiz();
};
$('btn-prev').onclick = goPrev;
$('btn-next').onclick = goNext;

$('btn-share').onclick = makeCard;
$('btn-close').onclick = function(){ $('modal').classList.remove('on'); };
$('modal').onclick = function(e){ if (e.target.id === 'modal') $('modal').classList.remove('on'); };

$('btn-review').onclick = function(){
  S.idx = 0;
  go('page-quiz');
  renderQuiz();
  toast('点上面的题号可以跳转；改完答案，走到最后一题点「查看结果」');
};

$('btn-restart').onclick = function(){
  S.idx = 0;
  S.answers = new Array(QUESTIONS.length).fill(null);
  go('page-quiz');
  renderQuiz();
  toast('已清空全部答案，重新开始');
};

/* 键盘操作（桌面端） */
document.addEventListener('keydown', function(e){
  if (!$('page-quiz').classList.contains('active')) return;
  if (e.key === 'ArrowLeft'){ goPrev(); }
  else if (e.key === 'ArrowRight'){ goNext(); }
  else if (e.key >= '1' && e.key <= '4'){
    var i = parseInt(e.key, 10) - 1;
    var q = QUESTIONS[S.idx];
    if (q.o[i]){ S.answers[S.idx] = q.o[i][1]; renderQuiz(); }
  }
});
</script>
</body>
</html>
