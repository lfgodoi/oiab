---
trigger: model_decision
description: "Functional and non-functional product requirements for OIAB. Load before planning, designing, implementing, or testing any feature."
---

# OIAB - Observatório Indústria-Academia Brasil

## Goal

An interactive web-based dashboard that allows users to explore Brazil's map to check where manufacturing companies, universities and technical schools are located and how they are distributed across the country.

## Functional requirements

The following functional requirements must be met in order to make this platform work as intended:

**F1. User access**
- [ ] F1.1. The platform must be available as a website accessed via a browser.
- [ ] F1.2. The user must be able to access the platform directly, without needing to log in.

**F2. Platform interaction**
- [ ] F2.1. The user must be able to navigate through Brazil's map at the country, region, state, and city levels.
- [ ] F2.2. The user must be able to view which companies and/or universities/technical schools are located in a given region.
- [ ] F2.3. The user must be able to view which companies and/or universities/technical schools are located in a given state.
- [ ] F2.4. The user must be able to view which companies and/or universities/technical schools are located in a given city.
- [ ] F2.5. The user must be able to filter companies and/or universities/technical schools by region.
- [ ] F2.6. The user must be able to filter companies and/or universities/technical schools by state.
- [ ] F2.7. The user must be able to filter companies and/or universities/technical schools by city.
- [ ] F2.8. The user must be able to filter universities/technical schools by course.
- [ ] F2.9. The user must be able to filter universities/technical schools by knowledge area.
- [ ] F2.10. The user must be able to filter companies by segment.
- [ ] F2.11. The user must be able to filter companies by product type.
- [ ] F2.12. The user must be able to filter companies and/or universities/technical schools by name.
- [ ] F2.13. The user must be able to filter both companies and universities/technical schools simultaneously by applying any of their respective filters.

**F3. Statistics generation and reporting**
- [ ] F3.1. The platform must produce relevant statistics based on the applied filters.
- [ ] F3.2. The user must be able to export statistics as a report in PDF format.
- [ ] F3.3. The report must contain a reference to the platform, as well as to the data sources.

**F4. Data ingestion and management**
- [ ] F4.1. The ingestor must frequently update the platform database automatically from official, free data sources.
- [ ] F4.2. The ingestor must check the data sources on a weekly basis to ingest any new data available.
- [ ] F4.3. The ingestor must keep the current data if no new data is available in the data sources.
- [ ] F4.4. The ingestor must retrieve only active companies, excluding MEIs and micro-enterprises, within the manufacturing industry following Section C of the CNAE specification.

**F5. General**
- [ ] F5.1. The app must be available in the Portuguese language only.

## Non-functional requirements

The following non-functional requirements must be met in order to make this platform work as intended:

**N1. System performance**
- [ ] N1.1. The transition between any navigation levels must take no more than 5 seconds.
- [ ] N1.2. The effective application of any filter combination must take no longer than 10 seconds.
- [ ] N1.3. The platform must be able to handle at least 10 concurrent users.
- [ ] N1.4. A caching strategy must be adopted to optimize user experience and avoid reloading the same content multiple times.

**N2. Data storage and access**
- [ ] N2.1. The data must be persisted in an isolated database service.
- [ ] N2.2. The data must be stored following a relational schema.

**N3. Security**
- [ ] N3.1. All endpoints must be secure to prevent malicious access.
- [ ] N3.2. The database user available to the backend must have read-only access.
- [ ] N3.3. The database user available to the ingestor must have write access without admin privileges.
- [ ] N3.4. The database credentials must be managed as environment variables within the application server.
- [ ] N3.5. Sensitive system information must never be hardcoded anywhere in the code.

**N4. Maintainability**
- [ ] N4.1. Each functional requirement must have a corresponding unit test implemented to verify any changes made to it.
- [ ] N4.2. Integration tests must be implemented to verify the app is working properly.

**N5. Budget**
- [ ] N5.1. The whole tech stack must be based on free-tier options, resulting in a totally zero-cost project.