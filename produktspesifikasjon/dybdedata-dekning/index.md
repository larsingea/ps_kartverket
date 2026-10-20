---
title: "Dybdedata - dekning"
updated: "2026-10-20"
organization: "Kartverket"
logo: "https://register.geonorge.no/data/organizations/971040238_Kartverket_liten.png"
---

# Produktspesifikasjon: Dybdedata - dekning

*Datasettet viser en oversikt over hvilke norske sjøområder som har blitt dybdekartlagt/sjømålt. Dybdedata er samlet inn over en lang tidsperiode, av ulike aktører og med ulikt utstyr. I egenskapstabellen til datasettet finnes det opplysninger som måleårstall, kartleggingsmetode, dataeier/hvilken aktør som har samlet inn dataene, utstyr, ekkolodd-type, spesifikasjon og oppløsning. 
Innholdet i datasettet er basert på tilgjengelig data hos Kartverket.

Kvalitet på data oppgis som en egenskap i egenskapstabellen, med en kategorisering på 1-4, hvor 1 er best kvalitet og 4 er dårligst. Disse er kategorisert etter dybdesensor (i hovedsak ekkoloddtype, men andre dybdesensorer kan forekomme, eks. laser). Kategori 1 er moderne multistråle, kategori 2 er relativt gode data, men inneholder mer støy og hull enn kategori 1. Kategori 3 er eldre multistråle, vanlig før år 2000, og kategori 4 er enkeltstråledata eller andre innsamlingsmetoder med lav kvalitet. 

Datasettet har to verdier som beskriver oppløsning: resolution og target_resolution. Resolution viser hvilken oppløsning Kartverket allerede har griddet målingen til, begrenset med søkeradius-metoden. Target-resolution er et automatisk beregnet estimat som viser hvor grovt datasettet maksimalt bør griddes for at kvaliteten skal være tilfredstillende over hele måleoppdraget. Beregningen gjøres ved å analysere punkttettheten i datasettet (binning-metoden) og ta utgangspunkt i de 5 % av områdene som har lavest punkttetthet. Verdien gir dermed en konservativ og helhetlig anbefalt grid-oppløsning for hele datasettet.*

**Nøkkelord:** MAREANO, batymetri, dybdedata, DTM, Marine grunnkart, sjømåling, ekkolodd, Høyde, Norge digitalt, fellesDatakatalog, Høydedata

**Emnekategorier:** Kyst og sjø

**Geografisk område**:
Nordsjøen, Barentshavet, Havområde, Hav, Sjømåling, MAREANO, Norge, Svalbard, Dybdedata, Batymetri, Marine grunnkart

**Tidsmessig utstrekning**:

- **Tidsperiode**:
  - **Fra**: 2021-11-26
  - **Til**: 2026-07-02

## Om spesifikasjonen


> **Denne versjonen av produktspesifikasjonen:** <br>
> **Opprettet dato:** 2021-11-26<br>
> **Endret dato:** 2026-07-02<br>
> **Språk:** eng<br>
> **Kontaktinformasjon:** Kartverket, [kundesenter@kartverket.no](mailto:kundesenter@kartverket.no)

## Om produktet Dybdedata - dekning


> **Romlig representasjonstype:** Vektor<br>
> **Unik identifikator:** <https://data.geonorge.no/sosi/dybdedata/dybdedata_dekning_sjomaling><br>
> **Kontaktinformasjon:** Kartverket, [kundesenter@kartverket.no](mailto:kundesenter@kartverket.no)
>
> **Romlig oppløsning:**
>
> **Avstand**:
>
> - **Måleenhet**: meter
> - **Verdi**: 50
>
> **Begrensninger:**
>
> **Juridiske begrensninger**:
>
> - **Tilgangsbegrensninger**: Åpne data
> - **Bruksbegrensninger**: Lisens
> - **Lisens**: Creative Commons BY 4.0 (CC BY 4.0)
> - **Lisenslenke**: <https://creativecommons.org/licenses/by/4.0/>
>
> **Sikkerhetsbegrensninger**:
>
> - **Klassifisering**: Ugradert

### Formål

Formålet med datasettet er å gi en oversikt over innsamlede og tilgjengelige dybdedata.

### Bruksområde

Datasettet kan benyttes til å få en oversikt over tilgjengelige dybdedata, f.eks. i forbindelse med planlagte aktiviteter i et spesifikt område. Ved hjelp av informasjon tilgjengelig i egenskapstabellen, vil man kunne få et innblikk i kvalitet og egnethet av dybdedata. Nyere data er å anse av best kvalitet, da det har hovedsakelig blitt samlet inn ved bruk av multistråle ekkolodd, mens eldre data er samlet inn med enkeltstråle ekkolodd eller annet eldre utstyr.  
Datasettet kan også benyttes til kart, presentasjoner, ulike analyser eller som beslutningsgrunnlag.

## Omfang

### Hele datasettet

**Nivå**: dataset

**Nivåbeskrivelse**: Gjelder hele datasettet. Hvis omfang ikke er oppgitt under en overskrift, gjelder teksten for hele datasettet og alle leveranser

### datamodell fra API

**Nivå**: dataset

**Nivåbeskrivelse**: OGC API-Features fra Kartverket

### UML

**Nivå**: dataset

**Nivåbeskrivelse**: Datamodell fra SOSI UML-modell

## Datainnhold og struktur



### Datamodell - datamodell fra API



<a href="datamodell-fra-api/datamodell-fra-api_feature_catalogue.png" title="Klikk for stor visning"><img src="datamodell-fra-api/datamodell-fra-api_feature_catalogue.png" alt="Datamodell datamodell fra API" style="max-width: 100%; height: auto;" /></a>



➡️ [Se full datamodell for omfang "datamodell fra API" (diagram per pakke og objektkatalog)](datamodell-fra-api/objektkatalog.html)

### Datamodell - UML



<a href="uml/uml_feature_catalogue.png" title="Klikk for stor visning"><img src="uml/uml_feature_catalogue.png" alt="Datamodell UML" style="max-width: 100%; height: auto;" /></a>



➡️ [Se full datamodell for omfang "UML" (diagram per pakke og objektkatalog)](uml/objektkatalog.html)

## Datakvalitet

**Nivå**: dataset

**Kvalitetsmål**: Prosentvis dekning i forhold til datasettets utstrekning

- **Målebeskrivelse**: Datasettets faktiske kartlagte areal i forhold til datasettets spesifiserte utstrekning
- **Resultat**: 45

**Kvalitetsmål**: Prosentvis oppfyllelse av FAIR-prinsipper

- **Målebeskrivelse**: Angir fullstendighet i forhold til krav fra FAIR-prinsippene (The FAIR Guiding Principles for scientific data management and stewardship)
- **Resultat**: 77

## Datafangst og produksjon

Datasettet tar utgangspunkt i Kartverkets oversikt over dekning sjømålte områder. Datasettet er delt inn i polygoner, hvor hvert polygon representerer et måleoppdrag (et oppdrag, tokt eller datasett med dybdedata) og viser utstrekningen av sjømålt område. Måleoppdragene er identifisert med en unik og persistent ID, som benyttes som identifikator for det bestemte måleoppdraget/toktet.

## Vedlikehold

**Vedlikeholdsfrekvens**: Kontinuerlig

**Status**: Kontinuerlig oppdatert

## Leveranse

| Tjeneste | Endepunkt | Type | Format | Leveranseenheter |
| --- | --- | --- | --- | --- |
| OGC API-Features | [Lenke](https://hybasapi.atgcp1-prod.kartverket.cloud/) | OGC:API-Features | GeoJSON | landsfiler |
| WMS-tjeneste | [Lenke](https://survey.kartverket.no/?service=WMS&request=GetCapabilities) | OGC:WMS | WMS, [{}] | landsfiler |

## Metadata

**Metadatastandard**: ISO19115

**Metadatastandardversjon**: 2003

**Metadatadato**: 2026-07-02

**språk**: nor

**Kontakt**:

- **Organisasjon**: Kartverket
- **Kontaktperson**: Matilde Skjæveland Skår
- **Logo**: <https://register.geonorge.no/data/organizations/971040238_Kartverket_liten.png>
- **Epost**: kundesenter@kartverket.no
- **rolle**: pointOfContact

**Metadataidentifikator**:

- **Utsteder**: Geonorge
- **kode**: 7fd4a1f7-be17-4dcb-8a16-df891dd0be9c
- **koderom**: <https://kartkatalog.geonorge.no/metadata/>
- **Metadatalenke**: <https://kartkatalog.geonorge.no/metadata/7fd4a1f7-be17-4dcb-8a16-df891dd0be9c>

## Tilleggsinformasjon



- **Produktark:** [https://register.geonorge.no/produktark/dybdedata-dekning](https://register.geonorge.no/produktark/dybdedata-dekning)
- **Produktside:** [https://hybasapi.atgcp1-prod.kartverket.cloud/](https://hybasapi.atgcp1-prod.kartverket.cloud/)
