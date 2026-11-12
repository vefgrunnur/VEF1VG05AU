# Uppbygging vefsíðu, DOM

Tráskipan vefsíðu, sem oft er kölluð **DOM (Document Object Model)**, virkar eins og rökrétt ættartré þar sem hver eining í HTML-kóðanum á sinn ákveðna stað í stigveldinu.

Hér er nánari útlistun á því hvernig þetta „ættartré“ er uppbyggt samkvæmt heimildunum:

*   **Rótin og stofninn:** Efst í trénu er skjalið sjálft, en út frá því vaxa meginhlutar vefsins. Í nútíma vefhönnun er lögð áhersla á að nota **merkingarfræðileg HTML5 tög** til að búa til skýra og rökrétta tráskipan. 
*   **Foreldra- og afkvæmaeiningar (Parent/Child):** Skipulagið byggist á því að einingar eru „hreiðraðar“ hver inn í aðra. Sem dæmi:
    *   **`<main>`** eða **`<section>`** virka sem „foreldrar“.
    *   Innan í þeim geta verið „afkvæmi“ eins og **`<article>`**, **`<h1>`** til **`<h6>`**, eða **`<p>`**.
    *   Listar eins og **`<ul>`** eða **`<ol>`** eru foreldrar fyrir **`<li>`** einingar, sem eru þá systkini innan trjámyndarinnar.
*   **Greinar ættartrésins:** Heimildirnar nefna sérstaklega mikilvægi þess að nota rétt tög til að skilgreina greinar trésins, svo sem:
    *   **`<header>`** og **`<nav>`** fyrir efsta hluta og valmyndir.
    *   **`<aside>`** fyrir hliðarefni.
    *   **`<footer>`** fyrir botninn á trénu.

**Hvar má finna ítarlegri upplýsingar?**
Fyrir þá sem vilja dýpka skilning sinn á því hvernig á að skrifa og skipuleggja þessa tráskipan, þá vísa heimildirnar í:
1.  **Bókina um vefforritun:** Sérstaklega **kafla 5 (HTML Element)** og **kafla 7 (Að skrifa HTML)**.
2.  **MDN kennsluefnið:** Kaflann um **„Structuring content with HTML“** sem fer ítarlega í hvernig á að byggja upp strúktúrinn.
3.  **HTML DOM API:** Ítarlegar tæknilegar tilvísanir um hvernig forritunarviðmótið heldur utan um þessa tráskipan.

Þessi uppbygging er undirstaðan í því að **vafrinn skilji samhengið** á síðunni og geti birt hana rétt, auk þess sem hún er lykilatriði fyrir **aðgengi** (accessibility) svo hjálpartæki eins og skjálesarar geti ratað um „ættartréð“.
