# Awesome-Vehicle-Telematics-Fleet-Tracking

## Top Vehicle Telematics & Fleet Tracking Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on GPS Fleet Tracking, ELD/Telematics, Vehicle Data Loggers, Asset Tracking & Driver Insights*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Vehicle Telematics & Fleet Tracking**. These systems collect GPS and vehicle data—location, trips, fuel, diagnostics—and turn them into maps, reports, and operational alerts.



**Examples** include TeslaFi, Samsara, Geotab, Verizon Connect, Teletrac Navman, Fleetio, Webfleet, Motive (KeepTruckin), Azuga, Omnitracs, and **TeslaMate** (`teslamate-org/teslamate`)—self-hosted data logger and analytics for Tesla vehicles.



**Open-source emphasis**: Commercial fleet platforms dominate ELD-compliant enterprise telematics. Open options are strong for **GPS tracking servers** and **owner data loggers**—**Traccar**, **TeslaMate**, **OwnTracks**, and related projects. This section lists every significant relevant project found.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Samsara, Geotab, Verizon Connect, Motive, Teletrac Navman, Azuga, Omnitracs, Webfleet](https://www.samsara.com/)**  

  Enterprise fleet telematics—GPS tracking, ELD/hours of service, cameras, maintenance, and compliance reporting.



- **[Fleetio and fleet maintenance platforms](https://www.fleetio.com/)**  

  Fleet operations software often integrated with telematics data for service and asset lifecycle.



- **[TeslaFi and EV-focused cloud loggers](https://teslafi.com/)**  

  Hosted analytics for Tesla and similar EVs—trip history, charging, and efficiency without self-hosting.



- **[Other commercial fleet & telematics platforms](https://www.geotab.com/)**  

  Additional OEM-connected and aftermarket tracking services.



## Open-Source GitHub Projects



### GPS Tracking Platforms



- **[Traccar](https://github.com/traccar/traccar)**  

  Leading open-source GPS tracking platform—200+ device protocols, self-hosted server, web UI, and mobile apps for fleet and personal tracking.



- **[OpenGTS](https://github.com/search?q=OpenGTS)**  

  Open GPS tracking system historically used for fleets—Java-based server with device communication and mapping.



- **[OwnTracks](https://github.com/owntracks/recorder)**  

  Open location tracking for personal devices—privacy-oriented recorder and apps that you host yourself.



- **[gpsd](https://github.com/gpsd/gpsd)**  

  Open service daemon for GPS receivers—building block for custom telematics on Linux gateways.



### Vehicle / EV Data Loggers



- **[TeslaMate](https://github.com/teslamate-org/teslamate)**  

  Self-hosted open data logger for Tesla vehicles—high-precision drives, charging, Grafana dashboards, MQTT, and no extra vampire drain design goals.



- **[tesla-apiscraper / community Tesla tools](https://github.com/search?q=tesla+api+logger)**  

  Community scrapers and loggers that complement or feed TeslaMate-style analytics.



- **[OBD / CAN logging projects](https://github.com/search?q=OBD+logger+open+source)**  

  Open tools for reading vehicle diagnostics over OBD-II and CAN for DIY telematics.



### Maps, Dashboards & Integration



- **[Grafana + MQTT stacks](https://github.com/grafana/grafana)**  

  Open observability stack commonly paired with TeslaMate and IoT GPS feeds for custom fleet dashboards.



- **[OsmAnd / open navigation](https://github.com/osmandapp/OsmAnd)**  

  Open map and navigation apps sometimes used alongside self-hosted tracking.



- **[Node-RED / Home Assistant vehicle integrations](https://github.com/home-assistant/core)**  

  Open automation platforms that consume MQTT vehicle data for alerts and home/fleet workflows.



### Additional Strong Open-Source Options



- **General GPS fleet server**: Traccar.

- **Tesla owner analytics**: TeslaMate.

- **Personal privacy tracking**: OwnTracks.

- **Composable stacks**: Hardware GPS/OBD → Traccar or custom logger → Postgres/Influx → Grafana; Tesla API → TeslaMate → MQTT → Home Assistant.

- Commercial platforms still lead for ELD compliance, cellular device fleets, AI cameras, and carrier integrations.



**Frameworks for building custom systems**:  

**Traccar** for multi-device GPS fleets; **TeslaMate** for Tesla-centric logging; **OwnTracks** for privacy-first personal tracking; pair with **Grafana** for analytics.  

Fully open telematics is practical for owner/operator and many SMB fleets; regulated trucking ELD programs are largely commercial.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Vehicle location is sensitive personal and operational data. Secure servers, limit access, and comply with employment and privacy laws when tracking drivers. ELD and safety regulations may require certified commercial solutions.

- Open-source trackers offer ownership of data. Commercial telematics shift devices, connectivity, and compliance packages to the vendor. Neither replaces safe driving policy and proper device installation.



---



**Made for fleet operators, EV enthusiasts, and builders of vehicle data systems.**  

Let's expand open telematics and tracking while recognizing the compliance depth that leading commercial fleet platforms deliver.
