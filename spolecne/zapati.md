# Jednotné zápatí výukových pomůcek

Zápatí neobsahuje název ani popis konkrétní pomůcky. Zachovávejte autorství, přiznání použití AI, odkazy a pořadí tlačítek. Použijte pouze u pomůcek vytvořených s pomocí AI.

HTML vložte za hlavní obsah stránky. CSS přidejte do stylů stránky. Zápatí je statické a funguje i bez JavaScriptu. Na úzké obrazovce se obsah a odkazy přirozeně zalomí. Vzor je nasazen v Po kouskách a v simulátoru rodičovské skupiny; při změně vzoru je potřeba aktualizovat jeho vložené kopie.

```html
<footer class="site-footer"><div class="footer-about"><p>Vytvořil Václav Maněna s pomocí umělé inteligence.</p><p>Chcete podpořit tvorbu dalších pomůcek? <a href="https://www.buymeacoffee.com/vmanena">Kupte mi virtuální kafe.</a></p></div><div class="footer-links"><a href="https://www.buymeacoffee.com/vmanena">☕ Kupte mi kafe</a><a href="https://vmanena.github.io/kyberprevence/">Další pomůcky a materiály →</a></div></footer>
```

```css
.site-footer{max-width:1100px;margin:24px auto 0;padding:24px;border-top:1px solid #d6deea;color:#596779;font-size:14px;display:flex;align-items:center;justify-content:space-between;gap:16px;flex-wrap:wrap}
.site-footer p{margin:0}
.site-footer a{display:inline-block;padding:10px 14px;border:1px solid #b5c5db;border-radius:10px;background:#fff;color:#2164c5;font-weight:650;text-decoration:none}
.site-footer a:hover{background:#e7eef8}
.site-footer a:focus-visible{outline:3px solid #bd8a49;outline-offset:3px}
.footer-about p+p{margin-top:8px}
.footer-links{display:flex;flex-wrap:wrap;gap:10px}
.site-footer .footer-about a{display:inline;padding:0;border:0;border-radius:0;background:transparent;color:#2164c5;font-weight:650;text-decoration:underline;text-underline-offset:3px}
.site-footer .footer-about a:hover{color:#184f9e;background:transparent}
```
