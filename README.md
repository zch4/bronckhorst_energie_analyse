# Bronckhorst Energie Analyse

Een data-engineeringproject voor energie- en duurzaamheidsdata op buurt- en wijkniveau in gemeente Bronckhorst. Dit project ontwikkelt een end-to-end datapipeline van open databronnen naar herbruikbare datasets en visualisaties in Power BI.

## Over dit project

Dit project onderzoekt energieverbruik, woningkenmerken en transitie-gereedheid op wijk- en buurtniveau in gemeente Bronckhorst. Het doel is om met open data en moderne data-engineeringtechnieken inzicht te bieden in de lokale energietransitie.

## Uitgevoerde werkzaamheden

### Data-ontsluiting
- Ontsluiting van ArcGIS FeatureServer-data (CBS Wijk- en Buurtkaart) via Python
- Ontsluiting van CBS StatLine open data voor energie- en woningkenmerken
- Filtering op gemeente Bronckhorst (gemeentecode GM1876)

### Data-engineering
- Harmonisatie van datasets op buurt- en wijkniveau
- Feature engineering: berekening energieverbruik per huishouden
- Ontwikkeling van dimensioneel datamodel (wijk/buurt, jaar, energie-indicatoren)
- Opgelost: GIS-projectieprobleem (RD New → WGS84) voor compatibiliteit met Power BI

### Output
- Export naar herbruikbare formaten (CSV, GeoJSON)
- Basis Power BI dashboard met geografische visualisaties
- GitHub-repository met documentatie

## Technologieën

- **Python** - Data-processing, ETL-pipeline en API-integratie
- **ArcGIS/GeoJSON** - Ontsluiting en verwerking ruimtelijke data
- **Power BI** - Interactieve dashboards en geografische visualisaties
- **Azure** - Cloud platform voor data storage en processing (gepland)

## Data bronnen

- **CBS Wijk- en Buurtkaart** - ArcGIS FeatureServer (ruimtelijke data)
- **CBS StatLine** - Buurt- en wijkgegevens (energie, demografie, woningen)
- **RVO energielabel database** - Energielabels woningvoorraad (gepland)
- **Gemeente Bronckhorst open data portaal** - Lokale datasets (gepland)

## Doelstellingen en inzichten

Inzicht geven in:

- Huidige energieverbruik (gas & elektriciteit) per buurt/wijk
- Woningvoorraad en energielabelverdeling
- Potentieel voor verduurzaming op buurtniveau
- Socio-economische aspecten van de energietransitie

## Status

Project in ontwikkeling - Onderdeel van data engineering portfolio

**Volgende stappen:**
- Uitbreiding met RVO energielabel data
- Verdieping Power BI dashboard (extra metrics en filters)
- Migratie naar Azure (Data Lake, Databricks)

---

*Laatst bijgewerkt: Januari 2026*
