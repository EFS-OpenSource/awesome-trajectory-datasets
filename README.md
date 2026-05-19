# Awesome Trajectory Datasets [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

A curated list of open datasets containing road traffic trajectories (vehicles and vulnerable road users), with a focus on large-scale, real-world data in global coordinate formats, suitable for traffic analysis, motion prediction, and autonomous systems research. 
- Several datasets below are already integrated and publicly explorable on [**Trajectory Trace**](https://city.app.sdk-cloud.de/). Look for the 🔍 badge. 
- Data access variates: It can be "Direct Download", "Registration Required" or "On Request"


## Contents

- [Mixed Traffic](#mixed-traffic-️-)
- [Vehicles](#vehicles-️)
- [Contributing](#contributing)
- [Related Lists](#related-lists)
- [Licensce](#license)


## Mixed Traffic 🚗🚌🚚🏍️ 🚶🚲🛴

- **[CitySim](https://github.com/UCF-SST-Lab/UCF-SST-CitySim1-Dataset)** - A Drone-Based Vehicle Trajectory Dataset for Safety Oriented Research and Digital Twins (2023): 12 locations (USA) · drone · ~1,140 trajectories · CC-BY-NC 4.0 · [Data on Request](https://github.com/UCF-SST-Lab/UCF-SST-CitySim1-Dataset/tree/main/data) · [Paper](https://arxiv.org/abs/2208.11036)

- **[DLR UT](https://zenodo.org/records/15754836)** - **DLR** **U**rban **T**raffic (2023):  Brunswick (Germany) · stereo cams · 12 h, inner ring road · trajectories, traffic lights, local weather, air quality, road conditions · CC-BY 4.0 · [Direct Download](https://zenodo.org/records/15754836) · [Paper](https://www.techrxiv.org/doi/full/10.36227/techrxiv.174000540.08271707/v1) · [🔍](https://city.app.sdk-cloud.de/location/24?start=20230924155955&end=20230924161205)

- **[DrivIng](https://github.com/cvims/DrivIng)** - A Large-Scale Multimodal Driving Dataset with Full Digital Twin Integration (2025): Ingolstadt (Germany) · cams + lidars 18km ego vehicle · CC BY-NC-ND 4.0 · [Direct Download](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/VBZKDY) · [Paper](https://arxiv.org/pdf/2601.15260)

- **[GeoLife](https://www.microsoft.com/en-us/research/publication/geolife-gps-trajectory-dataset-user-guide/)** - Geolife GPS trajectory dataset (2012): · Beijing (China) · GNSS · 182 users, 5 years, multi-modal · MSR-LA (NC) · [Direct Download](https://www.microsoft.com/en-us/download/details.aspx?id=52367) · [User Guide](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/User20Guide-1.2.pdf)

- **[INTERACTION](https://interaction-dataset.com/)** - **INTER**national, **A**dversarial and **C**ooperative mo**TION** Dataset (2019): Multi-country · drone + traffic cam · ~16 locations, merges + roundabouts + intersections · Custom License (NC) · [Data On Request](https://docs.google.com/forms/d/e/1FAIpQLSdX1XM14idrtHEd9HIiUMCCbiiQZlvwJTaixY8U4PfXCqJ5Zg/viewform) · [Paper](https://arxiv.org/abs/1910.03088) · [GIT](https://github.com/interaction-dataset/interaction-dataset)

- **[OpenDD](https://l3pilot.eu/data/opendd.html)** - A Large-Scale Roundabout Drone Dataset (2020): 7 roundabouts (Germany) · drone · 84,000+ tracks · CC-BY-ND 4.0 · [Direct Download](https://l3pilot.eu/data/opendd.html#downloads) · [Paper](https://arxiv.org/abs/2007.08463) 

- **[SinD](https://github.com/SOTIF-AVLab/SinD)** - A Drone Dataset at Signalized Intersection in China (2022): Changsha (China) · drone · ~14k tracks at signalized intersections · CC0 1.0 Universal · Demo data in Repo, [Full Data on Request](https://github.com/SOTIF-AVLab/SinD#access) · [Paper](https://arxiv.org/abs/2209.02297)

- **[TUMDOT-ING](https://www.mos.ed.tum.de/en/vt/forschung/datensaetze/tumdot-ing/)** - **T**rajectories from **U**rban **M**ultimodal **D**rone **O**bservations of **T**raffic **Ing**olstadt (2023): Ingolstadt (Germany) · 6 drones · 3 locations, 3 days, ~3 h each · covers the high definition testfield Ingolstadt (see UrbanIng-V2X) · CC-BY-NC 4.0 · [Direct Download](https://syncandshare.lrz.de/getlink/fiCe4FwFqAmwnPsdR83LxY/) · [🔍](https://city.app.sdk-cloud.de/location/39)

- **[TUMDOT-MUC](https://www.mos.ed.tum.de/en/vt/research/data-sets/tumdot-muc/)** - **T**rajectories from **U**rban **M**ultimodal **D**rone **O**bservations of **T**raffic **Mu**ni**c**h (2022): Munich (Germany) · 12 drones · 6 locations, >3 h each, 700 m continuous section along Rheinstraße, 0.08 s resolution · CC-BY-NC 4.0 · [Direct Download](https://syncandshare.lrz.de/getlink/fiD1PMw4bRxbgWggvTtTTJ/) · [Paper](https://doi.org/10.1007/s42421-024-00101-5) · [🔍](https://city.app.sdk-cloud.de/location/12)

- **[UrbanIng-V2X](https://thi-ad.github.io/urbaning/)** - A Large-Scale Multi-Vehicle, Multi-Infrastructure Dataset Across Multiple Intersections for Cooperative Perception (2025): Ingolstadt (Germany) · LiDAR + RGB cam + thermal cam + GNSS/IMU · V2X cooperative perception at 3 intersections, 34 sequences × 20 s, ~712k annotated instances at 10 Hz · CC-BY-NC-ND 4.0 · [Direct Download](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/A9LPY7) · [GIT](https://github.com/thi-ad/UrbanIng-V2X) · [Paper](https://arxiv.org/abs/2510.23478) · [🔍](https://city.app.sdk-cloud.de/location/30?start=20241127145920&end=20241127150000)


## Vehicles 🚗🚌🚚🏍️

- **[Automatum Data](https://automatum-data.com/de#dataset)**: Bavaria (Germany) · drone · 30 h · CC BY-ND / demo · [Data On Request](https://automatum-data.com/de/get-free-dataset) · [Paper](https://automatumdata.blob.core.windows.net/opendataset/IV21_Automatum.Data.eng.pdf) · [🔍highway](https://city.app.sdk-cloud.de/location/29) · [🔍roundabout](https://city.app.sdk-cloud.de/location/32?start=20260222110000&end=20260222110453)

- **[DLR HT](https://zenodo.org/records/18540070)** - **DLR** **H**ighway **T**raffic (2024): Brunswick (Germany) · Test Bed Lower Saxony, trajectory data + weather + road condition · CC-BY-NC-SA 4.0 · [Direct Download](https://zenodo.org/records/18540070) · [Paper](https://doi.org/10.1109/IAVVC61942.2025.11219599) · [🔍](https://city.app.sdk-cloud.de/location/40)

- **[MiTra](https://opara.zih.tu-dresden.de/items/68482417-ddc5-40ac-885a-83124bd459e8)** - **Mi**lan **Tra**jectories (2024): Milan (Italy) · 900 m section of the A50 urban freeway · 135 min, using 6 drones · CC BY 4.0 · [Direct Download](https://opara.zih.tu-dresden.de/items/68482417-ddc5-40ac-885a-83124bd459e8) · [Paper](https://www.nature.com/articles/s41597-025-05472-0) · [GIT](https://github.com/ankitiitm/MiTra)

- **[NGSIM](https://data.transportation.gov/Automobiles/Next-Generation-Simulation-NGSIM-Vehicle-Trajector/8ect-6jqj)** - **N**ext **G**eneration **Sim**ulation Vehicle Trajectories and Supporting Data (2006): California (USA) · roadside cam · ~9,000 tracks · CC BY-SA 3.0 · [Direct Download](https://data.transportation.gov/Automobiles/Next-Generation-Simulation-NGSIM-Vehicle-Trajector/8ect-6jqj/data_preview) · [Docs](https://ops.fhwa.dot.gov/trafficanalysistools/ngsim.htm) · [🔍](https://city.app.sdk-cloud.de/location/41)

- **[pNEUMA](https://open-traffic.epfl.ch/)** - Open large-scale dataset of naturalistic trajectories of half a million vehicles (2018): Athens (Greece) · 10 drones · 4 days, each ~4 h, city center · CC-BY-NC 4.0 · [Direct Download](https://open-traffic.epfl.ch/index.php/downloads/) · [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0968090X19310320?via%3Dihub) · [🔍](https://city.app.sdk-cloud.de/location/38)

- **[SWIFTraj](https://swiftraj.com/index.html)** - **Sw**arm **I**ntelligence **F**reeway–Urban **Traj**ectories Dataset (2022): Nanjing (China) · 16 drones · 4.5km Hurong Expressway, 4 hours · CC BY 4.0 · [Data on Request](https://zenodo.org/records/18616239) · [Paper](https://arxiv.org/abs/2602.22563) · [GIT](https://github.com/YuHan-Research-Group-SEU/trajectory-data-tools)


## Contributing

Contributions are very welcome! Please read the [contributing guidelines](CONTRIBUTING.md) before submitting a PR.

Quick checklist for adding a dataset or live feed:
- [ ] The data is publicly accessible (free download, registration, or free-tier API)
- [ ] It contains trajectory data (x/y/t positions over time)
- [ ] A citable source (paper, DOI, or official website) exists
- [ ] The license is clearly stated
- [ ] For live feeds: the protocol and update rate are documented

If your dataset shall be integrated into [Trajectory Trace](https://city.app.sdk-cloud.de/), mention it in the PR - we'll integrate it and add the 🔍 badge.


## Related Lists

- [Awesome-Interaction-Aware-Trajectory-Prediction](https://github.com/jiachenli94/Awesome-Interaction-aware-Trajectory-Prediction)
- [awesome-public-datasets#transportation](https://github.com/awesomedata/awesome-public-datasets#transportation)
- [OpenTraj](https://github.com/crowdbotp/OpenTraj)


## License

This Source Code Form is subject to the terms of the Apache License 2.0. If a copy of the APL2 was not distributed with this file, You can obtain one at [https://www.apache.org/licenses/LICENSE-2.0.txt](https://www.apache.org/licenses/LICENSE-2.0.txt).
