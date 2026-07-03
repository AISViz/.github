# MAPS Lab

Modeling and Analytics for Predictive Systems · Faculty of Computer Science, Dalhousie University

We advance modeling and analytics for predictive systems through research spanning big data, data science, network science, and machine learning. We study complex phenomena that pair heterogeneous data with structure evolving at scale, with an emphasis on data-driven methods for prediction, monitoring, and decision support. Our applied work reaches maritime transportation, ocean mobility forecasting, climate adaptation, and urban intelligence.

This organization hosts the lab's open-source software. Everything here is open, so anyone can inspect, reproduce, and build on it.

## Research themes

Big Data · Data Science · Network Science · Machine Learning

## Software

### AISViz (maritime informatics)

Open tools that make [Automatic Identification System](https://en.wikipedia.org/wiki/Automatic_identification_system) (AIS) vessel-tracking data accessible to everyone, from storage and querying to analysis and modeling.

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

## People and funding

MAPS Lab is directed by Gabriel Spadon in the Faculty of Computer Science at Dalhousie University, and collaborates with the Maritime Risk and Safety (MARS) research group. The maritime informatics work is funded by the [Department of Fisheries and Oceans](https://www.canada.ca/en/fisheries-oceans/news/2023/06/funded-projects-for-the-oceans-management-contribution-program.html) of the Government of Canada, and traces its roots to [MERIDIAN](https://meridian.cs.dal.ca), where the first generation of these tools was built.

## Get involved

We welcome questions, suggestions, and contributions from researchers, developers, conservation organizations, and learners. Organization-wide contributing and security guidelines live in the [.github](https://github.com/MAPS-Lab/.github) repository. Reach the team at mapslab@dal.ca or visit [mapslab.tech](https://mapslab.tech/).
