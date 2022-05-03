## Relevante standaarden en documentatie

*Overzicht van relevante standaarden. Nationale datastandaarden, normen, INSPIRE, internationale OGC/W3C/ISO standaarden, etc.* 

*Noem ook relevante documentatie zoals toelichtingen, richtlijnen en handreikingen die al dan niet aan de genoemde standaarden gerelateerd zijn.*

<aside class="issue">Onderstaande verzameling is een heel brede, eerste inventarisatie. Er kunnen nog standaarden in ontbreken, en voor veel van de standaarden die er wel in staan is nog niet bepaald of ze daadwerkelijk relevant zijn voor klimaatadaptatie-hitte.</aside>

<aside class="note">In deze inventarisatie is nog geen onderscheid gemaakt tussen standaarden die datasets beschrijven die bron kunnen zijn voor data die nodig zijn voor bv hittestresstests, en standaarden die concepten definiëren die we kunnen hergebruiken en/of bij aansluiten.

Dit onderscheid is lastig te maken totdat we een beter beeld hebben van scope/inhoud/doel van het informatiemodel.</aside>

### Nationaal
Lijst van standaarden, in willekeurige volgorde, met een korte duiding waarom ze relevant zouden kunnen zijn. 

Onder de tabel wordt op de standaarden die mogelijk relevant zijn, nader ingegaan. 

| Standaard | Inhoud | Relevantie |
| --------- | ------ | ---------- |
| informatiemodel Landelijk Gebied. Zie [2009 WUR rapport](https://edepot.wur.nl/154743). | Landbouw/tuinbouw/visserij is niet een van de sectoren waar wij ons op richten, in eerste instantie focussen we op natuur, gezondheid en infrastructuur. Stakeholder van het IMLG was/is LNV; het informatiemodel gaat over agrarische AAN percelen, aantallen dieren etc. Doel is agrarische subsidieregelingen te ondersteunen. Het heeft raakvlakken met natuur- en landschapsbeheer, daarom opgenomen in deze lijst. | Waarschijnlijk niet relevant |
| informatiemodel natuur [IMNa](https://www.geonovum.nl/geo-standaarden/informatiemodellen-nen3610-familie/informatiemodel-natuur-imna) | Ondersteunt landelijk uniforme uitwisseling van natuurgegevens. Van het IPO. | Waarschijnlijk relevant |
| landgebruik [BRT / Top10NL](https://www.geonovum.nl/geo-standaarden/informatiemodellen-nen3610-familie/informatiemodel-top10nl-imtop) | Landelijke topografie, basisgeoinformatie over waar terreinen, gebouwen, bovengrondse infrastructuur, water, bos, etc zich bevinden. Inclusief typering van gebouwen o.a. ziekenhuis. Heeft ook locatie beweegbare bruggen. | Vooral relevant als databron |
| [Basisregistratie Grootschalige Topografie](https://docs.geostandaarden.nl/bgt/def-im-gcbgt111-20130700) | Idem, maar gedetailleerder dan BRT met nauwkeurigere geometrie van topografische objecten, parken, groenstroken, grasvelden, verhardingssoort van wegen, en bv locatie van individuele bomen en fonteinen in steden. Maar veel van de gedetailleerdere informatie is optioneel en waarschijnlijk niet landsdekkend beschikbaar. | Vooral relevant als databron |
| Basisregistratie Gebouwen en Adressen (BAG) | Bevat gebouwen met locatie en bouwjaar. Energielabels zitten er niet in maar zijn te relateren aan BAG objecten. | Vooral relevant als databron |
| [Aquo standaarden](https://www.aquo.nl/) | Standaarden voor watermanagement. Naar verwachting is veel hergebruik van Aquo en gerelateerde vocabulaires mogelijk. Maar gevaar is wel dat definitie anders kan zijn vanuit waterbeheer dan vanuit juridische context. Dit is iets om verder over door te praten. Er is ook al een droogte vocabulaire. | Relevant |
| Gegevenswoordenboek Stedelijk Water (GWSW) | Uniform vastleggen, uitwissel en hergebruiken van gegevens in het stedelijke waterbeheer. i.e. riolering. | Mogelijk relevant als databron |
| [Omgevingswet standaarden](https://www.geonovum.nl/geo-standaarden/omgevingswet/STOPTPOD) | De Omgevingswet bundelt de wetgeving en regels voor ruimte, wonen, infrastructuur, milieu, natuur en water. De omgevingswet (DSO) standaarden zijn bedoeld om de besluiten van overheden over de leefomgeving te kunnen vastleggen. Het gaat concreet om omgevingsplannen, visies, waterschapsverordeningen etc. Er lijkt niet een direct raakvlak te zijn met hitte-adaptatie. | Waarschijnlijk niet relevant. |
| Informatiemodel Beheer Openbare Ruimte [IMBOR](https://www.crow.nl/thema-s/management-openbare-ruimte/imbor/over-imbor-1) | Veel details over objecten in de openbare ruimte, die relevant kunnen zijn voor hitte. Een voorbeeld is boomeigenschappen zoals hoogte, soort, etc. | Mogelijk relevant |
| landschapselementen agrarische gebied [IMLE](https://github.com/Geonovum/IMLE) | Informatiemodel in ontwikkeling. Modelleert informatie over landschapselementen zoals gegroepeerde bomen in verschillende vormen, individuele bomen inclusief stamhoogte en geometrie van de boomkruin, en kleine waterelementen. Veel landschapselementen hebben naast een historische en een landschappelijke ook een landschapsecologische functie: ze kunnen dan beschouwd worden als ecotopen in een ecosysteem.  | Mogelijk relevant, maar nog in ontwikkeling |
| Informatiemodel kabels en leidingen [IMKL](https://www.geonovum.nl/geo-standaarden/informatiemodellen-nen3610-familie/informatiemodel-kabels-en-leidingen-imkl)) | Voor het uitwisselen van gegevens over de positie van kabels en leidingen in de grond. | Waarschijnlijk niet relevant |
| Informatiemodel Metingen [IM Metingen](https://www.geonovum.nl/geo-standaarden/informatiemodellen-in-nen3610-familie/informatiemodel-metingen-im-metingen) | Nederlandse extensie op ISO/OGC Observations & Measurements. Voor het modelleren van observaties / metingen inclusief monstername en analyses in laboratoria. | Mogelijk relevant, maar waarschijnlijk gaat het te ver om daadwerkelijk observaties te modelleren in IMKA. |
| [standaarden van Nictiz](https://www.nictiz.nl/standaardisatie/informatiestandaarden/) | Nictiz maakt informatiestandaarden in het zorgdomein. Relevantie (zijn er raakvlakken met klimaatadaptatie/hitte?) moet nog bekeken worden. Waarschijnlijk hebben ze wel relevante begrippen rondom gezondheid. Denk bv aan sterfte, doodsoorzaken, etc. | Waarschijnlijk relevant |
| BRO standaarden (deze worden genoemd in de [Handreiking 'Hoe gebruik ik bodeminformatie bij klimaatadaptatie?](https://climadapserv.maps.arcgis.com/apps/MapSeries/index.html?appid=68303bbfd5904b62a55c8ef3c688da27)) | Geomorfologische kaart; Bodemkaart; Booronderzoek; GeoTOP; Digitaal Geologisch Model | Vooral relevant als databron |
| Informatiemodel Geluid [IMGeluid](https://docs.geostandaarden.nl/cvgg/img/) | Voor geluidsoverlastmodellen | Waarschijnlijk niet relevant. |
| Informatiemodel KICH | Gaat over cultuurhistorie. "Hittestress ontstaat juist doordat steen, beton en asfalt warmte vasthouden. Aan de hand van historische informatie kan ook de verstening en verharding van een stad in beeld worden gebracht. Historische kaarten kunnen eenvoudig gecombineerd worden met de kaartlagen uit de Klimaateffectatlas" [bron](https://klimaatadaptatienederland.nl/publish/pages/156580/cultuurhistorie_als_kennisbron_voor_de.pdf)| Waarschijnlijk niet relevant. IMKICH is niet in gebruik en cultuurhistorische informatie is vooral relevant bij waterhuishouding, bij hitte minder. | 

<aside class="issue">Er moet nog gezocht worden naar standaarden voor andere klimaattrends (wateroverlast, ...). </aside>

Standaarden die waarschijnlijk relevant zijn worden hieronder nader toegelicht. 

#### Informatiemodel Natuurbeheer (IMNa)
Dit informatiemodel heeft als doel om een aantal processen in de natuurketen te ondersteunen, te weten subsidieverlening, monitoring en verantwoording over natuurbeheer en natuurkwaliteit. Het IMNa bestaat uit vier productmodellen die apart beheerd worden: 
- Productmodel **Natuurbeheer**: model voor het uitwisselen van natuurbeheerplannen van provincies. Geeft inzicht in het soort natuur dat aanwezig of geambieerd is op een bepaalde plaats. 
- Productmodel **Natuurontwikkeling**: model voor het uitwisselen van kwantitatieve voortgangsgegevens. Wordt gebruikt voor de jaarlijkse [Voortgangsrapportage natuur](https://www.bij12.nl/vrn). Bevat ook de begrenzing van het Natuurnetwerk Nederland. 
- Productmodel **Natuurkwaliteit**: model voor het uitwisselen van kwaliteitsgegevens over natuur. De kwaliteit van natuur wordt gemonitord en beoordeeld en deze data wordt conform dit model uitgewisseld. 
- Productmodel **Vegetatie en habitats**: model om gegevens over vegetatie-, habitat- en structuurgegevens vast te leggen en uit te wisselen. Deze gegevens, gebaseerd op periodieke waarnemingen in het veld, zijn input voor de monitoring. 

Bron: [bij12](https://www.bij12.nl/onderwerpen/natuur-en-landschap/natuurgegevens-uniform-uitwisselen-imna/informatiemodel-natuur-imna/). Voor catalogus en codelijsten van het informatiemodel zie de Actuele downloads onderaan de pagina van Bij12. 

#### Aquo
Aquo is de Nederlandse standaard voor het uitwisselen van gegevens binnen de watersector voor kwaliteitsverbetering van het waterbeheer. Aquo wordt beheerd door het Informatiehuis Water; een samenwerkingsprogramma van de provincies, waterschappen en Rijkswaterstaat. De set Aquo standaarden bestaat uit een begrippenkader, een symbolenset voor visualisatie, een verzameling domeintabellen, en het semantisch informatiemodel Aquo. 

Om een idee te krijgen van de reikwijdte van Aquo kunnen we kijken naar de [categorieën in het begrippenkader](https://www.aquo.nl/index.php/Categorie:Collecties). Hoewel onze focus 'hitte' is (waarbij 'droogte' is uitgesloten) en die van Aquo 'water' zijn er bij een snelle blik al wel raakvlakken te vinden. Onder de categorie [Calamiteitenzorg](https://www.aquo.nl/index.php/Id-ace3d4c1-0fb6-41f0-8941-be20911f5019) vallen bijvoorbeeld algemene begrippen zoals *bevoegd gezag*, *bevolking*, *calamiteit*, *effect*, of *maatschappelijke schade*. De categorie [Ecologie](https://www.aquo.nl/index.php/Id-4aebd96e-5744-4e08-9182-413e43f6b416) is ook interessant met bv termen als *bijzondere natuur*, *beschermde gebieden*, *biodiversiteit* en allerlei termen die soorten flora/fauna beschrijven. 

Bron: [aquo.nl](https://www.aquo.nl/index.php/Wat_is_Aquo%3F)

#### IMBOR
Het informatiemodel Beheer Openbare Ruimte is een door CROW ontwikkelde en beheerde uitbreiding op het IMGeo waarbij allerlei beheerkenmerken aan objecten in de openbare ruimte, waarvan de geometrie in IMGeo zit, worden toegevoegd. Gemeenten gebruiken dit voor de planning en uitvoering van hun beheer en inspectiewerkzaamheden. Het deel van IMBOR over Groen is met name interessant; hier kun je bijvoorbeeld informatie over individuele bomen vinden zoals diameter, soort, hoogte, en over de beplanting in plantsoenen etc. Maar ook Meubilair, Water en Wegen zou relevant kunnen zijn. 

<figure>
    <figcaption>IMBOR inhoud - overzicht</figcaption>
    <img src="https://www.crow.nl/getmedia/b555e3a6-02b6-412c-aad2-7ba890a5ee69/Figuur-Openingspagina-van-de-IMBOR-Access-Database.jpg.aspx" alt="Overzicht IMBOR inhoud, vakdisciplines en relaties"/>
</figure>

#### IMMetingen
Nederlandse standaard voor het uitwisselen van observaties / metingen, zowel in het veld als metingen op monsters door laboratoriumanalyse. Het Aquo is hier op gebaseerd. IMMetingen is op zijn beurt gebaseerd op het internationale OGC Observations & Measurements (O&M). 

O&M / IMMetingen is bedoeld voor het uitwisselen van allerlei (meta)informatie *over* metingen zoals door wie, wanneer, waar en hoe de meting is gedaan, informatie over de monstername etc. Alleen als al deze metainformatie van belang is om uit te wisselen, dienen deze standaarden te worden toegepast.

#### NICTIZ
NICTIZ is een organisatie die standaarden voor de zorg maakt. Het is een zeer omvangrijke set standaarden, wat het moeilijk maakt om tijdens een korte inventarisatie de relevantie te duiden. Er lijken echter wel raakvlakken te zijn, in het bijzonder de [Basisgegevensset Zorg](https://www.nictiz.nl/standaardisatie/informatiestandaarden/basisgegevensset-zorg-bgz/) waar allerlei aandoeningen die bij patiënten worden aangetroffen (bv *aandoening gerelateerd aan omgeving*, [*blootstelling aan hitte*](https://terminologie.nictiz.nl/art-decor/snomed-ct?conceptId=404684003), *zonnesteek*, veroorzaakt door *warmte*) en bevindingen die over patiënten worden gedaan, gedefinieerd worden.

### INSPIRE
De relevantie van de diverse thema's moet nog bekeken worden. Voor een eerste snelle inventarisatie is gekeken naar de [INSPIRE aanmerkingsrapporten](https://www.geonovum.nl/geo-standaarden/inspire-europese-leefomgeving#Dataproviders) die Geonovum heeft gemaakt, omdat die een compact overzicht bieden.

De volgende thema's zijn mogelijk interessant: 

| Standaard | Inhoud | Relevantie |
| --------- | ------ | ---------- |
| Protected sites | gebieden die worden aangeduid of beheerd in het kader van internationale en communautaire wetgeving of wetgeving van de lidstaten om specifieke  doelstellingen op het vlak van milieubescherming te verwezenlijken. Hieronder vallen oa Natura 2000 gebieden, nationale parken, wetlands. | Mogelijk relevant |
| Land cover | Fysiek voorkomen van het terrein, i.e. een niet-geïnterpreteerde vastlegging van de feitelijke bedekking van het grondgebied. Het gaat niet om het menselijk gebruik (dat is land use, een ander INSPIRE thema). De dataspecificaties zijn vrij algemeen gesteld. | Mogelijk wel relevant, maar land use wellicht relevanter. |
| Agricultural and aquaculture facilities | informatie die gaat over landbouw, jacht en dienstverlening voor de landbouw en jacht; en visserij en kweken van vis en schaaldieren.| Mogelijk relevant |
| Atmospheric conditions | Waarnemingen in de atmosfeer | Waarschijnlijk niet relevant |
| Buildings | Gebouwen met typering naar soort gebouw en huidig gebruik. | Mogelijk relevant |
| Environmental monitoring Facilities | betreft meet- en waarnemingsvoorzieningen, bv weerstations, grondwatermonitoringsputten. Het gaat niet om metingen of waarnemingen zelf. | Waarschijnlijk niet relevant |
| Human health and safety |  drie subthema’s: Statistische gezondheidsdata, Gezondheid gerelateerde milieudata en Calamiteiten. | Mogelijk relevant, vooral het eerste subthema. |
| Area management/restriction/regulation zones | gebieden die worden beheerd, gereguleerd of gebruikt voor rapportage op verschillende schaalniveaus (o.a. landelijk, lokaal, regionaal). Heel breed thema dat is afgebakend op gegevens gerelateerd aan milieubeheer. Mogelijk relevant in dit thema zijn bv plant health zones, animal health zones, forest management zones. | Mogelijk relevant |
| Meteorological geographical features | Weersomstandigheden en de metingen daarvan | Mogelijk relevant |
| Natural risk zones | Risicogebieden; onder andere gebieden met risico op natuurbranden, plagen, dierziekten, allergenen.  | Mogelijk relevant |
| Population distribution and demography | | |
| Species distribution | geografische verspreiding van dier- en plantsoorten | Mogelijk relevant |
| Bio-geographical regions | beschrijving van gebieden (habitats) op basis van ecologische omstandigheden. | Mogelijk relevant |
| Habitats and biotopes | ook een beschrijving van gebieden op basis van ecologische omstandigheden, maar dan veel specifieker uitgewerkt met ruimte voor gegevens over specifieke soorten. | Mogelijk relevant |
| Land use | menselijk gebruik van het grondgebied, i.e. de functie waarvoor een terrein benut wordt. Opgesplitst in huidig en toekomstig landgebruik (dit laatste is ingevuld met ruimtelijke plannen). | Mogelijk relevant |
| Soil | Gegevens over de ondiepe bodem. De samenstelling daarvan, grondwater, etc. | Mogelijk relevant |
| Geology | Gegevens over de diepe ondergrond | Waarschijnlijk niet relevant |

Ook mogelijk relevant - als O&M relevant is: 
- [Guidelines for the use of Observations & Measurements and Sensor Web Enablement-related standards in INSPIRE](https://inspire.ec.europa.eu/id/document/tg/d2.9-o%26m-swe)

### Overig internationaal

| Standaard | Inhoud | Relevantie |
| --------- | ------ | ---------- |
| ISO 19156 Observations & Measurements (O&M 2.0) | Conceptueel model voor het beschrijven van metingen. | Waarschijnlijk gaat dit te ver maar zou toegepast kunnen worden voor sterftecijfers e.d. |
| OGC Observations, Measurements & Samples 3.0 (O&M 3.0) | Conceptueel model voor het beschrijven van metingen; nieuwe 3.0 versie die bij ISO nog niet is goedgekeurd maar bij OGC wel. | Idem als O&M 2.0 | 
| OGC CityGML 3.0 (het datamodel) | Conceptueel model voor het beschrijven van 3D modellen van stad en landelijk gebied. | Mogelijk relevant of alleen als databron |
| OGC Simple Features | Basis geometrietypen | Relevant voor het modelleren van geo-objecten |
| OGC WaterML | Hydrologie e.d. | Nader te onderzoeken als er een raakvlak hitte/water is.| 
| IFC | Bestandsformaat voor bouwwerkinformatiemodellen. | Wellicht relevant in het kader van infrastructuur. |
| OGC LandInfra | Informatiemodel voor bouwwerkinformatiemodellen (gebouwen / infra) | Wellicht relevant in het kader van infrastructuur |

### Technische standaarden
Standaarden over informatiemodellering e.d.

- **MIM**: Metamodel informatiemodellering. Relevant, IMKA zal conform MIM ontwikkeld worden.
- **NEN 3610**: basismodel geo-informatie. Relevant, IMKA zal conform NEN 3610 ontwikkeld worden.
- **SKOS**:	Linked data standaard voor begrippen en definities. Relevant; het IMKA begrippenkader zal conform SKOS ontwikkeld worden. 

### Andere relevante handreikingen e.d.

- [Geometrie in model en GML](https://docs.geostandaarden.nl/nen3610/gimeg/)
- [Handreiking Gebruik coördinaatreferentiesystemen bij uitwisseling en visualisatie van geo-informatie](https://docs.geostandaarden.nl/crs/crs/)