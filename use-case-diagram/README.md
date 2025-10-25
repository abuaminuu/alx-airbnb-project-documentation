

---

# 🏠 Airbnb Clone – Use Case Diagram

## Overview

The **Use Case Diagram** provides a high-level visualization of how different users interact with the **Airbnb Clone backend system**. It outlines the major roles—**Guest**, **Host**, and **Admin**—and their associated functionalities such as authentication, property management, bookings, payments, messaging, and reviews. This diagram helps communicate the system’s intended operations and clarifies the boundaries between user actions and backend processes.

---

## System Actors and Interactions

1. **Guest** – Represents users seeking accommodation. Guests can register, log in, search for properties, make bookings, process payments, leave reviews, and communicate with hosts. They primarily interact with the booking, payment, and review modules of the system.
2. **Host** – Represents property owners who can register, list their properties, edit property details, manage bookings, and engage in messaging with guests. Hosts interact with both the property management and communication modules.
3. **Admin** – Oversees the system by managing users, monitoring property listings, and ensuring data integrity. Admins have elevated permissions to view reports and enforce policies across the platform.

---

## Core Functionalities Represented

The diagram captures essential backend-supported features, including:

* **User Authentication** – Register, login, and profile management.
* **Property Management** – Add, update, or remove property listings.
* **Booking System** – Search listings, check availability, book stays, and cancel reservations.
* **Payment Processing** – Handle secure payments, confirmations, and refunds.
* **Review and Messaging** – Facilitate guest-host communication and post-stay feedback.
<!--
Additionally, relationships such as `«include»` and `«extend»` indicate feature dependencies (e.g., *Make Booking* includes *Make Payment*).
-->
---

## Purpose and Benefits

This Use Case Diagram provides a **clear visual reference** for developers, designers, and stakeholders. It ensures consistent understanding of system functionality, supports feature prioritization during development, and highlights how user interactions trigger backend operations. By mapping out these interactions, the diagram forms a foundation for database design, API structure, and system testing workflows.
