# Awesome Trajectory Datasets [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

A curated list of open trajectory datasets for road traffic (vehicles & VRUs) — with a focus on real-world, ground-truth annotated data suitable for traffic analysis, motion prediction, and autonomous systems research.

**See data in action:** Several datasets and live feeds below are already integrated and publicly explorable on [**Trajectory Trace**](https://city.app.sdk-cloud.de/). Look for the 🔍 badge.

---

## Contents

- [Mixed Traffic](#mixed-traffic-️-)
- [Vehicles](#vehicles-️)
- [Vulnerable Road Users (VRUs)](#vulnerable-road-users-vrus-)
- [See Data in Action](#see-data-in-action)
- [Contributing](#contributing)
- [Related Lists](#related-lists)
- [Licensce](#license)

---

## Mixed Traffic 🚗🚌🚚🏍️ 🚶🚲🛴

| Dataset | Description | License | Links |
|---------|-------------|---------|-------|
| TUMDOT-MUC | 2022 · Munich, Germany · 12 drones · 6 locations, >3 h each, 700 m continuous section along Rheinstraße, 0.08 s resolution | CC-BY-NC 4.0 | [Paper](https://doi.org/10.1007/s42421-024-00101-5) · [Data](https://www.mos.ed.tum.de/en/vt/research/data-sets/tumdot-muc/) · [🔍](https://city.app.sdk-cloud.de/location/12) |
| DLR Urban Traffic (DLR UT) | 2023 · Brunswick, Germany · cams + radars · 12 h, inner ring road | CC-BY 4.0 | [Paper](https://www.techrxiv.org/doi/full/10.36227/techrxiv.174000540.08271707/v1) · [Data](https://doi.org/10.5281/zenodo.15025237) · [🔍](https://city.app.sdk-cloud.de/location/24?start=20230924155955&end=20230924161205) |
| pNEUMA | 2018 · Athens, Greece · 10 drones · 4 days, each ~4 h, city center | CC-BY-NC 4.0 | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0968090X19310320?via%3Dihub) · [Data](https://open-traffic.epfl.ch/index.php/downloads/) |
| KITTI | 2012 · Karlsruhe, Germany · LiDAR + cam + GNSS · 389 sequences | custom (non-commercial) | [Website](https://www.cvlibs.net/datasets/kitti/) |
| inD | 2020 · Germany (4 intersections) · drone · 11,500+ tracks | custom (free academic) | [Paper](https://arxiv.org/abs/1911.07602) · [Data](https://levelxdata.com/ind-dataset/) |
| rounD | 2020 · Germany (3 roundabouts) · drone · 13,746 tracks | custom (free academic) | [Paper](https://arxiv.org/abs/2011.06713) · [Data](https://levelxdata.com/round-dataset/) |
| OpenDD | 2020 · Germany (7 roundabouts) · drone · 84,000+ tracks | CC-BY 4.0 | [Paper](https://dl.acm.org/doi/10.1145/3397536.3422207) · [Data](https://l3pilot.eu/data/opendd) |
| INTERACTION | 2019 · Multi-country · drone + traffic cam · ~16 locations, merges + roundabouts + intersections | CC-BY-NC-SA | [Paper](https://arxiv.org/abs/1910.03088) · [Data](https://interaction-dataset.com/) |
| CitySim | 2023 · USA (12 locations) · drone (4K) · ~1,140 trajectories | CC-BY 4.0 | [Paper](https://arxiv.org/abs/2208.11036) · [Data](https://github.com/UCF-SST-Lab/UIVeri) |
| UrbanIng-V2X | 2025 · Ingolstadt, Germany · LiDAR + RGB cam + thermal cam + GNSS/IMU · V2X cooperative perception at 3 intersections, 34 sequences × 20 s, ~712k annotated instances at 10 Hz, 13 object classes | CC-BY-NC-ND 4.0 | [Data](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/A9LPY7) [Github](https://github.com/thi-ad/UrbanIng-V2X) [Website](https://thi-ad.github.io/urbaning/) [Paper](https://arxiv.org/pdf/2510.23478) [🔍](https://city.app.sdk-cloud.de/location/30?start=20241127145920&end=20241127150000)|
| Ko-PER Intersection | 2014 · Aschaffenburg, Germany · infrared cam + laser · 6 scenarios | custom | [Paper](https://ieeexplore.ieee.org/document/6957972) · [Data](https://www.uni-ulm.de/in/mrm/forschung/datensaetze/) |
| TRAF | 2019 · China (multiple cities) · drone · 50 sequences | CC-BY-NC | [Paper](https://arxiv.org/abs/1910.03726) · [Data](https://github.com/C-C-Y/TRAF) |
| SIND | 2022 · Changsha, China · drone · ~14k tracks at signalized intersections | custom | [Paper](https://arxiv.org/abs/2209.02297) · [Data](https://github.com/SOTIF-AVLab/SinD) |
| Argoverse 2 Motion | 2023 · 6 US cities · LiDAR + cam · 250,000 scenarios | CC-BY-NC-SA 4.0 | [Paper](https://arxiv.org/abs/2301.00493) · [Data](https://www.argoverse.org/av2.html) |
| nuScenes | 2020 · Boston + Singapore · LiDAR + cam + radar · 1,000 scenes × 20 s | CC-BY-NC-SA | [Paper](https://arxiv.org/abs/1929.13868) · [Data](https://www.nuscenes.org/) |
| Waymo Open Motion | 2021 · USA (various) · LiDAR + cam · 100,000 segments | custom (non-commercial) | [Paper](https://arxiv.org/abs/2104.10133) · [Data](https://waymo.com/open/data/motion/) |
| Lyft Level 5 | 2020 · Palo Alto, USA · LiDAR + cam · 1,118 h, 170,000 scenes | custom (non-commercial) | [Paper](https://arxiv.org/abs/2104.13949) · [Data](https://self-driving.lyft.com/level5/data/) |
| BDD100K | 2020 · USA (various) · cam · 100k videos, 10 annotation tasks | BSD 3-Clause | [Paper](https://arxiv.org/abs/1805.04687) · [Data](https://www.bdd100k.com/) |
| Argoverse 1 | 2019 · Pittsburgh + Miami · LiDAR + cam + HD map · 324,557 sequences | CC-BY-NC-SA 4.0 | [Paper](https://arxiv.org/abs/1911.02620) · [Data](https://www.argoverse.org/av1.html) |
| nuPlan | 2023 · USA + Singapore · LiDAR + cam · 1,500 h driving | CC-BY-NC-SA | [Paper](https://arxiv.org/abs/2106.11810) · [Data](https://www.nuscenes.org/nuplan) |
| Waymo Open Perception | 2020 · USA · LiDAR + cam · 2,030 segments × 20 s | custom (non-commercial) | [Paper](https://arxiv.org/abs/1912.04838) · [Data](https://waymo.com/open/data/perception/) |
| Stanford Drone (SDD) | 2016 · Stanford, USA · drone · 19,000+ tracks across 8 campus scenes | custom (academic) | [Website](https://cvgl.stanford.edu/projects/uav_data/) |
| VisDrone | 2021 | China (multiple cities) | drone cam | 288 video clips from drone view | custom (non-commercial) | [Paper](https://arxiv.org/abs/2001.06303) · [Data](https://github.com/VisDrone/VisDrone-Dataset) |
| GeoLife GPS Trajectories | 2012 | Beijing, China | gnss | 🚶🚲🚗🚢 182 users, 5 years, multi-modal | MS Research (open) | [Paper](https://www.microsoft.com/en-us/research/publication/geolife-gps-trajectory-dataset-user-guide/) · [Data](https://www.microsoft.com/en-us/research/project/geolife-building-social-networks-using-human-location-history/) |


## Vehicles 🚗🚌🚚🏍️

| Dataset | Description | License | Links |
|---------|-------------|---------|-------|
| Automatum | Germany (different places in Bavaria) · drone · 30 h | CC BY-ND / demo | [Paper](https://automatumdata.blob.core.windows.net/opendataset/IV21_Automatum.Data.eng.pdf) · [Data](https://automatum-data.com/de#dataset) · [🔍](https://city.app.sdk-cloud.de/location/29) · [🔍](https://city.app.sdk-cloud.de/location/32?start=20260222110000&end=20260222110453)
| DLR Highway Traffic (DLR HT) | 2024 · Brunswick, Germany · Test Bed Lower Saxony · trajectory data (position, speed, acceleration, class) + weather + road condition data, OpenSCENARIO export | CC-BY-NC-SA 4.0 | [Paper](https://doi.org/10.1109/IAVVC61942.2025.11219599) · [Data](https://doi.org/10.5281/zenodo.18540070) |
| highD | 2018 · Germany (A3, A9) · drone · 110,000+ tracks, 147 h | custom (free academic) | [Paper](https://arxiv.org/abs/1810.05642) · [Data](https://levelxdata.com/highd-dataset/) |
| exiD | 2022 · Germany (A3, A40, A42) · drone · 69,172 tracks at highway exits | custom (free academic) | [Paper](https://arxiv.org/abs/2204.03940) · [Data](https://levelxdata.com/exid-dataset/) |
| NGSIM US-101 & I-80 | 2006 · California, USA · roadside cam · ~9,000 tracks | public domain | [Docs](https://ops.fhwa.dot.gov/trafficanalysistools/ngsim.htm) · [Data](https://data.transportation.gov/Automobiles/Next-Generation-Simulation-NGSIM-Vehicle-Trajector/8ect-6jqj) |
| Shifts | 2022 · Multi-country · GNSS · 1M+ km, distributional shift benchmark | CC-BY 4.0 | [Paper](https://arxiv.org/abs/2107.07455) · [Data](https://github.com/yandex-research/shifts) |


## Vulnerable Road Users (VRUs) 🚶🚲🛴

| Dataset | Description | License | Links |
|---------|-------------|---------|-------|
| ETH Pedestrian | 2009 · Zurich, Switzerland · overhead cam · 750 pedestrians, 2 scenes | custom (academic) | [Paper](https://ieeexplore.ieee.org/document/5206559) · [Data](https://icu.ee.ethz.ch/research/datsets.html) |
| UCY Crowds | 2007 · Cyprus / Israel · cam · 786 pedestrians, 3 scenes | custom (academic) | [Data](https://graphics.cs.ucy.ac.cy/research/downloads/crowd-data) |
| TrajNet++ | 2021 · Multi-source · cam + drone · benchmark aggregating ETH, UCY + others | CC-BY | [Paper](https://arxiv.org/abs/2007.03639) · [Data](https://www.aicrowd.com/challenges/trajnet-a-trajectory-forecasting-challenge) |
| PIE | 2019 · Toronto, Canada · in-vehicle cam · 293,000 frames, 1,842 pedestrians with intention labels | custom (non-commercial) | [Paper](https://openaccess.thecvf.com/content_ICCV_2019/html/Rasouli_PIE_A_Large-Scale_Dataset_and_Models_for_Pedestrian_Intention_Estimation_ICCV_2019_paper.html) · [Data](http://data.nvision2.eecs.yorku.ca/PIE_dataset/) |
| ATC Shopping Center | 2013 · Osaka, Japan · 3D range sensors · ~100k tracks over 92 days | CC-BY | [Paper](https://doi.org/10.1007/s10514-013-9348-y) · [Data](https://irc.atr.jp/crest2010_HRI/ATC_dataset/) |

---

## See Data in Action

[![Trajectory Trace](https://img.shields.io/badge/Trajectory%20Trace-Live%20Platform-blue?style=for-the-badge)](https://city.app.sdk-cloud.de/)

[Trajectory Trace](https://city.app.sdk-cloud.de/) is an open platform for traffic trajectory data management, visualization, and analysis. A key design goal is the seamless combination of historical archives and live streaming feeds in a single interface — replay a research dataset alongside a live GTFS-RT bus feed or real-time AIS stream. Datasets and feeds marked with 🔍 are publicly accessible there — no account required. Features include:

- 3D map navigation with free viewpoint control
- Live streaming + historical replay in one unified view
- Connect GTFS-RT, MQTT, or custom feeds alongside static datasets
- Trajectory filtering by road user class (vehicle, pedestrian, cyclist, …)
- Traffic volume histograms and heat maps
- Event detection and scenario analysis
- GraphQL API for custom queries

→ [Try the live demo](https://city.app.sdk-cloud.de/) · [Read the docs](https://city.app.sdk-cloud.de/docs/en/) · [API reference](https://city.app.sdk-cloud.de/api/graphql)

---

## Contributing

Contributions are very welcome! Please read the [contributing guidelines](CONTRIBUTING.md) before submitting a PR.

Quick checklist for adding a dataset or live feed:
- [ ] The data is publicly accessible (free download, registration, or free-tier API)
- [ ] It contains trajectory data (x/y/t positions over time)
- [ ] A citable source (paper, DOI, or official website) exists
- [ ] The license is clearly stated
- [ ] For live feeds: the protocol and update rate are documented

If your dataset is integrated or can be integrated into [Trajectory Trace](https://city.app.sdk-cloud.de/), mention it in the PR — we'll add the 🔍 badge.

---

## Related Lists

- [awesome-autonomous-vehicles](https://github.com/autonomousvision/awesome-autonomous-vehicles)
- [awesome-point-cloud-analysis](https://github.com/Yochengliu/awesome-point-cloud-analysis)
- [awesome-human-motion](https://github.com/derikon/awesome-human-motion)

---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

This list is released under CC0 — no rights reserved.
