# Rodičovská skupina
Statický vzdělávací simulátor. Nahrajte index.html a tipy.txt do kořene GitHub Pages nebo Cloudflare Pages. Není potřeba sestavení, backend ani API klíč. Na Cloudflare Pages ponechte příkaz sestavení prázdný a jako výstup zvolte složku obsahující index.html.

## Tipy
Upravujte tipy.txt v UTF-8: jeden celý tip na řádku včetně https odkazu, bez číslování. Prázdné řádky se přeskakují. Každá devátá generovaná zpráva je tip, tipy se postupně střídají.

## Místní spuštění
Ve složce spusťte `python3 -m http.server 8000` a otevřete http://localhost:8000. Při pouhém otevření HTML ze souboru může prohlížeč zabránit načtení tipy.txt.

## Chování
Pauza, tři rychlosti, volitelný zvuk (zpočátku vypnutý), počítadla a závěrečná reflexe. Při čtení starších zpráv se chat neposouvá na konec. Při skrytí karty se zprávy nepřidávají. Nejvýše 150 bublin v historii. Fiktivní jména a scénáře, bez analytiky, bez účtů, bez ukládání osobních údajů. Odkazy otevírají externí weby. Nezávislá parodie, bez spojení s WhatsAppem.

První verze nemá offline cache ani bodování ignorovaných zpráv: bez skutečné volby uživatele nelze poznat, co přečetl nebo ignoroval.

Při blokovaném načtení tipy.txt (například otevření přes file://) se použije sedm vestavěných tipů. Po úspěšném načtení je nahradí obsah tipy.txt. Úpravy textového souboru se při přímém otevření HTML nemohou načíst.
