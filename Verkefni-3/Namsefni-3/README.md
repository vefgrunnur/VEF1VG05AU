# Flexbox

Flexbox er einvítt skipulags-módel (_e. one-dimensional layout model_)  til að skipuleggja vefsíðuhluta. Flexbox býður upp fjölmarga jöfnunarmöguleika. Þegar við vinnum með flexbox þá erum við annað hvort að setja efni í röð eða í dálk (_e. row / column_). Það er hægt að ákveða breidd efnis í röðum og jafna hæð efnis eftir ákveðnu skipulagi.

 Flex skipulag hentar vel í alla runuvinnslu og þar sem nýtt efni er stöðugt að bætast við ss. spjallrásir. Einnig hentar Flex í efnisyfirlit (_content menu_) vefsíðu þar sem efni vefs er sífellt að breytast.

 [Sjá nánari lýsingu](Flexbox/README.md)

---

# Grid

CSS grid er notað til að skilgreina skipulag (_e. layout_) vefsíðu með því að skilgreina raðir (_e. rows_) og dálka (_e. columns_) sem efni síðunar er staðsett í. Þetta svipar til þess þegar vefsíður voru skipulagðar með &lt;table> taginu í gamla daga en Grid er hannað með skalanleika í huga.

Munurinn á **grid-template-columns** og **grid-template-areas** felst aðallega í því hvernig þú skilgreinir skipulag (layout) vefsíðunnar og hvernig þú staðsetur efnið innan þess.

Hér er helsti munurinn samkvæmt heimildunum:

### **Grid-template-columns**
*   **Hlutverk:** Notað til að skilgreina **fjölda og breidd dálka** í grid-kerfinu.
*   **Aðferð:** Þú tilgreinir stærðir hvers dálks, oft með einingunni `fr` (fractional unit). Til dæmis þýðir `grid-template-columns: repeat(3, 1fr);` að búið sé til þrjá jafnstóra dálka.
*   **Sveigjanleiki:** Þessi aðferð er mikið notuð með **viðmiðum (@media)** til að breyta dálkafjölda eftir skjástærð, svo sem að fara úr einum dálki í fjóra.

### **Grid-template-areas**
*   **Hlutverk:** Notað til að búa til **sjónrænt skipulag (template)** þar sem þú staðsetur nefnd svæði í ákveðin hólf.
*   **Aðferð:** Fyrst þarf að gefa HTML-einingum (klösum) nafn með skipuninni `grid-area` (t.d. `grid-area: article;`). Síðan er skipulagið teiknað upp með textastrengjum inni í gæsalöppum.
*   **Dæmi:** Á farsíma gæti skipulagið verið lóðrétt listi:
    ```css
    grid-template-areas: 
        "article" 
        "aside1" 
        "aside2";
    ```
    En á stærri skjá gæti því verið breytt í eina röð:
    ```css
    grid-template-areas: 
        "aside1 article article aside2";
    ```

[Sjá nánari lýsingu hér](Grid/Readme.md)

### **Helsti munurinn í hnotskurn**
*   **Grid-template-columns** stýrir **stærð og magni dálka** (lóðréttum brautum) sem efnið flæðir sjálfkrafa í.
*   **Grid-template-areas** býður upp á **rökrétta nafngift og staðsetningu** á heilum hlutum vefsíðunnar (t.d. að setja hliðarstiku vinstra megin við grein) með því að lýsa hnitum þeirra í grid-kerfinu.

Báðar aðferðirnar eru hluti af **CSS Grid** og eru oft notaðar saman til að ná fram hámarks stjórn á sveigjanlegri hönnun.


#### Lesefni

* Sjá nánari umfjöllun um **CSS Flexbox** hér: https://bok.vefforritun.is/17.css-flexbox
* Sjá nánari umfjöllun um **CSS Grid** skipulag hér:https://bok.vefforritun.is/21.grid
