# nexora.ai
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<meta name="description" content="Nexora AI builds intelligent tools that help people and businesses do more." />
<title>NEXORA AI — Intelligence, Amplified</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=DM+Mono:wght@400;500&family=Manrope:wght@400;500;600;700;800&display=swap" rel="stylesheet">
<style>
:root {
  --bg: #050608;
  --panel: #0c1015;
  --panel2: #101720;
  --text: #f4f7fb;
  --muted: #9aa6b5;
  --line: rgba(180, 205, 225, .13);
  --cyan: #79f2e2;
  --blue: #789cff;
  --violet: #b28aff;
  --max: 1180px;
}
* { box-sizing: border-box; margin: 0; padding: 0; }
html { scroll-behavior: smooth; scroll-padding-top: 88px; }
body { font-family: 'Manrope', sans-serif; background: var(--bg); color: var(--text); line-height: 1.6; overflow-x: hidden; }
a { color: inherit; text-decoration: none; }
button, input, textarea { font: inherit; }
.container { width: min(var(--max), calc(100% - 48px)); margin: auto; }
.eyebrow { font: 500 11px 'DM Mono', monospace; letter-spacing: .18em; text-transform: uppercase; color: var(--cyan); display: inline-flex; align-items: center; gap: 10px; }
.eyebrow:before { content: ''; width: 22px; height: 1px; background: currentColor; }
.section { padding: 108px 0; }
.section-head { max-width: 680px; margin-bottom: 48px; }
.section-head h2 { font-size: clamp(34px, 5vw, 54px); line-height: 1.08; letter-spacing: -.055em; margin: 17px 0; }
.section-head p { color: var(--muted); font-size: 15px; max-width: 570px; }
.gradient-text { background: linear-gradient(100deg, var(--cyan), #a8c5ff 55%, var(--violet)); -webkit-background-clip: text; background-clip: text; color: transparent; }

/* Navigation */
header { height: 76px; position: fixed; inset: 0 0 auto; z-index: 50; background: rgba(5, 6, 8, .76); backdrop-filter: blur(18px); border-bottom: 1px solid var(--line); }
.nav { height: 100%; display: flex; align-items: center; justify-content: space-between; }
.brand { display: flex; align-items: center; gap: 11px; font-weight: 800; letter-spacing: .12em; font-size: 15px; }
.brand-mark { width: 29px; height: 29px; border: 1px solid var(--cyan); border-radius: 9px; display: grid; place-items: center; color: var(--cyan); font-size: 16px; box-shadow: 0 0 20px #79f2e233; }
.nav-links { display: flex; align-items: center; gap: 31px; color: #b7c0cc; font-size: 12px; }
.nav-links a:hover { color: var(--cyan); }
.nav-cta, .btn { display: inline-flex; align-items: center; justify-content: center; gap: 10px; padding: 12px 18px; border: 1px solid rgba(121, 242, 226, .45); border-radius: 5px; color: var(--cyan); font-size: 12px; font-weight: 700; transition: .25s; background: rgba(121, 242, 226, .05); }
.nav-cta:hover, .btn:hover { background: var(--cyan); color: #04100f; box-shadow: 0 0 28px #79f2e244; transform: translateY(-2px); }
.menu-toggle { display: none; background: none; border: 0; color: white; font-size: 25px; }

/* Hero + Grid Hole canvas */
.hero { min-height: 790px; height: 100vh; max-height: 980px; position: relative; display: flex; align-items: center; overflow: hidden; background: #000; }
.grid-hole { position: absolute; inset: 0; overflow: hidden; background: radial-gradient(ellipse at 50% 65%, #101a24 0%, #050608 53%, #000 100%); }
.grid-hole canvas { position: absolute; inset: 0; width: 100%; height: 100%; opacity: .9; }
.hole-vignette { position: absolute; inset: 0; background: radial-gradient(ellipse at 50% 60%, transparent 5%, rgba(0, 0, 0, .12) 42%, #000 10
