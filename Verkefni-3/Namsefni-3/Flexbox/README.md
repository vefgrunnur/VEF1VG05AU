# Flex (_display_)

**Flex** (eða Flexbox) er öflug CSS skipun sem er notuð til að hafa **stjórn á uppsetningu, röðun og miðjun** efnis innan vefsíðu. Samkvæmt heimildunum virkar það á eftirfarandi hátt:

*   **Virkjun:** Til þess að nota Flex þarf fyrst að skilgreina foreldra-einingu (container) með skipuninni **`display: flex;`**.
*   **Endurröðun án HTML-breytinga:** Einn helsti kosturinn við Flex er að hægt er að **breyta röð atriða** sjónrænt án þess að snerta HTML kóðann sjálfan. Til dæmis er hægt að nota **`flex-flow: row-reverse;`** til að snúa við röð dálka (t.d. til að raða þeim í litaröðina gulur, rauður, grænn og blár).
*   **Stýring á flæði:** Flex gerir forriturum kleift að velja hvort efni eigi að raðast í **láréttar raðir eða lóðrétta dálka**.
*   **Auðveld miðjustilling:** Í verkefnum er Flex notað til að **miðjustilla texta** nákvæmlega innan dálka, sem er oft flóknara með öðrum aðferðum.

Í stuttu máli er Flex notað til að gera einstaka hluta vefsíðunnar **sveigjanlega**, þannig að auðvelt sé að stýra því hvernig þeir raðast upp og hvernig plássinu á milli þeirra er deilt.

*   **Endurröðun efnis:** Skipunin `flex-flow: row-reverse;` er notuð til að breyta **„Row order“** (röð dálka) á vefsíðu.
*   **Sjónræn stýring:** Hún er notuð til að raða dálkum í ákveðna litaröð (gulur, rauður, grænn og blár) með því að nýta Flex-stíla frekar en að breyta HTML kóðanum.
*   **Samvinna:** Til þess að `flex-flow` virki þarf einingin fyrst að vera skilgreind með **`display: flex;`**.


*   **`flex-direction`**: Skilgreinir aðeins **áttina** sem atriðin raðast í (t.d. `row`, `column`, eða `row-reverse`, `column-reverse`).
*   **`flex-flow`**: Er svokölluð **stytting (shorthand)**. Hún sameinar skipanirnar `flex-direction` og `flex-wrap` í eina línu. Með því að skrifa `flex-flow: row-reverse` í verkefninu ertu tæknilega séð að nota styttingu sem setur áttina á `row-reverse` og notar sjálfgefið gildi fyrir „wrap“ (sem er `nowrap`).
