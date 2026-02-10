# Magyar WWCI térkép

Ez a projekt a Brandmeister TG 91 World Wide Check‑In magyar állomásainak térképes megjelenítését tartalmazza. A térkép az elmúlt 12 hónap naplózott bejelentkezései alapján készült, és kizárólag a Magyarországon található állomásokat jeleníti meg.

**Élő térkép:**  
https://zolee1988.github.io/bmtg91-wwci-hun/

---

## Funkciók

- Magyarországra fókuszált, Leaflet‑alapú interaktív térkép  
- MarkerCluster a sűrűbb területek áttekinthető megjelenítéséhez  
- Minden állomás popupja QRZ.com hivatkozást tartalmaz  
- Automatikus állomásszámlálás  
- Egyszerű, egyfájlos HTML megoldás  
- Fekete fejléc magyar zászlóval és dátummal  

---

## Adatforrás

A térkép a WWCI (World Wide Check‑In) utolsó 12 hónapjának naplózott adataiból készült.

A hívójelekhez tartozó városadatok a **radioid.net** adatbázisából származnak.  
Ha egy állomás hibás helyen jelenik meg, annak oka általában a radioid.net‑en szereplő pontatlan vagy hiányos QTH‑adat.

A rádióamatőrök a saját adataikat közvetlenül a radioid.net felületén tudják javítani.  
A térkép ezeket az adatokból generált koordinátákat használja.

---

## Használat

A projekt egyetlen HTML fájlból áll, nincs szükség telepítésre vagy build folyamatra.  
A fájl böngészőben megnyitva azonnal működik.

A térkép működéséhez internetkapcsolat szükséges, mivel a Leaflet és a MarkerCluster CDN‑ről töltődik be.

---

## Licenc

A projekt szabadon felhasználható, módosítható és továbbfejleszthető.  
A WWCI logadatok a World Wide Check‑In közösség tulajdonát képezik.
