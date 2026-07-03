# MAPS Lab

MAPS Lab (Modeling and Analytics for Predictive Systems) is a research group at Dalhousie University building open-source tools for maritime informatics and predictive modeling of complex systems. Our work is funded by the [Department of Fisheries and Oceans](https://www.canada.ca/en/fisheries-oceans/news/2023/06/funded-projects-for-the-oceans-management-contribution-program.html) of the Government of Canada, and traces its roots to [MERIDIAN](https://meridian.cs.dal.ca), where the first generation of these tools was built. Learn more at [mapslab.tech](https://mapslab.tech/).

Everything we build is open, so anyone can inspect, reproduce, and extend our work. Our audience spans government bodies and policymakers, university researchers, NGOs, coastal communities, and the general public.

## Projects

### AISViz (maritime informatics)

Open-source tools that make [Automatic Identification System](https://en.wikipedia.org/wiki/Automatic_identification_system) (AIS) vessel-tracking data accessible to everyone, from storage and querying to analysis and modeling.

- [AISdb](https://github.com/MAPS-Lab/AISdb) is the core platform, a Python package with a Rust decoding engine for storing, querying, cleaning, and visualizing AIS data in SQLite or PostgreSQL, published on [PyPI](https://pypi.org/project/aisdb/).
- [AISdb-lite](https://github.com/MAPS-Lab/AISdb-lite) is a lightweight AISdb variant that ingests everything into TimescaleDB hypertables with PostGIS geometry for large-scale spatio-temporal analysis.
- [AISdb-NOAA-Integrator](https://github.com/MAPS-Lab/AISdb-NOAA-Integrator) acquires AIS archives from NOAA Marine Cadastre, covering every published format since 2009, and loads them into AISdb-aligned databases.
- [AISdb-Tutorials](https://github.com/MAPS-Lab/AISdb-Tutorials) holds the hands-on Jupyter notebooks behind our documentation, from database loading through track interpolation to bathymetry.
- [AISdb-GitBook](https://github.com/MAPS-Lab/AISdb-GitBook) is the source of our published documentation and tutorials.
- [aisviz.github.io](https://github.com/MAPS-Lab/aisviz.github.io) is the AISViz website, deployed to [aisviz.cs.dal.ca](https://aisviz.cs.dal.ca/).

### CiteForge (research tooling)

- [CiteForge](https://github.com/MAPS-Lab/CiteForge) is a Python tool for automated bibliographic data collection and enrichment, with multi-source aggregation and trust-based merging.

## Documentation

[AISdb Docs](https://aisviz.gitbook.io/documentation/) · [Tutorials](https://aisviz.gitbook.io/tutorials/) · [API reference](https://aisviz.cs.dal.ca/AISdb/) · [AISViz site](https://aisviz.cs.dal.ca/) · [Lab site](https://mapslab.tech/)

## Research applications

Our tools support research and policy work on environmental preservation, vessel traffic optimization, illegal fishing detection, aquatic invasive species prevention, and underwater noise monitoring. They also serve educators, students, and anyone curious about how vessel traffic shapes the oceans.

## Get involved

The lab grew out of collaboration and stays open to it. Whether you are a researcher, a programmer, an organization focused on marine conservation, or a learner drawn to ocean sciences, we welcome questions, suggestions, and contributions. Organization-wide contributing and security guidelines live in the [.github](https://github.com/MAPS-Lab/.github) repository, and you can reach the team at mapslab@dal.ca.
