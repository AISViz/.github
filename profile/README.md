# AISViz

AISViz builds open-source tools that make maritime informatics accessible to everyone, from storing and querying [Automatic Identification System](https://en.wikipedia.org/wiki/Automatic_identification_system) (AIS) vessel-tracking data to analyzing and modeling it. The project is developed and maintained by the [MAPS Lab](https://mapslab.tech/) (Modeling and Analytics for Predictive Systems) at Dalhousie University, and is funded by the [Department of Fisheries and Oceans](https://www.canada.ca/en/fisheries-oceans/news/2023/06/funded-projects-for-the-oceans-management-contribution-program.html) of the Government of Canada. AISViz traces its roots to [MERIDIAN](https://meridian.cs.dal.ca), where the first generation of these tools was built.

Our goal is a complete, easy-to-use toolbox for raw AIS data extraction, processing, visualization, and vessel modeling. The audience spans government bodies and policymakers, university researchers, NGOs, coastal communities, and the general public. Everything we build is open, so anyone can inspect, reproduce, and extend our work.

## Projects

- [AISdb](https://github.com/AISViz/AISdb) is the core platform, a Python package with a Rust decoding engine for storing, querying, cleaning, and visualizing AIS data in SQLite or PostgreSQL, published on [PyPI](https://pypi.org/project/aisdb/).
- [AISdb-lite](https://github.com/AISViz/AISdb-lite) is a lightweight AISdb variant that ingests everything into TimescaleDB hypertables with PostGIS geometry for large-scale spatio-temporal analysis.
- [NOAA-Integrator](https://github.com/AISViz/NOAA-Integrator) acquires AIS archives from NOAA Marine Cadastre, covering every published format since 2009, and loads them into AISdb-aligned databases.
- [Tutorials](https://github.com/AISViz/Tutorials) holds the hands-on Jupyter notebooks behind our documentation, from database loading through track interpolation to bathymetry.
- [GitBook](https://github.com/AISViz/GitBook) is the source of our published documentation and tutorials.
- [aisviz.github.io](https://github.com/AISViz/aisviz.github.io) is the project website, deployed to [aisviz.cs.dal.ca](https://aisviz.cs.dal.ca/).

## Documentation

[Docs](https://aisviz.gitbook.io/documentation/) · [Tutorials](https://aisviz.gitbook.io/tutorials/) · [API reference](https://aisviz.cs.dal.ca/AISdb/) · [Website](https://aisviz.cs.dal.ca/)

The documentation covers installation, database setup, receiver hardware, and step-by-step analysis workflows. The API reference describes the full AISdb programming interface.

## Research applications

AISViz supports research and policy work on environmental preservation, vessel traffic optimization, illegal fishing detection, aquatic invasive species prevention, and underwater noise monitoring. The same tools serve educators, students, and anyone curious about how vessel traffic shapes the oceans.

## Get involved

The project grew out of collaboration and stays open to it. Whether you are a researcher, a programmer interested in AIS data, an organization focused on marine conservation, or a learner drawn to ocean sciences, we welcome questions, suggestions, and contributions. Organization-wide contributing and security guidelines live in the [.github](https://github.com/AISViz/.github) repository, and you can reach the team at aisviz@dal.ca.
