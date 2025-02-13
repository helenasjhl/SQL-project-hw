# SQL-homework-project

A házidolgozat elkészítése során kialakított adatbázis egy háziorvosi rendelő működése kapcsán keletkező adatokat tartalmazza egy hónap intervallumban. Az adatbázis célja, hogy rögzítse a háziorvosi rendelőben megforduló páciensek alapvető adatait, a rendelőbe történő megjelenésük célját, az esetleges tüneteiket, a részükre felírt gyógyszereket, az őket kezelő orvos adatait és lehetővé tegye a betegekre, betegségekre, orvosokra és gyógyszerekre vonatkozó adatok különböző szempontok alapján történő értékelését, elemzését.
Az adatbázis elkészítése során SQLite adatbáziskezelő szoftver 3.12.2 verzióját használtuk, az adatok elemzését POWER BI elemző eszközzel végzetük. Ez utóbbi használatához szükség volt egy SQLite 64 bit ODBC program telepítésére (sqliteodbc_w64.exe) az adatmodel POWER BI-ba történő beolvasása érdekében.   
Az adatbázis elkészítése során egy relációs adatbázis modell került kialakításra, amely összesen 10 sémában tartalmazza az adatokat. 
