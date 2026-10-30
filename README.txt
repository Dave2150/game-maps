GAME MAPS – első webes prototípus

MI VAN BENNE?
- Sötét videojátékos stílusú Magyarország-térkép
- Nagyítás/kicsinyítés és térképmozgatás
- GPS-helyzet lekérése (HTTPS vagy localhost szükséges)
- Helykeresés Nominatim/OpenStreetMap segítségével
- RPG-szerű, szűrhető demó POI-jelölők
- PWA alapok iPhone kezdőképernyőre telepítéshez

FONTOS KORLÁTOK
- Ez prototípus, nem kész navigációs rendszer.
- A jelölők szándékosan mintaadatok, nem valódi boltok.
- Nincs még útvonaltervezés, hangnavigáció, forgalom vagy CarPlay.
- A térképcsempéket és a keresést külső szolgáltatások adják; internet kell.
- A nyilvános OSM/Nominatim végpontok tesztelésre valók, nem nagy forgalmú, üzemszerű alkalmazásra. Később megfelelő szolgáltatót vagy saját infrastruktúrát választunk.

WINDOWS-OS INDÍTÁS
1. Telepítsd a Node.js LTS verzióját (https://nodejs.org/).
2. Nyiss terminált ebben a mappában.
3. Futtasd: npx serve .
4. Nyisd meg a terminálban megjelenő localhost címet a PC böngészőjében.

IPHONE TESZT
A GPS és a PWA telepítéséhez HTTPS-es webcím kell (a localhost kivétel, de az csak a PC-n érvényes). Következő lépésként feltehetjük egy ingyenes statikus tárhelyre HTTPS-sel, majd iPhone Safari > Megosztás > Főképernyőhöz adás.

LICENC / ATTRIBÚCIÓ
A térképszolgáltatás és a helykeresés külső szolgáltatásoktól függ. Éles használat előtt át kell nézni az aktuális szolgáltatói felhasználási feltételeket és az OpenStreetMap attribúciós követelményeket.
