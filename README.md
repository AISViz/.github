# MAPS-Lab community health

This special `.github` repository provides the shared organization profile and default community-health files for the [MAPS Lab](https://mapslab.tech/) at Dalhousie University. GitHub reads these files to render the organization landing card and to supply fallback community documents to every MAPS Lab repository that does not ship its own. It is developed and maintained by the MAPS Lab.

## Contents

- [`profile/README.md`](profile/README.md) renders as the public organization profile card on the MAPS Lab GitHub page, describing the lab, its research themes, and its software.
- [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) sets the behavioural expectations for participants, adapted from the Contributor Covenant v2.0.
- [`CONTRIBUTING.md`](CONTRIBUTING.md) explains how to report bugs, suggest enhancements, improve documentation, and submit code across MAPS Lab projects.
- [`SECURITY.md`](SECURITY.md) describes how to report a vulnerability and what response to expect from the team.

## How GitHub uses this repository

GitHub applies `CODE_OF_CONDUCT.md`, `CONTRIBUTING.md`, and `SECURITY.md` org-wide as defaults, so any MAPS Lab repository without its own copy inherits the versions kept here. The `profile/README.md` file is special, rendering as the organization profile shown on the MAPS Lab landing page.

## Citation

If you use these community-health files in your work, please cite it. Citation metadata lives in [CITATION.cff](CITATION.cff), and the BibTeX entry follows.

```bibtex
@software{MAPSLabCommunityHealth2026:GSpadon,
  author    = {Spadon, Gabriel},
  title     = {MAPS-Lab community health},
  year      = {2026},
  publisher = {MAPS Lab, Dalhousie University},
  url       = {https://github.com/MAPS-Lab/.github},
  license   = {AGPL-3.0}
}
```

## License

This project is distributed under the terms of the GNU Affero General Public License v3.0 (AGPL-3.0). See [LICENSE](LICENSE) for details.
