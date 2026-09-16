# Awful Trajectory Datasets

This document catalogs datasets related to trajectory data that are **not** included on the main [Awesome Trajectory Datasets](README.md) list, along with documented reasons for exclusion. This can be useful for understanding curation decisions and finding relevant resources that may still be valuable for specific use cases.

---

## 📋 Exclusion Categories

### 🚫 Data Access Issues

| Dataset | Year | Location | Reason |
|---------|------|----------|--------|
| **[Harypdata](https://www.kios.ucy.ac.cy/harpydata/tlsdataset/)** | — | — | Download dataset -> 404 Error |
| **[Lyft Level 5](https://self-driving.lyft.com/level5/data/)** | 2020 | Palo Alto, USA | Server Not Found |
| **[Stanford Drone (SDD)](https://cvgl.stanford.edu/projects/uav_data/)** | 2016 | Stanford, USA | Download Dataset -> The connection has timed out, not georeferenced |

### 📬 Data Access Requested, No Feedback

| Dataset | Year | Location | Contact Status |
|---------|------|----------|----------------
| **[CitySim](https://github.com/UCF-SST-Lab/UCF-SST-CitySim1-Dataset)** | 2023 | USA | Requested 7 Sept |
| **[INTERACTION](https://interaction-dataset.com/)** | 2019 | Multi-country | Requested 7 Sept |
| **[SinD](https://github.com/SOTIF-AVLab/SinD)** | 2022 | Changsha, China | Requested 12 Aug, 7 Sept |

### 📍 Focus on Tracks, not Traffic

| Dataset | Year | Location | Limitation |
|---------|------|----------|-----------|
| **[GeoLife](https://www.microsoft.com/en-us/research/publication/geolife-gps-trajectory-dataset-user-guide/)** | 2012 | Beijing, China | Mixed personal + traffic |
| **[Single-User Trajectory Collection (Hannover)](https://data.uni-hannover.de/dataset/single-user-trajectory-collection-for-the-region-of-hannover)** | — | Hannover, Germany | Single vehicle personal tracking |
| **[Bicycle Driving Behaviour (CITY CYCLING)](https://opara.zih.tu-dresden.de/items/5cd85d7f-e86b-496d-98fb-21c509ba72ef)** | — | Germany (100 cities) | Incomplete trajectory data |

### 🎥 Focus on Sensor/Perception Data, very short trajectories, missing georeference

| Dataset | Year | Location | Reason |
|---------|------|----------|--------|
| **[Argoverse 1](https://www.argoverse.org/av1.html)** | 2019 | Pittsburgh + Miami, USA | Sensor-centric focus |
| **[Argoverse 2 Motion](https://www.argoverse.org/av2.html)** | 2023 | 6 US cities | Sensor-centric focus |
| **[BDD100K](https://www.bdd100k.com/)** | 2020 | USA | Video-centric, not trajectory |
| **[Ko-PER Intersection](https://www.uni-ulm.de/in/mrm/forschung/datensaetze/)** | 2014 | Aschaffenburg, Germany | Limited scenario data |
| **[L3Pilot Open Data](https://l3pilot.eu/data.html)** | 2020+ | Multiple | Sensor/perception focus |
| **[nuScenes](https://www.nuscenes.org/)** | 2020 | Boston + Singapore | Sensor-centric focus |
| **[nuPlan](https://www.nuscenes.org/nuplan)** | 2023 | USA + Singapore | Sensor-centric focus |
| **[PROVIDENTIA A9 Dataset](https://innovation-mobility.com/projekt-providentia/a9-dataset/)** | — | Germany | Missing georeference |
| **[Shifts](https://github.com/yandex-research/shifts)** | 2022 | Multi-country | GNSS benchmark, not driving |
| **[VisDrone](https://github.com/VisDrone/VisDrone-Dataset)** | 2021 | China | Detection/tracking, not trajectory focus |
| **[Waymo Open Motion](https://waymo.com/open/data/motion/)** | 2021 | USA | Sensor-centric focus |
| **[Waymo Open Perception](https://waymo.com/open/data/perception/)** | 2020 | USA | Sensor-centric focus |

### 🚗 Licensing

| Dataset | Year | Location | Reason |
|---------|------|----------|--------|
| **[inD](https://levelxdata.com/ind-dataset/)** | 2020 | Germany (4 intersections) | licensing restrictions |
| **[rounD](https://levelxdata.com/round-dataset/)** | 2020 | Germany (3 roundabouts) | licensing restrictions |
| **[highD](https://levelxdata.com/highd-dataset/)** | 2018 | Germany (A3, A9) | licensing restrictions |
| **[exiD](https://levelxdata.com/exid-dataset/)** | 2022 | Germany (A3, A40, A42) | licensing restrictions |
| **[uniD](https://levelxdata.com/unid-dataset/)** | 2020+ | Germany | licensing restrictions |

### 🚶 Focus on Pedestrians/Crowds

| Dataset | Year | Location | Limitation |
|---------|------|----------|-----------|
| **[ATC Shopping Center](https://irc.atr.jp/crest2010_HRI/ATC_dataset/)** | 2013 | Osaka, Japan | Relative/indoor coordinates, not geospatial |
| [Bicycle Driving Behaviour in Germany](https://opara.zih.tu-dresden.de/items/5cd85d7f-e86b-496d-98fb-21c509ba72ef) | 2024 | Germany | Only start and end gps data |
| **[ETH Pedestrian](https://icu.ee.ethz.ch/research/datsets.html)** | 2009 | Zurich, Switzerland | No georeferencing |
| **[PIE (Pedestrian Intention)](http://data.nvision2.eecs.yorku.ca/PIE_dataset/)** | 2019 | Toronto, Canada | No trajectory coordinates |
| **[TrajNet++](https://www.aicrowd.com/challenges/trajnet-a-trajectory-forecasting-challenge)** | 2021 | Multi-source | Benchmark aggregator, limited georeferencing |
| **[UCY Crowds](https://graphics.cs.ucy.ac.cy/research/downloads/crowd-data)** | 2007 | Cyprus / Israel | No GPS/georeferencing |

---

## 📌 Notes

- **Status as of:** 2025-09-16
- **Accessibility:** Some datasets may have regained access since last check; links should be verified before use.
- **Future Consideration:** Some of these datasets (e.g., missing feedback cases) may be added to the main awesome list if access is granted or if circumstances change.

---

## 🤝 Contributing

If you have information about:
- Datasets that regained accessibility
- Updates to licensing or access policies
- Additional exclusion reasons to document
- Corrections to this list

Please open an issue or pull request on the [main repository](https://github.com/yourusername/awesome-trajectory-datasets).
