# OIAB - Observatório Indústria-Academia Brasil

## Goal

An interactive web-based dashboard that allows users to explore Brazil's map to check where companies, universities and technical schools are located and how they are distributed across the country.

## Functional requirements

The following functional requirements must be met in order to make this platform work as intended:

**F1. Platform access and data ingestion**
[] F1.1. The platform must be available as a website accessed via browser.
[] F1.2. The user must be able to access the platform directly, without the need for logging into it.

**F2. Platform interaction**
[] F2.1. The user must be able to navigate through Brazil's map at country, region, state and city levels.
[] F2.2. The user must be able to view what companies and/or universities/technical are based in a given region.
[] F2.3. The user must be able to view what companies and/or universities/technical are based in a given state.
[] F2.4. The user must be able to view what companies and/or universities/technical are based in a given city.
[] F2.5. The user must be able to filter companies and/or universities/technical schools by region.
[] F2.6. The user must be able to filter companies and/or universities/technical schools by state.
[] F2.7. The user must be able to filter companies and/or universities/technical schools by city.
[] F2.8. The user must be able to filter companies and/or universities/technical schools by segment.
[] F2.9. The user must be able to filter companies and/or universities/technical schools by specific service/product type.
[] F2.10. The user must be able to filter companies and/or universities/technical schools by name.

**F3. Statistics generation and report**
[] F3.1. The platform must produce relevant statistics following the applied filters.
[] F3.2. The user must be able to import statistics as a report in PDF format.
[] F3.3. The report must contain a reference to the platform, as well to the data source.

**F4. Data ingestion and management**
[] F4.1. The platform must frequently update its database automatically from an official, free data source.
[] F4.2. The platform data must be automatically updated on a weekly basis.

**F5. General**
[] F5.1. The app must be available in Portuguese language only.

## Non-functional requirements

The following non-functional requirements must be met in order to make this platform work as intended:

**N1. System performance**
[] N1.1. The transition between any navigation levels must take no more than 5 seconds.
[] N1.2. The effective application of any filter combination must take no longer than 10 seconds.
[] N1.3. The platform must be able to handle at least 10 simultaneous accesses.
[] N1.4. Each functional requirement must have implemented a corresponding unit test to validate any change made on it.
[] N1.5. Caching strategy must be adopted to optimize user experience, avoiding reloading the same content multiple times. 

**N2. Data storage and access**
[] N2.1. The data must be persisted in an isolated database service.
[] N2.1. The data must be stored following a relational schema.

**N3. Security**
[] N3.1. All endpoints must be secure to prevent malicious access.
[] N3.2. The database user exposed to the backend must have read-only access.
[] N3.3. The database credentials must be managed as environment variable within the application server.
[] N3.4. No system-sensitive information must be harcoded anywhere in the code.

**N4. Budget**
[] N4.1. The whole tech stack must be based on free tier options, resulting in a totally zero-cost project.


