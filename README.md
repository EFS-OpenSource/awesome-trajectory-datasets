# Awesome Trajectory Datasets [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

> A curated list of open trajectory datasets and live data streams for road traffic (vehicles & VRUs), aerial, and maritime domains — with a focus on real-world, ground-truth annotated data suitable for traffic analysis, motion prediction, and autonomous systems research.

Covers both **historical datasets** (downloadable archives) and **live data streams** (real-time feeds you can connect to today).

**See data in action:** Several datasets and live feeds below are already integrated and publicly explorable on [**Trajectory Trace**](https://city.app.sdk-cloud.de/). Look for the 🔍 badge.

---

## Contents

- [Legend](#legend)
- [Road Traffic](#road-traffic)
  - [Mixed Traffic (Vehicles + VRUs)](#mixed-traffic-vehicles--vrus)
  - [Vehicles](#vehicles)
  - [VRUs (Pedestrians & Cyclists)](#vrus-pedestrians--cyclists)
- [Aerial (UAV / Aircraft)](#aerial-uav--aircraft)
- [Maritime](#maritime)
- [Live Data Streams](#live-data-streams)
  - [Public Transport (GTFS-RT)](#public-transport-gtfs-rt)
  - [Maritime (AIS Streams)](#maritime-ais-streams)
  - [Aviation (ADS-B Streams)](#aviation-ads-b-streams)
  - [Road Traffic (Open Feeds)](#road-traffic-open-feeds)
- [Benchmarks & Challenges](#benchmarks--challenges)
- [Contributing](#contributing)

---

## Legend

| Symbol | Meaning |
|--------|---------|
| 🚗 | Cars / light vehicles |
| 🚌 | Trucks / buses / heavy vehicles |
| 🚶 | Pedestrians |
| 🚲 | Cyclists / e-scooters |
| 🏍️ | Motorcycles |
| ✈️ | Aircraft / UAV |
| 🚢 | Vessels / maritime |
| 🔍 | [Live on Trajectory Trace](https://city.app.sdk-cloud.de/) |
| 📡 | Live / real-time stream |
| 🗄️ | Historical archive available |

**Sensor abbreviations:** `cam(s)` = camera(s), `lid(s)` = LiDAR(s), `rad(s)` = radar(s), `gps` = GPS/GNSS, `drone(s)` = aerial camera(s), `ais` = AIS transponder, `ads-b` = ADS-B transponder, `gtfs-rt` = GTFS Realtime feed

**License abbreviations:** `CC-BY` = Creative Commons Attribution, `CC-BY-NC` = non-commercial, `ODbL` = Open Database License, `MIT` = MIT License, `custom` = dataset-specific license (check source)

---

## Road Traffic

### Mixed Traffic (Vehicles + VRUs)

Datasets recorded from overhead / infrastructure perspective covering multiple road user classes simultaneously.

| Dataset | Description | Participants | License | Links |
|---------|-------------|--------------|---------|-------|
| **TUMDOT-MUC** | 2022 · Munich, Germany · 12 drones · 6 locations, >3 h each, 700 m continuous section along Rheinstraße, 0.08 s resolution | 🚗🚌🚶🚲🏍️ | CC-BY-NC 4.0 | [Paper](https://doi.org/10.1007/s42421-024-00101-5) · [Data](https://www.mos.ed.tum.de/en/vt/research/data-sets/tumdot-muc/) |
| **DLR Urban Traffic (DLR UT)** | 2023 · Brunswick, Germany · cams + radars · ~12 h, inner ring road | 🚗🚌🚶🚲🏍️ | CC-BY 4.0 | [Paper](https://www.techrxiv.org/doi/full/10.36227/techrxiv.174000540.08271707/v1) · [Data](https://doi.org/10.5281/zenodo.15025237) · 🔍 [View](https://city.app.sdk-cloud.de/location/24?start=20230924155955&end=20230924161205) |
| **pNEUMA** | 2018 · Athens, Greece · 10 drones · ~4 h, city center | 🚗🚌🚶🚲🏍️ | CC-BY-NC 4.0 | [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0968090X19310320?via%3Dihub) · [Data](https://open-traffic.epfl.ch/index.php/downloads/) |
| **inD** | 2020 · Germany (4 intersections) · drone · 11,500+ tracks | 🚗🚌🚶🚲 | custom (free academic) | [Paper](https://arxiv.org/abs/1911.07602) · [Data](https://levelxdata.com/ind-dataset/) |
| **rounD** | 2020 · Germany (3 roundabouts) · drone · 13,746 tracks | 🚗🚌🚶🚲🏍️ | custom (free academic) | [Paper](https://arxiv.org/abs/2011.06713) · [Data](https://levelxdata.com/round-dataset/) |
| **OpenDD** | 2020 · Germany (7 roundabouts) · drone · 84,000+ tracks | 🚗🚌🚶🚲🏍️ | CC-BY 4.0 | [Paper](https://dl.acm.org/doi/10.1145/3397536.3422207) · [Data](https://l3pilot.eu/data/opendd) |
| **INTERACTION** | 2019 · Multi-country · drone + traffic cam · ~16 locations, merges + roundabouts + intersections | 🚗🚌🚶🚲 | CC-BY-NC-SA | [Paper](https://arxiv.org/abs/1910.03088) · [Data](https://interaction-dataset.com/) |
| **CitySim** | 2023 · USA (12 locations) · drone (4K) · ~1,140 trajectories | 🚗🚌🚶🚲🏍️ | CC-BY 4.0 | [Paper](https://arxiv.org/abs/2208.11036) · [Data](https://github.com/UCF-SST-Lab/UIVeri) |
| **Ko-PER Intersection** | 2014 · Aschaffenburg, Germany · infrared cam + laser · 6 scenarios | 🚗🚶🚲 | custom | [Paper](https://ieeexplore.ieee.org/document/6957972) · [Data](https://www.uni-ulm.de/in/mrm/forschung/datensaetze/) |
| **TRAF** | 2019 · China (multiple cities) · drone · 50 sequences | 🚗🚌🚶🚲🏍️ | CC-BY-NC | [Paper](https://arxiv.org/abs/1910.03726) · [Data](https://github.com/C-C-Y/TRAF) |
| **SIND** | 2022 · Changsha, China · drone · ~14k tracks at signalized intersections | 🚗🚌🚶🚲🏍️ | custom | [Paper](https://arxiv.org/abs/2209.02297) · [Data](https://github.com/SOTIF-AVLab/SinD) |
| **Argoverse 2 Motion** | 2023 · 6 US cities · LiDAR + cam · 250,000 scenarios | 🚗🚌🚶🚲🏍️ | CC-BY-NC-SA 4.0 | [Paper](https://arxiv.org/abs/2301.00493) · [Data](https://www.argoverse.org/av2.html) |
| **nuScenes** | 2020 · Boston + Singapore · LiDAR + cam + radar · 1,000 scenes × 20 s | 🚗🚌🚶🚲🏍️ | CC-BY-NC-SA | [Paper](https://arxiv.org/abs/1929.13868) · [Data](https://www.nuscenes.org/) |
| **Waymo Open Motion** | 2021 · USA (various) · LiDAR + cam · 100,000 segments | 🚗🚌🚶🚲🏍️ | custom (non-commercial) | [Paper](https://arxiv.org/abs/2104.10133) · [Data](https://waymo.com/open/data/motion/) |
| **Lyft Level 5** | 2020 · Palo Alto, USA · LiDAR + cam · 1,118 h, 170,000 scenes | 🚗🚌🚶🚲 | custom (non-commercial) | [Paper](https://arxiv.org/abs/2104.13949) · [Data](https://self-driving.lyft.com/level5/data/) |

### Vehicles

Datasets focused on vehicle trajectories — highways, ego-vehicle recordings, and large-scale driving archives.

| Dataset | Description | Participants | License | Links |
|---------|-------------|--------------|---------|-------|
| **highD** | 2018 · Germany (A3, A9) · drone · 110,000+ tracks, 147 h | 🚗🚌 | custom (free academic) | [Paper](https://arxiv.org/abs/1810.05642) · [Data](https://levelxdata.com/highd-dataset/) |
| **exiD** | 2022 · Germany (A3, A40, A42) · drone · 69,172 tracks at highway exits | 🚗🚌 | custom (free academic) | [Paper](https://arxiv.org/abs/2204.03940) · [Data](https://levelxdata.com/exid-dataset/) |
| **NGSIM US-101 & I-80** | 2006 · California, USA · roadside cam · ~9,000 tracks | 🚗🚌 | public domain | [Docs](https://ops.fhwa.dot.gov/trafficanalysistools/ngsim.htm) · [Data](https://data.transportation.gov/Automobiles/Next-Generation-Simulation-NGSIM-Vehicle-Trajector/8ect-6jqj) |
| **Shifts** | 2022 · Multi-country · GNSS · 1M+ km, distributional shift benchmark | 🚗 | CC-BY 4.0 | [Paper](https://arxiv.org/abs/2107.07455) · [Data](https://github.com/yandex-research/shifts) |
| **KITTI** | 2012 · Karlsruhe, Germany · LiDAR + cam + GNSS · 389 sequences | 🚗🚶🚲 | custom (non-commercial) | [Website](https://www.cvlibs.net/datasets/kitti/) |
| **BDD100K** | 2020 · USA (various) · cam · 100k videos, 10 annotation tasks | 🚗🚌🚶🚲🏍️ | BSD 3-Clause | [Paper](https://arxiv.org/abs/1805.04687) · [Data](https://www.bdd100k.com/) |
| **Argoverse 1** | 2019 · Pittsburgh + Miami · LiDAR + cam + HD map · 324,557 sequences | 🚗🚌🚶🚲 | CC-BY-NC-SA 4.0 | [Paper](https://arxiv.org/abs/1911.02620) · [Data](https://www.argoverse.org/av1.html) |
| **nuPlan** | 2023 · USA + Singapore · LiDAR + cam · 1,500 h driving | 🚗🚌🚶🚲 | CC-BY-NC-SA | [Paper](https://arxiv.org/abs/2106.11810) · [Data](https://www.nuscenes.org/nuplan) |
| **Waymo Open Perception** | 2020 · USA · LiDAR + cam · 2,030 segments × 20 s | 🚗🚌🚶🚲🏍️ | custom (non-commercial) | [Paper](https://arxiv.org/abs/1912.04838) · [Data](https://waymo.com/open/data/perception/) |

### VRUs (Pedestrians & Cyclists)

Datasets focused on pedestrian and cyclist trajectories, including indoor crowds and intention estimation.

| Dataset | Description | Participants | License | Links |
|---------|-------------|--------------|---------|-------|
| **ETH Pedestrian** | 2009 · Zurich, Switzerland · overhead cam · 750 pedestrians, 2 scenes | 🚶 | custom (academic) | [Paper](https://ieeexplore.ieee.org/document/5206559) · [Data](https://icu.ee.ethz.ch/research/datsets.html) |
| **UCY Crowds** | 2007 · Cyprus / Israel · cam · 786 pedestrians, 3 scenes | 🚶 | custom (academic) | [Data](https://graphics.cs.ucy.ac.cy/research/downloads/crowd-data) |
| **Stanford Drone (SDD)** | 2016 · Stanford, USA · drone · 19,000+ tracks across 8 campus scenes | 🚶🚲🚗🏍️ | custom (academic) | [Website](https://cvgl.stanford.edu/projects/uav_data/) |
| **TrajNet++** | 2021 · Multi-source · cam + drone · benchmark aggregating ETH, UCY + others | 🚶 | CC-BY | [Paper](https://arxiv.org/abs/2007.03639) · [Data](https://www.aicrowd.com/challenges/trajnet-a-trajectory-forecasting-challenge) |
| **PIE** | 2019 · Toronto, Canada · in-vehicle cam · 293,000 frames, 1,842 pedestrians with intention labels | 🚶 | custom (non-commercial) | [Paper](https://openaccess.thecvf.com/content_ICCV_2019/html/Rasouli_PIE_A_Large-Scale_Dataset_and_Models_for_Pedestrian_Intention_Estimation_ICCV_2019_paper.html) · [Data](http://data.nvision2.eecs.yorku.ca/PIE_dataset/) |
| **ATC Shopping Center** | 2013 · Osaka, Japan · 3D range sensors · ~100k tracks over 92 days | 🚶 | CC-BY | [Paper](https://doi.org/10.1007/s10514-013-9348-y) · [Data](https://irc.atr.jp/crest2010_HRI/ATC_dataset/) |

---

## Aerial (UAV / Aircraft)

| Dataset | Year | Domain | Sensors | Participants | Size | License | Links |
|---------|------|--------|---------|--------------|------|---------|-------|
| **OpenSky Network** | ongoing | Global airspace | ADS-B | ✈️ | billions of state vectors, live + historical | CC-BY | [Paper](https://doi.org/10.1007/978-3-030-00916-8_17) · [Data](https://opensky-network.org/data/impala) |
| **FlightAware** | ongoing | Global | ADS-B | ✈️ | commercial, partial free tier | custom | [Data](https://flightaware.com/commercial/firehose/) |
| **ADS-B Exchange** | ongoing | Global | ADS-B | ✈️ | raw unfiltered data | custom (free) | [Data](https://www.adsbexchange.com/data/) |
| **DroneSim / MAVBench** | 2018 | Simulated | sim | ✈️ (UAV) | benchmark suite | MIT | [Paper](https://arxiv.org/abs/1905.07165) · [Data](https://github.com/harvard-edge/MAVBench) |
| **VisDrone** | 2021 | China (multiple cities) | drone cam | 🚗🚌🚶🚲🏍️ | 288 video clips from drone view | custom (non-commercial) | [Paper](https://arxiv.org/abs/2001.06303) · [Data](https://github.com/VisDrone/VisDrone-Dataset) |

---

## Maritime

| Dataset | Year | Domain | Sensors | Participants | Size | License | Links |
|---------|------|--------|---------|--------------|------|---------|-------|
| **MarineC / Danish Maritime Authority AIS** | ongoing | Denmark coastal | AIS | 🚢 | full AIS history since 2006 | custom (free) | [Data](https://www.dma.dk/safety-at-sea/navigational-information/ais-data) |
| **Marine Cadastre (US)** | ongoing | USA coastal waters | AIS | 🚢 | annual CSV archives | public domain | [Data](https://marinecadastre.gov/ais/) |
| **OpenSea / AIS Live** | ongoing | Global | AIS | 🚢 | real-time + historical | custom | [Data](https://www.marinetraffic.com/en/ais-api-services) |
| **GeoLife GPS Trajectories** | 2012 | Beijing, China | gnss | 🚶🚲🚗🚢 | 182 users, 5 years, multi-modal | MS Research (open) | [Paper](https://www.microsoft.com/en-us/research/publication/geolife-gps-trajectory-dataset-user-guide/) · [Data](https://www.microsoft.com/en-us/research/project/geolife-building-social-networks-using-human-location-history/) |

---

## Live Data Streams

Real-time trajectory feeds you can subscribe to or query today. Unlike static datasets, these provide continuous position updates — ideal for live dashboards, streaming analytics, and platforms that handle both historical and real-time data (such as [Trajectory Trace](https://city.app.sdk-cloud.de/)).

### Public Transport (GTFS-RT)

Many transit authorities publish vehicle positions in [GTFS Realtime](https://gtfs.org/realtime/) format — a standardized protobuf feed with live bus, tram, metro, and train locations.

| Feed | Region | Participants | Update Rate | License | Links |
|------|--------|--------------|-------------|---------|-------|
| **transport.rest (VBB Berlin-Brandenburg)** | Berlin, Germany | 🚌🚇🚊🚆 | ~10 s | CC-BY 4.0 | 📡 [API](https://v6.vbb.transport.rest/) · [Docs](https://www.vbb.de/vbb-services/api-open-data/api/) |
| **HSL Helsinki** | Finland | 🚌🚇🚊 | ~5 s | CC-BY 4.0 | 📡 [API](https://digitransit.fi/en/developers/) · [MQTT](https://digitransit.fi/en/developers/apis/4-realtime-api/vehicle-positions/) |
| **Transport for London (TfL)** | London, UK | 🚌🚇🚊 | ~30 s | custom (free registration) | 📡 [API](https://api.tfl.gov.uk/) · [Docs](https://api-portal.tfl.gov.uk/) |
| **Deutsche Bahn Open Data** | Germany | 🚌🚆 | real-time | custom (free) | 📡 [API](https://developer.deutschebahn.com/) · [Portal](https://data.deutschebahn.com/) |
| **SNCF Open Data** | France | 🚆🚌 | real-time | custom (free) | 📡 [API](https://data.sncf.com/explore/dataset/api-temps-reel-transports/) |
| **511 SF Bay** | San Francisco Bay Area, USA | 🚌🚇🚊 | ~15 s | custom (free) | 📡 [API](https://511.org/open-data/transit) |
| **MTA New York** | New York, USA | 🚌🚇🚆 | ~30 s | custom (free) | 📡 [API](https://api.mta.info/) |
| **transit.land** | Global aggregator | 🚌🚇🚊🚆 | varies | ODbL | 📡 [Website](https://www.transit.land/) · [API](https://www.transit.land/documentation) |
| **The Mobility Database** | Global aggregator | 🚌🚇🚊🚆 | varies | CC-BY | 📡 [Website](https://database.mobilitydata.org/) |

> **Tip:** [The Mobility Database](https://database.mobilitydata.org/) catalogs 1,000+ GTFS and GTFS-RT feeds globally — the best single starting point for public transport streams worldwide.

### Maritime (AIS Streams)

| Feed | Coverage | Participants | Protocol | License | Links |
|------|----------|--------------|----------|---------|-------|
| **AISstream.io** | Global | 🚢 all vessel types | WebSocket (JSON) | custom (free tier) | 📡 [Website](https://aisstream.io/) · [Docs](https://aisstream.io/documentation) |
| **aisHub** | Global | 🚢 | REST, WebSocket | custom (free with data sharing) | 📡 [Website](https://www.aishub.net/) |
| **Kystverket AIS Norway** | Norwegian waters | 🚢 | REST + WebSocket | NLOD (open government) | 📡 [API](https://www.kystverket.no/en/navigation-and-monitoring/ais/access-to-ais-data/) |
| **Danish Maritime Authority AIS** | Danish waters + global | 🚢 | REST / FTP | custom (free) | 📡 🗄️ [Data](https://www.dma.dk/safety-at-sea/navigational-information/ais-data) |
| **Marine Cadastre (US)** | US coastal | 🚢 | REST archive | public domain | 🗄️ [Data](https://marinecadastre.gov/ais/) |

### Aviation (ADS-B Streams)

| Feed | Coverage | Participants | Protocol | License | Links |
|------|----------|--------------|----------|---------|-------|
| **OpenSky Network** | Global | ✈️ | REST / WebSocket / Impala SQL | CC-BY (research) | 📡 🗄️ [Website](https://opensky-network.org/) · [API](https://opensky-network.org/apidoc/) |
| **ADS-B Exchange** | Global | ✈️ (unfiltered) | REST / WebSocket | custom (free) | 📡 [Website](https://www.adsbexchange.com/data/) |
| **ADSB.lol** | Global | ✈️ | REST / JSON | CC-BY (open) | 📡 [Website](https://adsb.lol/) · [API](https://api.adsb.lol/) |
| **Flightradar24 API** | Global | ✈️ | REST | commercial (limited free) | 📡 [API](https://www.flightradar24.com/blog/flightradar24-api/) |
| **FlightAware AeroAPI** | Global | ✈️ | REST | commercial (free tier) | 📡 [API](https://www.flightaware.com/commercial/aeroapi/) |

### Road Traffic (Open Feeds)

| Feed | Region | Participants | Protocol | License | Links |
|------|--------|--------------|----------|---------|-------|
| **MDM Mobilithek** | Germany | 🚗🚌🚲 | REST / MQTT | open government | 📡 [Portal](https://mobilithek.info/) |
| **Datex II / NDW** | Netherlands | 🚗🚌 (loop detectors + floating car) | REST / XML | custom (free) | 📡 [Portal](https://www.ndw.nu/pagina/en/11/open_data) |
| **data.gouv.fr traffic** | France | 🚗 | REST | Licence Ouverte 2.0 | 📡 [Portal](https://transport.data.gouv.fr/) |
| **Oslo kommune traffic** | Oslo, Norway | 🚗🚲 | REST (JSON) | NLOD | 📡 [Portal](https://www.vegvesen.no/en/traffic/traffic-information/traffic-data-api/) |

---

## Benchmarks & Challenges

| Name | Domain | Task | Links |
|------|--------|------|-------|
| **TrajNet++** | Pedestrian | Trajectory forecasting | [Website](https://trajnet.epfl.ch/) |
| **Waymo Motion Prediction Challenge** | Road traffic | Multi-agent motion prediction | [Website](https://waymo.com/open/challenges/2024/motion-prediction/) |
| **Argoverse Motion Forecasting** | Road traffic | Single/multi-agent forecasting | [Website](https://eval.ai/web/challenges/challenge-page/454/overview) |
| **nuScenes Prediction** | Road traffic | Vehicle + pedestrian prediction | [Website](https://www.nuscenes.org/prediction) |
| **INTERACTION Prediction** | Road traffic | Interactive multi-agent | [Website](https://interaction-dataset.com/prediction-benchmark) |
| **VisDrone Challenge** | Aerial view | Detection + tracking | [Website](https://github.com/VisDrone/VisDrone-Dataset) |

---

## See Data in Action

[![Trajectory Trace](https://img.shields.io/badge/Trajectory%20Trace-Live%20Platform-blue?style=for-the-badge)](https://city.app.sdk-cloud.de/)

[**Trajectory Trace**](https://city.app.sdk-cloud.de/) is an open platform for traffic trajectory data management, visualization, and analysis. A key design goal is the **seamless combination of historical archives and live streaming feeds** in a single interface — replay a research dataset alongside a live GTFS-RT bus feed or real-time AIS stream. Datasets and feeds marked with 🔍 are publicly accessible there — no account required. Features include:

- 3D map navigation with free viewpoint control
- **Live streaming + historical replay in one unified view**
- Connect GTFS-RT, MQTT, or custom feeds alongside static datasets
- Trajectory filtering by road user class (vehicle, pedestrian, cyclist, …)
- Traffic volume histograms and heat maps
- Event detection and scenario analysis
- GraphQL API for custom queries

→ [Try the live demo](https://city.app.sdk-cloud.de/) · [Read the docs](https://city.app.sdk-cloud.de/docs/en/) · [API reference](https://city.app.sdk-cloud.de/api/graphql)

---

## Contributing

Contributions are very welcome! Please read the [contributing guidelines](CONTRIBUTING.md) before submitting a PR.

**Quick checklist for adding a dataset or live feed:**
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
