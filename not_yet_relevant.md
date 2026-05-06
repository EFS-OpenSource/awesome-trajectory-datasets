- [Aerial (UAV / Aircraft)](#aerial-uav--aircraft)
- [Maritime](#maritime)
- [Live Data Streams](#live-data-streams)
  - [Public Transport (GTFS-RT)](#public-transport-gtfs-rt)
  - [Maritime (AIS Streams)](#maritime-ais-streams)
  - [Aviation (ADS-B Streams)](#aviation-ads-b-streams)
  - [Road Traffic (Open Feeds)](#road-traffic-open-feeds)
- [Benchmarks & Challenges](#benchmarks--challenges)



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
