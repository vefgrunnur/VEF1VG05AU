# Svegjanleg hönnun

### Viðmið (_Breakpoints_) - "_Mobile up_"

```CSS

/* Fyrst koma stílar sem gilda í öllum skjástærðum ss. leturgerð og litir */
body {
	font-family: sans-serif;
	background-color: lightblue;
	color: darkblue;
}
/* Farsími lárétt, Mobile Horisontal */
@media only screen and (min-width: 37.5rem) {  /* min-width= skjáir (screen) sem eru stærri en 600px */
	  body {
		background-color: blue;
		color:white;
	  }
} 
/* spjaldtölva, tablet */
@media only screen and (min-width: 48rem) {  /* skjáir sem eru stærri en 768px */
	  body {
		background-color: black;
		color: lime;
	  }
}
/* Fartölva, laptop */
@media only screen and (min-width: 60rem) {  /* skjáir sem eru stærri en 960px */
	  body {
		background-color: red;
		color: yellow;
	  }
}
/* Tölvuskjár, computer screen */
@media only screen and (min-width: 80rem) {  /* skjáir sem eru stærri en 1280px */
	body {
		max-width: 80rem; 
		margin: 0 auto;  /* efni body miðjusett */ 
	}
}

``` 

Samkvæmt heimildunum eru helstu viðmiðin (**breakpoints**) fyrir sveigjanlegt dálkaskipulag skilgreind með `@media screen` skipuninni til að tryggja að vefsíður birtist rétt á ólíkum skjástærðum. 

Hér eru þau viðmið sem lögð er áhersla á í verkefnunum:

*   **0 – 599px (Farsímar):** Allir dálkar hafa **100% breidd**. Notað er `grid-template-columns: (1fr);`. Ef notað er *grid-template-areas* er þeim raðað upp lóðrétt ("article", "aside1", "aside2").
*   **768px – 959px:** Skipulagið breytist í **tvo dálka** með 50% breidd (`grid-template-columns: (1fr 1fr);`).
*   **960px – 1279px:** Skipulagið fer í **þrjá dálka** með um 33.33% breidd (`grid-template-columns: repeat(3, 1fr);`). Með *grid-template-areas* er svæðunum raðað í eina röð: "aside1 article article aside2".
*   **1280px – 1599px:** Skipulagið fer í **fjóra dálka** með 25% breidd (`grid-template-columns: repeat(4, 1fr);`). Hér er efni vefsíðunnar einnig oft miðjusett með `margin: auto`.
*   **1600px og stærra:** Efni vefsíðunnar er **miðjusett** til að koma í veg fyrir að það teygist of mikið á breiðum tölvuskjám.

Þessi viðmið hjálpa okkur við að hanna viðmót sem er nothæft á öllum helstu tækjum, þar sem hefðbundið dálkaskipulag gengur sjaldnast upp á litlum farsímaskjám.

---

### Grid svæðaskipulag

- https://bok.vefforritun.is/18.skalanlegir
- https://bok.vefforritun.is/21.grid#20.4.2

