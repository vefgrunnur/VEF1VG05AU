# Glósur úr verkefnum 1 og 2

Hér eru ítarlegar glósur úr verkefnalýsingum 1, 2 og 3, sem taka saman helstu markmið og tæknileg atriði sem lögð er áhersla á í námskeiðinu.

### **Verkefni 1: Vinnuflæði og tól á GitHub**
Fyrsta verkefnið leggur áherslu á að kynnast því umhverfi og þeim verkfærum sem nútíma forritarar nota við smíði hugbúnaðar.

*   **AI og kóðun:** Nota skal tól eins og **GitHub Copilot** til að skrifa betri kóða með gervigreind og **GitHub Spark** til að byggja snjallforrit.
*   **Vinnuflæði (Workflows):**
    *   **Actions:** Notað til að **sjálfvirknivæða vinnuferla**.
    *   **Codespaces:** Býður upp á tafarlaus þróunarumhverfi í skýinu.
    *   **Issues:** Notað til að **skipuleggja og fylgjast með vinnu**.
*   **Öryggi og samvinna:** Lögð er áhersla á að finna veikleika með **Advanced Security** og stöðva leka á leynilegum upplýsingum með **Secret protection**. Nemendur geta nýtt **GitHub Skills** til að dýpka þekkingu sína.

---

### **Verkefni 2: Grundvöllur HTML og CSS**
Verkefni 2 snýst um að skilja strúktúr vefsíðna og hvernig grunneiningar þeirra eru stílaðar.

*   **Box módelið:** Skilningur á því hvernig einingar samanstanda af **padding (fyllingu), border (ramma) og margin (spássíu)** utan um innihald.
*   **Stýring á tögum:**
    *   **Display:** Breyta eiginleikum taga með `display:` skipuninni (t.d. fyrir lista).
    *   **Float:** Notað til að láta texta flæða í kringum myndir, gjarnan notað með `float: left`, `border` og `padding`.
*   **HTML5 ritháttur (Semantics):** Mikilvægt er að nota merkingarfræðileg tög til að byggja upp vefsíðuna rétt:
    *   Helstu tög: `<header>`, `<nav>`, `<section>`, `<main>`, `<article>`, `<aside>` og `<footer>`.
*   **Hulduklasar (Pseudo classes):** Stíla skal tengla (`<a>`) í nav-taginu út frá ástandi þeirra:
    *   `:link` (tengill), `:visited` (heimsóttur), `:hover` (mús yfir) og `:active` (virkt/smellt á).

Samkvæmt heimildunum um **box módelið** (verkefni 2.1) samanstendur hver eining af þremur meginlögum sem stýra rými og útliti:

*   **Padding (Fylling):** Þetta er rýmið sem liggur næst innihaldinu. Í verkefnunum er það notað til að búa til pláss á milli texta og ramma.
*   **Border (Rammi):** Þetta er línan sem umlykur fyllinguna og innihaldið. Hann er notaður til að afmarka einingar sjónrænt.
*   **Margin (Spássía):** Þetta er ysta lagið í box módelinu og er notað til að búa til rými **utan um** eininguna sjálfa til að aðskilja hana frá öðru efni á síðunni.

Í stuttu máli: **Padding** er rými innan rammans, **Border** er ramminn sjálfur, og **Margin** er rýmið utan rammans. Þessi þrjú gildi eru notuð saman í stílsíðum til að stjórna nákvæmlega hvernig einingar (eins og fyrirsagnir eða textablokkir) raðast upp á vefsíðunni.

