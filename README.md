# Třídíme Česko

Webová a mobilní aplikace (PWA) pro snadné a rychlé vyhledávání kontejnerů na tříděný odpad v různých městech České republiky. 
Umožňuje uživatelům zjistit polohu nejbližších kontejnerů s využitím zjišťování polohy a specializovaných map (Praha, Brno, Ostrava, Plzeň).

## Instalace a využití
Jedná se o statickou webovou aplikaci (HTML/JS/CSS). 
Pro lokální spuštění nebo nasazení jednoduše nakopírujte zdrojové soubory aplikace (`tridime-cesko`) na jakýkoliv webový server s HTTPS a nasměrujte svůj prohlížeč na soubor `index.html`.

> **Poznámka k API klíčům:**
> Aby aplikace úspěšně načítala živá data o separovaném odpadu z Prahy, je nutné vlastnit token pro služby Golemio. 
> Svůj klíč si zaregistrujte na [https://golemio.cz](https://golemio.cz) a vložte jej do zdrojového kódu v souborech `praha/index.html` a `kontejnery/index.html` namísto příslušného placeholderového řetězce `VÁŠ API KLÍČ`.

Před prvním nasazením se také přesvědčte, že váš webhosting podporuje HTTPS pro funkčnost Service Workeru pro PWA (možnost instalace na mobily) a geolokace.

Více v přiložené dokumentaci uvnitř složky se zdrojovým kódem.
