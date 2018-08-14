# VanillaUPDATER
API Converter plugin for PMMP/Altay

[![Discord](https://img.shields.io/discord/427472879072968714.svg?style=flat-square&label=discord&colorB=7289da)](https://discord.gg/35ZwazH)

Voice használata minimum 13 év!

**Parancsok:**
-
- **/updatetask <plugin könyvtár neve>**
- **/updatetask --all**

## TODOS AND FEATURES
- [x] onCommand és execute függvények hozzáadása a fügvényhez
- [x] Töröli a php funkciót > 7.0 szövegek. Példa: ?string $test => $test 
- [x] Megtísztitja a visszatérési funkció típusait (csak php > 7.0) Példa: function test() : ?int => function test()
- [x] Az import módosítása
- [x] onRun($tick) => onRun(int $tick)
- [ ] Timer frissítése, és létrehozássa (Fejlszetö részéröl, Discord-on kérhetsz)
- [ ] PluginTask újítás, és törlés (Fejlszetö részéröl, Discord-on kérhetsz)
