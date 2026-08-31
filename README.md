# Movie Ticket Booking Management System

A robust, enterprise-grade Pega application developed for movie ticket booking automation, featuring dynamic routing, case life cycle management, and seamless booking execution.

## Project Overview
The Movie Ticket Booking Management System was designed and implemented during the National Internship Program. The application streamlines the end-to-end movie ticket reservation lifecycle—from customer request and seat availability checks to managerial approvals and final booking execution.

## Key Features
* Automated Case Lifecycle: Built with multi-stage processing including Submission, Availability Check, Approval, and Booking Execution.
* Smart Routing & Queues: Automatically routes show requests and approvals to appropriate queues (e.g., Standard Show Queue, Cinema Manager).
* Dynamic Cost & Data Validation: Utilizes data transforms and property mappings to manage ticket counts, verification, and pricing.
* Booking Execution Stage: Features specialized user actions for seat allocation, ticket ID generation, and tracking booking confirmation statuses.
* Custom Data Modeling: Maintains core properties like Approval Dates, Seat Numbers, Ticket IDs, and Booking Statuses for comprehensive audit tracking.

## Tech Stack
* Platform: Pega App Studio / Pega Platform (Constellation UI architecture)
* Version Control: Git & GitHub

## Application Workflows
1. Submission: Customer initiates a movie ticket request specifying show details and ticket counts.
2. Availability: System checks seat availability and validates constraints.
3. Approval: Routes requests for review and manager authorization.
4. Booking Execution: Finalizes seat allocation, issues a unique Ticket ID, and updates the booking confirmation status.

---
Developed as part of the National Internship Program.
