---
title: 'A tőzsdei megbízás'
taxonomy:
    category:
        - docs
---

Amennyiben nem rendelkezünk valós idejű piaci információkkal, fontos tudni, hogy megbízás adásakor a Bszt. szerint brókerünk köteles tájékoztatni a pillanatnyi és a megelőző időszakra vonatkozó árfolyam alakulásról, valamint a megbízás tárgyát képező termékkel kapcsolatos legfontosabb hírekről, információkról.

Ha meghoztuk a befektetési döntést, azt pontosan kell megbízásba adnunk, rögzítve a **terméket, az ügylet irányát (eladás vagy vétel), a mennyiséget és árat, valamint az érvényességet (pl. aznapra, adott dátumig, visszavonásig).** Az ügylet teljesülésének végső paramétereit a tőzsdei kereskedési rendszerben nyilvántartott ellenoldali ajánlatok (vételi megbízás esetén eladási, eladási megbízás esetén a párosítható vételi ajánlatok) határozzák meg.

Ajánlatunk teljesülésének feltételeit a BÉT azonnali (nem származékos) piacán az alábbi paraméterek megadásával tudjuk testre szabni.

- **Limit ajánlat:** a megadott áron vagy annál jobb (számunkra kedvezőbb) áron teljesíthető. Ebből kifolyólag a limit ajánlatok a piaci helyzettől függően nem minden esetben teljesülnek azonnal.
- **Piaci (market) ajánlat:** ár megjelölése nélkül tett ajánlat, mely az ajánlati könyvben található ellenajánlatok párosításával teljesülhet (akár több áron és több kötésben is). A pillanatnyilag nem párosítható rész a kereskedési modelltől függően törlődik, vagy a megadott ideig aktív marad.
- **Iceberg ajánlat:** olyan limit áras ajánlat, mely mennyiségének van egy megadott méretű látható része, ami az ajánlati könyvben nyilvánosan szerepel. Ha ez a látható rész teljes egészében lekötődött, akkor a fennmaradó ajánlati mennyiségből újratöltődik a látható rész, amíg a teljes mennyiség le nem kötődik. Nagyobb összegű - jellemzően intézményi - megbízások esetén szokták használni, amikor a megbízó nem szeretné, hogy a piac számára kiderüljön, hogy jelentős vételi vagy eladási szándéka van az adott értékpapírban.
- **Market to Limit ajánlat:** olyan ár megjelölése nélkül tett ajánlat, amely az ajánlati könyvben található ellenajánlatok közül csak a legjobb árszinten lévővel párosítható.

Az ajánlatokhoz különböző végrehajtási feltételeket is megadhatunk, melyekkel tovább pontosíthatjuk a teljesülés lehetséges paramétereit.

- **Stop:** az ajánlat akkor válik aktívvá, ha az árfolyam elér egy rögzített szintet (aktiválási ár).
- **Most rész (Immediate-or-Cancel):** akár részletekben is teljesíthető ajánlat, de csak az ajánlattétel időpontjában. Az ajánlat le nem kötött része törlődik.
- **Most mind (Fill-or-Kill):** Csak akkor teljesül, ha az ajánlattétel időpontjában a teljes ajánlati mennyiség le tud kötődni, különben az ajánlat törlődik.
- **Book or Cancel:** Olyan Limit ajánlat, amely ha az ajánlattétel pillanatában az ajánlati könyvben található ellenajánlattal párosításra kerülne, akkor visszautasításra kerül.

Az itt felsorolt, BÉT által biztosított ügylettípusokon közül egyes befektetési szolgáltatóknál - a használt informatikai megoldástól függően – nem mindegyik érhető el.

A különböző kereskedési modellekben elérhető valamennyi ajánlattípus pontos leírását a BÉT Általános Üzletszabályzatának Kereskedési Szabályokról szóló [Ötödik könyve](https://bet.hu/pfile/file?path=/site/Magyar/Dokumentumok/Befektetok/BET_szabalyok/BET_Zrt_altalanos_uzletszabalyzata/5_Konyv_-_Kereskedesi_Szabalyok.pdf1) tartalmazza.

**Az ajánlati könyv**

A BÉT részvénypiacán a kereskedés folyamatos kereskedés modell szerint zajlik, ahol az ajánlatok összegyűjtése és párosítása az úgynevezett ajánlati könyvben történik. A limitáras vételi és eladási ajánlatok árszintenként kerülnek csoportosításra. Amennyiben egy adott árszinten vannak ellentétes oldali ajánlatok, akkor a közös mennyiség párosításra kerül, és az adott áron megkötődik az ajánlat. Amennyiben folyamatos kereskedés közben a vételi és eladási ajánlatok több árszinten is fedik egymást, úgy a korábban tett ajánlat árszintje mérvadó (a lent felvázolt ajánlati könyv példáján ez akkor fordulhat elő, ha 1001 Ft-on vételi és 1000 Ft-on pedig további eladási ajánlat szerepelne, ekkor a két ajánlat közül a korábbi árszintjén születne kötés). Az azonnali vagy más néven piaci, árfeltétel nélküli ajánlatok szintén az ajánlati könyvben elérhető legelőnyösebb ellenoldali ajánlatokkal kerülnek párosításra.


Az ajánlati könyv vázlata – példa:

| Árszint (Ft) | Vételi mennyiség (db) | Eladási mennyiség (db) |
| --- | --- | --- |
| 998 | 500 |   |
| 999 | 100 |   |
| 1000 | 200 |   |
| 1001 |   | 500 |
| 1002 |   | 2000 |

A példa szerint senki nem vásárolna 1000 forintnál magasabb áron, és senki nem adna el 1001 forintnál olcsóbban. Mint látható, a legjobb eladási és a legjobb vételi ajánlat árszintje nem egyezik meg, közöttük a húzódik a vételi-eladási árkülönbözet, vagy bid-ask spread. (Ugyanez a jelenség húzódik a pénzváltók kétoldali árfolyamjegyzése mögött is.)

A Budapesti értéktőzsde részvény és hitelpapír piacán a kereskedés a Folyamatos kereskedés aukciókkal modellben zajlik, a Xetra kereskedési rendszeren keresztül. Kereskedési napokon a piac 8:15-től 17:20-ig tart nyitva, ez az időszak további szakaszokra tagolódik. A nap elején és a végén egy-egy aukció kerül lebonyolításra, ezek között (9:00/9:02-17:00) zajlik a folyamatos kereskedés. Ebben a szakaszban folyamatos megbízás-párosítás zajlik, a rendszerbe folyamatosan bekerülő megbízásokból azonnal megszületnek az ügyletek, ha egymást átfedő árú – és egyéb korlátokba sem ütköző (pl. MIND ajánlatnál a mennyiségi korlát) – ajánlatok találkoznak a kereskedési rendszerben.

**Kereskedési szakaszok a részvénypiacon**

A különböző kereskedési modellek pontos leírását a BÉT Általános Üzletszabályzatának Kereskedési Szabályokról szóló [Ötödik könyve](https://bet.hu/pfile/file?path=/site/Magyar/Dokumentumok/Befektetok/BET_szabalyok/BET_Zrt_altalanos_uzletszabalyzata/5_Konyv_-_Kereskedesi_Szabalyok.pdf1) tartalmazza.