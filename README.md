# Novák Dániel Beadandó - OQC1QU

Ez a projekt egy térképet jelenít meg, amely a Városliget nevezetességeit, egy kép régi verzióját és a  városliget határait tartalmazza, amelyet GeoJSON poligonokkal ábrázol. A térképen OpenStreetMap rétegek, markerek, képátvetítések és poligonok is láthatók.

## Felhasznált Könyvtárak és Eszközök

- [Leaflet](https://leafletjs.com/) - Egy könnyű, interaktív térkép JavaScript könyvtár.
  
## Telepítés

Nincs szükség telepítésre. Egyszerűen nyissa meg a `index.html` fájlt egy böngészőben.

## Használat

A térképen különböző rétegek és jelölések találhatók, amelyek a következők:

### Alaprétegek:

- **OpenStreetMap**: Alapértelmezett OpenStreetMap réteg.
- **OpenStreetMap.HOT**: OpenStreetMap réteg a Humanitarian OpenStreetMap Team (HOT) szolgáltatásával.

### Fedőrétegek:

- **Marker-ek**: Különböző nevezetességek, mint a Széchenyi Gyógyfürdő és Uszoda, Fővárosi Állatkert, Hősök tere, Magyar Zene Háza, Millenium Háza.
- **Polygonok**: GeoJSON poligonok ábrázolása a Városliget területén.
- **Képek**: Régi Városliget kép átlátszó rétegként.

## Egyedi Stílusok és Elemek

- **Egyedi Csillag Ikon**: A markerekhez saját csillag ikont használ.
- **Polygon Stílus**: A Városliget területét ábrázoló poligonok vörös szegéllyel rendelkeznek.

## Térkép Elhelyezése

A térkép alapértelmezett középpontja a Városliget, a zoom szint pedig 16. Az alapértelmezett rétegek magukban foglalják az OpenStreetMap réteget, a markereket, a képek átlátszó rétegét és a poligonokat.

## Rétegvezérlő

A térkép jobb felső sarkában található rétegvezérlővel könnyen kapcsolhatja be vagy ki a különböző rétegeket és elemeket.


## Adatok, hivatkozások

A projekt elkészítéséhez felhasznált adatok elérhetőségei:

- https://hu.wikipedia.org/wiki/Széchenyi_gyógyfürdő
- https://hu.wikipedia.org/wiki/Fővárosi_Állat-_és_Növénykert
- https://hu.wikipedia.org/wiki/Hősök_tere
- https://hu.wikipedia.org/wiki/Magyar_Zene_Háza
- https://hu.wikipedia.org/wiki/Millennium_Háza
- https://leafletjs.com/
- https://geojson.io/
- https://s.24.hu/app/uploads/2021/03/156768186_171535867940884_5112334105194343847_n.jpg