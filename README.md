Leírás

A honlap egy képzeletbeli játék felhasználóinak nyújt szolgáltatást. Az oldalon publikusan megtalálható a játékosok által készített karakterek statisztikái (Karakter név, meglévő kiegészítők, játszott meccsek száma, ebből nyert/vesztett, nyerési arány). Karakternév ismerete esetén az adott karakterre is rá lehet keresni.  Az oldalra lehet regisztrálni. Regisztrált tagoknak a bejelentkezés után további funkciók érhetők el. Megváltoztathatják jelszavukat és a regisztrált email címet, vásárolhatnak kiegészítőket a játékhoz, készíthetnek karaktereket (akár többet is) és kihívhatnak más játékosokat/elfogadhatják a kihívást. A játékhoz tartoznak adminok, ők levonhatnak mmr pontot büntetésből, törölhetnek kihívásokat és érvényteleníthet meccseket.

Kihívás menete

Csak olyan játékos karaktere hívható ki egy kiegészítővel, akinek meg van az adott kiegészítő. Minden karakter csak a saját rangjával megegyező vagy nagyobb rangú játékost hívhat ki. A rang kiszámításához mmr pontokat nyer, illetve veszít a játékos. A játékos nem hívhatja ki saját karaktereit.

Az mmr pontok számítása

-	Egy nyert meccs egyenlő vagy kisebb rangú játékos ellen +10 mmr-t ad, egy vesztes meccs esetén levonásra kerül 12 mmr.
-	magasabb játékos ellen az alap mmr +2-el nő egy ranggal magasabb, +4-el a két ranggal magasabb játékosok ellen.
-	Az mmr pont nem mehet 0 alá, kivéve az új játékos kezdő értékével (-1), rang nélküli játékos +5 mmr-t kap az első meccsére.
-	MMR/Rangok: -1 nincs rang, 0-75 bronz, 76-120 ezüst, 121 – arany
Ha valakit kihívunk és, az elfogadja, a program kiszámol egy valószínű nyertest mmr és nyerési arányok alapján, ez váltja ki a valódi játékot. Új lejátszott játék bekerülésekor a program automatikusan frissíti a profilokat.

Funkcionális elvárások

-	regisztráció
-	bejelentkezés
-	profil adatainak megváltoztatása
-	kiegészítő vásárlás
-	karakterek listázása
-	karakter keresése
-	karakter megtekintése
-	karakter kihívása
-	kihívás elfogadás

Nem funkcionális elvárások

-	felhasználó barát felület
-	keresési eredmény gyors megjelenítése
-	jelszavas azonosítás
-	jelszó biztonságos tárolása
-	statisztika dinamikus frissülése

Szakterületi fogalomjegyzék

-	karakter: a játékos által irányított virtuális hős
-	rang: a játékosok képességei szerint osztályozva vannak
-	mmr: a rangsor felállításához számolt pont 
-	kiegészítő: az alap játékhoz új tartalmak érhetők el fizetés fejében
-	admin: különleges jogokkal rendelkező, a játékszabályok betartásáért felelős felhasználó

Szerepkörök

-	vendég: nem regisztrált és/vagy bejelentkezett látogató, lehetősége van megtekinteni a karakterlistákat és regisztrálni, illetve bejelentkezni
-	felhasználó: regisztrált és bejelentkezett személy, használhat minden funkciót
-	admin: különleges jogokkal rendelkező felhasználó, levonhat mmr pontot, törölhet kihívásokat és érvényteleníthet meccseket.
