# [Jegyzetár](https://jegyzetar.eu/)

> **Közösségi jegyzetmegosztó platform diákoknak.**  
> Ossz meg, rendszerezz és találj jegyzeteket egyszerűen - egy helyen, átláthatóan.

---

## Mi az a Jegyzetár?

A **Jegyzetár** egy diákok által épített, webalapú platform, amely lehetőséget ad jegyzetek megosztására, böngészésére és közös tanulásra.  
Célunk egy olyan **központi tudástár** létrehozása, amely kiváltja a szétszórt Messenger-, Drive- és e-mail-alapú megoldásokat.

**Alapelveink:**

- Egyszerű használat
- Áttekinthető felépítés
- Közösségi tudásmegosztás

---

## Fő funkciók

- Jegyzetek feltöltése, rendszerezése és letöltése
- Gyors keresés tantárgy, évfolyam és kulcsszó alapján
- Kommentelés és értékelés
- Közösségi pontgyűjtés és badge rendszer
- *(Jövőben)* valós idejű közös jegyzetelés és AI-alapú funkciók

---

## Célközönség

- Középiskolások (15–20 év)
- Egyetemisták és főiskolások
- Olyan diákok, akik:
  - szívesen megosztják saját jegyzeteiket
  - hatékony, strukturált tanulási forrást keresnek

---

## Projektcélok

- Egy központi, könnyen kezelhető jegyzetrendszer kialakítása
- A jegyzetek gyors elérhetőségének és kereshetőségének biztosítása
- A tanulás közösségi élménnyé tétele
- Motiváció növelése pontozási és jutalmazási rendszerekkel

---

## Funkciók részletesen

| Funkció                | Leírás |
|------------------------|--------|
| Jegyzetfeltöltés       | PDF, Word és egyéb formátumok feltöltése, tantárgy szerint |
| Keresés és szűrés      | Tantárgy, évfolyam, kulcsszó |
| Kommentek, értékelések | Visszajelzés és minősítés |
| Kedvencek              | Jegyzetek mentése későbbi használatra |
| Classroom-ok           | Tanulócsoportok és közös munka |
| Értesítések            | Új feltöltések, hozzászólások |
| Prémium funkciók       | Offline letöltés, statisztikák, reklámmentesség |

---

## Bevételi modell

### Freemium rendszer

- **Ingyenes:** keresés, megtekintés, kommentelés
- **Prémium:** offline letöltés, reklámmentes élmény, statisztikák, AI-funkciók

**Ár:** kb. 500–1000 Ft / hó

### Közösségi pontok és mikrotranzakciók

- Aktivitásért pontok járnak (feltöltés, értékelés)
- Pontok beválthatók:
  - badge-ekre
  - prémium napokra
  - akár valós pénzre

### Reklámok (csak ízlésesen)

- Oktatási jellegű hirdetések
- Prémium előfizetés esetén **nincs reklám**

---

## Design és UX

- **Stílus:** letisztult, modern
- **Színek:** kék–fehér paletta
- **Betűtípus:** Inter / Roboto
- **Fókusz:** gyors navigáció, tiszta tipográfia

**Reszponzív kialakítás:**

- Mobil: gyors keresés, egyszerű letöltés
- Tablet: kényelmes tanulás
- Desktop: teljes funkcionalitás

---

## Technológiai stack

| Terület           | Technológia         |
|------------------ |-------------------- |
| **Frontend**      | React *(tervezett)* |
| **Backend**       | PHP                 |
| **Adatbázis**     | MySQL               |
| **Verziókezelés** | Git + GitHub        |
| **Hosting**       | RackHost            |
| **Design**        | Figma               |

---

## A fejlesztőcsapat

A Jegyzetár egy diákok által indított és fejlesztett projekt.  
Az alábbi személyek alkotják a projekt **alap fejlesztőcsapatát**, amely a jövőben további közreműködőkkel bővülhet.

### [Baranyi Norbert](https://github.com/baranyi0)
**Szerepkör:** Backend fejlesztő / rendszerlogika  
**Fő fókusz:**
- Autentikáció és fiókkezelés
- Biztonságos bejelentkezési folyamatok
- E-mail alapú visszaigazolási rendszerek
- Jegyzetekhez kapcsolódó backend funkciók

**Kapcsolódó fejlesztések:**
- 2FA bejelentkezés
- Jelszó-visszaállítás e-mail rendszer
- Regisztrációs és e-mail-változtatási visszaigazolások
- Kedvencek mentése
- Külön jegyzet oldal (note.php)
- Jegyzethez ugrás funkció

### [Csontos Kincső Anasztázia](https://github.com/doomhyena)
**Szerepkör:** Frontend fejlesztő / UI–UX  
**Fő fókusz:**
- Felhasználói felület és élmény (profil oldal, redesign, custom design)
- Többnyelvűség (multilanguage támogatás)
- Jogosultság- és adatbiztonsághoz kapcsolódó frontend logika
- Profilfunkciók és kliensoldali validációk
- UI-hibák javítása és finomhangolás

**Kapcsolódó fejlesztések:**
- Discord login
- Custom profil design, oldal redesign
- Profiladatok szerkesztése
- Jegyzet statisztikák
- Database helper usage
- Frontend biztonsági fejlesztések

###  [PaladiTech](https://github.com/PaladiTech)
**Szerepkör:** Full-stack fejlesztő / közösségi rendszerek  
**Fő fókusz:**
- Tanulócsoportok és közösségi funkciók
- Tanár–diák rendszer kialakítása
- Mobilos felhasználói élmény javítása
- Monetizációs és üzleti funkciók
- Validációk és rendszerstabilitás

**Kapcsolódó fejlesztések:**
- Tanulócsoportok létrehozása és hibajavítása
- Tanár–diák rendszer
- Mobil navigáció javítása
- Hirdetések kezelése
- Születésnapi validáció
- Közösségi funkciók stabilizálása

**Fő fókusz:**

- modern webes technológiák gyakorlati alkalmazása
- valódi felhasználói problémák megoldása
- nyílt, fejlődő projekt szemlélet

A fejlesztés folyamatos, és a projekt nyitott új ötletekre, visszajelzésekre és jövőbeli közreműködőkre.

---

## Használt szofverek

- XAMPP
- Visual Studio Code
- PhpStorm
- Git
- GitHub
- Discord

---

## Jövőbeli tervek

- Felhasználói profilok és rangrendszer
- Mobilalkalmazás (React Native / Flutter)
- Iskolai és oktatási partnerprogramok
- AI-alapú jegyzetösszefoglalás és keresés

---

## Sikerességi mutatók

- Aktív felhasználók száma
- Feltöltött jegyzetek mennyisége
- Közösségi aktivitás és értékelések

---

## Közösségi mottó

> *"Tanuljunk együtt, ne külön-külön."*
