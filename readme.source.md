```aura width=860 height=340
<div style={{ position: 'relative', display: 'flex', flexDirection: 'column', justifyContent: 'center', width: '100%', height: '100%', overflow: 'hidden', borderRadius: 18, background: '#0A0B0E', border: '1px solid #2D313B', fontFamily: 'Inter, sans-serif' }}>
  <style>{`
    @keyframes pulse-dot { 0%, 100% { opacity: 1; transform: scale(1); } 50% { opacity: 0.42; transform: scale(1.8); } }
    @keyframes scan { 0% { transform: translateY(-120px); opacity: 0; } 18%, 75% { opacity: .65; } 100% { transform: translateY(360px); opacity: 0; } }
    #live-dot { animation: pulse-dot 1.8s ease-in-out infinite; transform-origin: center; }
    #scan-line { animation: scan 6s linear infinite; }
  `}</style>
  <svg width="860" height="340" style={{ position: 'absolute', inset: 0 }}>
    <defs>
      <radialGradient id="amberGlow" cx="25%" cy="8%" r="65%">
        <stop offset="0%" stopColor="rgba(245,166,35,0.26)" />
        <stop offset="100%" stopColor="rgba(245,166,35,0)" />
      </radialGradient>
      <radialGradient id="mintGlow" cx="86%" cy="20%" r="54%">
        <stop offset="0%" stopColor="rgba(94,234,212,0.18)" />
        <stop offset="100%" stopColor="rgba(94,234,212,0)" />
      </radialGradient>
      <pattern id="grid" width="48" height="48" patternUnits="userSpaceOnUse">
        <path d="M 48 0 L 0 0 0 48" fill="none" stroke="rgba(45,49,59,.72)" strokeWidth="1" />
      </pattern>
      <linearGradient id="headline" x1="0" x2="1" y1="0" y2="1">
        <stop offset="0%" stopColor="#F5A623" />
        <stop offset="72%" stopColor="#5EEAD4" />
      </linearGradient>
    </defs>
    <rect width="860" height="340" fill="url(#grid)" opacity=".7" />
    <rect width="860" height="340" fill="url(#amberGlow)" />
    <rect width="860" height="340" fill="url(#mintGlow)" />
    <rect id="scan-line" x="0" y="0" width="860" height="70" fill="rgba(94,234,212,.045)" />
    <line x1="42" y1="279" x2="818" y2="279" stroke="rgba(94,234,212,.3)" strokeWidth="1" strokeDasharray="8 10" />
    <circle cx="770" cy="66" r="52" fill="none" stroke="rgba(94,234,212,.24)" />
    <circle cx="770" cy="66" r="86" fill="none" stroke="rgba(245,166,35,.16)" />
  </svg>
  <div style={{ position: 'relative', display: 'flex', flexDirection: 'column', alignItems: 'flex-start', padding: '42px 48px 34px 48px' }}>
    <div style={{ display: 'flex', alignItems: 'center', gap: 10, marginBottom: 30 }}>
      <div style={{ display: 'flex', alignItems: 'center', gap: 8, border: '1px solid rgba(94,234,212,.55)', background: 'rgba(94,234,212,.08)', borderRadius: 999, padding: '7px 12px' }}>
        <svg width="10" height="10">
          <circle id="live-dot" cx="5" cy="5" r="4" fill="#5EEAD4" opacity=".85" />
          <circle cx="5" cy="5" r="3" fill="#5EEAD4" />
        </svg>
        <span style={{ color: '#5EEAD4', fontSize: 12, fontWeight: 700, fontFamily: 'monospace' }}>PROFILE: LIVE</span>
      </div>
      <span style={{ color: '#A6ADBB', fontSize: 12, fontFamily: 'monospace', letterSpacing: 1 }}>// GITHUB PROFILE</span>
    </div>
    <div style={{ display: 'flex', flexDirection: 'column' }}>
      <span style={{ color: '#F4F4F5', fontSize: 54, fontWeight: 800, lineHeight: 1.03, letterSpacing: -.8 }}>Hi, I'm Marvin Chandiary</span>
      <span style={{ marginTop: 14, color: '#A6ADBB', fontSize: 22, lineHeight: 1.35 }}>Information Systems Student · Data Analytics &amp; BI Enthusiast</span>
      <div style={{ display: 'flex', alignItems: 'center', gap: 9, marginTop: 25, border: '1px solid rgba(245,166,35,.28)', background: 'rgba(21,23,29,.72)', borderRadius: 8, padding: '13px 15px', width: 536 }}>
        <span style={{ color: '#F5A623', fontSize: 17, fontFamily: 'monospace' }}>&gt;</span>
        <span style={{ color: '#5EEAD4', fontSize: 14, fontFamily: 'monospace' }}>Always learning new things</span>
        <span style={{ width: 8, height: 18, background: '#5EEAD4' }} />
      </div>
    </div>
  </div>
</div>
```

<p align="center"> <img src="https://komarev.com/ghpvc/?username=marvrch&label=Profile%20views&color=f5a623&style=flat" alt="marvrch"> </p>

```aura width=860 height=178
<div style={{ position: 'relative', display: 'flex', width: '100%', height: '100%', overflow: 'hidden', borderRadius: 14, background: '#15171D', border: '1px solid #2D313B', fontFamily: 'Inter, sans-serif' }}>
  <svg width="860" height="178" style={{ position: 'absolute', inset: 0 }}>
    <defs>
      <pattern id="aboutGrid" width="36" height="36" patternUnits="userSpaceOnUse">
        <path d="M 36 0 L 0 0 0 36" fill="none" stroke="rgba(45,49,59,.55)" strokeWidth="1" />
      </pattern>
      <radialGradient id="aboutAmber" cx="5%" cy="0%" r="70%">
        <stop offset="0%" stopColor="rgba(245,166,35,.18)" />
        <stop offset="100%" stopColor="rgba(245,166,35,0)" />
      </radialGradient>
      <radialGradient id="aboutMint" cx="94%" cy="100%" r="62%">
        <stop offset="0%" stopColor="rgba(94,234,212,.13)" />
        <stop offset="100%" stopColor="rgba(94,234,212,0)" />
      </radialGradient>
    </defs>
    <rect width="860" height="178" fill="url(#aboutGrid)" opacity=".68" />
    <rect width="860" height="178" fill="url(#aboutAmber)" />
    <rect width="860" height="178" fill="url(#aboutMint)" />
  </svg>
  <div style={{ position: 'relative', display: 'flex', flexDirection: 'column', justifyContent: 'center', padding: '24px 36px' }}>
    <span style={{ color: '#F5A623', fontSize: 11, fontFamily: 'monospace', letterSpacing: 2.4, textTransform: 'uppercase', marginBottom: 12 }}>// about me</span>
    <span style={{ color: '#F4F4F5', fontSize: 17, lineHeight: 1.5, maxWidth: 790 }}>I'm an Information Systems student at BINUS University, passionate about turning data into insights. I focus on Data Analytics and Business Intelligence, and I love exploring tools that help make better, data-driven decisions. Outside of class, I build projects, learn new tech, and grow teamwork and leadership through organizational activities. Lifelong learner, always curious.</span>
  </div>
</div>
```

```aura width=860 height=78
<div style={{ display: 'flex', alignItems: 'center', width: '100%', height: '100%', borderRadius: 12, background: '#0A0B0E', border: '1px solid #2D313B', fontFamily: 'Inter, sans-serif', padding: '0 24px' }}>
  <span style={{ color: '#F5A623', fontSize: 13, fontFamily: 'monospace', letterSpacing: 2.2, marginRight: 14 }}>// 01</span>
  <span style={{ color: '#F4F4F5', fontSize: 28, fontWeight: 800 }}>🔥 Streak Stats</span>
  <div style={{ flex: 1, height: 1, background: 'rgba(94,234,212,.28)', marginLeft: 22 }} />
</div>
```

<p align="center"><img src="https://github-readme-streak-stats.herokuapp.com/?user=marvrch&theme=algolia" alt="marvrch"></p>

```aura width=860 height=78
<div style={{ display: 'flex', alignItems: 'center', width: '100%', height: '100%', borderRadius: 12, background: '#0A0B0E', border: '1px solid #2D313B', fontFamily: 'Inter, sans-serif', padding: '0 24px' }}>
  <span style={{ color: '#F5A623', fontSize: 13, fontFamily: 'monospace', letterSpacing: 2.2, marginRight: 14 }}>// 02</span>
  <span style={{ color: '#F4F4F5', fontSize: 28, fontWeight: 800 }}>🛠️ My Skills</span>
  <div style={{ flex: 1, height: 1, background: 'rgba(94,234,212,.28)', marginLeft: 22 }} />
</div>
```

```aura width=860 height=500
<div style={{ position: 'relative', display: 'flex', width: '100%', height: '100%', background: '#0A0B0E', fontFamily: 'Inter, sans-serif', padding: '8px 8px 8px 34px' }}>
  <div style={{ position: 'absolute', left: 18, top: 0, bottom: 0, width: 1, background: 'rgba(45,49,59,.85)' }} />
  <div style={{ position: 'absolute', left: 14, top: 38, width: 9, height: 9, borderRadius: 999, background: '#F5A623' }} />
  <div style={{ display: 'flex', flexDirection: 'column', width: '100%', height: '100%', borderRadius: 12, background: '#0D1116', border: '1px solid rgba(245,166,35,.48)', boxShadow: 'inset 0 1px 0 rgba(255,255,255,.04)', padding: 20 }}>
    <div style={{ display: 'flex', alignItems: 'flex-start', justifyContent: 'space-between', marginBottom: 18 }}>
      <div style={{ display: 'flex', flexDirection: 'column' }}>
        <span style={{ color: '#F4F4F5', fontSize: 20, fontWeight: 800 }}>Core foundations in progress.</span>
        <span style={{ color: '#A6ADBB', fontSize: 13, marginTop: 9 }}>My Skills</span>
      </div>
      <span style={{ color: '#5EEAD4', fontSize: 12, fontWeight: 800, fontFamily: 'monospace' }}>Fundamentals</span>
    </div>
    <div style={{ display: 'flex', flexWrap: 'wrap', gap: 12, flex: 1 }}>
  {[
    { title: '👉 Programming & Query Fundamentals', summary: 'Readable Python scripts and SQL queries for practical analysis.', items: ['Python', 'SQL'] },
    { title: '👉 Analysis Foundation', summary: 'Data cleaning, notebooks, and charting for repeatable insight work.', items: ['Pandas', 'Seaborn', 'Jupyter'] },
    { title: '👉 Database Basics', summary: 'Relational concepts, joins, aggregation, and reporting-ready tables.', items: ['Oracle', 'Microsoft SQL Server'] },
    { title: '👉 Workflow Tools', summary: 'Version control, coding environment, and practice platforms.', items: ['Git', 'Visual Studio Code', 'Kaggle'] },
  ].map(function(group, index) {
    return (
      <div key={group.title} style={{ display: 'flex', flexDirection: 'column', justifyContent: 'space-between', width: 374, height: 166, borderRadius: 10, background: 'rgba(10,11,14,.72)', border: '1px solid rgba(45,49,59,.95)', padding: '15px 16px' }}>
        <div style={{ display: 'flex', flexDirection: 'column' }}>
          <span style={{ color: '#A6ADBB', fontSize: 11, fontFamily: 'monospace', letterSpacing: 1.2 }}>{String(index + 1).padStart(2, '0')}</span>
          <span style={{ color: '#F4F4F5', fontSize: 16, fontWeight: 800, marginTop: 8 }}>{group.title}</span>
          <span style={{ color: '#A6ADBB', fontSize: 13, lineHeight: 1.45, marginTop: 9 }}>{group.summary}</span>
        </div>
        <div style={{ display: 'flex', flexWrap: 'wrap', gap: 7, marginTop: 14 }}>
          {group.items.map(function(item) {
            return <span key={item} style={{ color: '#D8DCE3', background: 'rgba(10,11,14,.6)', border: '1px solid rgba(94,234,212,.23)', borderRadius: 7, padding: '6px 10px', fontSize: 12, fontFamily: 'monospace' }}>{item}</span>;
          })}
        </div>
      </div>
    );
  })}
    </div>
  </div>
</div>
```

```aura width=860 height=78
<div style={{ display: 'flex', alignItems: 'center', width: '100%', height: '100%', borderRadius: 12, background: '#0A0B0E', border: '1px solid #2D313B', fontFamily: 'Inter, sans-serif', padding: '0 24px' }}>
  <span style={{ color: '#F5A623', fontSize: 13, fontFamily: 'monospace', letterSpacing: 2.2, marginRight: 14 }}>// 03</span>
  <span style={{ color: '#F4F4F5', fontSize: 28, fontWeight: 800 }}>📊 GitHub Stats (Expand to View)</span>
  <div style={{ flex: 1, height: 1, background: 'rgba(94,234,212,.28)', marginLeft: 22 }} />
</div>
```

<details>
  <summary><b>💻 GitHub Profile Stats</b></summary>
  <br>
  <p align="center">
    <a href="https://github.com/stats-organization/github-stats-extended"><img alt="Marvin's Github Stats" src="https://github-stats-extended.vercel.app/api?username=marvrch&show_icons=true&count_private=true&title_color=f5a623&text_color=d8dce3&icon_color=5eead4&bg_color=0a0b0e&border_color=2d313b&border_radius=8" height="192px"></a>
    <br>
    &nbsp;
    <img src="https://github-stats-extended.vercel.app/api/top-langs?username=marvrch&show_icons=true&locale=en&layout=compact&langs_count=8&title_color=f5a623&text_color=d8dce3&icon_color=5eead4&bg_color=0a0b0e&border_color=2d313b&border_radius=8" alt="Most used languages" height="192px">
    <br>
    <b>Note:</b> Top languages is a metric of the languages in my public repos and doesn't reflect experience or skill level.
  </p>
</details>

<details>
  <summary><b>⚡ Recent GitHub Activity</b></summary>
  <br>
  <a href="https://github.com/marvrch"><img alt="Marvin's Activity Graph" src="https://github-readme-activity-graph.vercel.app/graph?username=marvrch&custom_title=Marvin%27s%20Contribution%20Graph&theme=react-dark&hide_border=true"></a>
  <br>
</details>

```aura width=860 height=78
<div style={{ display: 'flex', alignItems: 'center', width: '100%', height: '100%', borderRadius: 12, background: '#0A0B0E', border: '1px solid #2D313B', fontFamily: 'Inter, sans-serif', padding: '0 24px' }}>
  <span style={{ color: '#F5A623', fontSize: 13, fontFamily: 'monospace', letterSpacing: 2.2, marginRight: 14 }}>// 04</span>
  <span style={{ color: '#F4F4F5', fontSize: 28, fontWeight: 800 }}>🙋‍♂️ Let’s Connect</span>
  <div style={{ flex: 1, height: 1, background: 'rgba(94,234,212,.28)', marginLeft: 22 }} />
</div>
```

```aura width=126 height=44 link="mailto:marvinchandiary@gmail.com" inline align=center
<SocialMediaButton icon="https://img.icons8.com/bubbles/50/000000/gmail.png" text="Email" backgroundColor="#15171D" textColor="#F4F4F5" borderColor="#2D313B" width={126} height={44} gradientStops={[{ offset: '0%', color: '#F5A623' }, { offset: '50%', color: '#5EEAD4' }, { offset: '100%', color: '#F5A623' }]} />
```
```aura width=144 height=44 link="https://www.linkedin.com/in/marvinchandiary" inline align=center
<SocialMediaButton icon="https://img.icons8.com/bubbles/50/000000/linkedin.png" text="LinkedIn" backgroundColor="#15171D" textColor="#F4F4F5" borderColor="#2D313B" width={144} height={44} gradientStops={[{ offset: '0%', color: '#F5A623' }, { offset: '50%', color: '#5EEAD4' }, { offset: '100%', color: '#F5A623' }]} />
```
```aura width=132 height=44 link="https://drive.google.com/file/d/1lQHH1OpiArFIfbbTV92y0YXVZJhw-1rv/view?usp=sharing" inline align=center
<SocialMediaButton icon="https://img.icons8.com/bubbles/50/000000/resume.png" text="Resume" backgroundColor="#15171D" textColor="#F4F4F5" borderColor="#2D313B" width={132} height={44} gradientStops={[{ offset: '0%', color: '#F5A623' }, { offset: '50%', color: '#5EEAD4' }, { offset: '100%', color: '#F5A623' }]} />
```

---

<ul>
  <li>Credit: Design inspired by <a href="https://github.com/collectioneur/readme-aura">collectioneur/readme-aura</a> and <a href="https://github.com/formidablae/formidablae">formidablae/formidablae</a>; template and stats parts adapted from <a href="https://github.com/DenverCoder1">DenverCoder1</a>, <a href="https://github.com/anuraghazra">anuraghazra</a>, and <a href="https://github.com/stats-organization/github-stats-extended">stats-organization/github-stats-extended</a></li>
  <li>Last Edited on: 05/07/2026</li>
</ul>

<!-- Quick blurb for visitors -->

<p align="center">
  🌱 Currently learning <b>Data Engineering</b> • 📫 Reach me at <b>marvinchandiary@gmail.com</b>
</p>
