# MNS-Event-Booking-System

A C# event booking portfolio project focused on quality assurance and database correctness.

## Architecture

The source folders follow the three-layer architecture taught in SWEN90007 Software Design and Architecture.

| Layer | Folder |
| --- | --- |
| Presentation | [src/Presentation](src/Presentation/) |
| Domain | [src/Domain](src/Domain/) |
| Data Source | [src/DataSource](src/DataSource/) |

The [Service Layer](src/Domain/Services/) sits within Domain and coordinates application operations.

Resources used by multiple layers belong in [src/shared](src/shared/).
