Fényhíd — alapmodell v0.1

## Cél

A Fényhíd egy kísérleti, moduláris AI-munkatér. Nem általános chatfelület: a felhasználó szándékából indul, és ahhoz illő, követhető munkafolyamatot kínál.

## Közös alap

- A felhasználó ne lásson vagy másoljon rendszerpromptot.
- A rendszer emlékezzen a választott munkaszálra a megengedett tárolási kereten belül.
- Minden eredményben legyen világos, mi tény, mi javaslat és mi bizonytalan.
- A Fényhíd támogassa, ne helyettesítse az ember szakmai vagy alkotói döntését.
- Kezdetben ne kerüljön bele betegazonosító vagy más bizalmas adat.

## Kutató modul

**Feladata:** kérdésből kutatható problémát, forrásirányokat és ellenőrizhető következő lépéseket készíteni.

**Első élő kimenet:** tisztázott kérdés, 2–4 kutatási irány, hivatkozott források és egy javasolt következő lépés.

## Alkotó műhely

**Feladata:** egy szándékból vagy töredékes ötletből megvalósítható alkotói irányt készíteni.

**Első élő kimenet:** a szándék visszatükrözése, 2–3 alkotói irány és az első munkalépés. Később szöveg-, kép-, hang- vagy kódkészítés kapcsolható hozzá.

## Technikai elv

A GitHub Pages oldal a felület. Az AI-hívás külön, biztonságos háttérszolgáltatáson keresztül történik; ott marad az API-kulcs és a modulok működési leírása. Az első éles változat egy AI-szolgáltatóval indul, majd tapasztalat alapján bővíthető.
