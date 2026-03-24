# VendaCuraçao audit — Marketing, Sales & Customer Experience

**Datum audit:** 24 maart 2026  
**Geanalyseerd:** live site via `curl` / `web_fetch` + code in `/tmp/vendacuracao-repo`  
**Scope:** homepage, aanmeldpagina, blogindex + 3 blogartikelen, desktop en mobile breakpoints

---

## 1. Scorecard

| Discipline | Score | Korte uitleg |
|---|---:|---|
| Marketing | **7/10** | De kernpropositie is sterk en snel duidelijk: zelf verkopen op Curaçao, lage fee, direct contact. Maar trust signals, social proof en merkautoriteit ontbreken nog te veel. |
| Sales | **6/10** | Er zit een duidelijke funnel in (landing → pricing → aanmelden), maar bezwaren worden nog niet diep genoeg weggewerkt en het aanmeldproces voelt operationeel in plaats van verkoopgedreven. |
| Customer Experience | **6.5/10** | Design oogt net en rustig, maar er zijn fricties in vertrouwen, contactdetails, meertaligheid en mobiele navigatie/duidelijkheid rond vervolgstappen. |

### Totaalbeeld
VendaCuraçao heeft **een bovengemiddeld sterke basis voor een nieuw nicheplatform**. De grootste kracht is de heldere positionering: **geen traditionele makelaar, wel zichtbaarheid + begeleiding + veel lagere kosten**. De grootste zwakte is dat de site nu nog voelt als **een slim concept in lancering**, niet als een **volwassen, bewezen verkoopplatform**.

---

## 2. Belangrijkste bevindingen per discipline

## Marketing Specialist

### Wat werkt goed
1. **Value proposition is binnen 5 seconden begrijpelijk**  
   De hero communiceert direct:
   - zelf verkopen op Curaçao
   - besparing versus makelaar
   - prijs vanaf ANG 399
   - 1% bij verkoop

2. **Sterke differentiatie**  
   Het contrast met de traditionele makelaar is duidelijk. Dat is precies wat de markt nodig heeft, omdat er geen duidelijke pure FSBO-speler op Curaçao lijkt te zitten.

3. **Prijsanker werkt goed**  
   De vergelijking met 4% makelaarscommissie maakt het voordeel concreet. Op ANG 450.000 wordt het verschil tastbaar.

4. **Drietaligheid is strategisch slim**  
   NL / EN / PAP sluit goed aan op Curaçao: lokale markt, expats, Nederlanders en internationale kopers/verkopers.

5. **Blog sluit inhoudelijk goed aan op koopintentie**  
   De onderwerpen zijn logisch en transactioneel relevant:
   - woning verkopen zonder makelaar
   - wat kost een makelaar
   - FSBO vs makelaar

### Wat marketingmatig mist
1. **Bijna geen trust signals**  
   Er zijn geen testimonials, reviews, case studies, verkochte objecten, klantquotes, logos, persvermeldingen of cijfers als “X listings live” / “X aanvragen ontvangen”.

2. **Hero mist bewezenheid**  
   De propositie is sterk, maar er is weinig bewijs dat het al werkt. Voor een nieuw platform is dat cruciaal.

3. **Urgentie is zwak/inconsistent**  
   De lanceringscopy (“eerste 25 objecten gratis en permanent online”) is goed, maar voelt niet overal hard genoeg door en wordt niet overal herhaald.

4. **Merk voelt nog wat ‘conceptueel’**  
   Design is verzorgd, maar placeholder-telefoonnummer (`59995000000`) en copy-inconsistenties halen direct geloofwaardigheid weg.

5. **SEO-content is nuttig, maar nog dun als cluster**  
   De 3 blogs zijn inhoudelijk relevant, maar missen:
   - interne links naar specifieke landingspagina’s
   - calculators/tabellen/visuals
   - auteur/expertise-signalen
   - lokale data, buurten, voorbeelden en named entities

### Oordeel content marketing / SEO
De blogartikelen zijn **goed gekozen qua zoekintentie**, maar nog **meer top-of-funnel/mid-funnel dan overtuigende bottom-funnel assets**. Ze helpen ranking opbouwen, maar converteren waarschijnlijk pas echt goed zodra ze worden uitgebreid met:
- lokale praktijkvoorbeelden
- rekenvoorbeelden per prijsklasse
- FAQ-secties
- interne links naar aanmelden, prijzen, buurten en relevante objecttypes
- schema / author trust / update dates

---

## Sales Specialist

### Funnel-analyse
### Huidige customer journey
1. Homepage
2. Scroll naar hoe het werkt / voordelen / pricing / FAQ
3. Klik op CTA
4. Aanmeldpagina
5. Formulier versturen via `mailto:` of via WhatsApp

### Wat goed is
- Er is een **heldere primaire route**.
- Pricing staat op de homepage en is niet verstopt.
- CTAs zijn zichtbaar in hero, pricing en onderaan.
- FAQ vangt al een deel van de basisbezwaren op.

### Waar de funnel lekt
1. **Aanmelden via mailto is hoge frictie**  
   Als na submit iemands e-mailapp opent, voelt dat ouderwets en kwetsbaar. Op mobiel kan het soms werken, maar op desktop of bij webmail geeft het onzekerheid.

2. **Prijscommunicatie is sterk, maar deels inconsistent**  
   Ik zie op de homepage duidelijke pricing van **ANG 399 / 599 / 899 + 1%**, maar op meta descriptions / teksten op de aanmeldpagina staat nog copy als **“gratis basisplaatsing”** en **“geen commissie”**. Dat veroorzaakt direct twijfel.

3. **Objection handling is nog te dun**  
   De belangrijkste verkopersvragen op Curaçao zijn waarschijnlijk:
   - Is dit legaal en hoe werkt dat juridisch?
   - Wie doet de notaris?
   - Wie helpt met prijs bepalen?
   - Wat als ik niet op het eiland ben?
   - Hoe krijg ik serieuze kopers i.p.v. alleen kijkers?
   - Wat als ik hulp wil bij foto’s, onderhandeling of screening?
   Deze vragen worden nu maar deels beantwoord.

4. **Upsell pad is logisch, maar niet scherp genoeg verkocht**  
   Start / Plus / Full Service zijn logisch opgebouwd, maar de keuzehulp ontbreekt. Er staat te weinig:
   - welk pakket voor wie is
   - wanneer je beter Plus kiest
   - wanneer Full Service de investering waard is

5. **Er is weinig reden om vandaag te starten**  
   De launch urgency is aanwezig, maar zou veel zichtbaarder kunnen zijn in hero, pricing en sticky CTA’s.

### Pricing-analyse
### Wat sterk is
- De vergelijking met 4% makelaarstarief is salesmatig uitstekend.
- Het 1%-model is eenvoudig te begrijpen.
- Er is natuurlijke upsell naar hogere pakketten.

### Wat beter moet
- Zeg niet alleen wat het kost, maar ook **wat het oplevert**.
- Voeg per pakket een **‘beste voor’**-regel toe.
- Voeg een **vergelijkingstabel met makelaar** toe.
- Maak heel duidelijk of de startfee vooraf betaald wordt en **wanneer** de 1% exact verschuldigd is.
- Licht toe wat “social media promotie”, “waardetaxatie / prijsadvies” en “begeleiding” concreet betekenen.

### Aanmeldformulier
### Wat goed is
- Kort formulier
- Weinig verplichte velden
- WhatsApp-alternatief aanwezig

### Wat niet goed is
- `mailto:` voelt niet professioneel genoeg voor een verkoopfunnel.
- Geen progress indicator, geen bevestigingspagina, geen verwachtingsmanagement na submit.
- Geen veld voor foto-upload, buurt, gewenste verkooptermijn, eigendomstype (erfpacht/eigendomsgrond), of hulpvraag.
- Geen copy als: “Geen zorgen, je zit nergens aan vast.”

---

## Customer Experience Expert

### First impression
De eerste indruk is: **“dit is een frisse, moderne en betaalbare manier om zonder makelaar te verkopen.”** Dat is positief. Maar binnen enkele seconden denkt een kritische gebruiker ook:
- Is dit al echt live / bewezen?
- Wie zit hierachter?
- Kan ik dit vertrouwen met een object van enkele tonnen?

### Vertrouwen
Het design helpt, maar vertrouwen wordt ondermijnd door:
- placeholder telefoonnummer
- beperkte bedrijfsidentiteit
- geen team/over-ons/persoon achter het merk
- geen klantverhalen of bewijs van succes
- geen echte contactverankering op Curaçao

### Informatiearchitectuur
De homepage is overzichtelijk opgebouwd:
- hero
- how it works
- why
- pricing
- object types
- FAQ
- CTA

Dat is logisch. Wel mist nog:
- duidelijke pagina “Hoe werkt verkopen stap voor stap?”
- aparte “Waarom geen makelaar?” salespage / comparison page
- volwaardige FAQ-pagina
- vertrouwen/over-ons/contactpagina

### Contact
Er is contactmogelijkheid via e-mail en WhatsApp, maar het voelt nog **te minimaal** voor een vastgoedplatform. Voor deze categorie verwachten gebruikers sneller:
- vaste contactpersoon
- lokaal nummer
- WhatsApp CTA met echte naam/foto
- service hours / reactietijd
- eventueel intake call / vrijblijvende consult

### Taal en doelgroep-fit
Het drietalige model is slim, maar er zijn aandachtspunten:
- de live site laadt in de praktijk niet zichtbaar dynamisch anders via `?lang=` in de server-rendered HTML; taalwissel gebeurt client-side
- metadata en first-load content lijken niet per taalvariant mee te wisselen
- aanmeldpagina staat in de code standaard op `lang="pap"`, terwijl de zichtbare default content Nederlands is; dat is niet ideaal voor SEO/accessibility
- tone of voice is helder en direct, maar mag op sommige plekken nog iets menselijker en betrouwbaarder, minder puur promotioneel

---

## 3. Desktop & mobile analyse

## Breakpoints / code-observaties
Ik heb in de code o.a. deze breakpoints gezien:
- `@media (max-width: 960px)`
- `@media (max-width: 600px)`

### Positieve mobile punten
- navigatie schakelt op meerdere pagina’s naar hamburger / off-canvas patroon
- grids vallen terug naar 1 kolom
- pricing/cards en bloglayout zijn mobiel leesbaar
- sticky/positioned sidebar op desktop wordt op mobile statisch, wat goed is

### Mobile aandachtspunten
1. **Home lijkt complexer qua nav dan aanmeldpagina**  
   De homepage heeft uitgebreidere mobiele nav; de aanmeldpagina gebruikt een eenvoudiger pattern met verstopte nav-links. Dat voelt niet helemaal consistent.

2. **Hero-copy is vrij lang voor mobile**  
   Veel claimgedreven tekst boven de fold. Voor mobiel zou een strakkere hero sterker converteren.

3. **Pricing kan mobiel cognitief zwaar worden**  
   Drie kaarten met meerdere bullets zijn prima, maar baat hebben bij:
   - kortere benefit-headlines
   - “meest gekozen” visueel nóg sterker
   - vergelijkingssamenvatting erboven

4. **Form submit via mail-app op mobile kan onduidelijk zijn**  
   Sommige gebruikers denken dat het formulier kapot is als ineens een mailapp opent.

5. **WhatsApp is op mobile juist een groot voordeel**  
   Dit kanaal verdient veel prominentere behandeling, inclusief sticky WhatsApp CTA.

---

## 4. Top 5 quick wins

Dit zijn verbeteringen die relatief snel implementeerbaar zijn en direct impact hebben.

### 1. Verwijder alle copy-inconsistenties over prijs / commissie
**Probleem:** op meerdere plekken staat nog “gratis basisplaatsing” of “geen commissie”, terwijl de echte pricing ANG 399/599/899 + 1% is.  
**Waarom belangrijk:** pricing-twijfel sloopt vertrouwen.  
**Actie:** audit alle meta descriptions, OG descriptions, aanmeldcopy en CTA’s op prijsconsistentie.

### 2. Vervang placeholder contactgegevens direct
**Probleem:** `59995000000` staat zichtbaar op site en WhatsApp-links.  
**Waarom belangrijk:** dit is één van de grootste trust-killers.  
**Actie:** vervang door echt WhatsApp-nummer, echte contactnaam of teamlabel, en voeg reactietijd toe.

### 3. Voeg trust bar toe onder hero
**Voorstel inhoud:**
- Drietalig platform: NL / EN / PAP
- Direct contact met kopers
- Notarisverplichting? Wij leggen het uit
- Reactie binnen 24 uur
- Tot X gulden besparen t.o.v. makelaar

**Waarom belangrijk:** verhoogt direct scanbaarheid en vertrouwen boven de fold.

### 4. Voeg 3 extra FAQ’s toe die echte bezwaren opvangen
**Minimaal toevoegen:**
- Wat als ik niet op Curaçao woon?
- Is FSBO legaal op Curaçao?
- Wat gebeurt er nadat iemand interesse toont?

**Waarom belangrijk:** neemt onzekerheid weg die nu nog onder de oppervlakte blijft.

### 5. Maak pricing meer salesgedreven met “Beste voor” labels
**Voorbeeld:**
- Start — voor verkopers die zelf foto’s, bezichtigingen en contact willen regelen
- Plus — voor verkopers die extra zichtbaarheid willen
- Full Service — voor verkopers die begeleiding en snelheid willen

**Waarom belangrijk:** helpt keuze maken en verhoogt upsell.

---

## 5. Top 5 strategische verbeteringen

### 1. Bouw een echte trust layer
Voeg binnen 2–6 weken toe:
- testimonials
- eerste klantcases
- “verkocht via VendaCuraçao”-voorbeelden
- team/over-ons
- lokale partnervermeldingen (notarissen/fotograaf/etc. alleen als echt)

**Impact:** grootste conversiehefboom voor een nieuw merk.

### 2. Vervang `mailto:` door echte lead capture flow
Denk aan:
- webformulier met backend / form service
- confirmation state
- automatische intakebevestiging
- CRM of inboxstructuur
- optioneel foto-upload

**Impact:** veel minder frictie, hogere completion rate, professionelere ervaring.

### 3. Ontwikkel een ‘Makelaar vs VendaCuraçao’ vergelijkingspagina
Inhoud:
- kostenvergelijking per prijsklasse
- wie doet wat?
- wanneer kies je welk model?
- juridische rol notaris
- hybride ondersteuning via Full Service

**Impact:** sterke BOFU-pagina voor sales en SEO.

### 4. Maak een calculator / bespaar-tool
Bijvoorbeeld:
- “Wat bespaar jij op makelaarskosten?”
- voer verkoopprijs in
- zie 4% makelaar vs VendaCuraçao
- CTA naar aanmelden / WhatsApp

**Impact:** hoge engagement, deelbaar, sterk verkoopinstrument.

### 5. Bouw content cluster rondom lokale buurten en type verkopers
Nieuwe pagina’s/artikelen zoals:
- huis verkopen Jan Thiel zonder makelaar
- kavel verkopen Bandabou
- woning verkopen vanuit Nederland op Curaçao
- erfpacht vs eigendomsgrond bij verkoop
- checklist documenten voor verkoop Curaçao

**Impact:** SEO-groei + meer vertrouwen via lokale expertise.

---

## 6. Missende elementen — wat ontbreekt volledig?

1. **Testimonials / reviews / klantverhalen**
2. **Over-ons / team / gezicht achter het merk**
3. **Echte contactverankering** (persoon, echt nummer, lokaal vertrouwen)
4. **Calculator voor kostenbesparing**
5. **Vergelijkingstabel met makelaar**
6. **Case studies of voorbeeldverkooptrajecten**
7. **Explainer-video of korte walkthrough**
8. **Volwaardige FAQ-pagina**
9. **Serieuze lead capture flow i.p.v. mailto**
10. **Bewijs van tractie** (aantal listings, aantal leads, aantal views, eerste successen)
11. **Juridische / procespagina** over notaris, documenten, overdracht
12. **Segmentatie per verkoperstype** (op eiland / in NL / expat / investeerder / erfgenamen)

---

## 7. Concurrentievoordelen — wat doet VendaCuraçao nu al beter?

T.o.v. **RE/MAX Bonbini (traditionele makelaar)**:
1. **Veel scherper prijsverhaal** — vaste lage instap + 1% is extreem duidelijk.
2. **Direct contact met koper** — aantrekkelijk voor zelfstandige verkopers.
3. **Meer ownership voor verkoper** — minder afhankelijk van tussenpersoon.
4. **Sterke anti-makelaar positioning** — duidelijk onderscheidend.
5. **Drietalige positionering** — slim voor Curaçao-markt.

T.o.v. **Caribbean House Hunt (aggregator)**:
1. **Heldere focus op verkoper** — niet alleen een overzicht, maar een verkooppad.
2. **Sterkere propositie** — goedkoper alternatief voor agenten, niet alleen exposure.
3. **Concretere pricing** — duidelijk pakketmodel.
4. **Meer funnel-denken** — homepage stuurt naar aanmelden.
5. **Lokaler en directer merkgevoel** — Curaçao-first in plaats van generieke listingervaring.

### Strategische kern
VendaCuraçao wint niet door “nog een woningwebsite” te zijn. Het wint door dit te ownen:
> **“Het slimste alternatief voor verkopers op Curaçao die geen 4% makelaarscommissie willen betalen, maar wél professioneel zichtbaar willen zijn.”**

---

## 8. Concrete copy-suggesties

## Verbeterde hero copy — homepage

### Variant A — meest conversiegericht
**Eyebrow:**  
Zonder makelaar verkopen op Curaçao

**Headline:**  
Verkoop je woning of kavel zelf op Curaçao — en bespaar duizenden guldens

**Subheadline:**  
Plaats je object vanaf ANG 399 en betaal pas 1% bij verkoop. Geen 4% makelaarscommissie, wel direct contact met kopers en begeleiding wanneer jij dat nodig hebt.

**Primary CTA:**  
Start met verkopen →

**Secondary CTA:**  
Stel je vraag via WhatsApp

**Trust row onder CTA:**  
NL / EN / PAP · Reactie binnen 24 uur · Notaris blijft gewoon geregeld · Direct contact met kopers

### Variant B — iets premiumer
**Headline:**  
Het slimme alternatief voor de makelaar op Curaçao

**Subheadline:**  
Jij houdt de regie over prijs, bezichtigingen en kopercontact. Wij zorgen voor zichtbaarheid, presentatie en ondersteuning — vanaf ANG 399.

---

## Verbeterde CTA-teksten

### Homepage
Huidig: “Start je verkoop — ANG 399 + 1% →”  
Beter: **Plaats mijn object vanaf ANG 399 →**

Huidig: “WhatsApp ons”  
Beter: **Bespreek mijn situatie via WhatsApp**

### Pricing
**Start:**  
Kies Start en verkoop zelf →

**Plus:**  
Vergroot mijn zichtbaarheid →

**Full Service:**  
Ik wil begeleiding bij de verkoop →

### Onderaan pagina
**Plan een vrijblijvende intake →**

---

## Copy voor pakketkeuze

### Start
Voor verkopers die zelf het contact en de bezichtigingen willen regelen, maar wél professioneel online zichtbaar willen zijn.

### Plus
Voor verkopers die sneller op willen vallen en extra bereik willen creëren voor hun object.

### Full Service
Voor verkopers die hulp willen bij prijsstrategie, presentatie en begeleiding richting verkoop.

---

## FAQ-toevoegingen

### 1. Is verkopen zonder makelaar legaal op Curaçao?
Ja. Je mag je woning of kavel zelf verkopen. De juridische overdracht verloopt nog steeds via een notaris, zoals gebruikelijk op Curaçao.

### 2. Wat als ik niet op Curaçao woon?
Ook dan kun je via VendaCuraçao verkopen. We helpen je met de presentatie, communicatie en uitleg over de vervolgstappen, zodat je het proces ook vanuit Nederland of elders kunt aansturen.

### 3. Wie regelt de notaris en de juridische afhandeling?
De uiteindelijke overdracht loopt altijd via een notaris. We leggen je uit welke stappen daarbij horen en kunnen je doorverwijzen naar notarissen op Curaçao.

### 4. Wat gebeurt er nadat ik mijn object aanmeld?
Na je aanmelding nemen we contact met je op om je gegevens te controleren, de beste presentatie te bepalen en je listing zo snel mogelijk live te zetten.

### 5. Kan ik hulp krijgen als ik niet precies weet hoe ik moet verkopen?
Ja. Juist daarvoor hebben we onze Plus- en Full Service-opties. Zo bepaal je zelf hoeveel begeleiding je nodig hebt.

### 6. Wanneer betaal ik die 1% commissie?
Alleen wanneer je object daadwerkelijk verkocht wordt. De startfee betaal je voor het online plaatsen en presenteren van je object.

---

## 9. Concrete aanbevelingen per pagina

## Homepage
- Voeg trust bar direct onder hero toe
- Maak launch-offer prominenter en specifieker
- Voeg vergelijkingstabel met makelaar toe
- Voeg 1 mini-case of testimonial blok toe boven pricing
- Voeg “voor wie is dit?” segment toe (zelfstandig / extra zichtbaarheid / begeleiding)

## Aanmeldpagina
- Verwijder alle verwijzingen naar “gratis basisplaatsing” en “geen commissie” als die niet kloppen
- Vervang `mailto:` door echte submit flow
- Voeg verwachtingsblok toe: “Na je aanvraag: binnen 24 uur reactie / intake / livegang”
- Voeg geruststellende microcopy toe: “Vrijblijvend, je zit nergens aan vast”
- Voeg optie toe: “Ik woon niet op Curaçao”

## Blog
- Voeg in elk artikel 2–4 interne links toe naar relevante pagina’s
- Voeg CTA halverwege artikelen toe, niet alleen onderaan
- Voeg auteur / update datum / leestijd toe
- Voeg concrete rekentabellen toe
- Schrijf vervolgcontent op lokale zoektermen en verkoopvragen

---

## 10. Prioritering: wat zou ik als eerste doen?

### Week 1
1. Prijs- en commissiecopy overal consistent maken
2. Echt telefoonnummer/WhatsApp/contact toevoegen
3. Extra FAQ’s toevoegen
4. Pakketlabels “beste voor” toevoegen
5. Aanmeldpagina-copy verkoopgerichter maken

### Week 2–3
1. Vergelijkingstabel makelaar vs VendaCuraçao
2. Bespaar-calculator
3. Echte form flow
4. Over-ons/contact trustpagina
5. Eerste testimonials of proof blocks

### Week 4+
1. Lokale SEO-cluster uitbreiden
2. Case studies bouwen
3. Video/explainer toevoegen
4. CRO-testen op hero en CTA’s
5. Lead opvolgflow automatiseren

---

## Eindoordeel
VendaCuraçao heeft **een sterk, onderscheidend commercieel idee** en de site communiceert dat al verrassend goed voor een vroege fase. De bottleneck is niet de kernpropositie — die is sterk. De bottleneck is **vertrouwen, bewijs en funnel-afwerking**.

Als jullie nu de trust layer, pricing-consistentie en leadflow verbeteren, kan deze site vrij snel van **“interessant nieuw concept”** naar **“geloofwaardig alternatief voor de makelaar”** bewegen.

Dat is precies de zone waarin conversions echt gaan stijgen.

---

## Bewijs / observaties uit audit
- Live homepage opgehaald via `https://vendacuracao.pages.dev/`
- Live aanmeldpagina opgehaald via `https://vendacuracao.pages.dev/aanmelden`
- Live blog opgehaald via `https://vendacuracao.pages.dev/blog`
- Code gecheckt in `/tmp/vendacuracao-repo/index.html`, `/tmp/vendacuracao-repo/aanmelden.html`, `/tmp/vendacuracao-repo/blog/*.html`
- Mobile breakpoints gezien op o.a. `960px` en `600px`
- Placeholdernummer en copy-inconsistenties bevestigd in code/live content
