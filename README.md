# Procesverslag
Markdown is een simpele manier om HTML te schrijven.  
Markdown cheat cheet: [Hulp bij het schrijven van Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

Nb. De standaardstructuur en de spartaanse opmaak van de README.md zijn helemaal prima. Het gaat om de inhoud van je procesverslag. Besteedt de tijd voor pracht en praal aan je website.

Nb. Door *open* toe te voegen aan een *details* element kun je deze standaard open zetten. Fijn om dat steeds voor de relevante stuk(ken) te doen.





## Jij

<details open>
  <summary>uitwerken voor kick-off werkgroep</summary>

  ### Auteur:
  Julia Hoek

  #### Je startniveau:
  Rood

  #### Je focus:
  Responsive
 
</details>





## Je website

<details open>
  <summary>uitwerken voor kick-off werkgroep</summary>

  ### Je opdracht:
  https://www.bol.com/nl/nl/

  #### Screenshot(s) van de eerste pagina (small screen): 
  homepage  
  <img src="readme-images/bolhomescreen.png" width="375px" alt="Homepage van bol.com">

  #### Screenshot(s) van de tweede pagina (small screen):
  detailpagina  
  <img src="readme-images/boldetailpagina.png" width="375px" alt="Detailpagina van bol.com">
 
</details>



## Toegankelijkheidstest 1/2 (week 1)

<details>
  <summary>uitwerken na test in 1e werkgroep</summary>

  ### Bevindingen
  Lijst met je bevindingen die in de test naar voren kwamen:

  #### Screenreader
  Hier korte omschrijving (met indien nodig afbeeldingen)
  Problemen:
  1. Screenreader skipt niet naar de volgende "H" als die niet in beeld is.
  2. Als de screenreader tussen linkjes skipt, leest hij de productinformatie voor zowel op de afbeelding als het tekstje daaronder (dubbele informatie).
  3. Als de gebruiker een item in zijn winkelwagen doet, krijgt hij geen audio-feedback dat dit gelukt is.

  Hier een omschrijving van hoe het opgelost kan worden (met indien nodig afbeeldingen)
  1. -
  2. Een aria-label toevoegen bij de linkjes (a-tags) van producten die ook een afbeelding bevatten en de alt-tekst van de afbeelding leeg laten.
  3. Automatische audio-feedback toevoegen.


  #### Muis en Toetsenbord 
  Hier korte omschrijving (met indien nodig afbeeldingen)
  Wat gaat goed:
  1. Focus state toont door omlijning waar de gebruiker zich op het scherm bevindt met voldoende contrast.
  2. Er zijn veel opties op de homepage, maar bol.com heeft genoeg ruimte per item gekozen zodat de gebruiker niet snel misklikt.
  
  Problemen:
  1. De navigatie opent niet als de gebruiker er met zijn tab-toets op staat en vervolgens op "enter" drukt.
  2. Geen feedback als de gebruiker hovered over: klikbare afbeeldingen, social media buttons en pijltje naar rechts om meer producten in de caroussel te bekijken.
  3. Geen feedback als de gebruiker op een knop klikt (active).
  

  Hier een omschrijving van hoe het opgelost kan worden (met indien nodig afbeeldingen)
  1. -
  2. Hover feedback toevoegen door bijvoorbeeld de kleur van het lettertype aan te passen, de gehele achtergrond van kleur te veranderen, vergroten van de tekst, tekst te omlijnen, etc.
  3. Active state toevoegen zodat gebruikers kunnen zien waar ze geklikt hebben.


  #### Motoriek (shocks, elastiekjes)
  Hier korte omschrijving (met indien nodig afbeeldingen)
  Problemen bij concentratie stoornis:
  1. Er zijn heel veel opties op de home-pagina die het lastig maken om alles in je op te nemen en een actie te kiezen. Bol doet al zijn best om deze keuzes te   beperken, maar het blijft lastig.

  Hier een omschrijving van hoe het opgelost kan worden (met indien nodig afbeeldingen)


  #### Visueel (brillen, contrast, kleurenblind, dark/light). 
  Hier korte omschrijving (met indien nodig afbeeldingen)
  Wat gaat goed:
  1. Central field loss: De gebruiker moet veel van links naar rechts kijken om de gehele content te bekijken. Doordat Bol zijn content in kleine vakjes heeft opgedeeld, blijft het redelijk scanbaar voor deze gebruikers.
  2. Kleurenblindheid heeft geen invloed op het onduidelijk maken van de content omdat het voldoende contrast heeft.
  
  Problemen:
  1. Periphal field loss: Kleine tekst op de site is lastig te lezen, bijvoorbeeld de items in het menu.
  2. Diabetic eye disease: De tekst is opzich leesbaar, maar het blijft lastig.
  3. Bij volledige kleurenblindheid is er geen feedback op de linkjes in de hoverstate in de footer.
  4. Gebruikers met blurred vision kunnen de dunne tekst in bijvoorbeeld de navigatie lastig lezen.
  5. Geen dark-mode beschikbaar
  
 
  Hier een omschrijving van hoe het opgelost kan worden (met indien nodig afbeeldingen)
  Oplossingen:
  1. Periphal field loss: Mogelijkheid geven om de tekstgrootte op de site aan te passen.
  2. Zelfde oplossing als periphal field loss. Zo kan elke gebruiker de site aanpassen op zijn specifieke needs.
  3. Hoverstate in de footer aanpassen door bij hover een lijntje onder de tekst te laten verschijnen.
  4. Mogelijkhed geven om het gewicht van de tekst aan te passen als gebruikers hier behoefte aan hebben.
  5. Dark-modus toevoegen waarbij bol.com meer gebruik maakt van gedempte kleuren en zwart/grijze achtergrond.


</details>



## Breakdownschets (week 1)

<details>
  <summary>uitwerken na afloop 2e werkgroep</summary>

  ### de hele pagina: 
  <img src="readme-images/homepagebreakdown1.jpg" width="375px" alt="breakdown van de hele pagina">
  <img src="readme-images/homepagebreakdown2.jpg" width="375px" alt="breakdown van sections hele pagina">
  
  ### dynamisch deel (bijv menu): 
  <img src="readme-images/homepagedynamischbreakdown.jpg" width="375px" alt="breakdown van een dynamisch deel">

  ### wellicht nog een dynamisch deel (bijv filter): 
  <img src="readme-images/dummy-plaatje.jpg" width="375px" alt="breakdown van nog een dynamisch deel">

</details>





## Voortgang 1 (week 2)

<details>
  <summary>uitwerken voor 1e voortgang</summary>

  ### Stand van zaken
  hier dit ging goed & dit was lastig (neem ook screenshots op van delen van je website en code)


  ### Agenda voor meeting
  samen met je groepje opstellen

  | student 1 - Kim      | student 2 - Tim        | student 3 - Julia (ik)   | student 4 - Robin       |
  | ---            | ---                | ---          | ---              |
  | dit bespreken  | en dit             | 1. Hoe kan ik gebruikers door een carousel laten skippen d.m.v. buttons?    | en dan ik dat    |
  | en dat ook nog | dit als er tijd is | 2. Hoe kan ik m'n hamburgermenu full-screen tonen? Ja, display:block; , maar die class via JS toevoegen of anders?| dit wil ik zeker |
  |                |                    |3. Met 3 css-style sheets, kan ik de variabele van kleuren in 1 sheet zetten en die dan in de andere twee sheets gebruiken?| |
  | ...            | ...                | ...          | ...              |


  ### Verslag van meeting
  hier na afloop snel de uitkomsten van de meeting vastleggen

  - punt 1
  - punt 2
  - nog een punt
  - ...

</details>





## Voortgang 2 (week 3)

<details>
  <summary>uitwerken voor 2e voortgang</summary>

  ### Stand van zaken
  hier dit ging goed & dit was lastig (neem ook screenshots op van delen van je website en code)


  ### Agenda voor meeting
  samen met je groepje opstellen

  | student 1      | student 2          | student 3    | student 4        |
  | ---            | ---                | ---          | ---              |
  | dit bespreken  | en dit             | en ik dit    | en dan ik dat    |
  | en dat ook nog | dit als er tijd is | nog een punt | dit wil ik zeker |
  | ...            | ...                | ...          | ...              |


  ### Verslag van meeting
  hier na afloop snel de uitkomsten van de meeting vastleggen

  - punt 1
  - punt 2
  - nog een punt
- ...

</details>





## Toegankelijkheidstest 2/2 (week 4)

<details>
  <summary>uitwerken na test in 8e werkgroep</summary>

  ### Bevindingen
  Lijst met je bevindingen die in de test naar voren kwamen (geef ook aan wat er verbeterd is):

  #### Screenreader
  Hier korte omschrijving (met indien nodig afbeeldingen)

  Hier een omschrijving van hoe het opgelost kan worden (met indien nodig afbeeldingen)


  #### Muis en Toetsenbord 
  Hier korte omschrijving (met indien nodig afbeeldingen)

  Hier een omschrijving van hoe het opgelost kan worden (met indien nodig afbeeldingen)


  #### Motoriek (shocks, elastiekjes)
  Hier korte omschrijving (met indien nodig afbeeldingen)

  Hier een omschrijving van hoe het opgelost kan worden (met indien nodig afbeeldingen)


  #### Visueel (brillen, contrast, kleurenblind, dark/light). 
  Hier korte omschrijving (met indien nodig afbeeldingen)

  Hier een omschrijving van hoe het opgelost kan worden (met indien nodig afbeeldingen)

</details>





## Voortgang 3 (week 4)

<details>
  <summary>uitwerken voor 3e voortgang</summary>

  ### Stand van zaken
  hier dit ging goed & dit was lastig (neem ook screenshots op van delen van je website en code)


  ### Agenda voor meeting
  samen met je groepje opstellen

  | student 1      | student 2          | student 3    | student 4        |
  | ---            | ---                | ---          | ---              |
  | dit bespreken  | en dit             | en ik dit    | en dan ik dat    |
  | en dat ook nog | dit als er tijd is | nog een punt | dit wil ik zeker |
  | ...            | ...                | ...          | ...              |


  ### Verslag van meeting
  hier na afloop snel de uitkomsten van de meeting vastleggen

  - punt 1
  - punt 2
  - nog een punt
  - ...

</details>





## Eindgesprek (week 5)

<details>
  <summary>uitwerken voor eindgesprek</summary>

  ### Je uitkomst - karakteristiek screenshots:
  <img src="readme-images/dummy-plaatje.jpg" width="375px" alt="uitomst opdracht 1">


  ### Dit ging goed/Heb ik geleerd: 
  Korte omschrijving met plaatjes

  <img src="readme-images/dummy-plaatje.jpg" width="375px" alt="top">


  ### Dit was lastig/Is niet gelukt:
  Korte omschrijving met plaatjes

  <img src="readme-images/dummy-plaatje.jpg" width="375px" alt="bummer">
</details>





## Bronnenlijst

<details open>
  <summary>continu bijhouden terwijl je werkt</summary>

  Nb. Wees specifiek ('css-tricks' als bron is bijv. niet specifiek genoeg).

  1. bron 1
  2. bron 2
  3. ...

</details>
