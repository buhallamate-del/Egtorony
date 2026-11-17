# Égtorony

Harcos roguelite-incremental: 30 emeletes mászás a felhők fölé, mesterek, ereklyék, Krónika-történet és Végtelen torony.

Játszható a böngészőben: https://buhallamate-del.github.io/Egtorony/

Egyetlen fájl (`index.html`), a mentés a böngésző helyi tárhelyén él.

## Multiverzum

Az Égtorony a szerző többi játékával közös naplót vezet (Eseményhorizont, Kísérleti Lőtér, Raktár 3D, Mézország):
az „Utad” fül alján a „Más világok” panel mutatja, hol jártál már, és a Szív legyőzése kaput nyit az Eseményhorizont felé.

## Heti toronyverseny

A „Verseny” fülön heti rangsor: ki jut a héten a legmagasabbra (a Végtelen toronyban a 30. emelet fölé is), egyezésnél
a nagyobb erőszint nyer. Élő hírek a többiek csúcsairól; hétfőn új hét, a múlt heti győztes +40 emlékpontot kap.
A név és a heti eredmény egy nyilvános MQTT üzenetközvetítőn (HiveMQ) megy át; a könyvtár: `vendor/mqtt/` (MIT licenc).
