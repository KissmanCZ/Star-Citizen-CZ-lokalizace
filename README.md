# Star Citizen lokalizace
🚧 Toto je rozpracovaná verze neoficiální překladu hry Star Citizen, na které se stále pracuje.

⚠️ Hra ještě nemá implementované building blocky pro UI a některé prvky jsou zastaralé (např. mobiGlas a lodní HUD). To znamená, že některé texty nelze vůbec přeložit, neboť jsou fixní částí dané interface. Taktéž řada tlačítek má fixní rozměry a je nutné překlad jejich textu přizpůsobit jejich velikosti.

---
## Návod pro instalaci (automatická)
1. Stáhněte si instalační soubor: Star_Citizen_-_Instalator_jazyku-V1.cmd
2. Spusťte ho v herním adresáři `\StarCitizen\LIVE\data\`.
3. Po dokončení instalace můžete začít hrát!

## Návod pro instalaci (manuální)
1. Stáhněte si zip soubor: [main.zip](https://github.com/JarredSC/Star-Citizen-CZ-lokalizace/archive/refs/heads/main.zip).
2. Rozbalte jej v v herním adresáři `\StarCitizen\LIVE\data\`. Vytvoří se vám tak nová složka `Localization` s jazykovou podsložkou `english`, kde se nachází samotný soubor s překladem `global.ini`.
3. V herním adresáři `\StarCitizen\LIVE\data\` poté editujte soubor `user.cfg`.
4. Do tohoto souboru vložte nový řádek: `g_language = english` a změnu uložte.
5. To je vše, můžete začít hrát!
---
## Otázky a odovědi

**Může mi překlad rozbít hru? Hrozí mi 30k?**
> Ne. Soubor global.ini pouze nahrazuje znaky textových řětezců ve hře. Na chod hry, klienta nebo serveru nemá žádný vliv.

**Všechno mám naistalované správně, ale ve hře se všude objevují technické texty začínající zavináčem. Co je špatně?**
> Zřejmě nemá soubor global.ini správné kódování. Ujistěte se, že soubor je uložen v kódování UTF-8 BOM.

**Našel jsem chybu, kde ji mohu nahlásit?**
> Chyby nám prosím hlaště na komunitním discordu v kanálu [Lokalizace Star Citizen](https://discord.com/channels/926921932341919765/1162077785376964719)

---
## Přispěvatelé
* Jarred
* TrionCZ
* Hawell_cze
* DarbyScabb
* Atisis
* The_Boogie
* fid0rka
---
## Provedené změny
### verze 0.1 (v přípravě)
* ASOP terminál: překlad rozhraní pro claimování
* velká část těžebního gameplay
* přeložen dialog pro ukončení hry
* inventář: přeloženo rozhraní
* mobiGlas: přeloženo rozhraní pro majáky (beacons) a texty ke všem typům majáků: medical, combat, escort, transport, rescue
* mobiGlas: přeloženo rozhraní F11 (některé prvky jsou fixní a nepřeložitelné v žádných jazycích - a to včetně nastavení kanálů)
* překlad několika klávesových hintů
* překlad rozhraní terminálu lékárny a nabízeného zboží
* překlad rozhraní terminálu pojišťovny (výběr místa pro regeneraci)
* překlad výrobků od Gemini
* překlad popisků hlavních lokací a orbitálních stanic
* stovky malých překladů a úprav

### verze 0.0b (experimentální) 13-10-2024 12:00
* opravy překlepů a přizpůsobení přeložených stringů na kapitálky, kde si to žádá diakritika
* pojem "vehicle" je dočaně nahrazen slovem "stroj" (ne všude)
* ASOP terminál: specifický font nepodporuje diakritiku, překlad tedy ponechán bez diakritiky
* ASOP terminál: doplnění překladu
* "Otevíř/zavřít" na dveěřích bylo vráceno do originálního tvaru "Open/Close" kvůli starým assetům, které nepodporují diakritiku
* přeložen terminál výtahů (font u starých assetů nepodporuje háčky, ale čárky ano); výjimku tvoří slovo "Hangár", který je použit bez čárky, neboť se tento string propisuje do nátěru čísla hangáru na podlaze hangáru a do displeje terminálu -> oboje nepodporují znak "Á".
* přeložen terminán u klinik
* přeloženy popisky chladičů pro Arena Commander
* přeložeby delivery mise od UDM
* název aplikace v mobiGlas "Contract Manager" je v češtině zkrácen jen na "Kontrakty"


