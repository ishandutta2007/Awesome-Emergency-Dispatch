# Awesome-Emergency-Dispatch

## Top Emergency Dispatch (CAD) Platforms Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Computer Aided Dispatch, Incident Management, First Responder Coordination & Emergency Response*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Emergency Dispatch (CAD)**. These tools help 911 centers, fire departments, EMS agencies, and emergency management organizations manage incident calls, dispatch first responders, track unit locations, and coordinate multi-agency responses.



**Examples** include CentralSquare CAD, Tyler Technologies CAD, Mark43 CAD, Hexagon HxGN OnCall, Motorola PremierOne, RapidDeploy, Carbyne, Priority Dispatch, Spillman Flex, and Zetron MAX (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom dispatch workflows, and transparent emergency data management — ideal for volunteer fire departments, ARES/RACES ham radio groups, campus security, and organizations that need full control over their dispatch operations without six-figure licensing fees.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents



- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[CentralSquare CAD](https://www.centralsquare.com/)**  

  Comprehensive public safety platform serving law enforcement, fire, and EMS agencies. Provides computer aided dispatch, records management, and mobile data solutions with multi-agency coordination.



- **[Tyler Technologies CAD](https://www.tylertech.com/)**  

  Public safety CAD solution integrated with Tyler's enterprise ERP and permitting systems. Handles incident creation, unit recommendation, and field unit status tracking.



- **[Mark43 CAD](https://mark43.com/)**  

  Cloud-native public safety platform designed for law enforcement and first responders. Modern interface with real-time data sharing, mapping, and mobile access for field units.



- **[Hexagon HxGN OnCall](https://www.hexagon.com/)**  

  Public safety dispatch platform combining call handling, dispatch, and analytics. Part of Hexagon's safety and infrastructure portfolio with strong GIS integration.



- **[Motorola PremierOne](https://www.motorolasolutions.com/)**  

  Enterprise CAD and records management system from Motorola Solutions. Integrates with radio systems, body cameras, and command center infrastructure for unified public safety operations.



- **[RapidDeploy](https://www.rapiddeploy.com/)**  

  Cloud-native emergency response platform with 911 call handling, dispatch, and real-time data integration. Provides NG911-compliant infrastructure for PSAPs.



- **[Carbyne](https://carbyne911.com/)**  

  911 call handling and emergency response platform. Enables live video streaming, accurate location data, and real-time communication between callers and dispatch centers.



- **[Priority Dispatch](https://www.prioritydispatch.net/)**  

  Medical, fire, and police dispatch protocol provider. Offers structured call triage and dispatch protocols used by emergency communication centers worldwide.



- **[Spillman Flex](https://www.spillman.com/)**  

  Public safety software suite (Motorola Solutions) providing CAD, records management, and mobile data for law enforcement, fire, and EMS agencies.



- **[Zetron MAX](https://www.zetron.com/)**  

  Integrated dispatch console and CAD system for mission-critical communications. Supports radio, telephony, and emergency call handling for public safety agencies.



## Open-Source GitHub Projects



- **[Resgrid Core](https://github.com/Resgrid/Core)**  

  The most complete open-source CAD, personnel, shift management, and emergency management platform. Powers Resgrid.com with hosted and self-hosted options. Features comprehensive **Computer Aided Dispatch** (manual and automatic dispatches), personnel management with certifications and roles, unit support with AVL and logging, duty shift system with swap/trade support, learning management, inventory tracking, document storage, and department linking for mutual aid agreements. Native mobile apps for Personnel, Units, Stations, and Commanders. **Apache 2.0**. ~131 stars .



- **[Tickets CAD](https://github.com/openises/TicketsCAD)**  

  Free, full-featured open-source CAD system with **50,000+ downloads and 30+ years of active development**. Serves organizations where budget is zero but mission is critical: volunteer fire departments, ARES/RACES ham radio, CERT teams, campus security, and small EMS agencies. Features incident dispatch with full lifecycle management, Leaflet-powered interactive mapping with OpenStreetMap, multi-mode communications (chat, SMS via Twilio/BulkVS, email, Slack, Zello push-to-talk, Meshtastic mesh networking, DMR radio messaging), 7 location providers (APRS, Meshtastic, OwnTracks, etc.), ICS forms with Winlink XML export, 65 granular RBAC permissions, and real-time SSE alerts. Runs on Apache + PHP 7.4+ and MySQL/MariaDB — Raspberry Pi capable. Docker image available. **Free and open source** .



- **[TAK CAD](https://tak-ops.com/blogs/work/what-are-we-working-on-tak-computer-aided-dispatch-tak-cad)**  

  Open-source CAD plugin for the Team Awareness Kit (TAK) ecosystem, supported by the US Air Force and Army. Includes plugins for TAK Server, WinTAK (dispatcher), and ATAK (responder). Dispatchers create incidents, assign personnel and vehicles, and manage resources. Responders receive alerts, access incident details, self-assign to vehicles, and navigate via auto-generated routes. Integrates with existing CAD systems and Active911. **Free and open source**. Currently in alpha release, being evaluated by several public safety organizations .



- **[TPT Emergency Services System](https://github.com/tpt-solutions/tpt-emergency)**  

  Modular offline-first emergency response platform. **100% offline capable** — all features work without internet. Progressive Web App installs on any device. Supports fire, ambulance, police, and disaster management modules with a live dispatch console, native Bluetooth mesh networking, unit tracking, and offline map tile caching. Runs on a single executable, Node.js, static HTML file, Raspberry Pi, cloud server, or Docker. Stack: SolidJS + Tailwind, Fastify, SQLite + IndexedDB, MapLibre GL, Socket.IO. **MIT**. Currently 51% complete .



- **[EmComMap](https://github.com/DanRuderman/EmComMap)**  

  Open-source CAD designed by an Amateur Radio Emergency Service operator for use on AREDN mesh networks during deployments. Leverages interactive maps and sync-able web browser databases for map-based situational awareness. Features incident tab with location tracking, traffic tab for message traffic (filterable, sortable, exportable to spreadsheet), operators tab for location/status updates, and OpenStreetMap tile download for standalone operation. Tracks all communications with severity levels and tactical call signs. Active development .



- **[OpenCAD](https://github.com/opencad-community/OpenCAD-php)**  

  Web-based open-source CAD system for roleplay communities (101 stars, 74 forks). LAMP-stack compatible. Defines multiple user roles with tailored dashboard views: communications/dispatch, police, fire, EMS, sheriff, highway patrol, roadside assistance, and civilian. Law enforcement roles can view BOLOs and active calls, create citations, warnings, and arrest reports. Dispatchers create, edit, and assign calls, track resource availability. Fire/EMS roles view and edit call details and accept assignments .



### Additional Strong Open-Source Options



- **Complete CAD Suites**: **Resgrid Core** (most feature-complete, Apache 2.0, hosted + self-hosted), **Tickets CAD** (30+ years active, 50k+ downloads, volunteer-focused).

- **TAK Ecosystem**: **TAK CAD** (US military-supported, TAK Server/WinTAK/ATAK plugins).

- **Offline/Mesh**: **TPT Emergency** (100% offline PWA, Bluetooth mesh), **EmComMap** (AREDN mesh networks).

- **Roleplay/Lightweight**: **OpenCAD** (law enforcement focus, LAMP stack), **WebCAD** (rural emergency management, HTML-based) .



**Frameworks for building custom systems**: Combine **Resgrid Core** for the full CAD/personnel/logistics platform, **Tickets CAD** for a lightweight volunteer-focused deployment, **TAK CAD** for military/TAK ecosystem integration, and **TPT Emergency** for offline-first mobile response. Add **Leaflet/OpenStreetMap** for mapping, **Twilio** for SMS alerts, and **Docker** for deployment.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Emergency dispatch systems handle life-critical communications; ensure proper testing, redundancy, and compliance with local PSAP regulations before production deployment.

- Self-hosted open-source solutions require proper security hardening, network isolation, and regular maintenance. For mission-critical emergency use, consider hybrid approaches with commercial backup systems.



---



**Made for emergency communications centers, volunteer fire departments, EMS agencies, campus security, and emergency management professionals.**  

Let's make emergency dispatch more open, accessible, and resilient.
