# MAPS Lab

Modelling and Analytics for Predictive Systems · Faculty of Computer Science, Dalhousie University

We develop modelling and analytics methods for predictive systems that operate over complex, heterogeneous, and evolving data. Our research connects big data, data science, network science, machine learning, and geospatial intelligence to understand systems where structure, scale, uncertainty, and time shape prediction. Our work advances data-driven methods for forecasting, monitoring, pattern discovery, representation learning, optimization, and decision support, with applications in maritime mobility, climate adaptation, urban and ocean intelligence, and other large-scale socio-technical and environmental systems.

This organization hosts the lab’s open-source software, research prototypes, reproducible experiments, and supporting documentation, with datasets shared whenever licensing and redistribution permit. The goal is to make our work inspectable, reusable, and extensible, so researchers, students, practitioners, and partners can reproduce results, build on our tools, and contribute to predictive systems research.

## Research themes

Our research is organized around four complementary pillars.

- **Big Data.** High-throughput pipelines and storage engines for massive spatiotemporal data streams, with careful attention to ingestion, indexing, querying, and the performance and memory footprint required to operate at scale.
- **Data Science.** Spatiotemporal analytics, time-series forecasting, trajectory mining, and anomaly detection that turn heterogeneous mobility and environmental data into evidence for monitoring and decision support.
- **Network Science.** Complex network mining and graph-based modelling of interconnected systems, from shipping routes and port networks to spatial interaction structures, including representation learning over graphs.
- **Machine Learning.** Predictive and multimodal models for forecasting and behaviour modelling, including approaches that fuse vessel tracking with underwater acoustics and other environmental signals.

## Software

### Maritime Informatics

AISViz is an open-source maritime informatics initiative from the [MAPS Lab](https://mapslab.tech/) at [Dalhousie University](https://www.dal.ca/), funded by [Fisheries and Oceans Canada](https://www.dfo-mpo.gc.ca/) through the AISViz project, *Making Vessels Tracking Data and Maps Available to Everyone*. The project builds on previous efforts developed through [MERIDIAN](https://meridian.cs.dal.ca/), the *Marine Environmental Research Infrastructure for Data Integration and Application Network*, a Canadian research infrastructure for ocean data and its applications.

AISViz lowers the technical barrier to using [Automatic Identification System](https://en.wikipedia.org/wiki/Automatic_identification_system) vessel-tracking data by turning raw vessel movement records into accessible maps, queries, analyses, and models. Its tools support historical and real-time vessel traffic workflows, including ingestion, cleaning, storage, indexing, spatiotemporal querying, visualization, trajectory analysis, and vessel behaviour modelling. The initiative serves researchers, students, public agencies, policymakers, NGOs, coastal communities, and other users who work with maritime mobility data for safety, conservation, ocean planning, environmental monitoring, vessel impact assessment, and climate-aware transportation studies.

| Project | What it does |
| --- | --- |
| [AISdb](https://github.com/MAPS-Lab/AISdb) | Core platform. A Python package with a Rust decoding engine for storing, querying, cleaning, and visualizing AIS data in SQLite or PostgreSQL. Published on [PyPI](https://pypi.org/project/aisdb/). |
| [AISdb-lite](https://github.com/MAPS-Lab/AISdb-lite) | Lightweight variant that ingests into TimescaleDB hypertables with PostGIS geometry for large-scale spatio-temporal analysis. |
| [NOAA-Integrator](https://github.com/MAPS-Lab/NOAA-Integrator) | Acquires AIS archives from NOAA Marine Cadastre, covering every published format since 2009, and loads them into AISdb-aligned databases. |
| [AISdb-Tutorials](https://github.com/MAPS-Lab/AISdb-Tutorials) | Hands-on Jupyter notebooks, from database loading through track interpolation to bathymetry. |
| [AISdb-GitBook](https://github.com/MAPS-Lab/AISdb-GitBook) | Source of the published documentation and tutorials. |
| [aisviz.github.io](https://github.com/MAPS-Lab/aisviz.github.io) | The AISViz website, deployed to [aisviz.cs.dal.ca](https://aisviz.cs.dal.ca/). |

See the [documentation](https://aisviz.gitbook.io/documentation/) and the [tutorials](https://aisviz.gitbook.io/tutorials/).

### Research Tooling

| Project | What it does |
| --- | --- |
| [CiteForge](https://github.com/MAPS-Lab/CiteForge) | Automated bibliographic data collection and enrichment, with multi-source aggregation and trust-based merging. |

## People

MAPS Lab was founded and is led by [Gabriel Spadon](https://github.com/gabrielspadon), Assistant Professor in the Faculty of Computer Science at Dalhousie University ([Google Scholar](https://scholar.google.com/citations?user=bfdGsGUAAAAJ) · [ORCID](https://orcid.org/0000-0001-8437-4349) · [ResearchGate](https://www.researchgate.net/profile/Gabriel-Spadon) · [LinkedIn](https://www.linkedin.com/in/spadon/)). The team brings together postdoctoral fellows and graduate students working across data science, machine learning, signal processing, computer vision, and geoinformatics; the current roster is on our [website](https://mapslab.tech/people).

## Affiliation

MAPS Lab is part of the Faculty of Computer Science at Dalhousie University and collaborates with the Maritime Risk and Safety (MARS) research group. Its maritime informatics work traces its roots to [MERIDIAN](https://meridian.cs.dal.ca), where the first generation of these tools was built.

## Funding

Our work is supported by public research funders and mission-driven programs, including [Fisheries and Oceans Canada](https://www.dfo-mpo.gc.ca/) through the AISViz project, the [Natural Sciences and Engineering Research Council of Canada](https://www.nserc-crsng.gc.ca/) for ocean mobility forecasting, the [Ocean Frontier Institute](https://www.ofi.ca/) for community-centered climate adaptation, and Brazil’s [National Council for Scientific and Technological Development](https://www.gov.br/cnpq/pt-br) for geophysics-informed modeling. This list highlights active programs and is not exhaustive; funding acknowledgments for individual projects can be found in the corresponding repositories and publications.

## Join the lab

We welcome applications from prospective MSc and PhD students through the graduate programs of the [Faculty of Computer Science](https://www.dal.ca/faculty/computerscience.html) at Dalhousie University, and we regularly host international research interns through programs such as [Mitacs](https://www.mitacs.ca/our-programs/globalink-research-award/), [ELAP](https://www.educanada.ca/scholarships-bourses/can/institutions/elap-pfla.aspx), and [SICS](https://www.educanada.ca/scholarships-bourses/can/institutions/study-in-canada-sep-etudes-au-canada-pct.aspx). Prospective postdoctoral fellows are encouraged to get in touch about fellowship opportunities. If your interests align with our research themes, email *mapslab@dal.ca* with your CV and a short statement of interest.

## Get involved

We welcome questions, suggestions, and contributions from researchers, developers, conservation organizations, and learners. Reach the team at mapslab@dal.ca or visit [mapslab.tech](https://mapslab.tech/).
