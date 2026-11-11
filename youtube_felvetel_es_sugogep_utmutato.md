# 🎬 TD-AI YouTube Stúdió, Képernyőfelvétel & Szemkontaktus-Súgógép Útmutató

> **Készült:** Tóth Dániel István (`tdaimarketing.hu`) első, 15 diás YouTube esettanulmány-videójához  
> **Cél:** Egyetlen felvétellel (vágás nélkül!), **1080p 60 FPS** minőségben, kristálytiszta hanggal felvenni a 3D diasort ÉS a webkamerádat úgy, hogy közben a Súgógépet olvasod — **de a nézők ebből semmit nem látnak, és végig úgy érzik, mintha egyenesen a szemükbe néznél.**

---

## 📋 TARTALOMJEGYZÉK

1. [1. RÉSZ: Milyen programmal vedd fel a monitorodat ÉS magadat egyszerre? (OBS Studio 5 perces útmutató + Alternatívák)](#1-rész-milyen-programmal-vedd-fel-a-monitorodat-és-magadat-egyszerre)
   - [A LEGFONTOSABB TRÜKK: „Ablak rögzítése” (hogy a Súgógép 0%-ban látszódjon a videón!)](#3-lépés-a-legfontosabb-trükk--hogyan-legyen-láthatatlan-a-súgógép-1-monitoron-is)
   - [Webkamera beállítása (2 profi módszer: Beépített `K` gomb vs. OBS Kamera réteg)](#4-lépés-saját-magad-webkamera-elhelyezése-a-jobb-alsó-sarokban)
   - [2 kattintásos Stúdió Hang: OBS Zajszűrés (RNNoise)](#5-lépés-2-kattintásos-stúdió-hangminőség-zajszűrés--rnnoise)
   - [Alternatív, 1-kattintásos programok (CapCut Desktop, Loom, ScreenPal)](#2-alternatív-még-egyszerűbb-1-kattintásos-programok)
2. [2. RÉSZ: Hogyan olvasd a Súgógépet úgy, hogy SENKI ne vegye észre? (A 4 Szemkontaktus-Szabály)](#2-rész-hogyan-olvasd-a-súgógépet-úgy-hogy-a-kamerában-senki-ne-vegye-észre)
   - [1. A „Kamera-Alatti Keskeny Sáv” szabály (350–450 px)](#1-szabály-a-kamera-alatti-keskeny-sáv-szabály-a-legfontosabb-optikai-trükk)
   - [2. A 60–75 cm-es távolság szabály](#2-szabály-a-6075-cm-es-távolság-szabály-karnyújtásnyi-távolság)
   - [3. A „80% Súgó + 20% Saját Szó” technika](#3-szabály-a-80-súgó--20-saját-szó-technika)
   - [4. Telefonos alternatíva (ha nem a monitorról olvasnál)](#4-szabály-telefonos-alternatíva-ha-külön-eszközről-szeretnéd-olvasni)
3. [3. RÉSZ: Az Emberközeli, Bátorító YouTube-Koncepció („A srác, aki munka után felépítette”)](#3-rész-az-emberközeli-bátorító-youtube-koncepció-a-srác-aki-munka-után-felépítette)
   - [Miért ver meg minden „Lamborghinis gurut” a nyers őszinteség 2026-ban?](#miért-működik-2026-ban-a-nyers-őszinteség-hormozi--dokumentarista-stílus)
   - [A videó 4 lépcsős érzelmi íve (Storytelling Arc)](#hogyan-épül-fel-a-videó-4-lépcsős-érzelmi-íve)
4. [BÓNUSZ: Felvétel előtti 5 perces Checklist & Billentyűparancs Puskázó](#bónusz-felvétel-előtti-5-perces-ellenőrzőlista-checklist)

---

## 1. RÉSZ: Milyen programmal vedd fel a monitorodat ÉS magadat egyszerre?

Ha azt szeretnéd, hogy a felvétel végén **egyetlen kész MP4 videófájlod** legyen (rajta a tűéles 3D diasorral, a jobb alsó sarokban a webkameráddal és a zajszűrt hangoddal), amit **vágás nélkül, azonnal feltölthetsz a YouTube-ra**, akkor az alábbi megoldások közül válassz.

---

### 🏆 #1 Legjobb ingyenes megoldás: OBS Studio (Open Broadcaster Software)

A világ összes profi YouTubere (Alex Hormozi csapatától a tech csatornákig) az **OBS Studio**-t használja.  
**Miért ez a legjobb neked?**
- **100% ingyenes**, nincs vízjel, nincs időkorlát.
- Tudja a **tűéles 1080p 60 FPS** felvételt (a 3D arany részecskék és a kártyák vajpuhán mozognak).
- **Képes CSAK a böngészőablakot rögzíteni**, így a felette lebegő Súgógép ablakod **láthatatlan marad** a felvételen!
- Beépített **AI zajszűrője (RNNoise)** van, ami egy sima mikrofont is stúdióminőségűvé varázsol.

---

#### 🛠️ LÉPÉSRŐL LÉPÉSRE BEÁLLÍTÁS (5 PERC ALATT, MAGYAR MENÜVEL)

##### 1. lépés: Letöltés és az *Automatikus beállítás varázsló (Auto-Configuration Wizard)*
1. Töltsd le innen: **[obsproject.com](https://obsproject.com/)** (Windows verzió), majd telepítsd.
2. Első indításkor felugrik az **Automatikus beállítás varázsló** *(ha nem ugrana fel: felső menü ➔ `Eszközök (Tools)` ➔ `Automatikus beállítás varázsló`)*.
3. Válaszd a **„Csak felvételre optimalizálás, nem fogok streamelni”** *(Optimize just for recording)* opciót ➔ **Tovább**.
4. **Felbontás és FPS:**
   - **Alap (vászon) felbontás:** `1920x1080`
   - **FPS:** `60 FPS` *(vagy „60 vagy 30, de 60 előnyben részesítése”)* ➔ **Tovább** ➔ **Beállítások alkalmazása**.

##### 2. lépés: YouTube-kész MP4 formátum beállítása
1. Kattints jobb alul a **Beállítások (Settings)** gombra ➔ bal oldalon válaszd a **Kimenet (Output)** fület.
2. A **Felvétel (Recording)** résznél:
   - **Felvételi formátum (Recording Format):** Válaszd a **`Hybrid MP4`** vagy **`MPEG-4 (.mp4)`** opciót *(így a felvétel leállítása után azonnal kész az `.mp4` fájl, amit egyből húzhatsz be a YouTube-ra!)*.
   - **Felvétel minősége (Recording Quality):** `Magas minőség, közepes fájlméret (High Quality, Medium File Size)`.
3. Kattints az **Alkalmaz (Apply)** ➔ **OK** gombra.

---

##### 🚨 3. lépés: A LEGFONTOSABB TRÜKK — Hogyan legyen LÁTHATATLAN a Súgógép (1 monitoron is!)

> [!IMPORTANT]
> **SOHA NE „Kijelző rögzítést (Display Capture)” válassz!**  
> Ha a teljes kijelződet rögzíted, akkor minden látszani fog a videón, ami a monitorodon van — beleértve a Súgógépet is.  
> Ehelyett **„Ablak rögzítést (Window Capture)”** kell használni!

**Így működik a varázslat 1etlen monitoron:**
1. Nyisd meg Chrome-ban vagy Edge-ben a diasort: `youtube_slides_foallas_mellett.html`.
2. Nyomd meg a diasorban a **`P` billentyűt** (vagy kattints alul a `📱 Külön Súgó (P)` gombra). Ekkor egy **különálló, keskeny felugró ablakban** megnyílik a **TD-AI Szemkontaktus Súgógép**.
3. Menj át az **OBS Studio**-ba, és lent a **Források (Sources)** dobozban kattints a **`+` (Hozzáadás)** gombra.
4. Válaszd az **`Ablak rögzítése (Window Capture)`** lehetőséget ➔ Nevezd el pl. *„TD-AI Diasor”*-nak ➔ **OK**.
5. A felugró tulajdonságoknál:
   - **Ablak (Window):** Válaszd ki a legördülő listából a fő böngészőablakot: `[chrome.exe]: Főállás Mellett: 0-ról 1 Millió Ft-ig — TD-AI & Marketing...`
   - **Rögzítési mód (Capture Method):** Válaszd a **`Windows 10 (1903 és újabb)`** opciót.
   - *(Opcionális)* Kapcsold be vagy ki a *„Kurzor rögzítése (Capture Cursor)”* pipát (ha használod a diasorban az `L` gombos arany lézert vagy kattintasz a kártyákra, hagyd bekapcsolva!).
   - Kattints az **OK** gombra.
6. Ha a diasor képe nem tölti ki teljesen az OBS előnézeti ablakát, kattints rá jobb gombbal az OBS-ben ➔ **`Átalakítás (Transform)`** ➔ **`Képernyőhöz igazítás (Fit to screen)`** *(gyorsbillentyű: `Ctrl + F`)*.

🎯 **Mi történik most?**
- A fő böngészőablakban fut a 15 diás 3D prezentáció.
- A `P` gombbal megnyitott **Súgógép ablakot** nyugodtan **ráhúzhatod a képernyőd legfelső közepére** (pont a fizikai webkamerád alá).
- **Te a monitorodon látod és olvasod a Súgógépet**, de mivel az OBS **csak a hátsó diasor ablakot** rögzíti, **a videón a Súgógép 0%-ban látszik!** A nézők kizárólag a tiszta, profi 3D diasort látják!

---

##### 4. lépés: Saját magad (Webkamera) elhelyezése a jobb alsó sarokban

Két szuper lehetőséged van — válaszd azt, amelyik szimpatikusabb:

###### 🅰️ MÓDSZER (A legegyszerűbb!): A diasorba beépített Arany Kör-Kamera (`K` gomb)
A `youtube_slides_foallas_mellett.html` diasorba már beépítettünk egy **mozgatható, arany keretes kör-kamerát**!
1. A diasorban nyomd meg a **`K` billentyűt** (alul a `🎥 Kamera (K)` gomb).
2. Jobb alul megjelenik az arany kör. **Kattints bele duplán**, majd engedélyezd a böngészőben a webkamerát!
3. Máris ott a saját élő kameraképed a diasoron belül (egérrel bárhova húzhatod).
4. **Előnye:** Mivel ez a böngészőablakon *belül* van, az OBS „Ablak rögzítése” automatikusan felveszi a diasorral együtt, egyetlen beállítás nélkül!

###### 🅱️ MÓDSZER: Webkamera hozzáadása közvetlenül az OBS-ben
Ha inkább az OBS-ben szeretnéd kezelni a kamerádat:
1. Az OBS **Források (Sources)** dobozában kattints a **`+`** gombra ➔ **`Videórögzítő eszköz (Video Capture Device)`** ➔ Nevezd el *„Webkamera”*-nak ➔ **OK**.
2. Válaszd ki a webkamerádat a listából, a felbontást állítsd `1920x1080` vagy `1280x720`-ra ➔ **OK**.
3. Az OBS előnézeti képén a piros sarokpontoknál fogva **kicsinyítsd le a kamerádat**, és húzd a **jobb alsó sarokba** *(ügyelj rá, hogy a `Webkamera` réteg a `Források` listában a `TD-AI Diasor` FELETT legyen!)*.

---

##### 5. lépés: 2 kattintásos Stúdió Hangminőség (Zajszűrés — RNNoise)

A YouTube-on a nézők a jó hangot még a 4K képnél is többre értékelik. Az OBS-ben 10 másodperc alatt bekapcsolhatod a mesterséges intelligencia alapú zajszűrést, ami eltünteti a gépzúgást, a szobavisszhangot és a háttérzajt:

1. Az OBS alsó részén, a **Hangkezelő (Audio Mixer)** panelen keresd meg a **`Mikrofon / Aux (Mic/Aux)`** sávot.
2. Kattints a mellette lévő **három pontra (`⋮`)** ➔ válaszd a **`Szűrők (Filters)`** menüpontot.
3. Bal alul kattints a **`+`** gombra ➔ válaszd a **`Zajszűrés (Noise Suppression)`** opciót ➔ **OK**.
4. A **Módszer (Method)** legördülőnél legyen kiválasztva: **`RNNoise (jobb minőség, nagyobb CPU használat)`**.
5. *(Pro tipp)* Ugyanitt a `+` gombbal adhatsz hozzá egy **`Kompresszor (Compressor)`** szűrőt is alapbeállítással — ez kiegyenlíti a hangerődet, hogy a halkabb mondatok is tisztán hallatszódjanak, és a lelkesebb részek se torzítsanak.
6. Kattints a **Bezárás (Close)** gombra. Kész is a stúdióhang!

---

### 🥈 #2 Alternatív, még egyszerűbb 1-kattintásos programok

Ha nem szeretnél az OBS Studio-val bajlódni, ez a 3 program szó szerint **1 kattintással** felveszi a képernyődet és a kör alakú webkamerádat:

| Program neve | Kinek ajánlott? | Legnagyobb előnye | Mire figyelj? |
| :--- | :--- | :--- | :--- |
| **1. CapCut Desktop** *(Ingyenes PC/Mac app)* | Ha felvétel után esetleg levágnád az elejét/végét, vagy automatikus magyar feliratot tennél rá. | A kezdőképernyőn van egy **„Képernyő rögzítése (Record Screen)”** gomb: egyszerre veszi a képernyőt és a kamerát külön sávra! | Ha nem „Ablakot”, hanem teljes képernyőt rögzít, a Súgógépet inkább telefonról olvasd a kamera alól. |
| **2. Loom** *(loom.com)* | Ha a világ legegyszerűbb, gyönyörű kör-kamerás felvevőjét keresed. | Csodaszép kerek kamera-buborék a sarokban, 0 beállítás, azonnal letölthető MP4-ben. | Az ingyenes verzióban **5 perc** a limit (fizetőssel korlátlan), így egy 12–15 perces videóhoz az OBS vagy CapCut jobb. |
| **3. ScreenPal** *(korábban Screencast-O-Matic)* | Kezdőknek, akik egy keretet akarnak húzni a diasor köré. | Beállíthatsz egy „Rögzítési keretet” csak a diasorra, miközben a kereten kívül (fent) olvasod a Súgógépet. | Az ingyenes verzióban 15 perc a limit és kis vízjel lehet a sarokban. |

> [!TIP]
> **Összegző ajánlás Dánielnek:** Használd az **OBS Studio**-t az **„Ablak rögzítése (Window Capture)”** móddal! Egyszer kell beállítani (5 perc), utána minden jövőbeli YouTube videódnál csak megnyomod a *Felvétel indítása* gombot, és 1080p 60fps stúdióminőséget kapsz.

---

## 2. RÉSZ: Hogyan olvasd a Súgógépet úgy, hogy a kamerában SENKI ne vegye észre?

A legtöbb kezdő YouTuber ott rontja el a súgógépezést, hogy **teljes képernyőre** teszi a szöveget, vagy egy második monitorra rakja oldalra. Ilyenkor a szemgolyó folyamatosan **balról jobbra pingpongozik**, vagy lefelé néz — a néző pedig 3 másodperc alatt kiszúrja, hogy olvasol.

Íme a **4 profi szabály**, amivel **100%-ban természetes szemkontaktust** tartasz, miközben végig előtted van a szöveg:

---

### 🎯 1. Szabály: A „Kamera-Alatti Keskeny Sáv” szabály (A legfontosabb optikai trükk!)

Az emberi szem fókuszpontja miatt, ha a szöveg **közvetlenül a fizikai webkamera lencséje alatt (1–3 centiméterrel)** helyezkedik el, és **keskeny oszlopba** van tördelve, a kamerában **fizikailag lehetetlen észrevenni**, hogy nem a lencsébe nézel!

```text
         [ 📷 FIZIKAI WEBKAMERA A MONITOR TETEJÉN ]
   ┌─────────────────────────▼─────────────────────────┐
   │      ┌─────────────────────────────────────┐      │
   │      │ 🎯 IDE NÉZZ (KAMERA ALATTI SÁV)     │ ◄── A P gombbal megnyitott Súgógép ablak
   │      │ „Sziasztok! Ebben a videóban        │     (380-460 px széles, legfelülre húzva!)
   │      │  őszintén megmutatom, hogyan...”    │     A szemed NEM mozog balról jobbra!
   │      └─────────────────────────────────────┘      │
   │                                                   │
   │         HÁTTÉRBEN FUTÓ 3D DIASOR ABLAK            │
   │     (Az OBS csak ezt az ablakot rögzíti!)         │
   │                                          ┌─────┐  │
   │                                          │ 🎥  │  │
   └──────────────────────────────────────────┴─────┴──┘
```

**Hogyan használd a diasorba épített Szemkontaktus-Súgógépet (`P` gomb)?**
1. Nyomd meg a **`P` billentyűt** a diasorban.
2. A felugró Súgógép ablakot már eleve úgy programoztuk be neked, hogy **keskeny (460 px széles)** legyen, és a képernyő felső közepén nyíljon meg!
3. Húzd fel az egérrel a Súgógép ablakot **koppra a monitorod legfelső szélére**, pont a webkamerád lencséje alá!
4. A Súgógép ablakban használd a beépített vezérlőket:
   - **`🎯 IDE NÉZZ (KAMERA ALATTI OLVASÓSÁV)`:** Mindig a Súgógép **legfelső 2–3 sorát** olvasd (ez van a legközelebb a kamerához)!
   - **`▶ Görgetés` (Auto-scroll) + `Sebesség -/+`:** Kapcsold be az automatikus görgetést, így a szöveg magától úszik felfelé a kamerád alá, a szemednek még lefelé sem kell vándorolnia!
   - **`Keskeny Sáv Mód`:** Egy sorban csak **32–38 karakter** van. Ezt a szemed egyetlen fókuszpontból (perifériás látással) átlátja **nulla vízszintes szemmozgással**!

---

### 📏 2. Szabály: A 60–75 cm-es távolság szabály (Karnyújtásnyi távolság)

Ez tiszta geometria:
- Ha **30 cm-re** (nagyon közel) ülsz a webkamerához, akkor már 3 centiméternyi szövegolvasás is látványos szögelfordulást jelent a szemedben.
- Ha viszont **60–75 cm-re** (kb. egy kinyújtott karnyújtásnyira) ülsz a monitortól/webkamerától, a látószög annyira beszűkül, hogy a kamera lencséje és a lencse alatti 3 centis olvasósáv között **gyakorlatilag 0 fok a különbség**!
- **Mit tegyél?** Ülj hátrébb 60–75 cm-re, és ha emiatt kisebbnek látod a betűket, a Súgógép ablakban nyomd meg az **`A+` (Betűméret növelése)** gombot!

---

### 🗣️ 3. Szabály: A „80% Súgó + 20% Saját Szó” technika

Attól lesz egy előadás igazán élő és emberi, ha nem gépi hírolvasóként darálod a szöveget:
1. **A mondatvégi „Felpillantás” (A 10 millió forintos trükk):**
   - Amikor egy fontos mondat végére érsz (vagy amikor a szövegben látod a `[NÉZZ EGYENESEN A KAMERÁBA]` / `[SZÜNET 1 MP]` jelzést), az utolsó 2-3 szónál **emeld fel a tekinteted 2 centivel közvetlenül a fizikai kamera lencséjébe**, tarts 1 másodperc szünetet, és mosolyogj!
   - Az emberi agy ezt úgy érzékeli, mintha **végig** a kamera lencséjébe néztél volna.
2. **Bátran mondd a saját szavaiddal (80% / 20%):**
   - A Súgógépben lévő szöveg a biztonsági hálód: ott van minden szám (`~25.000 Ft/hó`, `~150.000 Ft`, `6–7 lead`, `~1.000.000 Ft`), hogy semmit ne felejts el.
   - De ha egy mondatot menet közben kicsit lazábban, debreceni közvetlenséggel, saját szlenggel fejezel be, **attól csak még hitelesebb lesz!**
3. **Mozgasd a kezed és kattints a kártyákra!**
   - Beszéd közben nyugodtan gesztikulálj (akkor is, ha a kezed csak részben látszik a kis kamerában — a vállad mozgása és a hanghordozásod sokkal természetesebb lesz tőle!).
   - Amikor a diasoron egy konkrét kártyáról beszélsz (pl. a 3. dián a költségekről vagy a 13. dián a 3 hibáról), **kattints rá az egérrel a kártyára** — a diasor automatikusan ráközelít és arany fénnyel kiemeli (*Spotlight mód*)!

---

### 📱 4. Szabály: Telefonos alternatíva (ha külön eszközről szeretnéd olvasni)

Ha valamiért nem a monitorodon szeretnéd megnyitni a Súgógépet, a **saját okostelefonodból** is csinálhatsz profi súgógépet:
1. Nyisd meg a telefonodon a `youtube_teljes_beszed_forgonyv.md` fájlt (vagy küldd át magadnak Messengeren / Google Keep-ben a szöveget, vagy használj egy ingyenes **Nano Teleprompter / Elegant Teleprompter** appot).
2. **Hová tedd a telefont?**
   - Állítsd vagy rögzítsd a telefont **függőlegesen (álló módban) közvetlenül a webkamera lencséje alá**, a monitor felső kávájához (egy autós szellőzőrács-tartóval, mágneses tartóval vagy akár két befőttesgumival a webkamera alá rögzítve).
   - Mivel a telefon kijelzője eleve keskeny (kb. 6–7 cm), a szemed itt sem fog jobbra-balra mozogni, és 1 centire olvasol a kamera lencséjétől!

---

## 3. RÉSZ: Az Emberközeli, Bátorító YouTube-Koncepció („A srác, aki munka után felépítette”)

### 🔥 Miért működik 2026-ban a nyers őszinteség (Hormozi + dokumentarista stílus)?

2026-ra a magyar és a nemzetközi YouTube-nézők is **allergiásak lettek a megjátszott „Lamborghinis, dubaji, 20 évesen milliárdos vagyok” gurukra**. Senki nem hisz már nekik, mert mindenki érzi, hogy műanyag.

Ezzel szemben **két tartalomtípus robbant nagyot 2026-ban**:
1. **Az Alex Hormozi-féle „0 Bullshit, Tiszta Matematika” stílus:** Konkrét számok, valós költségek, valós árazás, érthető piaci logika mellébeszélés nélkül.
2. **A dokumentarista „Build in Public” (Egy közülünk) stílus:** Amikor nem egy megközelíthetetlen sztár beszél a felhőkből, hanem **egy 26 éves debreceni srác, aki pontosan ugyanúgy napi 8–10 órát dolgozik a főállásában**, mint a néző — csak ő 2026 elején nem kifogásokat keresett, hanem este 6 és éjfél között leült a laptopja elé, és felépítette a `tdaimarketing.hu`-t.

> [!NOTE]
> **A te legnagyobb szupererőd ebben a videóban:**  
> Az, hogy az első percben őszintén kimondod: *„Kezdő vagyok a kamera előtt, nem vagyok profi előadó — de minden szám, amit ma mutatok, 100%-ig valódi.”*  
> Ettől a mondattól kezdve a néző **neked fog szurkolni**! Nem a hibákat fogja keresni, hanem azt mondja magában: *„Basszus, ha a Dani Debrecenből, főállás mellett, 25 ezer Ft-ból meg tudta csinálni, akkor én is képes vagyok rá!”*

---

### 📈 Hogyan épül fel a videó 4 lépcsős érzelmi íve?

A 15 diás prezentációd és a hozzá tartozó beszéd-forgatókönyv (`youtube_teljes_beszed_forgonyv.md`) nem véletlenül követi ezt a **4 felvonásos pszichológiai ívet**:

#### 1. Felvonás: Őszinte vallomás és „Sama-Sama” (Sorstárs) érzés *(1–3. dia)*
- **Érzelmi cél:** Bizalomépítés az első 30 másodpercben.
- **Mit érzel és közvetítesz?** Nem felvágni jöttél. Bevallod, hogy új neked a kamera, és pontosan tudod, milyen érzés délután 5-kor fáradtan hazaesni a 8–10 órás munkahelyről úgy, hogy közben érzed: többre vagy hivatott.
- **Kulcsüzenet:** *„Ugyanott ültem, ahol most te. Nem volt millióm, nem volt irodám — csak a meglévő laptopom és havi ~25.000 Ft-om.”*

#### 2. Felvonás: A 2026-os AI korszak történelmi lehetősége *(2., 4–6. és 10. dia)*
- **Érzelmi cél:** Felnyitni a néző szemét („Aha-élmény”).
- **Mit érzel és közvetítesz?** Lelkesedést és tiszta jövőképet. Elmeséled, hogyan kezdted el tervezni az egészet **2026 év elején**, amikor berobbant az AI korszak és egymás után jöttek ki a jobbnál jobb új AI modellek (Claude, Cursor).
- **Kulcsüzenet:** *„A magyar KKV-k 90%-a még a régi világban él, a régi ügynökségek pedig lassúak és drágák. Az AI nem helyetted gondolkodik, de 8-szorosára gyorsítja a munkádat — így este 6 után, egyedül is egy teljes ügynökség sebességével tudsz építeni!”*

#### 3. Felvonás: Valós számok, kemény munka és őszinte pofonok *(7–9. és 11–13. dia)*
- **Érzelmi cél:** Hitelesség és megvalósíthatóság bizonyítása.
- **Mit érzel és közvetítesz?** Büszkeséget a befektetett munkára és alázatot a nehézségek iránt.
  - Megmutatod, hogyan jött az **1. ügyfél és ~150.000 Ft 3 hét alatt** 0 Ft hirdetésből (szakmai segítségnyújtással Facebook csoportokban, aki a mai napig aktív ügyfeled!).
  - Megmutatod a **Facebook Lead Ads gépezetet**, ami **1 hét alatt 6–7 komoly KKV cégvezetőt** hozott, akiket 17:00 után hívtál vissza.
  - Levezeted az **~1.000.000 Ft matematikáját** (90e Ft+ landing oldal, 100e Ft/hó+ Start csomag = 3–4 KKV ügyfél 4 hónap alatt).
  - És nem hallgatod el az árát sem: a **14–16 órás napokat (18:00–24:00)** és a **3 hibát** (tökéletesítés halogatása, esti fáradtság, kezdeti alulárazás).

#### 4. Felvonás: Bátorító üzenet a nézőnek, hogy merjen elindulni! *(14–15. dia)*
- **Érzelmi cél:** Inspiráló cselekvésre ösztönzés (Call to Action).
- **Mit érzel és közvetítesz?** Úgy beszélsz a nézőhöz, mint egy jó baráthoz, akinek fogod a vállát, és bátorítod, hogy ne várjon tovább.
- **Kulcsüzenet:** *„Ne várd a tökéletes pillanatot! Az 1. ügyfélre fókuszálj, ne a századikra! Nem az a kérdés, hogy van-e időd főállás mellett — hanem az, hogy mennyire AKAROD felépíteni a saját szabadságodat.”*

---

## ✅ BÓNUSZ: Felvétel Előtti 5 Perces Ellenőrzőlista (Checklist)

Mielőtt megnyomod a **Felvétel indítása** gombot az OBS-ben, fuss végig ezen a 8 ponton:

- [ ] **1. Fények és Kamera:** Töröld meg a webkamera lencséjét egy puha kendővel! Ülj úgy, hogy szemből vagy enyhén oldalról kapjon fényt az arcod (ne mögötted legyen az ablak/lámpa), és ülj **60–75 cm-re** a kamerától.
- [ ] **2. Diasor megnyitása:** Nyisd meg a `youtube_slides_foallas_mellett.html` fájlt, és ellenőrizd, hogy az **01 / 15** dián állsz.
- [ ] **3. Szemkontaktus Súgógép (`P` gomb):** Nyomd meg a **`P` billentyűt**, és húzd a felugró keskeny Súgógép ablakot a **monitorod legfelső közepére, közvetlenül a webkamera alá**!
- [ ] **4. Kamera Keret (`K` gomb) vagy OBS Kamera:** Ha a diasor beépített arany kör-kameráját használod, nyomd meg a **`K` billentyűt**, és kattints bele duplán, hogy megjelenjen az élő képed!
- [ ] **5. OBS Forrás ellenőrzés:** Az OBS-ben győződj meg róla, hogy **`Ablak rögzítése (Window Capture)`** van kiválasztva a diasor böngészőablakára — így az előnézeti képen a Súgógép **NEM látszik**!
- [ ] **6. Hang próba:** Mondj 2 mondatot, és nézd meg az OBS-ben, hogy a **Mikrofon** zöld/sárga sávja mozog-e, és rajta van-e az **RNNoise zajszűrő**.
- [ ] **7. Egy pohár víz:** Tegyél magad mellé egy pohár vizet, és némítsd le a telefonodat.
- [ ] **8. Indulhat a felvétel!** Ha elrontasz egy szót, **ne állítsd le a felvételt!** Csak mosolyogj egyet, és folytasd tovább — ettől lesz emberi és vágás nélkül is imádni való a videó!

---

### ⌨️ Gyors Billentyűparancs Puskázó (Felvétel Közben)

| Billentyű | Mit csinál a diasorban? | Mikor használd? |
| :---: | :--- | :--- |
| **`Space`** vagy **`➔`** | Következő dia (3D kamera-mozgással és számláló animációval) | Amikor a Súgógépben látod a `[SPACE ➔ KÖVETKEZŐ DIA]` jelzést |
| **`⬅`** | Előző dia | Ha visszalépnél egy gondolathoz |
| **`P`** | **Szemkontaktus Súgógép megnyitása külön ablakban** | Felvétel előtt — húzd fel a webkamera alá! |
| **`K`** | **Arany Kör-Webkamera be/kikapcsolása** | Felvétel előtt (dupla kattintás a körbe = élő kamera!) |
| **`Kattintás kártyára`** | **Spotlight (Reflektorfény) kiemelés** | Beszéd közben kattints arra a kártyára, amiről épp beszélsz! |
| **`L`** | Arany Lézerpointer be/kikapcsolása | Ha az egérrel látványosan mutatnál a számokra vagy grafikonra |
| **`B`** | YouTube „Iratkozz fel!” TV-banner beúsztatása | A 2. és 8. dián automatikusan beúszik, de bármikor megnyomhatod |
| **`R`** | Aktuális dia animációinak és számlálóinak újrajátszása | Ha újra felpörgetnéd az 1.000.000 Ft-os számlálót |
| **`H`** | Tiszta OBS Mód (alsó vezérlősáv végleges elrejtése) | Felvétel indítása előtt, hogy alul se villanjon fel a menü |
| **`F`** | Teljes képernyő (Fullscreen) | Ha teljes képernyős ablakban rögzítesz |
