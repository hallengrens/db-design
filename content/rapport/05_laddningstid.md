---
---
Laddningstid
=========================

Denna rapport avser en kortare analys av "page speed"-mätresultat från tre separata webbplatser.

Urval
-----------------------

Jag har valt att titta på tre webbplatser som drivs av två av mina nuvarande kunder. Jag har varit involverad i skapandet av 2 av dessa tre webbplatser – dock med väldigt olika möjligheter att påverka slutresultatet.

Metod
-----------------------

Mötningarna av webbsidornas hastighet(?) har uppmätts via [Google PageSpeed Insight](https://developers.google.com/speed/pagespeed/insights/) och dels med utvecklarverktyget i Firefox.

Resultat
-----------------------

Samtliga emperi finns att tillgå [på denna länk](https://docs.google.com/spreadsheets/d/1mAa_zPaXjNBURK7-e0vXDHDDg88muzsnV2EsuiSfLe8/edit?usp=sharing).

### Talanda / J&J ###

[FIGURE src=image/talanda.png?width=100% caption="Startsidan på Talanda.se."]

### Utvalda sidor för mätning ###
* [Rooten](https://talanda.se/)
* [/talanda](https://talanda.se/talanda/)
* [/recept](https://talanda.se/recept/)

##### Mätresultat #####

<table style="border-spacing: 4px; border-collapse: separate; width: 100%;">
    <tr>
        <td colspan="4" style="height: 30px; background-color: #000; color:#fff;">Talanda.se</td>
    </tr>
    <tr>
        <td style="height: 50px; background-color: #ddd">Undersida</td>
        <td style="height: 50px; background-color: #ddd">/(rooten)</td>
        <td style="height: 50px; background-color: #ddd">/talanda</td>
        <td style="height: 50px; background-color: #ddd">/recept</td>
    </tr>
    <tr>
        <td style="height: 50px; background-color: #ddd">Laddningstid (sek)</td>
        <td style="height: 50px; background-color: #ff7d63">20.70</td>
        <td style="height: 50px; background-color: #ff7d63">21.55</td>
        <td style="height: 50px; background-color: #ff7d63">20.03</td>
    </tr>
    <tr>
        <td style="height: 50px; background-color: #ddd">Antal resurser</td>
        <td style="height: 50px; background-color: #ddd">174</td>
        <td style="height: 50px; background-color: #ddd">189</td>
        <td style="height: 50px; background-color: #ddd">155</td>
    </tr>
    <tr>
        <td style="height: 50px; background-color: #ddd">Storlek (MB ned)</td>
        <td style="height: 50px; background-color: #ddd">42.86 MB</td>
        <td style="height: 50px; background-color: #ddd">46.57 MB</td>
        <td style="height: 50px; background-color: #ddd">37.68 MB</td>
    </tr>
    <tr>
        <td style="height: 50px; background-color: #ddd">PSI Mobile Score</td>
        <td style="height: 50px; background-color: #ff7d63">17</td>
        <td style="height: 50px; background-color: #ff7d63">17</td>
        <td style="height: 50px; background-color: #ff7d63">22</td>
    </tr>
    <tr>
        <td style="height: 50px; background-color: #ddd">PSI Desktop Score</td>
        <td style="height: 50px; background-color: #ff7d63">41</td>
        <td style="height: 50px; background-color: #ff7d63">39</td>
        <td style="height: 50px; background-color: #ff7d63">44</td>
    </tr>
</table>

##### Förbättringsmöjligheter #####

Värt att notra är att koden som jag levererade till kund, då jag skrev HTML och CSS för sidan, hade en laddningstid på ~1 sek och fick 96/100 på Google PSI. Så man kan rimligen säga att implementationen av koden som jag levererade inte riktigt har gjorts som den skulle.

* Bättre cachning av statiska resurser
* Bättre optimerade bilder
* Responsiva bilder
* Reducera externa resurser
* Minifiera/Optimera CSS
* Reducera/Optimera WP-plugins
* Reducera antal DOM-element


### Candypeople ###

[FIGURE src=image/candypeople.png?width=100% caption="Startsidan på Candypeople.se."]

### Utvalda sidor för mätning ###
* [Rooten](https://candypeople.se/)
* [/produkter](https://candypeople.se/produkter/)
* [/om-oss](https://candypeople.se/om-oss/)

##### Mätresultat #####

<table style="border-spacing: 4px; border-collapse: separate; width: 100%;">
    <tr>
        <td colspan="4" style="height: 30px; background-color: #000; color:#fff;">Talanda.se</td>
    </tr>
    <tr>
        <td style="height: 50px; background-color: #ddd">Undersida</td>
        <td style="height: 50px; background-color: #ddd">/(rooten)</td>
        <td style="height: 50px; background-color: #ddd">/produkter</td>
        <td style="height: 50px; background-color: #ddd">/om-oss</td>
    </tr>
    <tr>
        <td style="height: 50px; background-color: #ddd">Laddningstid (sek)</td>
        <td style="height: 50px; background-color: #ffd166">4.98</td>
        <td style="height: 50px; background-color: #ff7d63">6.20</td>
        <td style="height: 50px; background-color: #9eff66">1.63</td>
    </tr>
    <tr>
        <td style="height: 50px; background-color: #ddd">Antal resurser</td>
        <td style="height: 50px; background-color: #ddd">119</td>
        <td style="height: 50px; background-color: #ddd">243</td>
        <td style="height: 50px; background-color: #ddd">76</td>
    </tr>
    <tr>
        <td style="height: 50px; background-color: #ddd">Storlek (MB ned)</td>
        <td style="height: 50px; background-color: #ddd">5.47 MB</td>
        <td style="height: 50px; background-color: #ddd">8.10 MB</td>
        <td style="height: 50px; background-color: #ddd">0.97 MB</td>
    </tr>
    <tr>
        <td style="height: 50px; background-color: #ddd">PSI Mobile Score</td>
        <td style="height: 50px; background-color: #ff7d63">7</td>
        <td style="height: 50px; background-color: #ff7d63">10</td>
        <td style="height: 50px; background-color: #ff7d63">20</td>
    </tr>
    <tr>
        <td style="height: 50px; background-color: #ddd">PSI Desktop Score</td>
        <td style="height: 50px; background-color: #ff7d63">38</td>
        <td style="height: 50px; background-color: #ff7d63">47</td>
        <td style="height: 50px; background-color: #ffd166">56</td>
    </tr>
</table>

##### Förbättringsmöjligheter #####

Detta är en sida som kund har tagit fram själva inhouse. Sidan haltar inte bara när det kommer till det kommunikativa; utan den haltar även rent tekniskt. Det är samma person som har byggt denna sidan och Talanda.se – därav så ser jag även samma problem som skulle behöva lösas:

* Bättre cachning av statiska resurser
* Bättre optimerade bilder (format, storlek m.m.)
* Responsiva bilder
* Reducera externa resurser
* Minifiera/Optimera CSS


### Kverneriet ###

[FIGURE src=image/kverneriet.png?width=100% caption="Restaurangsida på Kverneriet.com."]

### Utvalda sidor för mätning ###
* [Rooten](https://kverneriet.com/)
* [/tonsberg.html](https://kverneriet.com/tonsberg.html)
* [/ws-tonsberg.html](https://kverneriet.com/ws-tonsberg.html)

##### Mätresultat #####

<table style="border-spacing: 4px; border-collapse: separate; width: 100%;">
    <tr>
        <td colspan="4" style="height: 30px; background-color: #000; color:#fff;">Talanda.se</td>
    </tr>
    <tr>
        <td style="height: 50px; background-color: #ddd">Undersida</td>
        <td style="height: 50px; background-color: #ddd">/(rooten)</td>
        <td style="height: 50px; background-color: #ddd">/tonsberg.html</td>
        <td style="height: 50px; background-color: #ddd">/ws-tonsberg.html</td>
    </tr>
    <tr>
        <td style="height: 50px; background-color: #ddd">Laddningstid (sek)</td>
        <td style="height: 50px; background-color: #9eff66">0.49</td>
        <td style="height: 50px; background-color: #9eff66">0.54</td>
        <td style="height: 50px; background-color: #9eff66">0.80</td>
    </tr>
    <tr>
        <td style="height: 50px; background-color: #ddd">Antal resurser</td>
        <td style="height: 50px; background-color: #ddd">8</td>
        <td style="height: 50px; background-color: #ddd">11</td>
        <td style="height: 50px; background-color: #ddd">46</td>
    </tr>
    <tr>
        <td style="height: 50px; background-color: #ddd">Storlek (MB ned)</td>
        <td style="height: 50px; background-color: #ddd">0.06 MB</td>
        <td style="height: 50px; background-color: #ddd">0.26 MB</td>
        <td style="height: 50px; background-color: #ddd">1.94 MB</td>
    </tr>
    <tr>
        <td style="height: 50px; background-color: #ddd">PSI Mobile Score</td>
        <td style="height: 50px; background-color: #9eff66">98</td>
        <td style="height: 50px; background-color: #9eff66">93</td>
        <td style="height: 50px; background-color: #ff7d63">38</td>
    </tr>
    <tr>
        <td style="height: 50px; background-color: #ddd">PSI Desktop Score</td>
        <td style="height: 50px; background-color: #9eff66">100</td>
        <td style="height: 50px; background-color: #9eff66">98</td>
        <td style="height: 50px; background-color: #ffd166">73</td>
    </tr>
</table>

##### Förbättringsmöjligheter #####

Denna sida är hårdkodad och skapades av mig för ca 4 år sedan och syftat var egentligen att den endast skulle fungera som temporär sida för restaurangen tills dess att de fick upp sin nya WP-sida. Dock så hade kunden problem att få fram allt innehåll som WP-sidan behövde så den blev aldrig lanserad. Nu står vi dock inför en vidareutveckling av sidan med bl.a. administration.

* Bättre cachning av statiska resurser



Analys
-----------------------

Givet att jag har varit involverad i utvecklandet av två av dessa tre sajter så sitter jag således även på lite "inside information".

Det som först slår mig är diskrepansen mellan den levenas jag gjorde för Talanda.se kontra vad det var som kom ut på andra sidan av denne. Den HTML/CSS/JS som jag hade tagit fram för gränssnittet gick från en laddningtid på ca 1 sek till 20 sek; och vidare från ett PSI score på 96/100 till ca 20/40.

Detta säger mig att hur bra det än må vara med att implementera ett CMS för att kunna hantera innehåller på en sajt så måste det fortfarande göras på rätt sätt och med rätt kunskap. Att göra en snabbt WP-implementation betyder inte per definition att man får en "bra" eller "bättre" webbplats utåt.

Hypotesen styrks när man kollar vidare på [Candypeople.se](https://candypeople.se/) som är till 100% utvecklad av samma individ som även ansvarade för att förvalta den "font-ent" som jag tagit fram för [Talanda.se](https://talanda.se/). Och vi ser likvärdiga problem även med den sidan. Med de sagt så vet jag att detta är en individ som premieras för att göra saker snabbt snarare än "rätt" – så det går inte klandra honom. Däremot så blir det därför viktigt att informera kunden som är tekniskt novis på vad detta kan ha för inverkan.

Vidare så kan vi kolla på [Kverneriet.com](https://kverneriet.com/) som jag i ett första skede tog fram som en statisk temporär sajt i väntan på en ny WP-sajt. Även om den inte har varit så omsorgsfullt konstruerad från början så är den fortfarande väldigt snabb och får även väldigt fina PSI scores. Undantaget är den undersida som avser "Take-Away" och som implementerades på ett vis som jag inte föredrog; den är nämligen inlagd som en iframe med innehåll från en extern sida – vilket dessvärre är den enda tekniska lösning som tjänsteleverantörer erbjuder.


Rangordning
-----------------------

Baserat på vilken sida som presterar bäst när det kommer till laddningstid så är rangordningen rätt självklar i detta fall:

1. [Kverneriet.com](https://kverneriet.com/)
2. [Candypeople.se](https://candypeople.se/)
3. [Talanda.se](https://talanda.se/)


Gränsvärde
-----------------------

Baserat på en rad artiklar och undersökningar bl.a. [denna från Google](https://www.thinkwithgoogle.com/marketing-resources/data-measurement/mobile-page-speed-new-industry-benchmarks/) så har jag valt att rangordna laddningstiderna efter följande intervall:

1. 0-3 sek : Bra laddningstid som minimerar bouncerate.
2. 3-10 sek : OK med bör förbättras.
3. över 10 sek : På tok för lång laddningstid omgående insats krävs.

Detta innebär således att det bara är en av dessa sajter som fatkiskt levererar bra laddningstider på samtliga sidor (Kverneriet); Candypeople.se leverar OK men kan bli bättre – och Talanda.se är undermålig när det kommer till läddningstider.


Referenser
-----------------------

* [Google PageSpeed Insight](https://developers.google.com/speed/pagespeed/insights/)
* [Think with Google](https://www.thinkwithgoogle.com/marketing-resources/data-measurement/mobile-page-speed-new-industry-benchmarks/)


Övrigt
-----------------------

Skriven Henrik Hallengren, som avlägger denna rapport självständigt