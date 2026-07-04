# MAPS Lab

Modeling and Analytics for Predictive Systems · Faculty of Computer Science, Dalhousie University

We develop modelling and analytics methods for predictive systems that operate over complex, heterogeneous, and evolving data. Our research connects big data, data science, network science, machine learning, and geospatial intelligence to understand systems where structure, scale, uncertainty, and time shape prediction. Our work advances data-driven methods for forecasting, monitoring, representation learning, and decision support, with applications in maritime transportation, ocean mobility, climate adaptation, urban intelligence, and other large-scale socio-technical and environmental systems.

This organization hosts the lab’s open-source software, research prototypes, datasets where redistribution is permitted, reproducible experiments, and supporting documentation. The goal is to make our work inspectable, reusable, and extensible, so researchers, students, practitioners, and partners can reproduce results, build on our tools, and contribute to predictive systems research.

## Research themes

Big Data · Data Science · Network Science · Machine Learning

## Software

### Maritime Informatics

AISViz is an open-source maritime informatics initiative from the [MAPS Lab](https://mapslab.tech/) at [Dalhousie University](https://www.dal.ca/), primarily funded by [Fisheries and Oceans Canada](https://www.dfo-mpo.gc.ca/) through the AISViz project, *Making Vessels Tracking Data and Maps Available to Everyone*. The project builds on previous efforts developed through [MERIDIAN](https://meridian.cs.dal.ca/), the *Marine Environmental Research Infrastructure for Data Integration and Application Network*, a Canadian research infrastructure for underwater acoustic and vessel-tracking data.

AISViz lowers the technical barrier to using [Automatic Identification System](https://en.wikipedia.org/wiki/Automatic_identification_system) vessel-tracking data by turning raw vessel movement records into accessible maps, queries, analyses, and models. Its tools support historical and real-time vessel traffic workflows, including ingestion, cleaning, storage, indexing, spatiotemporal querying, visualization, trajectory analysis, and vessel behaviour modelling. The initiative serves researchers, students, public agencies, policymakers, NGOs, coastal communities, and other users who work with maritime mobility data for safety, conservation, ocean planning, environmental monitoring, vessel impact assessment, and climate-aware transportation studies.

| Project | What it does |
| --- | --- |
| [AISdb](https://github.com/MAPS-Lab/AISdb) | Core platform. A Python package with a Rust decoding engine for storing, querying, cleaning, and visualizing AIS data in SQLite or PostgreSQL. Published on [PyPI](https://pypi.org/project/aisdb/). |
| [AISdb-lite](https://github.com/MAPS-Lab/AISdb-lite) | Lightweight variant that ingests into TimescaleDB hypertables with PostGIS geometry for large-scale spatio-temporal analysis. |
| [AISdb-NOAA-Integrator](https://github.com/MAPS-Lab/AISdb-NOAA-Integrator) | Acquires AIS archives from NOAA Marine Cadastre, covering every published format since 2009, and loads them into AISdb-aligned databases. |
| [AISdb-Tutorials](https://github.com/MAPS-Lab/AISdb-Tutorials) | Hands-on Jupyter notebooks, from database loading through track interpolation to bathymetry. |
| [AISdb-GitBook](https://github.com/MAPS-Lab/AISdb-GitBook) | Source of the published documentation and tutorials. |
| [aisviz.github.io](https://github.com/MAPS-Lab/aisviz.github.io) | The AISViz website, deployed to [aisviz.cs.dal.ca](https://aisviz.cs.dal.ca/). |

See the [documentation](https://aisviz.gitbook.io/documentation/), the [tutorials](https://aisviz.gitbook.io/tutorials/), and the [API reference](https://aisviz.cs.dal.ca/AISdb/).

### Research tooling

| Project | What it does |
| --- | --- |
| [CiteForge](https://github.com/MAPS-Lab/CiteForge) | Automated bibliographic data collection and enrichment, with multi-source aggregation and trust-based merging. |

## Affiliation

MAPS Lab is part of the Faculty of Computer Science at Dalhousie University and collaborates with the Maritime Risk and Safety (MARS) research group. Its maritime informatics work traces its roots to [MERIDIAN](https://meridian.cs.dal.ca), where the first generation of these tools was built.

## Get involved

We welcome questions, suggestions, and contributions from researchers, developers, conservation organizations, and learners. Organization-wide contributing and security guidelines live in the [.github](https://github.com/MAPS-Lab/.github) repository. Reach the team at mapslab@dal.ca or visit [mapslab.tech](https://mapslab.tech/).
