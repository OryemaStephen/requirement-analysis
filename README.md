# Requirement Analysis

## What is Requirement Analysis?

Requirement Analysis is a crucial phase in the Software Development Life Cycle (SDLC) where the needs and expectations of stakeholders are gathered, analyzed, and documented to guide the development process. It involves understanding **what the customer wants** and **translating those needs into clear, actionable requirements** for the development team.

### Importance in SDLC:
- **Foundation for Development:** It sets a clear roadmap for developers, ensuring the final product aligns with stakeholder expectations.
- **Reduces Risks:** By clarifying requirements early, it minimizes misunderstandings and reduces the risk of costly changes later.
- **Improves Quality:** Well-analyzed requirements help in building a product that meets user needs, enhancing overall quality and customer satisfaction.

---

## Why is Requirement Analysis Important?

Requirement Analysis plays a key role in the success of software projects. Below are three major reasons why it’s important:

- **Clear Understanding of Needs:**  
  It ensures all stakeholders have a shared understanding of what the software should do, avoiding ambiguity.

- **Cost and Time Efficiency:**  
  Proper analysis reduces the chances of rework and helps in accurate project estimation, saving both time and money.

- **Improved Project Planning:**  
  It enables better planning for resources, timelines, and milestones, leading to smoother project execution.

---

## Key Activities in Requirement Analysis

Here are the five key activities typically involved in Requirement Analysis:

- **Requirement Gathering:**  
  Collecting information from stakeholders through interviews, surveys, and observations.

- **Requirement Elicitation:**  
  Engaging stakeholders to uncover their true needs using techniques like brainstorming, workshops, and questionnaires.

- **Requirement Documentation:**  
  Clearly writing down the requirements in a formal document (like Software Requirement Specification - SRS).

- **Requirement Analysis and Modeling:**  
  Analyzing gathered data for conflicts, feasibility, and completeness. Creating models like Data Flow Diagrams (DFD) or Use Case Diagrams to visualize the system.

- **Requirement Validation:**  
  Confirming that the documented requirements accurately reflect stakeholder needs and are achievable within scope and resources.

---

## Types of Requirements

### Functional Requirements

Functional Requirements describe **what the system should do**. They define specific functionalities and behaviors the system must perform.

**Examples for Booking Management Project:**
- Users should be able to **search for available rooms** by date.
- The system should allow **users to make a booking reservation**.
- Admin should be able to **cancel or modify bookings**.

### Non-functional Requirements

Non-functional Requirements define **how the system should behave**, focusing on performance, usability, reliability, etc.

**Examples for Booking Management Project:**
- The booking system should **respond within 2 seconds** for any booking search.
- The system must support **500 concurrent users** without downtime.
- The UI must be **accessible on both desktop and mobile devices**.

---

## Use Case Diagrams

### What is a Use Case Diagram?

A Use Case Diagram is a **visual representation of the interactions between users (actors) and the system (use cases)**. It helps in understanding **who uses the system and for what purpose**.

### Benefits:
- Provides a clear picture of system functionality.
- Helps identify all system actors and their interactions.
- Useful for both technical teams and business stakeholders.

### Use Case Diagram for the Booking System:

![Use Case Diagram](./alx-booking-uc.png)

**Actors:**
- User
- Admin
- Payment Gateway

**Use Cases:**
- Search Rooms
- Book Room
- Cancel Booking
- Modify Booking
- Make Payment
- Generate Booking Report

*(Diagram created using Draw.io and saved as `alx-booking-uc.png`)*

---

## Acceptance Criteria

### Importance of Acceptance Criteria:

Acceptance Criteria are **predefined conditions** that a software feature must meet to be considered complete and acceptable by stakeholders. They ensure that both the development team and the client have the **same understanding of the expected outcome**.

### Example: Acceptance Criteria for "Checkout" Feature in Booking Management System:

- Users must be able to **review booking details** before checkout.
- Users must provide valid **payment information**.
- The system must **process payment securely**.
- A **booking confirmation page** must be displayed after successful checkout.
- The system should **send a booking confirmation email** to the user.

---

## Manual Check

This repository (`requirement-analysis`) now contains all the required sections as specified:

- [x] What is Requirement Analysis?
- [x] Why is Requirement Analysis Important?
- [x] Key Activities in Requirement Analysis
- [x] Types of Requirements
- [x] Use Case Diagrams (including image link)
- [x] Acceptance Criteria

