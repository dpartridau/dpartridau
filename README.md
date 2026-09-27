# 🏛️ Daryl Partridge | Principal NetDevOps Systems Architect
### *Sovereign Carrier-Grade Infrastructure Authority & First-Principles Engineering Pioneer*

An unassailable technical anchor with a **34-year marathon** designing, automating, and safeguarding national critical communications infrastructure from **"go to whoa."** Forged in the rigorous, first-principles era of electrical engineering, my core expertise bridges the absolute boundary between heavy physical hardware dynamics (silicon queue management, heavy-current DC power engineering) and cloud-scale NetDevOps automation (asynchronous streaming telemetry, event-driven message architectures).

---

## 🚀 The Sovereign Track Record
*   **The Fleet Anchor:** Served as the sole tri-fold technical authority (**Lead Architect, Principal Designer, and Chief Regression Specialist**) for Telstra’s national BRAS and BNG core network edge estates.
*   **Sovereign Production Scale:** Commanded absolute technical governance over a critical nationwide infrastructure footprint sustaining over **5.5 million active concurrent user sessions** and **120+ secure wholesale service providers**.
*   **Architectural Resilience:** Engineered core automation scripts, configuration engines, and transport fabrics that ran continuously in a high-density carrier network for **over 22 years without structural collapse**.

---

## 🗂️ Production Automation Code Vault

This profile serves as the definitive engineering ledger for seven custom production-grade scripts and microcode modules deployed across national broadband aggregation fabrics:

### 🐍 Python-Based Streaming Telemetry Analytics (Cloud-Scale Ingestion Core)
*   [**Module 4: jti_oc_protobuf_fileread_analyse_v5.py**](./)
    *   *Architectural Impact:* Object-oriented Protocol Buffer (`gRPC`) client designed to handle un-throttled binary streaming telemetry off production Apache Kafka event buses. Utilizes **optimized zip-slicing array mathematics (`[0::]` and `[1::]`)** inside native `zip()` loops to extract precise packet and timestamp deltas, tracking live silicon behavior at microsecond accuracy. Protected via strict `try/except ZeroDivisionError` fail-safes to survive major ingestion storms.
*   [**Module 5: tlive_telemetry_control_bng.py**](./)
    *   *Architectural Impact:* Encrypted HTTPS REST control-plane manager co-developed with the T-Live data analytics group. Recursively mines active telemetry sensor subscription states and programmatically builds and pushes JSON payloads to enforce gRPC settings, Root CA cryptographic IDs, and port profiles back onto active BNG routing silicon.
*   [**Module 6: kafkaTest_production.py**](./)
    *   *Architectural Impact:* Asynchronous Kafka consumer test suite establishing raw streaming socket listeners over production metrics topics. Unpacks serialized OpenConfigData structures on-the-fly, isolates transmission identifiers, and implements inline generator expressions to output live, bit-level hexadecimal diagnostic packet signatures.

### 🐪 Perl-Based Network Operations & Audit Engines (Carrier-Grade Hygiene)
*   [**Module 7: bngStatsMan.pl (The Olivino Engine Core)**](./)
    *   *Architectural Impact:* The legendary core of the national network metadata engine. **Bypassed high-overhead vendor `ifTable` SNMP walks** by batching **180 custom Utility MIB OID transactions** into single-burst microcode pushes. Implements compiled regex anchors (`qr//`) to parse dynamic interface topologies (`demux0` vs. `ae`) at line-rate, protected by asynchronous process signaling hooks (`SIGTERM`/`SIGKILL`) and automated child reaping loops to prevent management host memory leaks.
*   [**Module 2: junos_slogin_clivtyshellcmds.pl**](./)
    *   *Architectural Impact:* Secure multi-protocol ingestion pipeline that polls device function metadata to dynamically initialize **SNMPv3 sessions utilizing SHA authentication and AES-128 CFB bitwise encryption** across the national MX-BRAS estate. Performs low-level string pruning to normalize dirty vendor system descriptors into predictable release tags.
*   [**Module 1: reboot_history_report.pl**](./)
    *   *Architectural Impact:* Central automated log-scrape compiler that crawled ERX filesystem directories across 100+ national nodes. Parses `reboot.hty` files to track redundant Switch Route Processor (`SRP-`) failover states and maps system timestamps to verify Veritas active/standby disk mirroring synchronization.
*   [**Module 3: graph.cgi**](./)
    *   *Architectural Impact:* Highly optimized web front-end rendering engine for RRDtool. Introduced **modulo time-clamping (`% 300`)** to lock canvas graphing boundaries perfectly with background 5-minute polling heartbeats, eliminating rendering anomalies. Cached local graph structures and migrated output compilation from legacy `.gif` to compressed `.png` (dropping payloads from **17 KB down to 4 KB**) to completely stop server CPU degradation.

---

## 📡 Active Research: The Home Lab Telemetry Foundry

To maintain absolute mastery over emerging event-driven telemetry and message transport topologies from first principles, I design and run an isolated micro-services infrastructure mimicking carrier-grade pub/sub decoupling:

[433 MHz RF Burst] ──► [RTL-SDR v5 Dongle] ──► [rtl_433 Engine] ──► [MQTT Message Bus] ──► [Weewx Analytics Engine](Weather Station)       (IQ Waveform Ingestion)    (Signal Demodulation)    (Mosquitto Broker)        (Time-Series Database)


*   **Distributed Compute Layer:** Orchestrated across a private Linux cluster utilizing **four Raspberry Pi 3 Model B** single-board computers to study isolated task scheduling and distributed processing topologies.
*   **Quadrature Ingestion & Demodulation:** Leveraged final-year university **Digital Signal Processing (DSP)** frameworks to operate an **RTL-SDR v5 (NESDR Smart HF/VHF/UHF)** receiver. Intercepts raw analog RF telemetry bursts over the 433.92 MHz ISM band, compiling and deploying the open-source [**`merbanan/rtl_433`**](https://github.com) engine to execute software-defined demodulation and waveform extraction.
*   **Telemetry Stream Transport:** Puts raw decoded text streams into an eclipse-backed message broker running native **MQTT (Message Queuing Telemetry Transport)** protocols. Manages pub/sub topic trees, payload serialization profiles, and event-driven data streaming patterns packet-by-packet, feeding into the **Weewx** time-series analytics engine at line-rate.

---

## 🛠️ Core Competencies & Technical Ledger
*   **Carrier Core Architectures:** BGP, OSPF, L2TP LAC / LNS Split-Plane Tunneling, Virtual Private Routed Networks (VPRNs), 802.1ad Q-in-Q VLAN Stacking, Layer 2 Aggregation.
*   **Hardware Routing Platforms:** Juniper MX960, MX10003 Virtual Chassis, Juniper ERX-1400/1440, E320 BRAS, T1600 IGR, Cisco 7200 VXR routers, Alcatel ASAM, NEC IP-DSLAM.
*   **Languages & Formats:** Python 2.7/3, Perl, Google Protocol Buffers (gRPC), JSON, XML-RPC APIs, C, Turbo Pascal, dBase III, Assembly (Intel 80x86, Motorola 68000 / 6809 / 6805, Intel 8051, Microchip PIC microcontrollers).
*   **Data Lakes & Operations Systems:** VictoriaMetrics, Prometheus, InfluxDB, RRDtool, MySQL, syslog-ng TCP routing fabrics, Veritas File System (VxFS), Cramer OSS, Splunk.
*   **Physical Infrastructure Engineering:** Heavy-Current DC Power System design, Dual-Fed PDP Engineering exemptions, N:N power array mapping, and geographic optical path conduit trench diversity.

---
*“Understanding infrastructure systems from Go to Whoa.”*
