# HTML5 ritháttur

Að nota merkingarfræðileg (semantic) HTML5 tög eins og `<header>`, `<main>`, `<section>`, `<article>`, `<aside>` og `<footer>` er ein mikilvægasta undirstaða nútíma vefhönnunar. Hér eru helstu ástæðurnar fyrir því að þessi ritháttur er skynsamlegur samkvæmt heimildunum:

### **1. Betra aðgengi (Accessibility)**
Einn mikilvægasti kosturinn við þessi tög er að þau bæta **aðgengi** vefsíðunnar. Hjálpartæki, svo sem skjálesarar fyrir fólk með sjónskerðingu, nota þessi tög til að átta sig á strúktúr síðunnar. Til dæmis:
*   **`<main>`** lætur skjálesara vita hvar aðalefni síðunnar byrjar, sem gerir notandanum kleift að hoppa beint yfir valmyndir.
*   **`<nav>`** (oft inni í header) og **`<footer>`** hjálpa notendum að átta sig á hvar þeir eru staddir og hvar megi finna upplýsingar um tengiliði eða leiðarkerfi.

### **2. Leitarvélabestun (SEO)**
Notkun þessara taga er mikilvæg fyrir **leitarvélabestun (SEO)**. Leitarvélar eins og Google nota þessi tög til að greina hvaða hlutar síðunnar eru mikilvægastir.
*   Efni inni í **`<article>`** er túlkað sem sjálfstætt efni (t.d. bloggpóstur eða frétt), sem auðveldar leitarvélum að flokka það rétt.
*   **`<aside>`** segir leitarvélum að efnið sé ekki aðalatriðið, sem hjálpar þeim að einbeita sér að mikilvægari texta.

### **3. Rökrétt skipulag og læsilegur kóði**
HTML er notað til að **skipuleggja strúktúr vefsíðunnar** og innihald hennar á rökréttan hátt. 
*   Í stað þess að nota óendanlega mörg óljós `<div>` tög, gera HTML5 tögin forriturum kleift að sjá strax hvaða hlutverk hver hluti síðunnar hefur.
*   Þetta gerir samvinnu forritara auðveldari og flýtir fyrir þegar gera þarf breytingar á kóðanum síðar.

### **Yfirlit yfir hlutverk taga:**
*   **`<header>`**: Inniheldur yfirleitt titil síðunnar, lógó og helstu valmyndir.
*   **`<main>`**: Markar hið eina, sanna aðalefni hverrar síðu.
*   **`<section>`**: Hópar saman skylt efni innan skjalsins.
*   **`<article>`**: Fyrir efni sem gæti staðið eitt og sér, óháð síðunni sjálfri.
*   **`<aside>`**: Fyrir hliðarefni eða tengdar upplýsingar (sidebar).
*   **`<footer>`**: Neðsti hluti síðunnar með upplýsingum um höfundarétt eða tengla.

***

**Samlíking til að einfalda málið:**
Að nota þessi tög er eins og að skrifa **vandaða skýrslu með réttum fyrirsögnum, efnisgreinum og neðanmálsgreinum**. Ef þú myndir skrifa heila bók í einni langri málsgrein án kaflaheita, væri mjög erfitt fyrir lesandann (og leitarvélar eða hjálpartæki) að finna það sem skiptir máli. HTML5 tögin virka eins og skilti sem vísa veginn í gegnum efnið þitt.