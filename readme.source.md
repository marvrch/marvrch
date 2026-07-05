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
  <div style={{ position: 'relative', display: 'flex', flexDirection: 'column', padding: '42px 48px 34px 48px' }}>
    <div style={{ display: 'flex', alignItems: 'center', gap: 10, marginBottom: 30 }}>
      <div style={{ display: 'flex', alignItems: 'center', gap: 8, border: '1px solid rgba(94,234,212,.55)', background: 'rgba(94,234,212,.08)', borderRadius: 999, padding: '7px 12px' }}>
        <svg width="10" height="10">
          <circle id="live-dot" cx="5" cy="5" r="4" fill="#5EEAD4" opacity=".85" />
          <circle cx="5" cy="5" r="3" fill="#5EEAD4" />
        </svg>
        <span style={{ color: '#5EEAD4', fontSize: 12, fontWeight: 700, fontFamily: 'monospace' }}>PROFILE: LIVE</span>
      </div>
      <span style={{ color: '#A6ADBB', fontSize: 12, fontFamily: 'monospace', letterSpacing: 1 }}>// GITHUB README</span>
    </div>
    <div style={{ display: 'flex', flexDirection: 'column' }}>
      <span style={{ color: '#F4F4F5', fontSize: 54, fontWeight: 800, lineHeight: 1.03, letterSpacing: -.8 }}>Hi , I'm Marvin Chandiary</span>
      <span style={{ marginTop: 14, color: '#A6ADBB', fontSize: 22, lineHeight: 1.35 }}>Information Systems Student · Data Analytics &amp; BI Enthusiast · Always learning new things</span>
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

```aura width=860 height=220
<div style={{ position: 'relative', display: 'flex', width: '100%', height: '100%', overflow: 'hidden', borderRadius: 14, background: '#15171D', border: '1px solid #2D313B', fontFamily: 'Inter, sans-serif' }}>
  <svg width="860" height="220" style={{ position: 'absolute', inset: 0 }}>
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
    <rect width="860" height="220" fill="url(#aboutGrid)" opacity=".68" />
    <rect width="860" height="220" fill="url(#aboutAmber)" />
    <rect width="860" height="220" fill="url(#aboutMint)" />
  </svg>
  <div style={{ position: 'relative', display: 'flex', flexDirection: 'column', justifyContent: 'center', padding: '30px 36px' }}>
    <span style={{ color: '#F5A623', fontSize: 12, fontFamily: 'monospace', letterSpacing: 2.4, textTransform: 'uppercase', marginBottom: 16 }}>// about me</span>
    <span style={{ color: '#F4F4F5', fontSize: 21, lineHeight: 1.55, maxWidth: 780 }}>I'm an Information Systems student at BINUS University, passionate about turning data into insights. I focus on Data Analytics and Business Intelligence, and I love exploring tools that help make better, data-driven decisions. Outside of class, I build projects, learn new tech, and grow teamwork and leadership through organizational activities. Lifelong learner, always curious.</span>
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

```aura width=860 height=300
<div style={{ display: 'flex', flexDirection: 'column', gap: 14, width: '100%', height: '100%', borderRadius: 14, background: '#15171D', border: '1px solid #2D313B', fontFamily: 'Inter, sans-serif', padding: 22 }}>
  {[
    { title: '👉 Programming & Query Languages', items: ['Python', 'SQL'] },
    { title: '👉 Data Stack', items: ['Pandas', 'Seaborn', 'Jupyter'] },
    { title: '👉 Databases', items: ['Oracle', 'Microsoft SQL Server'] },
    { title: '👉 Software & Tools', items: ['Git', 'Visual Studio Code', 'Kaggle'] },
  ].map(function(group, index) {
    return (
      <div key={group.title} style={{ display: 'flex', alignItems: 'center', gap: 18, flex: 1, borderRadius: 10, background: 'rgba(10,11,14,.58)', border: '1px solid rgba(45,49,59,.9)', padding: '14px 16px' }}>
        <div style={{ display: 'flex', flexDirection: 'column', width: 282 }}>
          <span style={{ color: '#A6ADBB', fontSize: 11, fontFamily: 'monospace', letterSpacing: 1.4 }}>{String(index + 1).padStart(2, '0')}</span>
          <span style={{ color: '#F4F4F5', fontSize: 17, fontWeight: 700, marginTop: 4 }}>{group.title}</span>
        </div>
        <div style={{ display: 'flex', flexWrap: 'wrap', gap: 8 }}>
          {group.items.map(function(item) {
            return <span key={item} style={{ color: '#D8DCE3', background: 'rgba(94,234,212,.075)', border: '1px solid rgba(94,234,212,.23)', borderRadius: 7, padding: '7px 11px', fontSize: 13, fontFamily: 'monospace' }}>{item}</span>;
          })}
        </div>
      </div>
    );
  })}
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
    <a href="https://github.com/anuraghazra/github-readme-stats"><img alt="Marvin's Github Stats" src="https://github-readme-stats.vercel.app/api?username=marvrch&show_icons=true&count_private=true&theme=algolia" height="192px"></a>
    <br>
    &nbsp;
    <img src="https://github-readme-stats.vercel.app/api/top-langs?username=marvrch&show_icons=true&locale=en&layout=compact&theme=algolia" alt="marvrch" height="192px">
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
<SocialMediaButton icon="https://img.icons8.com/bubbles/50/000000/gmail.png" text="Gmail" backgroundColor="#15171D" textColor="#F4F4F5" borderColor="#2D313B" width={126} height={44} gradientStops={[{ offset: '0%', color: '#F5A623' }, { offset: '50%', color: '#5EEAD4' }, { offset: '100%', color: '#F5A623' }]} />
```
```aura width=132 height=44 link="https://github.com/marvrch" inline align=center
<SocialMediaButton icon="https://img.icons8.com/bubbles/50/000000/github.png" text="GitHub" backgroundColor="#15171D" textColor="#F4F4F5" borderColor="#2D313B" width={132} height={44} gradientStops={[{ offset: '0%', color: '#F5A623' }, { offset: '50%', color: '#5EEAD4' }, { offset: '100%', color: '#F5A623' }]} />
```
```aura width=144 height=44 link="https://www.linkedin.com/in/marvinchandiary" inline align=center
<SocialMediaButton icon="https://img.icons8.com/bubbles/50/000000/linkedin.png" text="LinkedIn" backgroundColor="#15171D" textColor="#F4F4F5" borderColor="#2D313B" width={144} height={44} gradientStops={[{ offset: '0%', color: '#F5A623' }, { offset: '50%', color: '#5EEAD4' }, { offset: '100%', color: '#F5A623' }]} />
```
```aura width=154 height=44 link="https://www.hackerrank.com/marvinchandiary" inline align=center
<SocialMediaButton icon="https://img.icons8.com/external-tal-revivo-color-tal-revivo/48/external-hackerrank-is-a-technology-company-that-focuses-on-competitive-programming-logo-color-tal-revivo.png" text="HackerRank" backgroundColor="#15171D" textColor="#F4F4F5" borderColor="#2D313B" width={154} height={44} gradientStops={[{ offset: '0%', color: '#F5A623' }, { offset: '50%', color: '#5EEAD4' }, { offset: '100%', color: '#F5A623' }]} />
```

---

<ul>
  <li>Credit: Template parts adapted from <a href="https://github.com/DenverCoder1">DenverCoder1</a> & <a href="https://github.com/anuraghazra">anuraghazra</a></li>
  <li>Last Edited on: 20/08/2025</li>
</ul>

<!-- Quick blurb for visitors -->

<p align="center">
  🌱 Currently learning <b>Data Analytics & Data Science</b> • 📫 Reach me at <b>marvinchandiary@gmail.com</b>
</p>
