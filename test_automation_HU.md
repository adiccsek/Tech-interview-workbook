# Tesztautomatizálási kérdések

## Tesztelési alapok (ISTQB-hez kapcsolódó)
<img src="https://www.mindsmapped.com/wp-content/uploads/2016/06/ISTQB.jpg" alt="image" width="300" height="220">

#### ✅ Mi a tesztelés célja? Mi nem az?
**A tesztelés célja:**
- A szoftverhibák azonosítása és javítása.
- A rendszer minőségének és megbízhatóságának mérése.
- A kockázatok felmérése és kezelése a fejlesztés során.

**Mi nem a tesztelés?**
- Nem garantálja a teljes hibamentességet.
- Nem csupán hibakeresés, hanem folyamatos minőségbiztosítás.
- Nem helyettesíti a fejlesztési folyamatot, hanem annak része.

#### ✅ Mik a tesztelési alapelvek?
- **Hiba jelenléte** – A tesztelés hibák megtalálására szolgál, nem a hiányuk bizonyítására.
- **Korai tesztelés** – A fejlesztés korai szakaszában hatékonyabb a hibák javítása.
- **Hibák koncentrációja** – A problémák gyakran bizonyos részeken halmozódnak.
- **Teljes tesztelés lehetetlensége** – Nem lehet minden kombinációt tesztelni, ezért a kritikus területekre kell fókuszálni.
- **Tesztelés kontextusfüggő** – Különböző rendszerek eltérő tesztelési megközelítést igényelnek.

#### ✅ Mi az egységtesztelés (unit testing)? Ki felelős az egységtesztek írásáért?
Az **egységtesztelés** a szoftverfejlesztés egyik alapvető tesztelési módszere, amely során az alkalmazás legkisebb egységeit (például függvényeket, metódusokat) külön-külön tesztelik. Célja, hogy biztosítsa az egyes komponensek helyes működését.  
**Ki felelős az egységtesztek írásáért?**  
Az egységteszteket általában a **fejlesztők** írják, mivel ők ismerik legjobban a kód szerkezetét és működését. Gyakran használnak tesztkereteket, mint például JUnit (Java), NUnit (.NET) vagy pytest (Python).

#### ✅ Mik a tesztszintek, és mi a különbség köztük?
A szoftvertesztelés több szinten történik, hogy biztosítsa a rendszer teljes körű ellenőrzését:
- **Egységtesztelés** – Az egyes komponensek különálló tesztelése.
- **Integrációs tesztelés** – A komponensek közötti kapcsolatok ellenőrzése.
- **Rendszertesztelés** – Az egész rendszer működésének vizsgálata.
- **Felhasználói elfogadási teszt (UAT)** – A végfelhasználók által végzett tesztelés, amely igazolja, hogy a rendszer megfelel az üzleti követelményeknek.

#### ✅ Mi a különbség a verifikáció és a validáció között?
- **Verifikáció**: Annak ellenőrzése, hogy a szoftver megfelel-e a specifikációknak és a tervezési dokumentációnak. ("Jól építjük a terméket?")
- **Validáció**: Annak ellenőrzése, hogy a szoftver megfelel-e a felhasználói igényeknek és elvárásoknak. ("A megfelelő terméket építjük?")

#### ✅ Mik a tesztelési típusok, és mi a különbség köztük?
- **Funkcionális tesztelés** – Az alkalmazás funkcióinak ellenőrzése.
- **Nem-funkcionális tesztelés** – Teljesítmény, biztonság, használhatóság vizsgálata.
- **Automatizált tesztelés** – Tesztelési szkriptek futtatása emberi beavatkozás nélkül.
- **Manuális tesztelés** – Tesztelés emberi interakcióval.

#### ✅ Mi a különbség a fehér doboz, szürke doboz és fekete doboz tesztelés között?
- **Fehér doboz tesztelés** – A belső kódstruktúra ismeretében történő tesztelés.
- **Szürke doboz tesztelés** – Részleges ismeretekkel rendelkező tesztelés.
- **Fekete doboz tesztelés** – Csak a bemeneteket és kimeneteket vizsgálja, a belső működés ismerete nélkül.

#### ✅ Mi a különbség a felhasználói elfogadási teszt (UAT) és a rendszerteszt között?
- **Rendszerteszt** – Az egész rendszer működésének ellenőrzése technikai szempontból.
- **UAT** – A végfelhasználók által végzett tesztelés, amely igazolja, hogy a rendszer megfelel az üzleti követelményeknek.

#### ✅ Sorolj fel különbségeket a regressziós tesztelés, a füsttesztelés és az újratesztelés között!
- **Regressziós tesztelés** – Annak ellenőrzése, hogy a módosítások nem okoztak új hibákat.
- **Füsttesztelés** – Az alapvető funkciók gyors ellenőrzése.
- **Újratesztelés** – Egy korábban hibás funkció ismételt tesztelése a javítás után.

#### ✅ Mi a különbség a statikus és dinamikus tesztelés között?
- **Statikus tesztelés** – A kód és dokumentáció átvizsgálása futtatás nélkül.
- **Dinamikus tesztelés** – A program futtatása és viselkedésének vizsgálata.

### ✅ Hasonlítsd össze a V-modellt, a vízesés modellt és az Agile megközelítést a tesztelés szempontjából!
| Modell | Jellemzők | Előnyök | Hátrányok |
|--------|----------|--------|----------|
| **V-modell** | Fejlesztés és tesztelés párhuzamosan zajlik | Korai hibafelismerés, strukturált | Rugalmatlan, nehéz változtatni |
| **Vízesés modell** | Lineáris, egymás után következő fázisok | Könnyen érthető, jól dokumentált | Késői hibafelismerés, nehéz módosítani |
| **Agile** | Iteratív, folyamatos fejlesztés és tesztelés | Gyors alkalmazkodás, folyamatos visszacsatolás | Nehezebb tervezni, több erőforrást igényel |


<img src="https://t4.ftcdn.net/jpg/03/90/15/65/360_F_390156585_8w1lsOyICIAOvDCU8tExXW2QwLCOFwXD.jpg" alt="image" width="550" height="400">


<img src="https://i.imgur.com/S38EBJw.png" alt="image" width="550" height="400">   <img src="https://segedletek.level14.hu/assets/img/modszertan-vizeses.svg" alt="image" width="550" height="400">


<img src="https://promanconsulting.hu/wp-content/uploads/2022/03/agilis-modszertanok-optimized.jpg" width="550" height="400">





## Reporting, Bugs
<img src="https://moolya.com/blog/wp-content/uploads/2023/05/Bug-Report.png" alt="image" width="300" height="220">

#### ✅ Milyen lépéseket követnél egy hiba megtalálásakor?
A hiba megtalálásának folyamata strukturált és hatékony kell legyen:
1. **Hiba azonosítása** – Figyeld meg a rendszer viselkedését és keresd a rendellenességeket.
2. **Reprodukálás** – Próbáld meg ismét előidézni a hibát, hogy pontosan megértsd a körülményeit.
3. **Dokumentálás** – Jegyezd fel a hiba részleteit, beleértve a környezetet, a lépéseket és az elvárt vs. tényleges eredményt.
4. **Prioritás meghatározása** – Értékeld a hiba súlyosságát és üzleti hatását.
5. **Jelentés készítése** – Küldd el a hibát a fejlesztői csapatnak részletes leírással.
6. **Javítás és tesztelés** – A fejlesztők kijavítják a hibát, majd újratesztelik a rendszert.
7. **Végső ellenőrzés** – Győződj meg róla, hogy a javítás nem okozott új problémákat.

#### ✅ Beszélj a gyakori tesztjelentésekről és részleteikről!
A tesztjelentések dokumentálják a tesztelési folyamatot és segítenek a döntéshozatalban:
- **Tesztösszegző jelentés** – Összefoglalja a tesztelési eredményeket, a sikeres és sikertelen teszteseteket.
- **Hibajelentés** – Részletezi az észlelt hibákat, azok súlyosságát és reprodukálhatóságát.
- **Teljesítményteszt jelentés** – A rendszer sebességét és stabilitását elemzi különböző terhelési szinteken.
- **Biztonsági teszt jelentés** – Azonosítja a lehetséges sebezhetőségeket és javaslatokat tesz a javításra.
- **Automatizált teszt jelentés** – Az automatizált tesztek futtatásának eredményeit tartalmazza.

#### ✅ Mit tartalmaz egy hibajelentés?
Egy jól megírt hibajelentés segíti a fejlesztőket a gyors javításban:
- **Egyedi azonosító** – Minden hiba kap egy egyedi azonosítót.
- **Cím** – Rövid, pontos megnevezés a hibáról.
- **Leírás** – Részletes információ a hibáról, beleértve a környezetet és a lépéseket.
- **Reprodukciós lépések** – Pontosan leírja, hogyan lehet előidézni a hibát.
- **Elvárt vs. tényleges eredmény** – Mi lett volna a helyes működés, és mi történt valójában?
- **Súlyosság és prioritás** – A hiba hatása a rendszerre és az üzleti folyamatokra.
- **Mellékletek** – Képernyőképek, log fájlok, videók a hiba bemutatására.

#### ✅ Hogyan rangsorolnál egy hibát?
A hibák rangsorolása segít a fejlesztőknek a legfontosabb problémák kezelésében:
- **Kritikus (P1)** – A rendszer nem működik, vagy súlyos adatvesztést okoz.
- **Magas (P2)** – Fontos funkciók hibásan működnek, de a rendszer használható.
- **Közepes (P3)** – Kisebb funkcionális problémák, amelyek nem akadályozzák a használatot.
- **Alacsony (P4)** – Esztétikai vagy kisebb UI hibák, amelyek nem befolyásolják a működést.
- **Triviális (P5)** – Apró elírások vagy vizuális eltérések, amelyek nem igényelnek azonnali javítást.


## Test Automation, Selenium
<img src="https://media.licdn.com/dms/image/C4D12AQE3GOyVsZazOw/article-cover_image-shrink_600_2000/0/1583830696602?e=2147483647&v=beta&t=bYHbKyhMoWsMgtEug6eSf3m0db5ZtGEl437TeS1qkfI" alt="image" width="320" height="220">

#### ✅ Melyik teszteseteket érdemes automatizálni és melyiket nem?

#### ✅ Írj le egy jó automatizált tesztet!

#### ✅ Mi a Selenium, Selenium IDE és Selenium WebDriver?

#### ✅ Hogyan lehet azonosítani a webes elemeket?

#### ✅ Hogyan lehet várni az elemekre, és mi lehet a probléma? Gyűjtsd össze a lehetséges hibákat és okokat!

#### ✅ Hasonlítsd össze a POM és a Keyword Driven Testing megközelítéseket!

#### ✅ Mi a különbség a TDD és BDD között?

#### ✅ Mi az API tesztelés és miért hasznos?

#### ✅ Mi az adatvezérelt tesztelés és miért hasznos?