# Cyber Threat Intelligence Framework Implementation

**Status:** ⚠️ **Project in Progress** <i>(Target March 2024)</i>

## Objective

This project aims to build a robust Cyber Threat Intelligence Framework by leveraging industry-standard tools such as MISP for threat intelligence sharing, Splunk for real-time threat analysis, and TheHive for incident response. The objective is to ingest open-source threat feeds into MISP, integrate these feeds into Splunk to enable dynamic threat analysis, and automate alerting in TheHive to enhance the organization's ability to rapidly respond to cyber threats. Additionally, the framework will utilize the MITRE ATT&CK navigator to map detected threats to adversary Tactics, Techniques, and Procedures (TTPs), thereby enhancing the understanding and mitigation of potential security breaches.

## Proposed Solution Architecture
![Capstone_Flow2 drawio](https://github.com/arviiyer/CTI-Framework/assets/26136879/15c512a5-237d-419b-931f-4223ff843cfd)

> **Note:** The steps listed below are part of the planned and proposed implementation strategy for the Cyber Threat Intelligence Framework. These steps are subject to change as the project evolves and are indicative of the direction and activities intended for the project.

## Planned Implementation Steps

### Ingesting Threat Feeds into MISP
- Open-source threat feeds will be ingested into MISP for the collection of Indicators of Compromise (IoCs).
  `# Screenshot placeholder for MISP threat feed ingestion`

### Integrating MISP with Splunk for Threat Monitoring
- MISP’s IoCs will be integrated into Splunk to enable real-time monitoring and dynamic threat analysis.
  `# Screenshot placeholder for MISP and Splunk integration`

### Automating Alerts in TheHive
- Splunk will be configured to trigger automated alerts in TheHive for rapid incident response based on identified cyber threats.
  `# Screenshot placeholder for automated alert configuration in TheHive`

### Mapping Threat Findings with MITRE ATT&CK
- Utilize the MITRE ATT&CK navigator to map threat findings to adversary Tactics, Techniques, and Procedures (TTPs) for a structured analysis.
  `# Screenshot placeholder for mapping with MITRE ATT&CK navigator`

## Current Progress

- [x] Plan and design the CTI Framework.
- [ ] Open-source threat feeds ingested into MISP.
- [ ] Real-time threat monitoring enabled in Splunk.
- [ ] Automated alerts in TheHive configured.
- [ ] MITRE ATT&CK navigator used for mapping TTPs.

> **Disclaimer:** This project is a work in progress and the steps above are indicative of the planned activities. They will be updated as the project progresses to reflect the current state and milestones achieved.
