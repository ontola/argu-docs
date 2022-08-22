Argu wordt gebruikt om mensen te betrekken bij besluitvorming.
Het is daarom extra belangrijk dat iedereen een kans krijgt om mee te doen.
We vinden het daarom belangrijk dat de website toeganklijk is voor iedereen; dus ook mensen met een beperking waardoor web browsen lastiger gaat.

## Toeganklijkheidsverklaring

Voor overheidswebsites is het verplicht om een toegankelijkheidsverklaring te hebben. Die van Argu.co is [hier terug te lezen](https://www.toegankelijkheidsverklaring.nl/verklaringen/445/preview
). Deze geld voor alle websites die draaien op de Argu software.

## Webrichtlijnen / WCAG standaard

De internationale standaard voor toegankelijkheidsonderzoek is de [WCAG](https://www.w3.org/TR/WCAG21/), een standaard die door het W3C wordt onderhouden.
De strengere, moderne versie hiervan is de WCAG 2.1.
Er bestaan hier diverse niveaus van: A, AA en AAA.
Wij proberen met onze webapplicatie (die je gebruikt om deze pagina mee te bekijken) te voldoen aan de strengste eisen.
We hebben daarom de volgende onderzoeken uitgevoergd:

- We hebben een [quickscan uitgevoerd op WCAG.nl](https://wcag.nl/rapporten/dada75b412bc/), waar we aan alle checks voldoen voor de hoogste AAA richtlijn. De laatste controle is gedaan op 10 januari 2020 voor [een kenmerkende pagina voor Argu discussie](https://argu.nl/m/79).
- Wij hebben alle punten uit de WCAG 2.1 [specificatie](https://www.w3.org/TR/WCAG21/) uitgewerkt. De laatste controle is gedaan op 26 juni 2020. Zie hieronder te uitkomsten:

### WCAG 2.1 AA

- [x] [1.1.1 – Non-text Content](http://www.w3.org/TR/UNDERSTANDING-WCAG20/text-equiv-all.html). Afbeeldingen zijn, waar mogelijk, voorzien van 'alt' tags. Gebruikers kunnen ook aan afbeeldingen tags toevoegen, maar dit is niet verplicht.
- [x] [1.2.1 – Audio-only and Video-only (Pre-recorded) ](http://www.w3.org/TR/UNDERSTANDING\\-WCAG20/media-equiv-av-only-alt.html). Niet van toepassing, gezien de applicatie geen video en audio ondersteund.
- [x] [1.2.2 – Captions (Pre-recorded)](http://www.w3.org/TR/UNDERSTANDING-WCAG20/media-equiv-captions.html). Niet van toepassing.
- [x] [1.2.3 – Audio Description or Media Alternative (Pre-recorded)](http://www.w3.org/TR/UNDERSTANDING-WCAG20/media-equiv-audio-desc.html). Niet van toepassing.
- [x] [1.2.4 – Captions (Live)](http://www.w3.org/TR/UNDERSTANDING-WCAG20/media-equiv-real-time-captions.html). Niet van toepassing.
- [x] [1.2.5 – Audio Description (Pre-recorded)](http://www.w3.org/TR/UNDERSTANDING-WCAG20/media-equiv-audio-desc-only.html). Niet van toepassing.
- [X] [1.3.1 – Info and Relationships](http://www.w3.org/TR/UNDERSTANDING-WCAG20/content-structure-separation-programmatic.html). Argu maakt gebruik van logische, semantische HTML5 tags en gebruikt Aria attributen om semantische waarde voor niet-visuele gebruikers duidelijk te maken. Formulieren hebben visuele en niet-visuele indicaties om vereiste velden te arceren.
- [x] [1.3.2 – Meaningful Sequence](http://www.w3.org/TR/UNDERSTANDING-WCAG20/content-structure-separation-sequence.html). Argu heeft een logische volgorde van HTML elementen, die aansluit op wat er visueel te zien is.
- [X] [1.3.3 – Sensory Characteristics](http://www.w3.org/TR/UNDERSTANDING-WCAG21/content-structure-separation-understanding.html). De structuur en acties van een pagina zijn helder in text beschreven, zodat ook slechtziende gebruikers de applicatie kunnen gebruiken.
- [X] [1.3.4 – Orientation](https://www.w3.org/WAI/WCAG21/Understanding/orientation.html). De structuur en acties van een pagina zijn helder in text beschreven, zodat ook slechtziende gebruikers de applicatie kunnen gebruiken.
- [X] [1.3.5 – Identify Input Purpose](https://www.w3.org/WAI/WCAG21/Understanding/identify-input-purpose.html). We gebruiken semantische formulieren, waarbij de computer kan uitlezen wat de betekenis is van en veld.
- [X] [1.4.1 – Use of Colour](http://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-without-color.html). Kleur wordt gebruikt om informatie weer te geven in formulieren, maar we gebruiken ook 'disabled' tags om elementen te deactiveren zodat de focus er voor slechtziende gebruikers er niet heen gaat.
- [X] [1.4.2 – Audio Control](http://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-dis-audio.html). Niet van toepassing.
- [x] [1.4.3 – Contrast (Minimum)](http://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-contrast.html). We houden hoge contrastwaarden aan van 3:1 (grote tekst) en 4.5:1 (kleine tekst) om leesbaarheid zo hoog mogelijk te houden.
- [x] [1.4.4 – Resize Text](http://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-scale.html). Alle content kan worden opgeschaald met in-browser font-size controls. De applicatie is uitgedrukt in relatieve maten, zodat de interface ook met grootte letters bruikbaar blijft. De content kan tot meer dan 200% worden vergroot, zonder dat functionaliteit verloren gaat.
- [x] [1.4.5 – Images of Text](http://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-text-presentation.html). De applicatie gebruikt geen afbeeldingen van tekst.
- [x] [1.4.10 – Reflow](https://www.w3.org/WAI/WCAG21/Understanding/reflow.html). Je kunt inzoomen / de tekst vergroten en de website blijft bruikbaar en leesbaar.
- [x] [1.4.11 – Non-Text contrast](https://www.w3.org/WAI/WCAG21/Understanding/non-text-contrast.html). We hanteren een minimum van 3:1 contrast, ook voor iconen.
- [x] [1.4.12 – Text spacing](https://www.w3.org/WAI/WCAG21/Understanding/text-spacing.html). We hanteren voldoende ruimte tussen letters en regels.
- [x] [1.4.12 – Content on Hover or Focus](https://www.w3.org/WAI/WCAG21/Understanding/content-on-hover-or-focus.html). Hover en focus interacties zijn optioneel en altijd makkelijk weer weg te halen.
- [x] [2.1.1 – Keyboard](http://www.w3.org/TR/UNDERSTANDING-WCAG20/keyboard-operation-keyboard-operable.html). De applicatie is goed te bedienen met slechts het toetsenbord. Je kunt de gehele registratie + post flow zonder muis afhandelen.
- [x] [2.1.2 – No Keyboard Trap](http://www.w3.org/TR/UNDERSTANDING-WCAG20/keyboard-operation-trapping.html). Er zitten geen plekken in de applicatie waar de focus blijft hangen en niet meer ontsnapbaar is. Modals kunnen worden gesloten met 'escape'.
- [x] [2.1.4 – Character Key Shortcuts](https://www.w3.org/WAI/WCAG21/Understanding/character-key-shortcuts.html). We gebruiken geen keyboard shortcuts die met basis toetsen conflicteren.
- [x] [2.2.1 – Timing Adjustable](http://www.w3.org/TR/UNDERSTANDING-WCAG20/time-limits-required-behaviors.html). Niet van toepassing - geen tijdlimieten in de app.
- [x] [2.2.2 – Pause, Stop, Hide](http://www.w3.org/TR/UNDERSTANDING-WCAG20/time-limits-pause.html). Niet van toepassing - geen automatisch bewegende items.
- [x] [2.3.1 – Three Flashes or Below](http://www.w3.org/TR/UNDERSTANDING-WCAG20/seizure-does-not-violate.html). Niet van toepassing - geen flitsende items.
- [x] [2.4.1 – Bypass Blocks](http://www.w3.org/TR/UNDERSTANDING-WCAG20/navigation-mechanisms-skip.html). We bieden een 'skip to main' knop na 2 tabs.
- [x] [2.4.2 – Page Titled](http://www.w3.org/TR/UNDERSTANDING-WCAG20/navigation-mechanisms-title.html). Alle pagina's hebben titels.
- [x] [2.4.3 – Focus Order](http://www.w3.org/TR/UNDERSTANDING-WCAG20/navigation-mechanisms-focus-order.html). De focus volgorde komt overeen met een logische volgorde, gelijk aan die op het scherm.
- [x] [2.4.4 – Link Purpose (In Context)](http://www.w3.org/TR/UNDERSTANDING-WCAG20/navigation-mechanisms-refs.html). Alle applicatie links hebben logische benamingen en icoontjes hebben een alt tag.
- [x] [2.4.5 – Multiple Ways](http://www.w3.org/TR/UNDERSTANDING-WCAG20/navigation-mechanisms-mult-loc.html). Pagina's zijn vindbaar via klikken op links, via hierarchie (de breadcrumbs) en via de zoekfunctionaliteit.
- [x] [2.4.6 – Headings and Labels](http://www..w3.org/TR/UNDERSTANDING-WCAG20/navigation-mechanisms-descriptive.html). De applicatie maakt consistent gebruikt van semantisch juiste HTML5 tags, waaronder Headings in artikelen en labels in formulieren.
- [x] [2.4.7 – Focus Visible](http://www.w3.org/TR/UNDERSTANDING-WCAG20/navigation-mechanisms-focus-visible.html). De huidige focus is zichtbaar. De stijl is wel overschreven om het geheel consistent te doen ogen.
- [x] [2.5.1 – Pointer Gestures](https://www.w3.org/WAI/WCAG21/Understanding/pointer-gestures.html). In vrijwel alle onderdelen van de app zijn geen meerdere vingers nodig op touch screens, en als fallback bij kaartweergaven kan je zoomen met aparte knoppen.
- [x] [2.5.2 – Pointer Cancellation](https://www.w3.org/WAI/WCAG21/Understanding/pointer-cancellation.html). Onze buttons voeren hun actie pas uit wanneer je de knop los laat.
- [x] [2.5.3 – Label in Name](https://www.w3.org/WAI/WCAG21/Understanding/name-in-label.html). We gebruiken altijd textuele labels, of iconen met een name veld.
- [x] [2.5.4 – Motion Actuation](https://www.w3.org/WAI/WCAG21/Understanding/motion-actuation.html). We gebruiken geen motion controls.
- [x] [3.1.1 – Language of Page](http://www.w3.org/TR/UNDERSTANDING-WCAG20/meaning-doc-lang-id.html). We stellen een taal van de pagina in.
- [ ] [3.1.2 – Language of Parts](http://www.w3.org/TR/UNDERSTANDING-WCAG20/meaning-other-lang-id.html). Hier voldoen we nog niet aan. Onderdelen van teksten met een andere taal dan de hoofdtaal van de website (zoals het engelse begin van dit 3.1.2) kunnen in deze applicatie niet gemarkeerd worden als andere taal. Dit komt doordat de teksten zijn opgesteld in de [MarkDown syntax](https://www.markdownguide.org/), en dat heeft geen ondersteuning voor taal metadata. Dit probleem beperkt zich alleen tot onderdelen van een enkel stuk tekst - losse items (zoals twee losse reacties) zouden met onze technologie wel een eigen taal attribuut kunnen krijgen. Dit is iets dat we in het komende jaar willen introduceren.
- [x] [3.2.1 – On Focus](http://www.w3.org/TR/UNDERSTANDING-WCAG20/consistent-behavior-receive-focus.html). Het wijzigen van focus triggert nooit acties.
- [x] [3.2.2 – On Input](http://www.w3.org/TR/UNDERSTANDING-WCAG20/consistent-behavior-unpredictable-change.html). Formulieren maken gebruik van semantisch correcte buttons en triggeren onSubmit.
- [x] [3.2.3 – Consistent Navigation](http://www.w3.org/TR/UNDERSTANDING-WCAG20/consistent-behavior-consistent-locations.html). De navigatiebalk met het menu is altijd gelijk binnen de Applicatie.
- [x] [3.2.4 – Consistent Identification](http://www.w3.org/TR/UNDERSTANDING-WCAG20/consistent-behavior-consistent-functionality.html). De applicatie heeft zeer consistent gebruik van iconografie en tekst om functionaliteiten aan te duiden.
- [X] [3.3.1 – Error Identification](http://www.w3.org/TR/UNDERSTANDING-WCAG20/minimize-error-identified.html). Fouten in formulieren worden direct, inline genoteerd met een textuele uitleg.
- [x] [3.3.2 – Labels or Instructions](http://www.w3.org/TR/UNDERSTANDING-WCAG20/minimize-error-cues.html). Formulieren bevatten tips over invoer van componenten.
- [x] [3.3.3 – Error Suggestion](http://www.w3.org/TR/UNDERSTANDING-WCAG20/minimize-error-suggestions.html). Formulieren bevatten bij foute invoer tips over juiste invoer.
- [x] [3.3.4 - Error Prevention (Legal, Financial, Data)](http://www.w3.org/TR/UNDERSTANDING-WCAG20/minimize-error-reversible.html). Om onbedoelde acties terug te draaien, kunnen gebruikers altijd eerder geplaatste content permanent verwijderen. Daarnaast is bij het plaatsen van belangrijke content, waarbij mensen een melding ontvangen, een aparte "publiceer" actie naast een "opslaan" actie.
- [X] [4.1.1 – Parsing](http://www.w3.org/TR/UNDERSTANDING-WCAG20/ensure-compat-parses.html). De gegenereerde HTML content wordt gerelmatig geautomatiseerd gecontroleerd op validiteit.
- [X] [4.1.2 – Name, Role, Value](http://www.w3.org/TR/UNDERSTANDING-WCAG20/ensure-compat-rsv.html). We maken gebruik van bestaande HTML componenten en A11Y tested react formulier componenten.

###  WCAG 2.1 AAA

De nog strengere norm is de AAA ranking. Hier volgt een lijst:

- [x] [1.2.6 – Sign Language (Pre-recorded)](https://www.w3.org/TR/UNDERSTANDING-WCAG20/media-equiv-sign.html).  Niet van toepassing.
- [x] 1.2.7 – Extended Audio description (Pre-recorded). Niet van toepassing.
- [x] 1.2.8 – Media Alternative (Pre-recorded). Niet van toepassing.
- [x] 1.2.9 – Audio Only (Live). Niet van toepassing.
- [X] [1.3.6 – Identify Purpose](https://www.w3.org/WAI/WCAG21/Understanding/identify-input-purpose.html). We gebruiken aria tags om de functies van knoppen e.d. te verhelderen voor screenreaders.
- [ ] 1.4.6 – Contrast (Enhanced). Onze contrastwaarden zijn 4.5:1, niet 7:0. We voldoen hier niet aan. De reden hiervoor is dat hoge contrastwaarden veel aandacht vragen en onrustig overkomen. Sommige items, zoals de datum waarop een bericht geplaatst is, tonen we daarom in een lager contrast. Dit zijn echter vaak geen essentieele componenten - de items voor participatie (zoals een reactie plaatsen / inloggen) voldoen wel aan de 7:0 verhouding.
- [x] 1.4.7 – Low or No Background Audio. Niet van toepassing.
- [ ] 1.4.8 – Visual Presentation	Offer users a range of presentation options. Hebben we nog niet.
- [x] 1.4.9 – Images of Text (No Exception). We gebruiken geen afbeeldingen met tekst er in - tenzij gebruikers die zelf plaatsen.
- [ ] 2.1.3 – Keyboard (No Exception). Bijna alles is met het toetsenbord te doen, maar sommige zaken nog niet - zoals het kiezen van een locatie op de kaart.
- [x] 2.2.3 – No Timing. Er zitten geen tijdlimieten op de website.
- [x] 2.2.4 – Interruptions.	Gebruikers worden nooit onderbroken.
- [x] 2.2.5 – Re-authenticating. Ingevulde formulieren worden onthouden door de applicatie, ook na in te loggen.
- [X] [2.2.6 – Timeouts](https://www.w3.org/WAI/WCAG21/Understanding/timeouts.html). We houden data in niet-opgeslagen formulieren opgeslagen totdat de gebruiker handmatig de local storage verwijdert.
- [x] 2.3.2 – Three Flashes. De applicatie heeft geen flitsen.
- [X] [2.3.3 – Animations from Interactions](https://www.w3.org/WAI/WCAG21/Understanding/animation-from-interactions.html). We gebruiken op dit moment geen animaties.
- [x] 2.4.8 – Location. We gebruiken breadcrumbs om de locatie van een gebruiker aan te geven.
- [x] 2.4.9 – Link Purpose (Link Only). De links hebben altijd nuttige, contextuele tekst.
- [x] 2.4.10 – Section Headings. Pagina's van Argu zelf hebben altijd headings om tekst op te breken.
- [ ] [2.5.5 – Target Size](https://www.w3.org/WAI/WCAG21/Understanding/target-size.html). We gebruiken voor belangrijke knoppen (zoals inloggen / verzenden) grote knoppen die voldoen aan de standaard, maar geavanceerde functionaliteit kan kleiner dan 44px zijn. Het is verder wel goed mogelijk om de font-size in de browser te verhogen, waardoor de knoppen wel groot genoeg worden.
- [x] [2.5.5 – Concurrent Input Mechanisms](https://www.w3.org/WAI/WCAG21/Understanding/concurrent-input-mechanisms.html). Het is goed mogelijk om meerde soorten input devices door elkaar heen te gebruiken.
- [x] 3.1.3 – Unusual words. In onze eigen documentatie proberen we moeilijke woorden uit te leggen of te voorzien van een link.
- [x] 3.1.4 – Abbreviations. Afkortingen proberen we ook uit te leggen.
- [x] 3.1.5 – Reading Level. We doen actief ons best om onze eigen content zo leesbaar mogelijk te hebben - voor ieder leeniveau.
- [ ] 3.1.6 – Pronunciation. We geven geen toelichting over uitspraak van woorden.
- [X] 3.2.5 – Change on Request. Items wijzigen alleen wanneer gebruikers hier om vragen. Zo worden formulieren niet automatisch verzonden, en zijn er geen automatisch verspringende items op het scherm. In de toekomst kan dit echter wel wijzigen, want we willen het juist mogelijk maken dat wijzigingen direct in het scherm worden verwerkt. We moeten dan nog en handige manier vinden om de toegankelijkheid te waarborgen.
- [X] 3.3.5 – Help. We voegen toelichtende teksten toe bij formulieren, en bieden een helpdesk (die je nu bekijkt).
- [x] 3.3.6 – Error Prevention (All). Bij iedere fout in een formulier geven we textuele feedback op de plek waar de fout zit.
- [x] [4.1.3 – Status Messages](https://www.w3.org/WAI/WCAG21/Understanding/status-messages.html). Pop-up berichten (bijv. na inloggen / foutmelding / plaatsen) voldoen aan aria richtlijnen.

## Gebruikerscontent

Sommige WCAG richtlijnen hebben te maken met de content die er wordt geschreven.
Zo is het nodig om ingewikkelde woorden uit te leggen, en om afkortingen toe te lichten.
Aangezien gebruikers zelf op Argu content (teksten, reacties, afbeeldingen en downloads) kunnen plaatsen, kunnen we daar geen controle op doen.
Wel zorgen we er voor dat onze eigen conten (zoals deze help artikelen) zo toegankelijk mogelijk zijn.

## Feedback

Mis je nog dingen?
Weet jij manieren waarop we Argu toegankelijker kunnen maken? Laat dan een reactie achter of mail naar [info@argu.co](mailto:info@argu.co).
