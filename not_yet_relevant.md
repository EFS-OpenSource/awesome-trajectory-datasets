Covers both **historical datasets** (downloadable archives) and **live data streams** (real-time feeds you can connect to today).

- [Vulnerable Road Users (VRUs)](#vulnerable-road-users-vrus-)
- [Aerial (UAV / Aircraft)](#aerial-uav--aircraft)
- [Maritime](#maritime)
- [Live Data Streams](#live-data-streams)
  - [Public Transport (GTFS-RT)](#public-transport-gtfs-rt)
  - [Maritime (AIS Streams)](#maritime-ais-streams)
  - [Aviation (ADS-B Streams)](#aviation-ads-b-streams)
  - [Road Traffic (Open Feeds)](#road-traffic-open-feeds)
- [Benchmarks & Challenges](#benchmarks--challenges)



## Road Traffic
Too commercial? -> Maybe aggregate to one or two entries 
- **[inD](https://levelxdata.com/ind-dataset/)** - 2020 · Germany (4 intersections) · drone · 11,500+ tracks · custom (free academic) · [Paper](https://arxiv.org/abs/1911.07602)  -> mixed
- **[rounD](https://levelxdata.com/round-dataset/)** - 2020 · Germany (3 roundabouts) · drone · 13,746 tracks · custom (free academic) · [Paper](https://arxiv.org/abs/2011.06713)  -> vehicles
- **[highD](https://levelxdata.com/highd-dataset/)** - 2018 · Germany (A3, A9) · drone · 110,000+ tracks, 147 h · custom (free academic) · [Paper](https://arxiv.org/abs/1810.05642)   -> vehicles
- **[exiD](https://levelxdata.com/exid-dataset/)** - 2022 · Germany (A3, A40, A42) · drone · 69,172 tracks at highway exits · custom (free academic) · [Paper](https://arxiv.org/abs/2204.03940)  -> vehicles
- [uniD](https://levelxdata.com/unid-dataset/)  -> mixed

Too much focus on raw data
- **[Argoverse 1](https://www.argoverse.org/av1.html)** - 2019 · Pittsburgh + Miami · LiDAR + cam + HD map · 324,557 sequences · CC-BY-NC-SA 4.0 · [Paper](https://arxiv.org/abs/1911.02620)
- **[Argoverse 2 Motion](https://www.argoverse.org/av2.html)** - 2023 · 6 US cities · LiDAR + cam · 250,000 scenarios · CC-BY-NC-SA 4.0 · [Paper](https://arxiv.org/abs/2301.00493)
- **[nuScenes](https://www.nuscenes.org/)** - 2020 · Boston + Singapore · LiDAR + cam + radar · 1,000 scenes × 20 s · CC-BY-NC-SA · [Paper](https://arxiv.org/abs/1929.13868)
- **[nuPlan](https://www.nuscenes.org/nuplan)** - 2023 · USA + Singapore · LiDAR + cam · 1,500 h driving · CC-BY-NC-SA · [Paper](https://arxiv.org/abs/2106.11810)
- **[Waymo Open Motion](https://waymo.com/open/data/motion/)** - 2021 · USA (various) · LiDAR + cam · 100,000 segments · custom (non-commercial), Registration via Google required · [Paper](https://arxiv.org/abs/2104.10133)
- **[Waymo Open Perception](https://waymo.com/open/data/perception/)** - 2020 · USA · LiDAR + cam · 2,030 segments × 20 s · custom (non-commercial) · [Paper](https://arxiv.org/abs/1912.04838)
- **[BDD100K](https://www.bdd100k.com/)** - 2020 · USA (various) · cam · 100k videos, 10 annotation tasks · BSD 3-Clause · [Paper](https://arxiv.org/abs/1805.04687)
- **[VisDrone](https://github.com/VisDrone/VisDrone-Dataset)** - 2021 · China (multiple cities) · drone cam · 288 video clips · custom (non-commercial) · [Paper](https://arxiv.org/abs/2001.06303)
- **[Shifts](https://github.com/yandex-research/shifts)** - 2022 · Multi-country · GNSS · 1M+ km, distributional shift benchmark · CC-BY 4.0 · [Paper](https://arxiv.org/abs/2107.07455)
- **[Ko-PER Intersection](https://www.uni-ulm.de/in/mrm/forschung/datensaetze/)** - 2014 · Aschaffenburg, Germany · infrared cam + laser · 6 scenarios, 6:28 minutes · No Licensce mentioned, Direct Download · [Paper](https://www.uni-ulm.de/fileadmin/website_uni_ulm/iui.inst.110/Bilder/Forschung/Datensaetze/20141010_DatasetDocumentation.pdf)
- **[L3Pilot Open Data](https://l3pilot.eu/data.html)

Not accessible
- **[Lyft Level 5](https://self-driving.lyft.com/level5/data/)** - 2020 · Palo Alto, USA · LiDAR + cam · 1,118 h, 170,000 scenes · custom (non-commercial) · [Paper](https://arxiv.org/abs/2104.13949)
- **[Stanford Drone (SDD)](https://cvgl.stanford.edu/projects/uav_data/)** - 2016 · Stanford, USA · drone · 19,000+ tracks across 8 campus scenes · CC BY-NC-SA 3.0, Direct Download -> Link is not working right now
- **[ETH Pedestrian](https://icu.ee.ethz.ch/research/datsets.html)** - 2009 · Zurich, Switzerland · overhead cam · 750 pedestrians, 2 scenes · custom (academic) · [Paper](https://ieeexplore.ieee.org/document/5206559)

## Vulnerable Road Users (VRUs) 🚶🚲🛴
No description / Crowds (no gps data)
- **[UCY Crowds](https://graphics.cs.ucy.ac.cy/research/downloads/crowd-data)** - 2007 · Cyprus / Israel · cam · 786 pedestrians, 3 scenes · custom (academic)
- **[TrajNet++](https://www.aicrowd.com/challenges/trajnet-a-trajectory-forecasting-challenge)** - 2021 · Multi-source · cam + drone · benchmark aggregating ETH, UCY + others · CC-BY · [Paper](https://arxiv.org/abs/2007.03639)
- **[PIE](http://data.nvision2.eecs.yorku.ca/PIE_dataset/)** - 2019 · Toronto, Canada · in-vehicle cam · 293,000 frames, 1,842 pedestrians with intention labels · custom (non-commercial) · [Paper](https://openaccess.thecvf.com/content_ICCV_2019/html/Rasouli_PIE_A_Large-Scale_Dataset_and_Models_for_Pedestrian_Intention_Estimation_ICCV_2019_paper.html)
- **[ATC Shopping Center](https://irc.atr.jp/crest2010_HRI/ATC_dataset/)** - 2013 · Osaka, Japan · 3D range sensors · ~100k tracks over 92 days · CC-BY · [Paper](https://doi.org/10.1007/s10514-013-9348-y)

Not georeferenced
- SDD https://github.com/crowdbotp/OpenTraj/blob/master/datasets/SDD

No real gps tracks
- [Bicycle Driving Behaviour in Germany: A Driving Parameter Dataset Across 100 Cities based on CITY CYCLING GPS trajectories](https://opara.zih.tu-dresden.de/items/5cd85d7f-e86b-496d-98fb-21c509ba72ef) -> Only start and end gps data -> But maybe partner with https://www.stadtradeln.de/ (they should have real gps data)


## Aerial (UAV / Aircraft) ✈️

| Dataset | Year | Domain | Sensors | Participants | Size | License | Links |
|---------|------|--------|---------|--------------|------|---------|-------|
| **OpenSky Network** | ongoing | Global airspace | ADS-B | billions of state vectors, live + historical | CC-BY | [Paper](https://doi.org/10.1007/978-3-030-00916-8_17) · [Data](https://opensky-network.org/data/impala) |
| **FlightAware** | ongoing | Global | ADS-B | commercial, partial free tier | custom | [Data](https://flightaware.com/commercial/firehose/) |
| **ADS-B Exchange** | ongoing | Global | ADS-B | raw unfiltered data | custom (free) | [Data](https://www.adsbexchange.com/data/) |
| **DroneSim / MAVBench** | 2018 | Simulated | sim | benchmark suite | MIT | [Paper](https://arxiv.org/abs/1905.07165) · [Data](https://github.com/harvard-edge/MAVBench) |


---

## Maritime 🚢

| Dataset | Year | Domain | Sensors | Participants | Size | License | Links |
|---------|------|--------|---------|--------------|------|---------|-------|
| **MarineC / Danish Maritime Authority AIS** | ongoing | Denmark coastal | AIS | full AIS history since 2006 | custom (free) | [Data](https://www.dma.dk/safety-at-sea/navigational-information/ais-data) |
| **Marine Cadastre (US)** | ongoing | USA coastal waters | AIS | annual CSV archives | public domain | [Data](https://marinecadastre.gov/ais/) |
| **OpenSea / AIS Live** | ongoing | Global | AIS | real-time + historical | custom | [Data](https://www.marinetraffic.com/en/ais-api-services) |

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

[Trajectory Trace](https://city.app.sdk-cloud.de/) is an open platform for traffic trajectory data management, visualization, and analysis. A key design goal is the seamless combination of historical archives and live streaming feeds in a single interface - replay a research dataset alongside a live GTFS-RT bus feed or real-time AIS stream. Datasets and feeds marked with 🔍 are publicly accessible there - no account required. Features include:

- 3D map navigation with free viewpoint control
- Live streaming + historical replay in one unified view
- Connect GTFS-RT, MQTT, or custom feeds alongside static datasets
- Trajectory filtering by road user class (vehicle, pedestrian, cyclist, …)
- Traffic volume histograms and heat maps
- Event detection and scenario analysis
- GraphQL API for custom queries

→ [Try the live demo](https://city.app.sdk-cloud.de/) · [Read the docs](https://city.app.sdk-cloud.de/docs/en/) · [API reference](https://city.app.sdk-cloud.de/api/graphql)

---