<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>2026届国网笔试培训 · 报名流程</title>
<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+SC:wght@400;500;700&family=Noto+Serif+SC:wght@700;900&display=swap" rel="stylesheet">
<style>
:root {
  --gold: #C8963E;
  --gold-light: #E8B96A;
  --gold-pale: #FDF4E3;
  --ink: #1A1208;
  --ink-mid: #3D2E0E;
  --ink-light: #6B5B3E;
  --ink-faint: #BDA882;
  --red: #C0392B;
  --green: #1E7A4A;
  --blue: #1A4A7A;
  --bg: #FAF6EE;
  --white: #FFFDF7;
}
* { margin: 0; padding: 0; box-sizing: border-box; }
body { font-family: 'Noto Sans SC', sans-serif; background: var(--bg); color: var(--ink); min-height: 100vh; }

/* ── HEADER ── */
.header { background: var(--ink); text-align: center; padding: 30px 20px 24px; position: relative; overflow: hidden; }
.header::before { content: ''; position: absolute; inset: 0; background: repeating-linear-gradient(90deg, transparent, transparent 40px, rgba(200,150,62,.06) 40px, rgba(200,150,62,.06) 41px), repeating-linear-gradient(0deg, transparent, transparent 40px, rgba(200,150,62,.06) 40px, rgba(200,150,62,.06) 41px); }
.header-badge { display: inline-block; border: 1px solid var(--gold); padding: 3px 18px; font-size: 12px; letter-spacing: 4px; color: var(--gold); margin-bottom: 12px; position: relative; }
.header h1 { font-family: 'Noto Serif SC', serif; font-size: clamp(20px, 4.5vw, 30px); font-weight: 900; letter-spacing: 2px; color: var(--white); position: relative; line-height: 1.35; }
.header h1 span { color: var(--gold-light); }
.header-meta { margin-top: 12px; display: flex; justify-content: center; flex-wrap: wrap; gap: 20px; font-size: 13px; color: var(--ink-faint); position: relative; }
.header-meta span { display: flex; align-items: center; gap: 5px; }
.dot { width: 5px; height: 5px; background: var(--gold); border-radius: 50%; display: inline-block; flex-shrink: 0; }

/* ── NOTICE ── */
.notice-bar { background: linear-gradient(90deg, #7A1A1A, #C0392B, #7A1A1A); color: #FFD5D5; text-align: center; padding: 9px 20px; font-size: 13px; letter-spacing: 1px; font-weight: 500; }

/* ── MAIN ── */
.main { max-width: 860px; margin: 0 auto; padding: 24px 16px 48px; }

/* ── TABS ── */
.tab-row { display: flex; border: 1.5px solid #E0D0B0; border-radius: 9px; overflow: hidden; margin-bottom: 24px; box-shadow: 0 2px 8px rgba(200,150,62,.08); }
.tab-btn { flex: 1; padding: 13px 10px; background: var(--white); border: none; cursor: pointer; font-family: 'Noto Sans SC', sans-serif; font-size: 15px; color: var(--ink-light); transition: all .2s; letter-spacing: 1px; border-right: 1.5px solid #E0D0B0; }
.tab-btn:last-child { border-right: none; }
.tab-btn.active { background: var(--ink); color: var(--gold-light); font-weight: 700; }
.tab-panel { display: none; }
.tab-panel.active { display: block; animation: fadeUp .35s ease both; }

/* ── SECTION TITLE ── */
.section-title { display: flex; align-items: center; gap: 10px; margin: 28px 0 16px; }
.section-title::before, .section-title::after { content: ''; flex: 1; height: 1px; background: linear-gradient(90deg, transparent, var(--gold), transparent); }
.section-title h2 { font-family: 'Noto Serif SC', serif; font-size: 15px; font-weight: 700; color: var(--ink-mid); letter-spacing: 3px; white-space: nowrap; padding: 0 8px; }

/* ── FLOW STEPS ── */
.flow-step { display: flex; gap: 16px; position: relative; }
.flow-left { display: flex; flex-direction: column; align-items: center; flex-shrink: 0; width: 46px; }
.step-circle { width: 46px; height: 46px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-family: 'Noto Serif SC', serif; font-size: 17px; font-weight: 900; flex-shrink: 0; position: relative; z-index: 1; box-shadow: 0 3px 10px rgba(0,0,0,.18); }
.s1 { background: var(--ink); color: var(--gold-light); }
.s2 { background: var(--blue); color: #A8C8F8; }
.s3 { background: var(--gold); color: var(--ink); }
.s4 { background: var(--green); color: #A8E8C0; }
.s5 { background: var(--red); color: #FFD5D5; }

.step-line { width: 2px; flex: 1; min-height: 24px; background: linear-gradient(to bottom, #D4B896 60%, transparent); margin: 4px 0; }
.flow-right { padding-bottom: 28px; flex: 1; }
.step-card { background: var(--white); border: 1px solid #E8DCC8; border-radius: 9px; padding: 15px 17px; margin-top: 2px; box-shadow: 0 2px 8px rgba(200,150,62,.06); }
.step-top { display: flex; align-items: center; justify-content: space-between; margin-bottom: 9px; gap: 8px; }
.step-title { font-family: 'Noto Serif SC', serif; font-size: 16px; font-weight: 700; color: var(--ink); }
.step-time { font-size: 12px; color: var(--ink-faint); border: 1px solid #E8DCC8; padding: 2px 9px; border-radius: 20px; white-space: nowrap; flex-shrink: 0; }
.step-desc { font-size: 14px; color: var(--ink-light); line-height: 2; }
.step-desc strong { color: var(--ink-mid); }
.step-actions { display: flex; flex-wrap: wrap; gap: 8px; margin-top: 11px; }
.action-pill { font-size: 12px; padding: 4px 13px; border-radius: 20px; font-weight: 500; letter-spacing: .5px; }
.pill-gold { background: var(--gold-pale); color: var(--gold); border: 1px solid var(--gold-light); }
.pill-blue { background: #EDF3FB; color: var(--blue); border: 1px solid #B8D0F0; }
.pill-green { background: #EDFBF3; color: var(--green); border: 1px solid #A8E0C0; }
.pill-red { background: #FBEEED; color: var(--red); border: 1px solid #F0B8B8; }

.branch-box { background: #FFFBF4; border: 1px dashed var(--gold); border-radius: 7px; padding: 11px 14px; margin-top: 11px; }
.branch-title { font-size: 12px; font-weight: 700; color: var(--gold); letter-spacing: 1px; margin-bottom: 8px; }
.branch-row { display: grid; grid-template-columns: repeat(3,1fr); gap: 8px; }
@media(max-width:500px){ .branch-row { grid-template-columns: 1fr; } }
.branch-item { background: var(--white); border: 1px solid #E8DCC8; border-radius: 5px; padding: 8px 10px; }
.bi-name { font-weight: 700; color: var(--ink-mid); font-size: 13px; margin-bottom: 2px; }
.bi-info { color: var(--ink-faint); font-size: 12px; line-height: 1.7; }
.bi-status { display: inline-block; font-size: 11px; padding: 2px 7px; border-radius: 3px; margin-top: 5px; font-weight: 600; }
.status-ok { background: #EDFBF3; color: var(--green); }
.status-warn { background: #FFF8ED; color: #A05A00; }

/* ── CLASS CARDS ── */
.classes-grid { display: grid; grid-template-columns: repeat(3,1fr); gap: 13px; margin-bottom: 4px; }
@media(max-width:600px){ .classes-grid { grid-template-columns: 1fr; } }

.class-card { background: var(--white); border: 1.5px solid #E8DCC8; border-radius: 9px; overflow: hidden; position: relative; transition: all .25s ease; }
.class-card:hover { transform: translateY(-3px); box-shadow: 0 10px 28px rgba(200,150,62,.2); }

.class-header { padding: 15px 16px 11px; position: relative; }
.class-card:nth-child(1) .class-header { background: linear-gradient(135deg,#1A1208,#3D2E0E); }
.class-card:nth-child(2) .class-header { background: linear-gradient(135deg,#1A3A6A,#2A5A9A); }
.class-card:nth-child(3) .class-header { background: linear-gradient(135deg,#1E5A3A,#2A8A55); }

.class-tag { font-size: 10px; letter-spacing: 2px; color: rgba(255,255,255,.55); display: block; margin-bottom: 4px; }
.class-name { font-family: 'Noto Serif SC',serif; font-size: 20px; font-weight: 900; color: var(--white); display: block; }
.class-count { position: absolute; right: 14px; top: 50%; transform: translateY(-50%); text-align: right; }
.class-count .num { font-family: Georgia,serif; font-size: 28px; font-weight: 700; color: var(--gold-light); line-height: 1; }
.class-count .unit { font-size: 11px; color: rgba(255,255,255,.45); }

.class-body { padding: 13px 16px 15px; }
.class-price { font-size: 14px; color: var(--ink-faint); margin-bottom: 9px; font-family: 'Noto Serif SC',serif; }
.class-price span { font-size: 26px; font-weight: 900; color: var(--red); font-family: Georgia,serif; letter-spacing: -1px; }
.class-feature { font-size: 13px; color: var(--ink-light); line-height: 2.1; }
.class-feature strong { color: var(--ink-mid); font-weight: 500; }

.recommend-badge { position: absolute; top: 11px; left: -1px; background: var(--gold); color: var(--ink); font-size: 10px; font-weight: 700; padding: 2px 8px 2px 10px; clip-path: polygon(0 0,100% 0,90% 50%,100% 100%,0 100%); letter-spacing: 1px; }

/* ── TIPS ── */
.tips-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; }
@media(max-width:500px){ .tips-grid { grid-template-columns: 1fr; } }
.tip-item { background: var(--white); border: 1px solid #E8DCC8; border-radius: 8px; padding: 13px 14px; display: flex; gap: 10px; align-items: flex-start; }
.tip-icon { width: 32px; height: 32px; border-radius: 7px; display: flex; align-items: center; justify-content: center; font-size: 16px; flex-shrink: 0; }
.tip-text { font-size: 13.5px; color: var(--ink-light); line-height: 1.9; }
.tip-text strong { color: var(--ink-mid); font-weight: 600; display: block; margin-bottom: 2px; }

/* ── PROMO ── */
.promo-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 13px; }
@media(max-width:560px){ .promo-grid { grid-template-columns: 1fr; } }

.promo-card { border-radius: 11px; padding: 17px 16px; display: flex; gap: 13px; align-items: flex-start; position: relative; overflow: hidden; }
.promo-card::after { content: ''; position: absolute; right: -22px; bottom: -22px; width: 88px; height: 88px; border-radius: 50%; opacity: .09; }
.promo-deposit { background: linear-gradient(135deg,#FFF8ED,#FFF0D5); border: 1.5px solid #F0C870; }
.promo-deposit::after { background: var(--gold); }
.promo-group { background: linear-gradient(135deg,#EDF3FB,#DAE9FA); border: 1.5px solid #90B8E8; }
.promo-group::after { background: var(--blue); }
.promo-referral { background: linear-gradient(135deg,#EDFBF3,#D5F5E5); border: 1.5px solid #80D0A8; }
.promo-referral::after { background: var(--green); }
.promo-scholar { background: linear-gradient(135deg,#FDF2F2,#FAE0E0); border: 1.5px solid #E89090; }
.promo-scholar::after { background: var(--red); }

.promo-icon { font-size: 28px; flex-shrink: 0; line-height: 1; margin-top: 2px; }
.promo-title { font-family: 'Noto Serif SC',serif; font-size: 15px; font-weight: 700; color: var(--ink); margin-bottom: 7px; }
.promo-desc { font-size: 13px; color: var(--ink-light); line-height: 2.1; }
.promo-desc em { font-style: normal; font-weight: 700; color: var(--red); }
.promo-desc strong { color: var(--ink-mid); font-weight: 600; }
.promo-example { display: block; font-size: 12px; margin-top: 5px; padding: 5px 9px; background: rgba(0,0,0,.05); border-radius: 5px; color: var(--ink-mid); }
.promo-tag { display: inline-block; margin-top: 9px; font-size: 11px; font-weight: 600; letter-spacing: 1px; padding: 2px 11px; border-radius: 20px; background: rgba(0,0,0,.07); color: var(--ink-mid); }

/* ── FOOTER ── */
.footer { text-align: center; padding: 20px; font-size: 12px; color: var(--ink-faint); border-top: 1px solid #E8DCC8; margin-top: 10px; letter-spacing: 1px; }

/* ── ANIMATE ── */
@keyframes fadeUp { from { opacity: 0; transform: translateY(10px); } to { opacity: 1; transform: translateY(0); } }
.flow-step { animation: fadeUp .4s ease both; }
.flow-step:nth-child(1) { animation-delay: .05s; }
.flow-step:nth-child(2) { animation-delay: .12s; }
.flow-step:nth-child(3) { animation-delay: .19s; }
.flow-step:nth-child(4) { animation-delay: .26s; }
.flow-step:nth-child(5) { animation-delay: .33s; }
</style>
</head>
<body>

<!-- HEADER -->
<div class="header">
  <div class="header-badge">优学互连教育</div>
  <h1>2026届国网校园招聘·<span>笔试强化培训</span></h1>
  <div class="header-meta">
    <span><i class="dot"></i>成绩公布：3月17日 09:00</span>
    <span><i class="dot"></i>培训开班：3月17日下午</span>
    <span><i class="dot"></i>地点：酒店房改教室</span>
  </div>
</div>

<!-- NOTICE -->
<div class="notice-bar">⚡ 滚动开班 · 先到先得 · 满员即止 · 现场报名缴费即可入班</div>

<!-- MAIN -->
<div class="main">

  <!-- TABS：班次对比在左（默认），报名流程在右 -->
  <div class="tab-row">
    <button class="tab-btn active" onclick="switchTab('class')">📚 班次对比选择</button>
    <button class="tab-btn" onclick="switchTab('student')">📋 学生报名流程</button>
  </div>

  <!-- 班次对比（默认显示） -->
  <div id="tab-class" class="tab-panel active">

    <div class="section-title"><h2>三大班次 · 详细对比</h2></div>
    <div class="classes-grid">

      <div class="class-card">
        <div class="class-header">
          <span class="class-tag">TIER 01 · 精英</span>
          <span class="class-name">定制班</span>
          <div class="class-count"><div class="num">6</div><div class="unit">人满班</div></div>
        </div>
        <div class="class-body">
          <div class="class-price">¥<span>5,980</span></div>
          <div class="class-feature">
            <strong>适合：</strong>冲高分、基础薄弱需精讲<br>
            <strong>特点：</strong>一对多精讲，完全定制讲解<br>
            <strong>强度：</strong>高强度针对性训练<br>
            <strong>互动：</strong>随时提问，充分讨论
          </div>
        </div>
      </div>

      <div class="class-card">
        <div class="recommend-badge">推荐</div>
        <div class="class-header">
          <span class="class-tag">TIER 02 · 进阶</span>
          <span class="class-name">进阶班</span>
          <div class="class-count"><div class="num">8-10</div><div class="unit">人</div></div>
        </div>
        <div class="class-body">
          <div class="class-price">¥<span>3,180</span></div>
          <div class="class-feature">
            <strong>适合：</strong>有一定基础、高效提分<br>
            <strong>特点：</strong>高频考点系统梳理<br>
            <strong>强度：</strong>中高强度全面覆盖<br>
            <strong>互动：</strong>小组讨论，互相带动
          </div>
        </div>
      </div>

      <div class="class-card">
        <div class="class-header">
          <span class="class-tag">TIER 03 · VIP</span>
          <span class="class-name">VIP小班</span>
          <div class="class-count"><div class="num">12</div><div class="unit">人上限</div></div>
        </div>
        <div class="class-body">
          <div class="class-price">¥<span>1,980</span></div>
          <div class="class-feature">
            <strong>适合：</strong>全面备考、资源整合<br>
            <strong>特点：</strong>全模块覆盖，丰富题库<br>
            <strong>强度：</strong>系统完整，节奏稳健<br>
            <strong>互动：</strong>班级协作，资源共享
          </div>
        </div>
      </div>

    </div>

    <div class="section-title"><h2>如何快速选班</h2></div>
    <div class="tips-grid">
      <div class="tip-item">
        <div class="tip-icon" style="background:#FDF0E0;">💡</div>
        <div class="tip-text"><strong>基础薄弱 / 急需突破</strong>优先选「定制班」，6人精讲，针对性最强</div>
      </div>
      <div class="tip-item">
        <div class="tip-icon" style="background:#EDF3FB;">🎯</div>
        <div class="tip-text"><strong>有基础 / 想高效提分</strong>选「进阶班」，高频考点集中突破，性价比高</div>
      </div>
      <div class="tip-item">
        <div class="tip-icon" style="background:#EDFBF3;">📚</div>
        <div class="tip-text"><strong>全面备考 / 团队作战</strong>选「VIP小班」，覆盖面广，班级氛围好</div>
      </div>
      <div class="tip-item">
        <div class="tip-icon" style="background:#FBEEED;">⚡</div>
        <div class="tip-text"><strong>拿不定主意？</strong>告诉工作人员你的分数和弱项，30秒给出推荐！</div>
      </div>
    </div>

    <div class="section-title"><h2>优惠活动 · 限时专享</h2></div>
    <div class="promo-grid">

      <div class="promo-card promo-deposit">
        <div class="promo-icon">💰</div>
        <div class="promo-content">
          <div class="promo-title">早鸟定金优惠</div>
          <div class="promo-desc">
            出笔试成绩<strong>前</strong>交100元定金<br>
            立抵 <em>200元</em> 学费 · 定金可退
          </div>
          <div class="promo-tag">无风险 · 锁定名额</div>
        </div>
      </div>

      <div class="promo-card promo-group">
        <div class="promo-icon">👥</div>
        <div class="promo-content">
          <div class="promo-title">团报阶梯优惠</div>
          <div class="promo-desc">
            3人团：<em>9折 + 每人减100元</em><br>
            每多1人，每人再减100元<br>
            最高立省 <em>500元</em>
            <span class="promo-example">📌 5人团 = 9折 + 每人减300元</span>
          </div>
          <div class="promo-tag">人越多 · 省越多</div>
        </div>
      </div>

      <div class="promo-card promo-referral">
        <div class="promo-icon">🤝</div>
        <div class="promo-content">
          <div class="promo-title">老带新双向福利</div>
          <div class="promo-desc">
            老学员介绍一位新学员<br>
            老学员返 <em>200元现金</em><br>
            新学员立减 <em>100元</em> 学费
          </div>
          <div class="promo-tag">双向受益 · 推荐有礼</div>
        </div>
      </div>

      <div class="promo-card promo-scholar">
        <div class="promo-icon">🏆</div>
        <div class="promo-content">
          <div class="promo-title">面试奖学金</div>
          <div class="promo-desc">
            报面试班 · 按省内综合排名返学费：<br>
            🥇 第一名 → 返还 <em>100%</em> 学费<br>
            🥈 第二名 → 返还 <em>80%</em> 学费<br>
            🥉 第三名 → 返还 <em>50%</em> 学费
          </div>
          <div class="promo-tag">学得好 · 费用全返</div>
        </div>
      </div>

    </div>
  </div>

  <!-- 报名流程 -->
  <div id="tab-student" class="tab-panel">

    <div class="section-title"><h2>报名流程 · 五步入班</h2></div>

    <div class="flow-step">
      <div class="flow-left"><div class="step-circle s1">①</div><div class="step-line"></div></div>
      <div class="flow-right">
        <div class="step-card">
          <div class="step-top"><div class="step-title">到场 · 查成绩确认资格</div><div class="step-time">约 1 分钟</div></div>
          <div class="step-desc">
            3月17日上午9:00，登录国网招聘平台查询笔试成绩。<br>
            <strong>确认进入面试候选</strong>后，即可前往培训现场咨询报名。
          </div>
          <div class="step-actions">
            <span class="action-pill pill-gold">查询官方成绩</span>
            <span class="action-pill pill-blue">确认省份 / 专业方向</span>
          </div>
        </div>
      </div>
    </div>

    <div class="flow-step">
      <div class="flow-left"><div class="step-circle s2">②</div><div class="step-line"></div></div>
      <div class="flow-right">
        <div class="step-card">
          <div class="step-top"><div class="step-title">接待 · 快速了解情况</div><div class="step-time">约 2 分钟</div></div>
          <div class="step-desc">
            工作人员引导学生简单沟通三个方向：<br>
            ➤ 报考省份 &amp; 岗位类型<br>
            ➤ 笔试成绩大概区间<br>
            ➤ 备考基础与可用时间
          </div>
          <div class="step-actions">
            <span class="action-pill pill-blue">口头确认信息</span>
            <span class="action-pill pill-gold">领取班次对比单</span>
          </div>
        </div>
      </div>
    </div>

    <div class="flow-step">
      <div class="flow-left"><div class="step-circle s3">③</div><div class="step-line"></div></div>
      <div class="flow-right">
        <div class="step-card">
          <div class="step-top"><div class="step-title">选班 · 对照班次一键确认</div><div class="step-time">约 3 分钟</div></div>
          <div class="step-desc">根据情况，工作人员<strong>直接推荐适配班次</strong>，学生确认即可：</div>
          <div class="branch-box">
            <div class="branch-title">▸ 当前班次状态（实时更新）</div>
            <div class="branch-row">
              <div class="branch-item">
                <div class="bi-name">定制班</div>
                <div class="bi-info">6人满班<br>¥5,980 · 精讲定制</div>
                <span class="bi-status status-ok">招募中 ✓</span>
              </div>
              <div class="branch-item">
                <div class="bi-name">进阶班</div>
                <div class="bi-info">8-10人<br>¥3,180 · 系统强化</div>
                <span class="bi-status status-ok">招募中 ✓</span>
              </div>
              <div class="branch-item">
                <div class="bi-name">VIP小班</div>
                <div class="bi-info">12人上限<br>¥1,980 · 全面覆盖</div>
                <span class="bi-status status-warn">剩余少量</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="flow-step">
      <div class="flow-left"><div class="step-circle s4">④</div><div class="step-line"></div></div>
      <div class="flow-right">
        <div class="step-card">
          <div class="step-top"><div class="step-title">缴费 · 扫码完成报名</div><div class="step-time">约 1 分钟</div></div>
          <div class="step-desc">
            确认班次 → 扫码支付 → 截图发给工作人员 → <strong>登记姓名手机号</strong><br>
            支持：微信 / 支付宝 / 转账
          </div>
          <div class="step-actions">
            <span class="action-pill pill-green">扫码缴费</span>
            <span class="action-pill pill-gold">登记个人信息</span>
            <span class="action-pill pill-blue">领取《学员手册》</span>
          </div>
        </div>
      </div>
    </div>

    <div class="flow-step">
      <div class="flow-left"><div class="step-circle s5">⑤</div></div>
      <div class="flow-right">
        <div class="step-card">
          <div class="step-top"><div class="step-title">入班 · 等待开课通知</div><div class="step-time">即刻完成</div></div>
          <div class="step-desc">
            工作人员拉入<strong>专属班级群</strong>，通知入场时间与教室房号。<br>
            凑满人数后滚动开班，<strong>当天下午即可开课</strong>。
          </div>
          <div class="step-actions">
            <span class="action-pill pill-red">进入班级群</span>
            <span class="action-pill pill-gold">等待开班通知</span>
            <span class="action-pill pill-green">按时到教室</span>
          </div>
        </div>
      </div>
    </div>

  </div><!-- /tab-student -->

</div><!-- /main -->

<div class="footer">优学互连教育 · 2026届国网校园招聘笔试培训 · 3月17日 滚动开班</div>

<script>
function switchTab(name) {
  document.querySelectorAll('.tab-btn').forEach(b => b.classList.remove('active'));
  document.querySelectorAll('.tab-panel').forEach(p => p.classList.remove('active'));
  const idx = ['class','student'].indexOf(name);
  document.querySelectorAll('.tab-btn')[idx].classList.add('active');
  document.getElementById('tab-' + name).classList.add('active');
}
</script>
</body>
</html>
