# Tenglar (_links_)

Mjög gott getur verið að hafa tengla sem vísa á ákveðinn hluta innan vefsíðu. Þetta gerir notanda mögulegt að nálgast efnisatriði á auðveldan hátt. 

Í HTML er þetta gert með ID eigindinu. 

```HTML
    <body id =“top“>
```

ID eigindið sem geymir hina eiginlegu tilvísun á ákveðna staðsetningu í skjalinu. Vafrinn notar # táknið til að finna ID skilgreininguna.

```HTML
    <a href="#top">Efst á síðu</a>
```

* [Dæmi um innri tengla](Daemi/relative_links.html) (_relative links_)

## Hulduklasar (_pseudo-class_)

Til að gera vafrann móttækilegan (_responsive_) þá eru til svokallaðir _hulduklasar_ sem bregðast við notkun notandans.

```CSS
    a:link {color: #F00}
    a:visited {color: #0F0}
    a:hover {color: #F0F}
    a:active {color: #00F}
```

* ```:link``` upphaflegur litur. Blár er staðallitur og texti undirstrikaður
* ```:visited``` annar litur gefur til kynna að notandi hefur notað tenginguna
* ```:hover``` ATHUGIÐ! virkar ekki á snertiskjá
* ```:active``` virkar þegar tengill er snertur eða valinn

Það eru fjölmargir aðrir hulduklasar sem notaðir eru í CSS stílsíðu og við förum nánar í notkun þeirra í næsta áfanga. [Sjá nánar.](https://www.w3schools.com/css/css_pseudo_classes.asp)

---

### Leturstillingar í CSS

```CSS

body {
    font-family: Helvetica, sans-serif; /* vafrinn velur Helvetica ef það er til, annars system font (sans-serif) */ 
    font-style: normal;      /* italic, obligue */
    font-weight: 500;     /* normal, bold, 100 - 900 */
    font-size: 1rem;          /* 16px, 1em, 100% */
    line-height: 1.5;         /* tekur mið af einingunni sem er á font-size */
}

/* hér er öllum stílum sópað saman í eina skipun "font:"*/
body {
    font:normal 500 1rem/1.5 Helvetica, sans-serif;
    /*font-style, -weight, -size/-lineheight -family */
}


```

### Bakgrunnsmynd í vefsíðu

Þar sem meirihluti vafranotkunar er á farsímaskjáum þá ber að forðast flóknar og litríkar ljósmyndir. Best að sleppa þeim eða notast við hlutlausa fleti. Góð lausn er að nota [bakgrunnslitaskala](https://www.w3schools.com/css/css3_gradients.asp).


```CSS

body {
    background-color: #6ff;
    background-image:url(flott-logo.svg);
    background-repeat: no-repeat;     /* repeat-x eða repeat-y */
    background-position: 200px 300px; /* föst staðsetning frá vinstra horni efst */
    background-position: center middle;
    /* X lárétt: left, center, right. Y lóðrétt: top, middle, bottom */
    background-attachment: fixed; /* scroll */	
}
/* allar bakgrunns-skipanir í einni */
body {			
	background: rgb(3,3,3) url(image.jpg) 0px -5px scroll no-repeat;
            /*  litur,   mynd,  staðsetning X-Y,  fixed,  repeat -x -y */

}

```

## Línulengd texta og lesskilningur

Þegar kemur að góðri lestrarupplifun á skjá eða á prenti, þá er línulengdin (fjöldi stafa í hverri línu) einn mikilvægasti þátturinn. Ef línurnar eru of langar þreytist augað á að finna næstu línu, en séu þær of stuttar rofnar takturinn við það að augað þarf sífellt að hoppa vinstra megin aftur.

Hér eru viðurkennd viðmið fyrir bestu lestrarupplifunina:

### Gullna reglan

* **Ákjósanleg lengd:** 45 til 75 stafir (með bilum).
* **Fullkomin miðja:** Um **66 stafir** á línu er oft talið „hinn fullkomni staður“ fyrir samfellt lesmál.

---

### Viðmið eftir miðlum

| Miðill | Ráðlögð línulengd | Af hverju? |
| --- | --- | --- |
| **Prentmál** | 45–75 stafir | Hefðbundnar bækur og tímarit fylgja þessu til að halda einbeitingu lesandans. |
| **Vefsíður (skjár)** | 50–80 stafir | Skjáir þola örlítið lengri línur en prent, en farið yfir 100 stafi fer fólk að „skanna“ textann í stað þess að lesa hann. |
| **Snjallsímar** | 30–45 stafir | Vegna þrengra pláss er línan styttri til að textinn verði ekki of smár og ólæsilegur. |

---

### Af hverju skiptir þetta máli?

* **Vöðvaþreyta í augum:** Ef línan er of löng þarf augað að hreyfa sig meira en eðlilegt þykir. Þegar komið er að enda línunnar á lesandinn erfitt með að fókusera á rétta línu vinstra megin.
* **Hraði og skilningur:** Stuttar og hnitmiðaðar línur hjálpa heilanum að vinna úr upplýsingum hraðar.
* **Sálfræðileg áhrif:** Of langar línur geta virkað yfirþyrmandi á lesandann áður en hann byrjar, á meðan hæfileg lengd virkar aðgengileg og „létt“.

> **Pro-tip:** Ef þú ert að hanna vefsíðu er gott að nota CSS-skipunina `max-width: 70ch;` á textablokkir. Það takmarkar breiddina við um það bil 70 stafi, óháð skjástærð.

Hvað finnst þér sjálfum þægilegast – viltu hafa textann frekar þröngan eða finnst þér gott að nýta alla breiddina á skjánum?
