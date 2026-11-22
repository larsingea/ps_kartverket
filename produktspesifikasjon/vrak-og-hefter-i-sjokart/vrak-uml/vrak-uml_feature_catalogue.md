#### Vrakgrense

avgrensning av rest av fartøy som har strandet eller sunket og er etterlatt i ubrukbar tilstand<br />Delimitation of remains of vessel which has run aground or sunk and has been abandoned in useless condition

Egenskaper

<table class="feature-attribute-table">
  <thead>
    <tr>
      <th>Egenskap</th>
      <th>Beskrivelse</th>
      <th>Type</th>
      <th>Multiplisitet</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>grense</td>
      <td>forløp som følger overgang mellom ulike fenomener<br /><br />-- Definition --<br />course follwing the transition between different real world phenomena</td>
      <td>GM_<wbr />Curve</td>
      <td>1</td>
    </tr>
  </tbody>
</table>

#### Vrak

de ødelagte restene av et strandet eller senket fartøy som har blitt gjort ubrukelig.<br />The ruined remains of a stranded or sunken vessel which has been rendered useless.

Egenskaper

<table class="feature-attribute-table">
  <thead>
    <tr>
      <th>Egenskap</th>
      <th>Beskrivelse</th>
      <th>Type</th>
      <th>Multiplisitet</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>område</td>
      <td>objektets utstrekning<br /><br />-- Definition --<br />area over which an object extends</td>
      <td>GM_<wbr />Surface</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>posisjon</td>
      <td>sted som objektet eksisterer på<br /><br />-- Definition --<br />location where the object exists</td>
      <td>GM_<wbr />Point</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>vraktype</td>
      <td>kategori vrak.<br />The category of the wreck.  Note:  S-57 CATWRK</td>
      <td><a href="#kodeliste-vraktype">Vraktype</a><br />(kodeliste)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>dybde</td>
      <td>loddrett avstand fra et gitt referansenivå ned til bunnen eller annet objekt.<br />Vertical distance from a given reference level down to the bottom or another object.</td>
      <td>Real</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>vertikal<wbr />Datum</td>
      <td>vertikal referanse brukes til å spesifisere referansenivået for både høyder og dybder .<br />Vertical datum is used to specify the datum to which both heights (vertical datum) and soundings (sounding datum) are referred.</td>
      <td><a href="#kodeliste-vertikaldatum">Vertikal<wbr />Datum</a><br />(kodeliste)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>objektnavn<wbr />Engelsk</td>
      <td>vrakets navn på engelsk<br />The name of the wreck in English</td>
      <td>Character<wbr />String</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>objektnavn<wbr />Norsk</td>
      <td>vrakets navn på norsk<br />The name of the wreck in Norwegian</td>
      <td>Character<wbr />String</td>
      <td>0..1</td>
    </tr>
    <tr class="inherited-from">
      <th colspan="4" scope="rowgroup">Arvet fra Fellesegenskaper</th>
    </tr>
    <tr>
      <td>identifikasjon</td>
      <td>unik identifikasjon av et objekt</td>
      <td>Identifikasjon<br />(datatype)</td>
      <td>1</td>
    </tr>
    <tr>
      <td>- lokal<wbr />Id</td>
      <td>lokal identifikator, tildelt av dataleverendør/dataforvalter. Den lokale identifikatoren er unik innenfor navnerommet, ingen andre objekter har samme identifikator.<br /><br />NOTE: Det er data leverendørens ansvar å sørge for at denne lokale identifikatoren er unik innenfor navnerommet.</td>
      <td>Character<wbr />String</td>
      <td>1</td>
    </tr>
    <tr>
      <td>- navnerom</td>
      <td>navnerom som unikt identifiserer datakilden til objektet, starter med to bokstavs kode jfr ISO 3166. Benytter understreking  ("_") dersom data produsenten ikke er assosiert med bare et land.<br /><br />NOTE 1 : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og vil registreres i "INSPIRE external  Object Identifier Namespaces Register"<br /><br />Eksempel: NO for Norge.</td>
      <td>Character<wbr />String</td>
      <td>1</td>
    </tr>
    <tr>
      <td>første<wbr />Datafangstdato</td>
      <td>dato når data ble registrert/observert/målt første gang, som utgangspunkt for første digitalisering<br /><br />Merknad:<br />førsteDatafangstdato brukes hvis det er av interesse å forvalte informasjon om når en ble klar over objektet. Dette kan for eksempel gjelde datoen for første flybilde som var utgangspunkt for registrering i en database.</td>
      <td>Date<wbr />Time</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>oppdateringsdato</td>
      <td>dato for siste endring på objektetdataene<br /><br />Merknad:<br />Oppdateringsdato kan være forskjellig fra Datafangsdato ved at data som er registrert kan bufres en kortere eller lengre periode før disse legges inn i datasystemet (databasen).<br /><br />-Definition-<br />Date and time at which this version of the spatial object was inserted or changed in the spatial data set.</td>
      <td>Date<wbr />Time</td>
      <td>1</td>
    </tr>
    <tr>
      <td>datauttaksdato</td>
      <td>dato for uttak fra en database<br /><br />Merknad:<br />Skiller seg fra Kopidato ved at en ikke skiller på om det er uttak fra en originaldatabase eller en kopidatabase.</td>
      <td>Date<wbr />Time</td>
      <td>1</td>
    </tr>
    <tr>
      <td>kvalitet</td>
      <td>beskrivelse av kvaliteten på stedfestingen<br /><br />Merknad: Denne er identisk med ..KVALITET i tidligere versjoner av SOSI.</td>
      <td>Posisjonskvalitet<br />(datatype)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- målemetode</td>
      <td>metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
      <td><a href="#kodeliste-målemetode">Målemetode</a><br />(kodeliste)</td>
      <td>1</td>
    </tr>
    <tr>
      <td>- nøyaktighet</td>
      <td>punktstandardavviket i grunnriss for punkter samt tverravvik for linjer<br /><br />Merknad:<br />Oppgitt i cm</td>
      <td>Integer</td>
      <td>0..1</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
Fellesegenskaper

**Assosiasjoner**
Vrakgrense – rolle: avgrensesAvVrakgrense – kardinalitet: 0..*

#### Fellesegenskaper (abstrakt)

abstrakt objekt som bærer en rekke egenskaper som er fagområde-uavhengige og kan benyttes for alle objekttyper<br />Merknad:<br />Spesielt i produktspesifikasjonsarbeid vil en velge egenskaper og av grensningslinjer fra denne klassen.

Egenskaper

<table class="feature-attribute-table">
  <thead>
    <tr>
      <th>Egenskap</th>
      <th>Beskrivelse</th>
      <th>Type</th>
      <th>Multiplisitet</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>identifikasjon</td>
      <td>unik identifikasjon av et objekt</td>
      <td>Identifikasjon<br />(datatype)</td>
      <td>1</td>
    </tr>
    <tr>
      <td>- lokal<wbr />Id</td>
      <td>lokal identifikator, tildelt av dataleverendør/dataforvalter. Den lokale identifikatoren er unik innenfor navnerommet, ingen andre objekter har samme identifikator.<br /><br />NOTE: Det er data leverendørens ansvar å sørge for at denne lokale identifikatoren er unik innenfor navnerommet.</td>
      <td>Character<wbr />String</td>
      <td>1</td>
    </tr>
    <tr>
      <td>- navnerom</td>
      <td>navnerom som unikt identifiserer datakilden til objektet, starter med to bokstavs kode jfr ISO 3166. Benytter understreking  ("_") dersom data produsenten ikke er assosiert med bare et land.<br /><br />NOTE 1 : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og vil registreres i "INSPIRE external  Object Identifier Namespaces Register"<br /><br />Eksempel: NO for Norge.</td>
      <td>Character<wbr />String</td>
      <td>1</td>
    </tr>
    <tr>
      <td>første<wbr />Datafangstdato</td>
      <td>dato når data ble registrert/observert/målt første gang, som utgangspunkt for første digitalisering<br /><br />Merknad:<br />førsteDatafangstdato brukes hvis det er av interesse å forvalte informasjon om når en ble klar over objektet. Dette kan for eksempel gjelde datoen for første flybilde som var utgangspunkt for registrering i en database.</td>
      <td>Date<wbr />Time</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>oppdateringsdato</td>
      <td>dato for siste endring på objektetdataene<br /><br />Merknad:<br />Oppdateringsdato kan være forskjellig fra Datafangsdato ved at data som er registrert kan bufres en kortere eller lengre periode før disse legges inn i datasystemet (databasen).<br /><br />-Definition-<br />Date and time at which this version of the spatial object was inserted or changed in the spatial data set.</td>
      <td>Date<wbr />Time</td>
      <td>1</td>
    </tr>
    <tr>
      <td>datauttaksdato</td>
      <td>dato for uttak fra en database<br /><br />Merknad:<br />Skiller seg fra Kopidato ved at en ikke skiller på om det er uttak fra en originaldatabase eller en kopidatabase.</td>
      <td>Date<wbr />Time</td>
      <td>1</td>
    </tr>
    <tr>
      <td>kvalitet</td>
      <td>beskrivelse av kvaliteten på stedfestingen<br /><br />Merknad: Denne er identisk med ..KVALITET i tidligere versjoner av SOSI.</td>
      <td>Posisjonskvalitet<br />(datatype)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- målemetode</td>
      <td>metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
      <td><a href="#kodeliste-målemetode">Målemetode</a><br />(kodeliste)</td>
      <td>1</td>
    </tr>
    <tr>
      <td>- nøyaktighet</td>
      <td>punktstandardavviket i grunnriss for punkter samt tverravvik for linjer<br /><br />Merknad:<br />Oppgitt i cm</td>
      <td>Integer</td>
      <td>0..1</td>
    </tr>
  </tbody>
</table>

#### HefteUrenBunn

i marin navigasjon, alt som hindrer eller forhindrer bevegelse, spesielt alt som truer eller hindrer passasje av et fartøy. Begrepet brukes vanligvis for å referere til en isolert fare for navigering<br /><br />In marine navigation, anything that hinders or impedes movement, particularly anything that endangers or prevents the safe passage of a vessel. The term is usually used to refer to an isolated danger to navigation

Egenskaper

<table class="feature-attribute-table">
  <thead>
    <tr>
      <th>Egenskap</th>
      <th>Beskrivelse</th>
      <th>Type</th>
      <th>Multiplisitet</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>posisjon</td>
      <td>sted som objektet eksisterer på<br /><br />-- Definition --<br />location where the object exists</td>
      <td>GM_<wbr />Point</td>
      <td>1</td>
    </tr>
    <tr>
      <td>hefte<wbr />Uren<wbr />Bunntype</td>
      <td>klassifisering av uren bunn.<br />Category of obstruction.</td>
      <td><a href="#kodeliste-hefteurenbunntype">Hefte<wbr />Uren<wbr />Bunntype</a><br />(kodeliste)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>dybde</td>
      <td>loddrett avstand fra et gitt referansenivå ned til bunnen eller annet objekt<br /><br />-- Definition --<br />vertical distance from a given reference level down to the bottom or another object??</td>
      <td>Real</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>vertikal<wbr />Datum</td>
      <td>vertikal referanse brukes til å spesifisere referansenivået for både høyder og dybder .<br />Vertical datum is used to specify the datum to which both heights (vertical datum) and soundings (sounding datum) are referred.</td>
      <td><a href="#kodeliste-vertikaldatum">Vertikal<wbr />Datum</a><br />(kodeliste)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>objektnavn<wbr />Engelsk</td>
      <td>heftets navn på engelsk<br />The name of the obstruction in English</td>
      <td>Character<wbr />String</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>objektnavn<wbr />Norsk</td>
      <td>heftets navn på norsk<br />The name of the obstruction in Norwegian</td>
      <td>Character<wbr />String</td>
      <td>0..1</td>
    </tr>
    <tr class="inherited-from">
      <th colspan="4" scope="rowgroup">Arvet fra Fellesegenskaper</th>
    </tr>
    <tr>
      <td>identifikasjon</td>
      <td>unik identifikasjon av et objekt</td>
      <td>Identifikasjon<br />(datatype)</td>
      <td>1</td>
    </tr>
    <tr>
      <td>- lokal<wbr />Id</td>
      <td>lokal identifikator, tildelt av dataleverendør/dataforvalter. Den lokale identifikatoren er unik innenfor navnerommet, ingen andre objekter har samme identifikator.<br /><br />NOTE: Det er data leverendørens ansvar å sørge for at denne lokale identifikatoren er unik innenfor navnerommet.</td>
      <td>Character<wbr />String</td>
      <td>1</td>
    </tr>
    <tr>
      <td>- navnerom</td>
      <td>navnerom som unikt identifiserer datakilden til objektet, starter med to bokstavs kode jfr ISO 3166. Benytter understreking  ("_") dersom data produsenten ikke er assosiert med bare et land.<br /><br />NOTE 1 : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og vil registreres i "INSPIRE external  Object Identifier Namespaces Register"<br /><br />Eksempel: NO for Norge.</td>
      <td>Character<wbr />String</td>
      <td>1</td>
    </tr>
    <tr>
      <td>første<wbr />Datafangstdato</td>
      <td>dato når data ble registrert/observert/målt første gang, som utgangspunkt for første digitalisering<br /><br />Merknad:<br />førsteDatafangstdato brukes hvis det er av interesse å forvalte informasjon om når en ble klar over objektet. Dette kan for eksempel gjelde datoen for første flybilde som var utgangspunkt for registrering i en database.</td>
      <td>Date<wbr />Time</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>oppdateringsdato</td>
      <td>dato for siste endring på objektetdataene<br /><br />Merknad:<br />Oppdateringsdato kan være forskjellig fra Datafangsdato ved at data som er registrert kan bufres en kortere eller lengre periode før disse legges inn i datasystemet (databasen).<br /><br />-Definition-<br />Date and time at which this version of the spatial object was inserted or changed in the spatial data set.</td>
      <td>Date<wbr />Time</td>
      <td>1</td>
    </tr>
    <tr>
      <td>datauttaksdato</td>
      <td>dato for uttak fra en database<br /><br />Merknad:<br />Skiller seg fra Kopidato ved at en ikke skiller på om det er uttak fra en originaldatabase eller en kopidatabase.</td>
      <td>Date<wbr />Time</td>
      <td>1</td>
    </tr>
    <tr>
      <td>kvalitet</td>
      <td>beskrivelse av kvaliteten på stedfestingen<br /><br />Merknad: Denne er identisk med ..KVALITET i tidligere versjoner av SOSI.</td>
      <td>Posisjonskvalitet<br />(datatype)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- målemetode</td>
      <td>metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
      <td><a href="#kodeliste-målemetode">Målemetode</a><br />(kodeliste)</td>
      <td>1</td>
    </tr>
    <tr>
      <td>- nøyaktighet</td>
      <td>punktstandardavviket i grunnriss for punkter samt tverravvik for linjer<br /><br />Merknad:<br />Oppgitt i cm</td>
      <td>Integer</td>
      <td>0..1</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
Fellesegenskaper

### Kodelister

#### <a id="kodeliste-vraktype"></a>«CodeList» Vraktype

**Definisjon:** angir hvilke kategori vrak dette er.
The category of the wreck.  Note:  S-57 CATWRK.

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>true</td>
    </tr>
    <tr>
      <th scope="row">codeList</th>
      <td><a href="https://register.geonorge.no/sosi-kodelister/temadata/maritim-infrastruktur/vraktype">https://register.geonorge.no/sosi-kodelister/temadata/maritim-infrastruktur/vraktype</a></td>
    </tr>
  </tbody>
</table>

#### <a id="kodeliste-vertikaldatum"></a>«CodeList» VertikalDatum

**Definisjon:** vertikal referanse brukes til å spesifisere referansenivået for både høyder og dybder .
Vertical datum is used to specify the datum to which both heights (vertical datum) and soundings (sounding datum) are referred.

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>true</td>
    </tr>
    <tr>
      <th scope="row">codeList</th>
      <td><a href="https://register.geonorge.no/sosi-kodelister/temadata/maritim-infrastruktur/vertikal-datum">https://register.geonorge.no/sosi-kodelister/temadata/maritim-infrastruktur/vertikal-datum</a></td>
    </tr>
  </tbody>
</table>

#### <a id="kodeliste-målemetode"></a>«CodeList» Målemetode

**Definisjon:** metode som ligger til grunn for registrering av posisjon


-- Definition - -
method on which registration of position is based

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>true</td>
    </tr>
    <tr>
      <th scope="row">codeList</th>
      <td><a href="https://register.geonorge.no/sosi-kodelister/generelle-konsepter/4.5/m%C3%A5lemetode">https://register.geonorge.no/sosi-kodelister/generelle-konsepter/4.5/m%C3%A5lemetode</a></td>
    </tr>
  </tbody>
</table>

#### <a id="kodeliste-hefteurenbunntype"></a>«CodeList» HefteUrenBunntype

**Definisjon:** Klassifisering av uren bunn.
Category of obstruction.

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>true</td>
    </tr>
    <tr>
      <th scope="row">codeList</th>
      <td><a href="https://register.geonorge.no/sosi-kodelister/temadata/maritim-infrastruktur/hefte-uren-bunn-type">https://register.geonorge.no/sosi-kodelister/temadata/maritim-infrastruktur/hefte-uren-bunn-type</a></td>
    </tr>
  </tbody>
</table>
