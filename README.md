# Centralized Audit Trail Compliance Engine – Lab 3

## Component Modelling & Architectural Pattern Selection

This repository contains the submission for **Lab 3: Component Modelling & Architectural Pattern Selection**.

## System Overview

The Centralized Audit Trail Compliance Engine is designed to manage and protect audit records. The system receives audit logs, processes them, masks sensitive Personally Identifiable Information (PII), verifies data integrity, stores audit records, and supports searching and exporting of audit data.

## Selected Architecture

**Layered Architecture** was selected for the system.

The architecture is organized into three logical layers:

- **Presentation Layer:** Handles incoming audit logs and user requests through the Audit Log Interface.
- **Business/Service Layer:** Processes audit logs, masks sensitive PII, verifies integrity, and supports search and export operations.
- **Data Layer:** Stores and retrieves audit records through the Audit Repository.

## Main Components

The UML Component Diagram includes the following components:

1. Audit Log Interface
2. Audit Processing Service
3. PII Masking & Integrity Service
4. Audit Search & Export Service
5. Audit Repository

## Repository Contents

- `component_diagram.png` – UML Component Diagram showing the system components, interfaces, and dependencies.
- `architecture-justification.pdf` – Written justification for selecting the Layered Architecture.

## Lab Deliverables

This submission includes:

- A UML Component Diagram with at least five components and the required component interactions.
- An Architecture Justification document describing the architectural choice, reasons for the selection, security advantage, and performance benefit.
