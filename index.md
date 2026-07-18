<!DOCTYPE html>
<html lang="en">
<head><!-- PLAYABLE_TOUCH_PATCH_V1 --><script>
(function() {
  if (window.__playableTouchPatchInstalled) return;
  window.__playableTouchPatchInstalled = true;
  var origAdd = EventTarget.prototype.addEventListener;
  var blockedTypes = { touchstart: 1, touchmove: 1, wheel: 1 };
  EventTarget.prototype.addEventListener = function(type, listener, options) {
    if (blockedTypes[type]) {
      if (options === undefined || options === null) {
        options = { passive: true };
      } else if (typeof options === 'boolean') {
        options = { capture: options, passive: true };
      } else {
        options = Object.assign({}, options, { passive: true });
      }
    }
    return origAdd.call(this, type, listener, options);
  };
})();
</script><script>window.Intl=window.Intl||{};Intl.t=function(s){return(Intl._locale&&Intl._locale[s])||s;};</script>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Archa License - 1st Anniversary 🎉</title>
<style>
:root{--bg:#0d1117;--card:#161b22;--border:#30363d;--text:#c9d1d9;--gold:#f1c40f;--green:#238636}
*{margin:0;padding:0;box-sizing:border-box;font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Helvetica}
body{background:var(--bg);color:var(--text);line-height:1.6}
.anniv-banner{background:linear-gradient(90deg,#f1c40f,#e67e22);color:#000;text-align:center;padding:12px;font-weight:800;letter-spacing:1px}
header{text-align:center;padding:50px 20px}
header h1{font-size:3rem;color:#fff}
header h1 span{color:var(--gold)}
.container{max-width:900px;margin:auto;padding:20px}
.card{background:var(--card);border:1px solid var(--border);border-radius:12px;padding:25px;margin-bottom:20px;border-top:3px solid var(--gold)}
.btn{display:inline-block;background:var(--gold);color:#000;padding:12px 24px;border-radius:8px;text-decoration:none;font-weight:700;margin:6px}
.squad{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:15px;margin-top:15px}
.member{background:#0d1117;border:1px solid var(--border);border-radius:10px;padding:15px;text-align:center}
.member img{width:70px;height:70px;border-radius:50%;background:#30363d;margin-bottom:10px}
footer{text-align:center;padding:40px;color:#8b949e}
</style>
</head>
<body>
<div class="anniv-banner">🎉 ARCHA LICENSE ANNIVERSARY — 1 YEAR OF OPEN SOURCE — MADE IN BAGUIO CITY 🇵🇭 🎉</div>

<header>
<h1>Archa License <span>Anniversary</span></h1>
<p>1 Year — From Baguio City to Worldwide 🌍</p>
<p>by Rogge Ramos</p>
<p style="margin-top:15px">Thank you to our Squad, Contributors & Users!</p>
</header>

<div class="container">
<div class="card">
<h2>🎂 Anniversary Message</h2>
<p>One year ago, Archa License Community Edition was born in Baguio City, Philippines with one goal: <b>Make licensing simple for every developer.</b></p>
<p style="margin-top:10px">Today, we celebrate YOU — our contributors, users, and squad who believed!</p>
<p style="margin-top:10px"><b>What's next?</b> Archa License Pro + Marketplace + Global adoption!</p>
</div>

<div class="card">
<h2>👥 Anniversary Squad — Official Contributors</h2>
<div class="squad">
<div class="member">
<img src="https://avatars.githubusercontent.com/newssungoldentoday-dev" alt="Rogge">
<h3>Rogge Ramos</h3>
<p>Founder & Creator<br>Anniversary Lead</p>
</div>
<div class="member">
<img src="https://avatars.githubusercontent.com/u/1" alt="Contributor">
<h3>Join Anniversary Squad!</h3>
<p>Be part of history<br>PR before anniversary ends</p>
</div>
</div>
<a class="btn" href="data:application/octet-stream;base64,IyBBcmNoYSBMaWNlbnNlIC0gQ29udHJpYnV0b3JzIFNxdWFkIPCfh7Xwn4etCgpUaGFuayB5b3UgdG8gZXZlcnlvbmUgd2hvIG1ha2VzIEFyY2hhIExpY2Vuc2UgYmV0dGVyIQoKIyMgQ3JlYXRvcgotICoqUm9nZ2UgUmFtb3MqKiAoQG5ld3NzdW5nb2xkZW50b2RheS1kZXYpIOKAlCBDcmVhdG9yICYgTGVhZCDigJQgQmFndWlvIENpdHksIFBoaWxpcHBpbmVzCgojIyBDb3JlIFNxdWFkCi0gKkJlIHRoZSBmaXJzdCBjb250cmlidXRvciEgT3BlbiBhIFB1bGwgUmVxdWVzdC4qCgojIyBIb3cgdG8gYmVjb21lIGEgY29udHJpYnV0b3I/CjEuIEZvcmsgdGhlIHJlcG8KMi4gRml4IGEgYnVnIG9yIGFkZCBkb2NzCjMuIFN1Ym1pdCBQdWxsIFJlcXVlc3QKNC4gWW91IHdpbGwgYmUgYWRkZWQgaGVyZSEKCi0tLQrCqSAyMDI2IFJvZ2dlIFJhbW9zIOKAlCBnaXRodWIuY29tL25ld3NzdW5nb2xkZW50b2RheS1kZXYvYXJjaGFsaWNzCg==">View All Contributors</a>
</div>

<div class="card">
<h2>🏆 Anniversary Edition License</h2>
<p>Use this badge in your README during anniversary month:</p>
<pre style="background:#0d1117;border:1px solid #30363d;padding:15px;border-radius:8px;overflow-x:auto;margin-top:10px">[![Archa License Anniversary](https://img.shields.io/badge/Archa%20License-Anniversary%20Edition%20🎉-gold)] 
(https://github.com/newssungoldentoday-dev/archalics)</pre>
</div>

<div class="card" style="text-align:center">
<h2>🎁 Celebrate With Us</h2>
<p>Star the repo, share on socials, and become contributor!</p>
<a class="btn" href="https://github.com/newssungoldentoday-dev/archalics">⭐ Star Official Repo</a>
<a class="btn" style="background:transparent;color:#f1c40f;border:1px solid #f1c40f" href="https://github.com/newssungoldentoday-dev/archalics/issues">💬 Leave Anniversary Wish</a>
</div>
</div>

<footer>© 2026 Rogge Ramos — Archa License Anniversary — Baguio City, Philippines 🇵🇭<br>Made with ❤️ for 1 year and counting!</footer>
</body>
</html>
