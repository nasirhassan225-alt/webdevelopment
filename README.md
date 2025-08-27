<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>My Brief Site</title>
<style>
:root { font-family: system-ui, -apple-system, Segoe UI, Roboto, sans-serif; }
* { box-sizing: border-box; }
body { margin: 0; min-height: 100svh; display: grid; place-items: center; background: #f6f7fb; }
main { background: #fff; width: min(92vw, 720px); padding: 2.25rem; border-radius: 16px; box-shadow: 0 10px 30px rgba(0,0,0,.08); text-align: center; }
h1 { margin: 0 0 .5rem; letter-spacing: .3px; }
p { margin: 0 0 1.25rem; color: #444; }
.actions { display: flex; gap: .75rem; justify-content: center; flex-wrap: wrap; }
a.button { text-decoration: none; padding: .7rem 1rem; border-radius: 12px; border: 1px solid #e2e8f0; }
a.button.primary { background: #111; color: #fff; border-color: #111; }
footer { margin-top: 1.25rem; color: #6b7280; font-size: .9rem; }
</style>
</head>
<body>
<main>
<h1>hello, world ✨</h1>
<p>A tiny, single‑file website. Replace this text with your own content.</p>
<div class="actions">
<a class="button primary" href="#about">About</a>
<a class="button" href="#contact">Contact</a>
</div>


<section id="about" aria-label="About" style="margin-top:1.5rem; text-align:left">
<h2>About</h2>
<p>Keep it brief! This section explains who you are or what the site is for.</p>
</section>


<section id="contact" aria-label="Contact" style="margin-top:1rem; text-align:left">
<h2>Contact</h2>
<p>Email: <a href="mailto:you@example.com">you@example.com</a></p>
</section>


<footer>© 2025 Your Name</footer>
</main>
</body>
</html>
