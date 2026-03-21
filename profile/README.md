
# SPAS-Demographic

![](../images/SPAS-logo.png)

**Subnational Population and Administrative Spatial (SPAS) Data Collection**

We compile, harmonize, and publish sub-national population data by age and sex for low- and middle-income countries worldwide. Our collection integrates data from multiple international demographic programs and pairs them with geographic boundary files, enabling spatially explicit analysis of population composition at fine spatial scales.

## What We Do

- **Assemble** sub-national age-sex distributions from censuses and household surveys spanning the 1960s to the present
- **Link** demographic tabulations to sub-national administrative boundary files (GeoPackages)
- **Assess** data quality against international benchmarks (UN World Population Prospects)
- **Distribute** the collection as open-access, spatially referenced datasets

## Data Sources

Our collection draws on:

| Source | Type | Coverage |
|--------|------|----------|
| **DHS** | Household survey micro-data | 350+ surveys, 80+ countries, 1986-2023 |
| **IPUMS-I** | Census micro-data samples | 320 datasets, 1962-2020 |
| **MICS** | Household survey micro-data | 250+ surveys, 1999-2023 |
| **USCB** | Full-census tabulations | 58 censuses, 2002-2023 |
| **NSO** | National statistical office tabulations | Ongoing collection |
| **IHGIS** | Historical census tabulations | Selected countries |
| **WFS** | Early survey micro-data | 25 surveys, 1974-1980 |
| **REDATAM** | Full census micro-data | Latin America, 1991-2020 |

## Repositories

| Repository | Description |
|------------|-------------|
| [**AgeSex-Pop**](https://github.com/SPAS-Demographic/AgeSex-Pop) | Main data collection: sub-national age-sex distributions in GeoPackage format |

## Spatial Approach

Rather than forcing heterogeneous sub-national boundaries into artificially harmonized units, we preserve year-specific administrative boundaries and use the Global Human Settlement Layer (GHSL) built-up land rasters to identify plausible habitation points within each unit. This approach retains meaningful spatial variation from 1975 to the present.

## Team

- Mark R. Montgomery (Stony Brook University)
- Emanuel Agu (CUNY Institute for Demographic Research)
- Deborah Balk (CUNY Institute for Demographic Research)
- Alessandra Carioli (Joint Research Centre, European Commission)
- Stefan Leyk (University of Colorado, Boulder)
- Evgeny Noi (University of Bristol)
- Juan F. Martinez (CIESIN, Columbia University)
- Aleksander Berg (University of Colorado, Boulder)
- Tsu P. Zhu (CUNY Institute for Demographic Research)
