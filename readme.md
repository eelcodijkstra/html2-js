## HTML-2: interactie met JavaScipt in de browser

In deze lessen behandelen we hoe je JavaScript in de browser kunt gebruiken voor interactie met de gebruiker.

Interactie met de server via JavaScript in de browser behandelen we in een latere module.

### Voorbeeld: todo-lijst

Als voorbeeld behandelen we een eenvoudige todo-lijst. Ook in de andere modules, voor interactie met de server via formulieren, en voor interactie met de server via JavaScript (AJAX), gebruiken we dit voorbeeld.

Een todo-lijst bestaat uit todo-items, waarbij elk item de volgende eigenschappen heeft:

* `description`: een string-waarde
* `done`: een boolean waarde ("afgevinkt")

De gebruiker kan de lijst inzien, een items toevoegen, een item afvinken, de beschrijving van een item veranderen, en alle voltooide items verwijderen.

De lijst met items blijft bewaard, ook als de browser (of de computer) niet aktief is. (De lijst is "persistent".)

*Hoe ziet het resultaat er (mogelijk) uit? -> Voorbeeld*

### Overzicht van de lessen

1. Koppeling tussen HTML en JavaScript: het Document Object Model (DOM).
2. Events en het afhandelen daarvan.
3. Input-elementen (en formulieren)
4. Lokale opslag: `LocalStorage`; JSON
5. jQuery
6. 

### Welke omgeving?

Omdat je alleen werkt met een statische website, is het mogelijk om interactieve omgevingen zoals Thimble of JSBin te gebruiken. Het gebruik van Cloud9 is ook mogelijk, maar dit is niet direct noodzakelijk.

Als je liever lokaal werkt, dan kun je een slimme programmeer-editor gebruiken - bijvoorbeeld Atom, Brackets, of TextMate. Deze hebben soms mogelijkheden voor de preview van een statische website ingebouwd.

> Er is een verschil tussen het werken met een statische website (via http://...), en het werken met lokale bestanden (file://...).

### Gebruik van jQuery?

In eerste instantie werken we met de "kale" interfaces, om een begrip te krijgen voor de constructies - zowel de DOM-interfaces als de gebruikte JS-constructies.

Later maken we gebruik van jQuery. Een nadeel hiervan is dat het lang niet altijd duidelijk is welke JS-constructies gebruikt worden: er gebeurt het nodige "onder water". Een (groot) voordeel is dat de interfaces eenvoudiger zijn dan de standaard DOM-interfaces.

### Interactie met de server(s)?

We kunnen interactie met servers via AJAX al demonstreren; dit hoeft nog niet de server te zijn die de statische website host. (We maken dan gebruik van cross-site requests.) Voorbeeld: Google Maps.

We zouden een aparte server kunnen inrichten voor het opslaan en terughalen van todo-lijsten en elementen, via een REST interface. Deze server kunnen we later uitleggen. (We hebben dan ook een vorm van identificatie en authenticatie nodig?)

### Welke concepten?

Het doel van deze module is niet alleen om te leren werken met JavaScript in de browser. Dit is een context waarin we met meer algemene informatica-begrippen kennismaken. Deze begripppen komen ook in andere contexten voor.

Bij de behandeling van de verschillende onderdelen proberen we ook in te gaan op deze algemene concepten.
