# Awesome-Laboratory-Execution-System

### Top Laboratory Execution System (LES) Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on SOP-Driven Procedure Execution, Sample Prep Workflows, Touch-Screen Lab Guidance, Compliance Documentation & Integration with LIMS/ELN*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Laboratory Execution Systems (LES)**. These systems guide analysts through step-by-step laboratory procedures (sample preparation, testing sequences, data capture), enforce SOPs, capture results and attachments at the bench, and integrate with broader LIMS and ELN environments.

**Examples** include LabVantage LES, STARLIMS LES, Benchling, LabWare LES, Biovia ONE Lab, Thermo Fisher SampleManager, Agilent SLIMS, Labii, LabCollector, and CloudLIMS (the category leaders).

**Open-source emphasis**: Dedicated commercial LES modules are tightly coupled to enterprise LIMS. Open alternatives are primarily **open-source LIMS and lab workflow platforms** (SENAITE, LabKey, Aquarium, Open-LIMS, and related projects) that support procedure execution, sample tracking, and audit trails. This section lists the strongest available open resources and is realistic about the gap.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[LabVantage LES](https://www.labvantage.com/)**  
  Laboratory execution capabilities within the LabVantage platform, focused on enforcing SOPs and guiding procedure execution in quality and manufacturing labs.

- **[STARLIMS LES](https://www.starlims.com/)**  
  Lab Execution System module integrated with STARLIMS, providing touch-screen workflow guidance, parameter capture, and traceability for sample and method runs.

- **[Benchling](https://www.benchling.com/)**  
  Cloud-native R&D platform combining ELN, LIMS-like sample tracking, and workflow tools widely used in biotech and molecular biology labs.

- **[LabWare LES](https://www.labware.com/)**  
  Laboratory execution functionality within the LabWare LIMS suite, supporting configurable procedure execution and data capture at the bench.

- **[Biovia ONE Lab (Dassault)](https://www.3ds.com/)**  
  Lab informatics environment from Dassault Systèmes supporting experimental execution, data capture, and integration with broader scientific workflows.

- **[Thermo Fisher SampleManager](https://www.thermofisher.com/)**  
  Enterprise LIMS with strong QC and lab execution capabilities, including instrument integration and structured result entry.

- **[Agilent SLIMS](https://www.agilent.com/)**  
  Laboratory information and execution-oriented software supporting sample and workflow management in analytical environments.

- **[Labii](https://www.labii.com/)**  
  Flexible ELN/LIMS-style platform that can support structured experimental and procedure workflows for research labs.

- **[LabCollector](https://labcollector.com/)**  
  Modular LIMS and lab management software used by research and biotech labs for samples, inventory, and related workflows.

- **[CloudLIMS](https://cloudlims.com/)**  
  Cloud LIMS platform supporting sample tracking, testing workflows, and laboratory data management for various lab types.

## Open-Source GitHub Projects
- **[SENAITE LIMS / SENAITE.CORE](https://github.com/senaite/senaite.core)**  
  Enterprise-oriented open-source LIMS (Plone-based) with strong workflow, sample management, audit trails, and extensibility for regulated and research labs.

- **[LabKey Server](https://github.com/LabKey)**  
  Open-source platform for research data management, specimen tracking, and study workflows, widely used in biobanks and clinical research.

- **[Aquarium (Lab Operating System)](https://github.com/)**  
  Open protocol and workflow execution system originally developed for biofoundry/lab automation contexts, supporting designed procedures and inventory.

- **[Open-LIMS](https://github.com/open-lims/open-lims)**  
  Open-source Laboratory Information Management System project aimed at general lab sample and process management.

- **[OpenSylab and diagnostic open LIMS](https://github.com/)**  
  Open LIMS projects focused on medical diagnostics with audit trails, RBAC, and standards-oriented workflows (e.g., ISO 15189-oriented designs).

- **[Nexus Lab Tracker and lightweight open trackers](https://github.com/)**  
  Open laboratory tracking systems for containers, samples, and events with deterministic CLI and snapshot/audit workflows.

- **[Bika LIMS and related community forks](https://github.com/)**  
  Historical and community open LIMS lineages that influenced later projects such as SENAITE.

- **[ELN and notebook open platforms with workflow features](https://github.com/)**  
  Open electronic lab notebooks that support structured protocols and can approximate LES-style guided execution.

- **[Instrument and data capture open connectors](https://github.com/)**  
  Libraries and agents for bringing instrument data into open LIMS or custom execution systems.

- **[Protocol and SOP open template systems](https://github.com/)**  
  Tools for authoring, versioning, and executing digital protocols that complement LIMS data stores.

### Additional Strong Open-Source Options
- Starting with **SENAITE** or **LabKey** when an open, self-hosted LIMS with solid workflow and audit capabilities is required.
- Using **Aquarium**-style systems when the primary need is protocol design and execution in research or biofoundry settings.
- Combining open LIMS with commercial instruments and ELNs for hybrid environments.
- Accepting that dedicated touch-screen LES modules, deep regulated manufacturing integration, and polished enterprise support still favor commercial platforms (LabVantage, STARLIMS, LabWare, SampleManager, Benchling, etc.).
- Focusing open-source efforts on transparent sample tracking, auditability, and research flexibility rather than replacing full commercial LES suites.

**Frameworks for building custom systems**: Define procedures as structured workflows in an open LIMS or protocol engine → capture step results and attachments at the bench → store samples and results with full audit history → integrate instruments via open connectors → report and release under controlled processes. Suitable for research labs, academic cores, and organizations with informatics capacity. Most regulated QC and large manufacturing labs continue to adopt commercial LES/LIMS platforms for compliance and vendor support.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Laboratory systems in regulated environments (GLP, GMP, ISO 17025, clinical, etc.) must meet strict validation, audit-trail, and data-integrity requirements. Open-source or self-built solutions require formal validation and quality oversight before use in regulated work. This list is not regulatory or compliance advice.

---
**Made for lab managers, quality teams, and scientific informaticians who need reliable procedure execution.**
Let's keep laboratory workflows traceable, compliant, and as open as practical.
