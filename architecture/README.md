# Architecture

Here you find the documentation of the software architecture that we purpose to address Road Warrior requirements.

## Context Diagram

In the architecture views we find a description of the external entities in the diagram, along with an explanation of their interaction with the system.

## Microservices View

The main part of the software architecture is the set of four architecture views seen below.

### User Service

The scope is the operations that the user can perform related to creating and managing an account and user profile, which includes signing in using user ID and password or different credentials (Google, Facebook, etc.).

### Mail Adapter Service

The scope for polling email looking for travel-related emails, filter and whitelist certain emails, parsing & create reservations data into Road Warrior App.

### Reservation Service

This service covers all functionality / core functions related to view, add, update, delete, and share existing reservation, get updated travel details from the agency’s (delays, cancellations, updates, gate changes, etc.) and provide data for summary reports or data analytical.

### Analytic Service

The scope gathers analytical data from users' trips for various purposes - travel trends, locations, airline and hotel vendor preferences, cancellation and update frequency.
