```aura width=860 height=200
<div style={{
  width: '100%',
  height: '100%',
  background: '#08080c',
  display: 'flex',
  alignItems: 'center',
  fontFamily: 'Inter',
  position: 'relative',
  overflow: 'hidden',
  borderRadius: 16,
  border: '1px solid rgba(110,80,220,0.18)'
}}>
  <style>{`
    @keyframes float1 {
      0%, 100% { transform: translate(0, 0); opacity: .55; }
      50% { transform: translate(180px, -20px); opacity: .9; }
    }

    @keyframes float2 {
      0%, 100% { transform: translate(0, 0); opacity: .4; }
      50% { transform: translate(-160px, 20px); opacity: .8; }
    }

    #glow1 { animation: float1 10s ease-in-out infinite; }
    #glow2 { animation: float2 13s ease-in-out infinite; }
  `}</style>

  <svg width="860" height="200" style={{
    position: 'absolute',
    top: 0,
    left: 0
  }}>
    <defs>
      <radialGradient id="purple">
        <stop offset="0%" stopColor="rgba(120,50,255,.65)" />
        <stop offset="65%" stopColor="rgba(90,30,220,.12)" />
        <stop offset="100%" stopColor="rgba(90,30,220,0)" />
      </radialGradient>

      <radialGradient id="blue">
        <stop offset="0%" stopColor="rgba(30,100,255,.5)" />
        <stop offset="65%" stopColor="rgba(20,80,220,.1)" />
        <stop offset="100%" stopColor="rgba(20,80,220,0)" />
      </radialGradient>
    </defs>

    <ellipse
      id="glow1"
      cx="160"
      cy="210"
      rx="310"
      ry="190"
      fill="url(#purple)"
    />

    <ellipse
      id="glow2"
      cx="720"
      cy="210"
      rx="310"
      ry="190"
      fill="url(#blue)"
    />
  </svg>

  <div style={{
    position: 'absolute',
    left: 48,
    top: 52,
    width: 96,
    height: 96,
    borderRadius: 48,
    background: 'linear-gradient(135deg, #6622ee, #0088ff)',
    display: 'flex',
    alignItems: 'center',
    justifyContent: 'center'
  }}>
    <img
      src="https://github.com/xotwodfr.png"
      width={88}
      height={88}
      style={{ borderRadius: 44 }}
    />
  </div>

  <div style={{
    display: 'flex',
    flexDirection: 'column',
    marginLeft: 168,
    gap: 8,
    position: 'relative'
  }}>
    <div style={{
      display: 'flex',
      fontSize: 38,
      fontWeight: 800,
      color: '#ffffff',
      letterSpacing: '-1px',
      lineHeight: 1
    }}>
      Folke
    </div>

    <div style={{
      display: 'flex',
      fontSize: 15,
      color: 'rgba(180,165,255,.8)',
      letterSpacing: '.3px'
    }}>
      Linux • Homelabbing • Self-hosting
    </div>

    <div style={{
      display: 'flex',
      gap: 8,
      marginTop: 6
    }}>
      <div style={{
        display: 'flex',
        padding: '4px 12px',
        borderRadius: 20,
        background: 'rgba(80,40,220,.18)',
        border: '1px solid rgba(100,70,240,.32)',
        color: 'rgba(205,195,255,.85)',
        fontSize: 12,
        fontWeight: 600
      }}>
        Linux
      </div>

      <div style={{
        display: 'flex',
        padding: '4px 12px',
        borderRadius: 20,
        background: 'rgba(80,40,220,.18)',
        border: '1px solid rgba(100,70,240,.32)',
        color: 'rgba(205,195,255,.85)',
        fontSize: 12,
        fontWeight: 600
      }}>
        Homelabbing
      </div>

      <div style={{
        display: 'flex',
        padding: '4px 12px',
        borderRadius: 20,
        background: 'rgba(80,40,220,.18)',
        border: '1px solid rgba(100,70,240,.32)',
        color: 'rgba(205,195,255,.85)',
        fontSize: 12,
        fontWeight: 600
      }}>
        Self-hosting
      </div>
    </div>
  </div>
</div>
```

<div align="center">

[![Spotify](https://img.shields.io/badge/Spotify-111111?style=for-the-badge&logo=spotify&logoColor=1DB954)](https://open.spotify.com/user/31qrfhechd6ttx6zt7jkhgzggsry)
[![TikTok](https://img.shields.io/badge/TikTok-111111?style=for-the-badge&logo=tiktok&logoColor=white)](https://www.tiktok.com/@allademswallowww)
[![YouTube](https://img.shields.io/badge/YouTube-111111?style=for-the-badge&logo=youtube&logoColor=FF0000)](https://www.youtube.com/@Xotwodddd-xo)

</div>

[![GitHub Stats](https://ghstats.dev/api/card?username=xotwodfr&theme=catppuccin&hide=trend%2Cavg%2Cactive_day%2Cgrade%2Ccontributions%2Crepos%2Cfollowers&custom_title=Stats&border_radius=10)](https://github.com/xotwodfr)

```aura width=860 height=22
<div style={{
  display: 'flex',
  justifyContent: 'center',
  alignItems: 'center',
  width: '100%',
  height: '100%'
}}>
  <span style={{
    fontSize: 12,
    lineHeight: 1,
    color: 'rgba(150,140,200,.55)',
    fontWeight: 500,
    letterSpacing: '.4px'
  }}>
    powered by readme-aura
  </span>
</div>
```
