# WEBTECH1-Zad.6
Class Web Technologies Live Data Graphs

Zadanie cvičenia:
Úlohou zadania je na základe údajov generovaných na stránke http://vmzakova.fei.stuba.sk/sse  vykresľovať postupne graf až do momentu, pokiaľ nestlačíte na vašej stránke tlačidlo "Koniec". V tomto okamihu je potrebné, aby sa graf zobrazil celý, t.j. od začiatku jeho vykresľovania až po jeho koniec.
V obrázku vykresľujte dve farebne odlíšené grafické závislosti - zodpovedajúce dvom meraniam (zašumený sínus a kosínus). 

Na stránke umožnite užívateľovi meniť amplitúdu oboch meraní tak, že získané údaje vynásobíte konštantou. 

Zmenu amplitúdu robte pomocou slidera a pomocou vstupného textového poľa. To, ktorý z týchto dvoch prvkov bude zobrazený, definujte na základe prepínača (checkbox). Oba prvky budú medzi sebou prepojené (t.j. po zmene hodnoty sliderom sa zmení obsah textového poľa a naopak). Vizuálna podoba slideru je zobrazená na obrázku. Pri zmene hodnoty, je táto hodnota zobrazená na posuvníku.


Definovanie prvku na zmenu amplitúdy realizujte pomocou vytvorenia vlastného web komponentu.

Pri obrázku zobrazte ďalšie 2 checkboxy, pomocou ktorých bude možné ovplyvňovať, ktorý graf má byť v obrázku zobrazený (prvý alebo druhý, obidva naraz, žiadny). T.j. nespoliehajte sa iba na funkcionalitu knižnice.

Po ukončení merania v obrázku umožnite robiť aj "zoomovanie" časti grafov.



Poznámky:
Odporúčaná (nie povinná) knižnica na vykresľovanie grafov: https://plotly.com/javascript/ 
CSS a JS knižnice (napr. jQuery) je už možné používať. Nie je však dovolené používať jQuery UI.
Estetika je zasa len a len na Vás... ale pamätajte, že pekné sa predáva lepšie.
