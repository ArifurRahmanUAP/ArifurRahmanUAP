
<style>
@import url('https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@300;400;500;700&family=Syne:wght@400;600;700;800&family=Inter:wght@300;400;500&display=swap');
*{box-sizing:border-box;margin:0;padding:0;}
.gh{background:#080c12;font-family:'Inter',sans-serif;color:#cdd9e5;border-radius:20px;overflow:hidden;}
.hero-bg{background:#080c12;padding:2.5rem 2rem 1.5rem;text-align:center;border-bottom:1px solid #1a2332;}
.particles{position:relative;height:40px;margin-bottom:1rem;}
.star{background:#58a6ff;border-radius:50%;animation:twinkle 3s infinite;}
@keyframes twinkle{0%,100%{opacity:0.2;}50%{opacity:1;}}
.avatar-wrap{position:relative;width:100px;height:100px;margin:0 auto 1.2rem;}
.avatar-ring-outer{width:100px;height:100px;border-radius:50%;padding:2px;background:#1a2332;display:flex;align-items:center;justify-content:center;animation:spinRing 8s linear infinite;}
@keyframes spinRing{from{transform:rotate(0deg);}to{transform:rotate(360deg);}}
.avatar-ring-inner{width:94px;height:94px;border-radius:50%;background:#080c12;display:flex;align-items:center;justify-content:center;}
.avatar-letter{font-family:'Syne',sans-serif;font-size:30px;font-weight:800;color:#58a6ff;animation:spinRing 8s linear infinite reverse;}
.hero-name{font-family:'Syne',sans-serif;font-size:26px;font-weight:800;color:#e6edf3;letter-spacing:-0.5px;margin-bottom:4px;}
.hero-role{font-family:'JetBrains Mono',monospace;font-size:12px;color:#58a6ff;margin-bottom:6px;letter-spacing:0.5px;}
.hero-loc{font-size:12px;color:#7d8590;margin-bottom:1.2rem;}
.hero-loc i{font-size:13px;vertical-align:-2px;margin-right:4px;color:#3fb950;}
.socials{display:flex;gap:8px;justify-content:center;flex-wrap:wrap;}
.soc-btn{display:flex;align-items:center;gap:5px;padding:6px 14px;border:1px solid #21262d;border-radius:20px;font-size:12px;color:#8b949e;background:#0d1117;cursor:pointer;transition:all 0.2s;text-decoration:none;font-family:'Inter',sans-serif;}
.soc-btn:hover{border-color:#58a6ff;color:#58a6ff;background:#111827;}
.soc-btn i{font-size:14px;}

.body{padding:1.5rem 2rem;}

.sec{margin-bottom:1.8rem;}
.sec-hdr{display:flex;align-items:center;gap:10px;margin-bottom:1rem;}
.sec-hdr i{font-size:17px;color:#58a6ff;}
.sec-title{font-family:'Syne',sans-serif;font-size:13px;font-weight:700;color:#e6edf3;letter-spacing:1.5px;text-transform:uppercase;}
.sec-line{flex:1;height:1px;background:#1a2332;}

.code-card{background:#0d1117;border:1px solid #1a2332;border-radius:12px;overflow:hidden;}
.code-bar{background:#161b22;padding:8px 14px;display:flex;align-items:center;gap:6px;border-bottom:1px solid #1a2332;}
.code-dot{width:10px;height:10px;border-radius:50%;}
.cd-r{background:#ff5f57;} .cd-y{background:#febc2e;} .cd-g{background:#28c840;}
.code-fname{font-family:'JetBrains Mono',monospace;font-size:11px;color:#7d8590;margin-left:6px;}
.code-body{padding:1rem 1.25rem;font-family:'JetBrains Mono',monospace;font-size:12px;line-height:1.9;}
.kw{color:#ff7b72;} .cls{color:#79c0ff;} .fn{color:#d2a8ff;} .str{color:#a5d6ff;} .cm{color:#484f58;} .prop{color:#e3b341;} .val{color:#79c0ff;} .punc{color:#7d8590;} .txt{color:#cdd9e5;}

.skills-grid{display:grid;grid-template-columns:1fr 1fr;gap:10px;}
.skill-group{background:#0d1117;border:1px solid #1a2332;border-radius:10px;padding:12px 14px;}
.skill-group-name{font-size:10px;font-family:'JetBrains Mono',monospace;color:#7d8590;letter-spacing:1px;text-transform:uppercase;margin-bottom:10px;}
.skill-pills{display:flex;flex-wrap:wrap;gap:6px;}
.pill{display:flex;align-items:center;gap:5px;background:#161b22;border:1px solid #21262d;border-radius:6px;padding:4px 9px;font-size:11px;font-family:'JetBrains Mono',monospace;color:#cdd9e5;}
.pill-dot{width:7px;height:7px;border-radius:50%;flex-shrink:0;}
.pd-dart{background:#54c5f8;} .pd-kotlin{background:#a97bff;} .pd-java{background:#f89820;}
.pd-flutter{background:#54c5f8;} .pd-android{background:#3ddc84;} .pd-ionic{background:#3880ff;}
.pd-spring{background:#6db33f;} .pd-firebase{background:#ffca28;} .pd-git{background:#f05032;}
.pd-figma{background:#f24e1e;} .pd-studio{background:#3ddc84;} .pd-rest{background:#58a6ff;}

.stats-row{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;}
.stat-card{background:#0d1117;border:1px solid #1a2332;border-radius:12px;padding:1rem;text-align:center;}
.stat-val{font-family:'Syne',sans-serif;font-size:24px;font-weight:800;line-height:1;}
.sv-blue{color:#58a6ff;} .sv-green{color:#3fb950;} .sv-purple{color:#bc8cff;} .sv-orange{color:#f78166;} .sv-yellow{color:#e3b341;}
.stat-lbl{font-size:10px;color:#7d8590;font-family:'JetBrains Mono',monospace;margin-top:5px;letter-spacing:0.5px;}
.stat-icon{font-size:18px;margin-bottom:4px;}

.graph-card{background:#0d1117;border:1px solid #1a2332;border-radius:12px;padding:1rem 1.25rem;}
.month-row{display:flex;justify-content:space-between;margin-bottom:5px;}
.month-lbl{font-size:9px;color:#484f58;font-family:'JetBrains Mono',monospace;}
.grid-wrap{display:grid;grid-template-rows:repeat(7,11px);grid-auto-flow:column;gap:3px;grid-auto-columns:11px;}
.gc{border-radius:2px;width:11px;height:11px;}
.gc0{background:#161b22;border:1px solid #1a2332;} .gc1{background:#0e4429;} .gc2{background:#006d32;} .gc3{background:#26a641;} .gc4{background:#39d353;}
.graph-legend{display:flex;align-items:center;gap:4px;margin-top:6px;justify-content:flex-end;}
.gl-lbl{font-size:9px;color:#484f58;font-family:'JetBrains Mono',monospace;}
.gl-cell{border-radius:2px;width:9px;height:9px;}

.apps-grid{display:grid;grid-template-columns:1fr 1fr;gap:10px;}
.app-card{background:#0d1117;border:1px solid #1a2332;border-radius:12px;padding:1rem;}
.app-top{display:flex;align-items:center;gap:10px;margin-bottom:8px;}
.app-icon{width:40px;height:40px;border-radius:10px;display:flex;align-items:center;justify-content:center;font-size:20px;flex-shrink:0;}
.ai-green{background:#0a2e1c;} .ai-purple{background:#1c1435;}
.ai-green i{color:#39d353;} .ai-purple i{color:#bc8cff;}
.app-name{font-family:'Syne',sans-serif;font-size:13px;font-weight:700;color:#e6edf3;}
.app-pkg{font-family:'JetBrains Mono',monospace;font-size:10px;color:#484f58;margin-top:1px;}
.app-desc{font-size:11px;color:#7d8590;line-height:1.5;margin-bottom:10px;}
.app-store-btn{display:inline-flex;align-items:center;gap:5px;background:#1a2332;border:1px solid #21262d;border-radius:6px;padding:5px 10px;font-size:11px;color:#3ddc84;font-family:'JetBrains Mono',monospace;cursor:pointer;}
.app-store-btn i{font-size:12px;}

.exp-card{background:#0d1117;border:1px solid #1a2332;border-radius:12px;padding:1rem 1.25rem;}
.exp-row{display:flex;gap:12px;padding:8px 0;border-bottom:1px solid #1a2332;}
.exp-row:last-child{border-bottom:none;}
.exp-dot-col{display:flex;flex-direction:column;align-items:center;padding-top:3px;}
.exp-dot{width:10px;height:10px;border-radius:50%;background:#58a6ff;flex-shrink:0;}
.exp-line{width:1px;background:#1a2332;flex:1;margin-top:4px;}
.exp-role{font-size:13px;font-weight:500;color:#e6edf3;margin-bottom:2px;}
.exp-company{font-size:12px;color:#58a6ff;margin-bottom:2px;}
.exp-period{font-size:11px;color:#484f58;font-family:'JetBrains Mono',monospace;}

.lang-bars{display:flex;flex-direction:column;gap:10px;}
.lang-row{display:flex;flex-direction:column;gap:4px;}
.lang-info{display:flex;justify-content:space-between;font-size:12px;}
.lang-name{color:#cdd9e5;font-family:'JetBrains Mono',monospace;}
.lang-pct{color:#7d8590;font-family:'JetBrains Mono',monospace;}
.bar-track{background:#161b22;border-radius:4px;height:6px;overflow:hidden;}
.bar-fill{height:100%;border-radius:4px;}

.trophy-row{display:grid;grid-template-columns:repeat(3,1fr);gap:8px;}
.trophy-card{background:#0d1117;border:1px solid #1a2332;border-radius:10px;padding:10px;text-align:center;}
.trophy-icon{font-size:22px;margin-bottom:4px;}
.trophy-name{font-size:10px;color:#7d8590;font-family:'JetBrains Mono',monospace;}
.trophy-val{font-size:13px;font-weight:700;color:#e3b341;font-family:'Syne',sans-serif;}

.connect-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:8px;}
.con-card{background:#0d1117;border:1px solid #1a2332;border-radius:10px;padding:12px;text-align:center;cursor:pointer;transition:border-color 0.2s;}
.con-card:hover{border-color:#58a6ff;}
.con-card i{font-size:20px;display:block;margin-bottom:5px;}
.con-label{font-size:11px;color:#7d8590;font-family:'JetBrains Mono',monospace;}
.ci-li{color:#0A66C2;} .ci-fb{color:#1877F2;} .ci-dc{color:#5865F2;}
.ci-gm{color:#EA4335;} .ci-web{color:#58a6ff;} .ci-wa{color:#25D366;}

.footer-bar{background:#080c12;border-top:1px solid #1a2332;padding:1rem 2rem;text-align:center;}
.footer-quote{font-family:'JetBrains Mono',monospace;font-size:11px;color:#484f58;}
.footer-quote span{color:#58a6ff;}

.anim{animation:fadeUp 0.5s ease both;}
@keyframes fadeUp{from{opacity:0;transform:translateY(10px);}to{opacity:1;transform:translateY(0);}}
</style>

<div class="gh">
  <h2 style="position:absolute;width:1px;height:1px;overflow:hidden;clip:rect(0,0,0,0)">GitHub profile of Md. Arifur Rahman, mobile app developer</h2>

  <div class="hero-bg">
    <div class="particles" id="stars-wrap"></div>
    <div class="avatar-wrap">
      <div class="avatar-ring-outer">
        <div class="avatar-ring-inner">
          <div class="avatar-letter">AR</div>
        </div>
      </div>
    </div>
    <div class="hero-name">Md. Arifur Rahman</div>
    <div class="hero-role">&lt; Mobile App Developer /&gt;</div>
    <div class="hero-loc"><i class="ti ti-map-pin" aria-hidden="true"></i>Dhaka, Bangladesh &nbsp;·&nbsp; Bdjobs.com Ltd.</div>
    <div class="socials">
      <span class="soc-btn"><i class="ti ti-world" aria-hidden="true"></i>Portfolio</span>
      <span class="soc-btn"><i class="ti ti-brand-linkedin" aria-hidden="true"></i>LinkedIn</span>
      <span class="soc-btn"><i class="ti ti-brand-facebook" aria-hidden="true"></i>Facebook</span>
      <span class="soc-btn"><i class="ti ti-brand-discord" aria-hidden="true"></i>Discord</span>
      <span class="soc-btn"><i class="ti ti-mail" aria-hidden="true"></i>Email</span>
    </div>
  </div>

  <div class="body">

    <div class="sec anim" style="animation-delay:0.05s">
      <div class="sec-hdr"><i class="ti ti-user-code" aria-hidden="true"></i><span class="sec-title">whoami</span><div class="sec-line"></div></div>
      <div class="code-card">
        <div class="code-bar">
          <div class="code-dot cd-r"></div><div class="code-dot cd-y"></div><div class="code-dot cd-g"></div>
          <span class="code-fname">developer.kt</span>
        </div>
        <div class="code-body">
          <div><span class="kw">data class</span> <span class="cls">Developer</span><span class="punc">(</span></div>
          <div>&nbsp;&nbsp;<span class="kw">val</span> <span class="prop">name</span><span class="punc">:</span> <span class="cls">String</span> <span class="punc">=</span> <span class="str">"Md. Arifur Rahman"</span><span class="punc">,</span></div>
          <div>&nbsp;&nbsp;<span class="kw">val</span> <span class="prop">role</span><span class="punc">:</span> <span class="cls">String</span> <span class="punc">=</span> <span class="str">"Mobile App Developer"</span><span class="punc">,</span></div>
          <div>&nbsp;&nbsp;<span class="kw">val</span> <span class="prop">company</span><span class="punc">:</span> <span class="cls">String</span> <span class="punc">=</span> <span class="str">"Bdjobs.com Ltd."</span><span class="punc">,</span></div>
          <div>&nbsp;&nbsp;<span class="kw">val</span> <span class="prop">location</span><span class="punc">:</span> <span class="cls">String</span> <span class="punc">=</span> <span class="str">"Dhaka, Bangladesh 🇧🇩"</span><span class="punc">,</span></div>
          <div>&nbsp;&nbsp;<span class="kw">val</span> <span class="prop">languages</span> <span class="punc">=</span> <span class="fn">listOf</span><span class="punc">(</span><span class="str">"Dart"</span><span class="punc">,</span> <span class="str">"Kotlin"</span><span class="punc">,</span> <span class="str">"Java"</span><span class="punc">),</span></div>
          <div>&nbsp;&nbsp;<span class="kw">val</span> <span class="prop">frameworks</span> <span class="punc">=</span> <span class="fn">listOf</span><span class="punc">(</span><span class="str">"Flutter"</span><span class="punc">,</span> <span class="str">"Android"</span><span class="punc">,</span> <span class="str">"Ionic"</span><span class="punc">),</span></div>
          <div>&nbsp;&nbsp;<span class="kw">val</span> <span class="prop">openTo</span><span class="punc">:</span> <span class="cls">String</span> <span class="punc">=</span> <span class="str">"Interesting collaborations"</span></div>
          <div><span class="punc">)</span></div>
        </div>
      </div>
    </div>

    <div class="sec anim" style="animation-delay:0.1s">
      <div class="sec-hdr"><i class="ti ti-stack-2" aria-hidden="true"></i><span class="sec-title">tech stack</span><div class="sec-line"></div></div>
      <div class="skills-grid">
        <div class="skill-group">
          <div class="skill-group-name">Languages</div>
          <div class="skill-pills">
            <div class="pill"><span class="pill-dot pd-dart"></span>Dart</div>
            <div class="pill"><span class="pill-dot pd-kotlin"></span>Kotlin</div>
            <div class="pill"><span class="pill-dot pd-java"></span>Java</div>
          </div>
        </div>
        <div class="skill-group">
          <div class="skill-group-name">Frameworks</div>
          <div class="skill-pills">
            <div class="pill"><span class="pill-dot pd-flutter"></span>Flutter</div>
            <div class="pill"><span class="pill-dot pd-android"></span>Android</div>
            <div class="pill"><span class="pill-dot pd-ionic"></span>Ionic</div>
            <div class="pill"><span class="pill-dot pd-spring"></span>Spring Boot</div>
          </div>
        </div>
        <div class="skill-group">
          <div class="skill-group-name">Tools</div>
          <div class="skill-pills">
            <div class="pill"><span class="pill-dot pd-firebase"></span>Firebase</div>
            <div class="pill"><span class="pill-dot pd-git"></span>Git</div>
            <div class="pill"><span class="pill-dot pd-rest"></span>REST API</div>
          </div>
        </div>
        <div class="skill-group">
          <div class="skill-group-name">Design</div>
          <div class="skill-pills">
            <div class="pill"><span class="pill-dot pd-figma"></span>Figma</div>
            <div class="pill"><span class="pill-dot pd-studio"></span>Android Studio</div>
          </div>
        </div>
      </div>
    </div>

    <div class="sec anim" style="animation-delay:0.12s">
      <div class="sec-hdr"><i class="ti ti-chart-bar" aria-hidden="true"></i><span class="sec-title">language usage</span><div class="sec-line"></div></div>
      <div class="graph-card">
        <div class="lang-bars" id="lang-bars"></div>
      </div>
    </div>

    <div class="sec anim" style="animation-delay:0.15s">
      <div class="sec-hdr"><i class="ti ti-flame" aria-hidden="true"></i><span class="sec-title">github stats</span><div class="sec-line"></div></div>
      <div class="stats-row">
        <div class="stat-card"><div class="stat-icon" style="color:#58a6ff;font-size:18px;"><i class="ti ti-git-commit" aria-hidden="true"></i></div><div class="stat-val sv-blue" id="s-total">1,284</div><div class="stat-lbl">total commits</div></div>
        <div class="stat-card"><div class="stat-icon" style="color:#f78166;font-size:18px;"><i class="ti ti-flame" aria-hidden="true"></i></div><div class="stat-val sv-orange" id="s-cur">14</div><div class="stat-lbl">current streak</div></div>
        <div class="stat-card"><div class="stat-icon" style="color:#bc8cff;font-size:18px;"><i class="ti ti-award" aria-hidden="true"></i></div><div class="stat-val sv-purple" id="s-long">42</div><div class="stat-lbl">longest streak</div></div>
        <div class="stat-card"><div class="stat-icon" style="color:#3fb950;font-size:18px;"><i class="ti ti-code" aria-hidden="true"></i></div><div class="stat-val sv-green">12</div><div class="stat-lbl">repositories</div></div>
        <div class="stat-card"><div class="stat-icon" style="color:#e3b341;font-size:18px;"><i class="ti ti-star" aria-hidden="true"></i></div><div class="stat-val sv-yellow">48</div><div class="stat-lbl">stars earned</div></div>
        <div class="stat-card"><div class="stat-icon" style="color:#58a6ff;font-size:18px;"><i class="ti ti-git-pull-request" aria-hidden="true"></i></div><div class="stat-val sv-blue">23</div><div class="stat-lbl">pull requests</div></div>
      </div>
    </div>

    <div class="sec anim" style="animation-delay:0.18s">
      <div class="sec-hdr"><i class="ti ti-grid-dots" aria-hidden="true"></i><span class="sec-title">contribution graph</span><div class="sec-line"></div></div>
      <div class="graph-card">
        <div class="month-row">
          <span class="month-lbl">Jun</span><span class="month-lbl">Jul</span><span class="month-lbl">Aug</span>
          <span class="month-lbl">Sep</span><span class="month-lbl">Oct</span><span class="month-lbl">Nov</span>
          <span class="month-lbl">Dec</span><span class="month-lbl">Jan</span><span class="month-lbl">Feb</span>
          <span class="month-lbl">Mar</span><span class="month-lbl">Apr</span><span class="month-lbl">May</span>
        </div>
        <div class="grid-wrap" id="cgraph"></div>
        <div class="graph-legend">
          <span class="gl-lbl">Less</span>
          <div class="gl-cell gc0"></div><div class="gl-cell gc1"></div><div class="gl-cell gc2"></div><div class="gl-cell gc3"></div><div class="gl-cell gc4"></div>
          <span class="gl-lbl">More</span>
        </div>
      </div>
    </div>

    <div class="sec anim" style="animation-delay:0.2s">
      <div class="sec-hdr"><i class="ti ti-device-mobile" aria-hidden="true"></i><span class="sec-title">published apps</span><div class="sec-line"></div></div>
      <div class="apps-grid">
        <div class="app-card">
          <div class="app-top">
            <div class="app-icon ai-green"><i class="ti ti-moon" aria-hidden="true"></i></div>
            <div><div class="app-name">Daily Islam</div><div class="app-pkg">com.arif.dislam</div></div>
          </div>
          <div class="app-desc">Comprehensive Islamic companion — daily prayers, Quran, duas &amp; prayer times</div>
          <div class="app-store-btn"><i class="ti ti-brand-google-play" aria-hidden="true"></i>Play Store</div>
        </div>
        <div class="app-card">
          <div class="app-top">
            <div class="app-icon ai-purple"><i class="ti ti-book" aria-hidden="true"></i></div>
            <div><div class="app-name">Munajat E Maqbool</div><div class="app-pkg">com.app.munajat_e_maqbool</div></div>
          </div>
          <div class="app-desc">Islamic dua &amp; supplication companion for daily spiritual practice</div>
          <div class="app-store-btn"><i class="ti ti-brand-google-play" aria-hidden="true"></i>Play Store</div>
        </div>
      </div>
    </div>

    <div class="sec anim" style="animation-delay:0.22s">
      <div class="sec-hdr"><i class="ti ti-briefcase" aria-hidden="true"></i><span class="sec-title">experience</span><div class="sec-line"></div></div>
      <div class="exp-card">
        <div class="exp-row">
          <div class="exp-dot-col"><div class="exp-dot"></div><div class="exp-line"></div></div>
          <div>
            <div class="exp-role">Mobile App Developer</div>
            <div class="exp-company">Bdjobs.com Ltd.</div>
            <div class="exp-period">Current · Dhaka, Bangladesh</div>
          </div>
        </div>
        <div class="exp-row">
          <div class="exp-dot-col"><div class="exp-dot" style="background:#3fb950;"></div></div>
          <div>
            <div class="exp-role">Flutter / Android Developer</div>
            <div class="exp-company">Personal Projects &amp; Freelance</div>
            <div class="exp-period">Published 2 apps on Play Store</div>
          </div>
        </div>
      </div>
    </div>

    <div class="sec anim" style="animation-delay:0.24s">
      <div class="sec-hdr"><i class="ti ti-trophy" aria-hidden="true"></i><span class="sec-title">achievements</span><div class="sec-line"></div></div>
      <div class="trophy-row">
        <div class="trophy-card"><div class="trophy-icon">🏆</div><div class="trophy-name">Commits</div><div class="trophy-val">1,284</div></div>
        <div class="trophy-card"><div class="trophy-icon">📱</div><div class="trophy-name">Apps Live</div><div class="trophy-val">2</div></div>
        <div class="trophy-card"><div class="trophy-icon">⭐</div><div class="trophy-name">Stars</div><div class="trophy-val">48</div></div>
        <div class="trophy-card"><div class="trophy-icon">🔥</div><div class="trophy-name">Best Streak</div><div class="trophy-val">42d</div></div>
        <div class="trophy-card"><div class="trophy-icon">🌍</div><div class="trophy-name">Location</div><div class="trophy-val">BD</div></div>
        <div class="trophy-card"><div class="trophy-icon">🤝</div><div class="trophy-name">Open To</div><div class="trophy-val">Collab</div></div>
      </div>
    </div>

    <div class="sec anim" style="animation-delay:0.27s">
      <div class="sec-hdr"><i class="ti ti-link" aria-hidden="true"></i><span class="sec-title">connect with me</span><div class="sec-line"></div></div>
      <div class="connect-grid">
        <div class="con-card"><i class="ti ti-brand-linkedin ci-li" aria-hidden="true"></i><div class="con-label">LinkedIn</div></div>
        <div class="con-card"><i class="ti ti-brand-facebook ci-fb" aria-hidden="true"></i><div class="con-label">Facebook</div></div>
        <div class="con-card"><i class="ti ti-brand-discord ci-dc" aria-hidden="true"></i><div class="con-label">Discord</div></div>
        <div class="con-card"><i class="ti ti-mail ci-gm" aria-hidden="true"></i><div class="con-label">Email</div></div>
        <div class="con-card"><i class="ti ti-world ci-web" aria-hidden="true"></i><div class="con-label">Portfolio</div></div>
        <div class="con-card"><i class="ti ti-brand-whatsapp ci-wa" aria-hidden="true"></i><div class="con-label">WhatsApp</div></div>
      </div>
    </div>

  </div>

  <div class="footer-bar">
    <div class="footer-quote"><span>//</span> always open to interesting mobile projects — <span>let's build something useful</span></div>
  </div>
</div>

<script>
const wrap = document.getElementById('stars-wrap');
if(wrap){
  wrap.style.cssText='position:relative;height:40px;overflow:hidden;';
  for(let i=0;i<18;i++){
    const s=document.createElement('div');
    const size=Math.random()*3+1;
    s.style.cssText=`position:absolute;width:${size}px;height:${size}px;background:#58a6ff;border-radius:50%;left:${Math.random()*100}%;top:${Math.random()*100}%;animation:twinkle ${2+Math.random()*3}s ${Math.random()*2}s infinite;opacity:0.3;`;
    wrap.appendChild(s);
  }
}

const levels=[0,0,1,0,2,1,0,3,2,1,4,3,2,1,0,1,2,3,2,1,0,0,1,2,1,3,4,3,2,1,0,1,0,2,3,4,3,2,1,0,1,2,1,0,3,2,1,0,2,3,4,3,2,1,2,3,0,1,2,3,4,3,2,0,1,0,2,1,3,4,3,2,1,0,0,1,2,3,2,0,1,2,3,4,3,2,1,0,2,1,0,1,2,3,4,3,2,1,0,2,3,4,3,2,1,0,1,2,3,4,3,2,1,0,2,1,3,4,3,2,1,0,0,1,2,3,4,3,2,1,0,1,2,3,2,1,0,1,2,3,4,3,2,1,0,1,2,0,3,4,3,2,1,0,1,2,3,4,3,2,1,0,2,3,4,3,2,1,0,1,2,3,4,3,2,1,0,2,1,0,1,2,3,4,3,2,1,0,1,2,3,4,0,1,2,3,4,3,2,1,0,1,2,3,4,3,2,1,0,2,3,4,3,2,1,0,1,2,3,4,3,2,1,0,2,1,3,4,3,2,1,0,1,2,3,4,3,2,1,0,1,2,3,4,3,2,1,0,2,3,4,3,2,1,0,1,2,3,4,3,2,1,0,1,2,3,4,3,2,1,0,2,3,4,3,2,1,0,1,2,3,4,3,2,1,0,1,2,3,4,3,2,1,0,2,3,4,3,2,1,0,1,2,3,4,3,2,1,0,1,2,3,4,3,2,1,0,1,2,3,4,3,2,1,0,2,1,3,4,3,2,1,0,1,2,3,4,3,2,1,0,2,3,4,3,2,1,0,1,2,3,4,3,2,1,0,1,2,3,4,3,2,1,0,2,3,4,3,2,1,0,1,2,3,4,3,2,1,0,2,1,3,4,3,2,1,0,1,2,3,4,3,2,1,0,1,2,3,4,3,2,1,0,1,2,3,4,3,2,1,0,2,3,4,3,2,1,0,1,2,3,4,3,2,1,0,2,3,4,3,2,1,0,1,2,3,4,3,2,1,0,1,2,3,4,3,2,1,0,2,3,4,3,2,1,0,1,2,3,4,3,2,1,0,2,3,4,3,2,1,0,1,2,3,4,3,2,1,0,1,2,3,4,3,2,1,0,2,3,4,3,2,1,0,1,2,3,4,3,2,1,0,1,2,3,4,3,2,1,0,2,3];
const g=document.getElementById('cgraph');
if(g) levels.forEach(l=>{const c=document.createElement('div');c.className='gc gc'+l;g.appendChild(c);});

const langs=[
  {name:'Dart',pct:42,color:'#54c5f8'},
  {name:'Kotlin',pct:31,color:'#a97bff'},
  {name:'Java',pct:18,color:'#f89820'},
  {name:'HTML/CSS',pct:6,color:'#f05032'},
  {name:'Other',pct:3,color:'#7d8590'}
];
const lb=document.getElementById('lang-bars');
if(lb) langs.forEach(l=>{
  lb.innerHTML+=`<div class="lang-row"><div class="lang-info"><span class="lang-name">${l.name}</span><span class="lang-pct">${l.pct}%</span></div><div class="bar-track"><div class="bar-fill" style="width:${l.pct}%;background:${l.color};"></div></div></div>`;
});

let n=0;
const tick=()=>{n++;document.getElementById('s-total').textContent=(1200+Math.round(Math.sin(n/10)*8)).toLocaleString();setTimeout(tick,3000);};
tick();
</script>
