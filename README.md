# Awesome Trajectory Datasets [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

A curated list of open datasets containing road traffic trajectories (vehicles and vulnerable road users), with a focus on large-scale, real-world data in global coordinate formats, suitable for traffic analysis, motion prediction, and autonomous systems research.

- See data in action: Several datasets and live feeds below are already integrated and publicly explorable on [**Trajectory Trace**](https://city.app.sdk-cloud.de/). Look for the 🔍 badge.

- Sometimes Info and Data are not in the same place. In that case, name leads to Info and Data is linked seperately.

- Data access variates: It can be "Direct Download", "Registration Required" or "On Request"


## Contents

- [Mixed Traffic](#mixed-traffic-️-)
- [Vehicles](#vehicles-️)
- [Vulnerable Road Users (VRUs)](#vulnerable-road-users-vrus-)
- [See Data in Action](#see-data-in-action)
- [Contributing](#contributing)
- [Related Lists](#related-lists)
- [Licensce](#license)


## Mixed Traffic 🚗🚌🚚🏍️ 🚶🚲🛴

- **[CitySim](https://github.com/UCF-SST-Lab/UCF-SST-CitySim1-Dataset)** - 2023 · USA (12 locations) · drone (4K) · ~1,140 trajectories · CC-BY-NC 4.0, On Request · [Paper](https://arxiv.org/abs/2208.11036)

- **[DLR Urban Traffic (DLR UT)](https://zenodo.org/records/15025237)** - 2023 · Brunswick, Germany · cams + radars · 12 h, inner ring road with traffic lights · CC-BY 4.0, Direct Download · [Paper](https://www.techrxiv.org/doi/full/10.36227/techrxiv.174000540.08271707/v1) · [🔍](https://city.app.sdk-cloud.de/location/24?start=20230924155955&end=20230924161205)

- **[DrivIng](https://github.com/cvims/DrivIng)** - 2025 · Ingolstadt, Germany · cams + lidars 18km ego vehicle · CC BY-NC-ND 4.0, Direct Download · [Paper](https://arxiv.org/pdf/2601.15260)

- **[GeoLife GPS Trajectories](https://www.microsoft.com/en-us/research/publication/geolife-gps-trajectory-dataset-user-guide/)** - 2012 · Beijing, China · GNSS · 182 users, 5 years, multi-modal · MSR-LA (NC), Direct Download · [User Guide](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/User20Guide-1.2.pdf)

- **[Ko-PER Intersection](https://www.uni-ulm.de/in/mrm/forschung/datensaetze/)** - 2014 · Aschaffenburg, Germany · infrared cam + laser · 6 scenarios, 6:28 minutes · No Licensce mentioned, Direct Download · [Paper](https://www.uni-ulm.de/fileadmin/website_uni_ulm/iui.inst.110/Bilder/Forschung/Datensaetze/20141010_DatasetDocumentation.pdf)

- **[INTERACTION](https://interaction-dataset.com/)** - 2019 · Multi-country · drone + traffic cam · ~16 locations, merges + roundabouts + intersections · Custom License (NC), On Request · [Paper](https://arxiv.org/abs/1910.03088) · [GIT](https://github.com/interaction-dataset/interaction-dataset)

- **[OpenDD](https://l3pilot.eu/data/opendd.html)** - 2020 · Germany (7 roundabouts) · drone · 84,000+ tracks · CC-BY-ND 4.0, Direct Download · [Paper](https://arxiv.org/abs/2007.08463)

- **[SIND](https://github.com/SOTIF-AVLab/SinD)** - 2022 · Changsha, China · drone · ~14k tracks at signalized intersections · Custom (just academic), On Request · [Paper](https://arxiv.org/abs/2209.02297)

- **[TUMDOT-ING](https://www.mos.ed.tum.de/en/vt/forschung/datensaetze/tumdot-ing/)** - 2023 · Ingolstadt, Germany · 6 drones · 3 locations, 3 days, ~3 h each, covers the high definition testfield Ingolstadt (see UrbanIng-V2X), 0.03 s resolution · CC-BY-NC 4.0, Direct Download · [🔍](https://city.app.sdk-cloud.de/location/39)

- **[TUMDOT-MUC](https://www.mos.ed.tum.de/en/vt/research/data-sets/tumdot-muc/)** - 2022 · Munich, Germany · 12 drones · 6 locations, >3 h each, 700 m continuous section along Rheinstraße, 0.08 s resolution · CC-BY-NC 4.0, Direct Download · [Paper](https://doi.org/10.1007/s42421-024-00101-5) · [🔍](https://city.app.sdk-cloud.de/location/12)

- **[UrbanIng-V2X](https://thi-ad.github.io/urbaning/)** - 2025 · Ingolstadt, Germany · LiDAR + RGB cam + thermal cam + GNSS/IMU · V2X cooperative perception at 3 intersections, 34 sequences × 20 s, ~712k annotated instances at 10 Hz · CC-BY-NC-ND 4.0, Direct Download · [GIT](https://github.com/thi-ad/UrbanIng-V2X) · [Paper](https://arxiv.org/abs/2510.23478) · [Data](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/A9LPY7) · [🔍](https://city.app.sdk-cloud.de/location/30?start=20241127145920&end=20241127150000)


## Vehicles 🚗🚌🚚🏍️

- **[Automatum](https://automatum-data.com/de#dataset)** - Germany (Bavaria) · drone · 30 h · CC BY-ND / demo, On Request · [Paper](https://automatumdata.blob.core.windows.net/opendataset/IV21_Automatum.Data.eng.pdf) · [🔍](https://city.app.sdk-cloud.de/location/29) · [🔍](https://city.app.sdk-cloud.de/location/32?start=20260222110000&end=20260222110453)

- **[DLR Highway Traffic (DLR HT)](https://zenodo.org/records/18540070)** - 2024 · Brunswick, Germany · Test Bed Lower Saxony · trajectory data (position, speed, acceleration, class) + weather + road condition · OpenSCENARIO export · CC-BY-NC-SA 4.0, Direct Download · [Paper](https://doi.org/10.1109/IAVVC61942.2025.11219599) · [🔍](https://city.app.sdk-cloud.de/location/40)

- **[NGSIM US-101 & I-80](https://data.transportation.gov/Automobiles/Next-Generation-Simulation-NGSIM-Vehicle-Trajector/8ect-6jqj)** - 2006 · California, USA · roadside cam · ~9,000 tracks · CC BY-SA 4.0, Direct Download · [Docs](https://ops.fhwa.dot.gov/trafficanalysistools/ngsim.htm)

- **[pNEUMA](https://open-traffic.epfl.ch/index.php/downloads/)** - 2018 · Athens, Greece · 10 drones · 4 days, each ~4 h, city center · CC-BY-NC 4.0, Direct Download · [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0968090X19310320?via%3Dihub) · [🔍](https://city.app.sdk-cloud.de/location/38)


## Vulnerable Road Users (VRUs) 🚶🚲🛴



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
