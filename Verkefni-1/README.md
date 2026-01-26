# HTML og CSS 

### Markmið:

Nemendur geta:

- stofnað vefumsjónarkerfi með Visual Studio Code
- búið til HTML5 vefsíðu 
- sótt viðbótina _Live Server_ (_extension_) og skoðað vefsíðuna í vafra (_localhost_)
- búið til HTML vefsíðu og nota HTML ívafsmálið til að gera texta læsilegan
- hannað útlit vefsíðunnar með CSS stílum

---

### Innsetning forrits og uppsetning vefþróunarsvæðis

1. Byrjum á að hlaða inn [Visual Studio Code](https://code.visualstudio.com/) og setjum það inn (_install_) í tölvuna okkar

---

### 1.1 Vefþróunarsvæði

1. Búðu til verkefnamöppu í tölvunni þinni og nefndu hana td. **VEF1VG** 
   > Ekki nefna möppur eða skrár með íslenskum stöfum eða hafa bil í heitinu!
1. Opnaðu Visual Studio Code (VSC), veldu `File -> Open folder` og vísaðu VSC á verkefnamöppuna þar sem þú ætlar að vista öll gögn sem unnin eru í áfanganum
   ![open folder](Namsefni-1/img/vsc-openfolder.jpg)
1. Í VSC búðu til möppu með því að fara valglugga (sjá mynd) og smella á möppu+, nefnu hana **verkefni-1** 
   ![NewFolder](Namsefni-1/img/newFolder.jpg)
1. og í **verkefni-1** möppunni býrðu til HTML vefsíðu sem á að nefna **_index.html_** veldu `File -> New file`

```
  VEF1VG
  |_verkefni-1
    |_index.html
```
### Vefsíða skoðuð í vafra (_localhost_)

Það er hægt að ná í stuðningsforrit (_Extensions_) í VSC og láta VSC birta vefsíðuna í sýndarvefþjóni (_localhost_) sem birtir gögn eins og þau séu á internetinu. 

1. Fyrst þarf að ná í viðbótina, veldu **Extensions** í tólastikunni vinstra megin og skráðu síðan í leitargluggan **live server**
2. Veldu **Live Server**, höfundur Ritwick Dey og ýttu síðan á **Install**
   ![Install](Namsefni-1/img/liveServer.jpg)
3. Til að skoða vefsíðu í _localhost_ þá velur þú **Go Live** sem er neðst í hægra horni VSC
   ![Go Live](Namsefni-1/img/openLS.jpg)


### 1.2 HTML

VSC styður fjölmörg forritunarmál og HTML skrár eru studdar dyggilega af VSC forritinu

1. index.html skráin sem þú hefur búið til er alveg auð en VSC er tilbúið með flýtileið til að stofna grunnkóða HTML (_boilerplate_), það eina sem þú þarft að gera er að slá inn `!` og síðan ýtir þú á `enter` eða `tab` takkann á lyklaborðinu þínu

![Námsefni-1](Namsefni-1/img/boilerplate.jpg) 

1. Í möppunni [Námsefni-1](Namsefni-1/verkefni-1-texti.md) er texti sem þú getur notað í HTML vefsíðunni.
1. Settu viðeigandi HTML tög utan um textann til að gera hann læsilegan
1. Vandaðu frágang og notaðu tab lykilinn á lyklaborðinu til að búa til viðeigandi bil í HTML kóðann.  

```
<H1> til <H6>, <p>, <em>, <strong>, <sub>, <sup>, <ul>, <ol>, <li>, <pre>, <br>, <hr> <blockqoute> og <span> 
```
- [Skoða sýnidæmi](Namsefni-1/Synidaemi/README.md)

### 1.3 CSS

Búðu til stílsíðu (_Cascading Style Sheet_) og tengdu hana við html síðuna. Settu stíla á tögin.  Heildarbreidd vefsíðunnar getur verið 1280px og hún á að vera miðjusett í skjáum sem eru stærri en 1280px. Notaðu eftirfarandi CSS skipanir í stílsíðunni:

```CSS
color:; text-decoration:; font-family:; font-style:; font-weight:; border:; margin:; padding:;  
```
Á **a** tagið bætir þú við huldu-klösum (_pseudo class_) þeir eru skráðir með eftirfarandi hætti:

```CSS

  a:link {skipun:gildi;}
  a:visited {skipun:gildi;}
  a:hover {skipun:gildi;}
  a:active {skipun:gildi;}

```

### Námsmat 5% af heildareinkunn

#### Æfingaverkefni

- 1.1 HTML 
- 1.2 CSS 

### Verkefnaskil

- Setjið verkefnið í **.zip skrá** og skilið í INNU/verkefni/verkefni-1.

#### Einkunn verður birt í Innu

