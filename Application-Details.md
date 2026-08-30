
# Pega Application Details

## Application Information

- **Application Name:** NIP-MovieTicket-Roshini-K
- **Case Type:** Movie Ticket Booking
- **Platform:** Pega Platform
- **Project:** Movie Ticket Booking
- **Organization:** Bannari Amman Institute of Technology
- **Course:** AI & DS

## Application Purpose

The purpose of this application is to provide a simple and efficient movie ticket booking system. It manages the booking process from submitting a ticket request to final booking confirmation.

## Application Description

The Movie Ticket Booking application allows customers to submit a movie ticket request, search and select a movie and show, check show availability, calculate the booking cost, review booking details, confirm the booking, process payment, generate a ticket, and receive booking confirmation.

## Case Lifecycle

The Movie Ticket Booking case follows these stages:

1. Request Submission
2. Show Availability
3. Confirmation & Payment
4. Ticket Processing
5. Booking Confirmation

## User Stories Implemented

The application addresses the following ten user stories:

1. Submit Movie Ticket Request
2. Check Show Availability
3. Calculate Booking Cost
4. Confirm Booking Request
5. Maintain Movie and Show Data
6. Review Booking Details
7. Process Ticket Booking
8. Notify Booking Confirmation
9. Define Booking SLA
10. Route by Show Type

## Data Objects

### Movie

The Movie data object stores movie-related information.

Properties:
- Movie Name
- Genre
- Duration
- Language

### Show

The Show data object stores information about available movie shows.

Properties:
- Movie
- Show Date
- Show Time
- Ticket Price
- Seat Capacity
- Available Seats

## Key Business Logic

### Booking Cost Calculation

The total booking cost is calculated automatically using:

Total Cost = Ticket Price × Number of Tickets

The calculated total cost is displayed to the customer before payment.

### Show Availability

The application checks the availability of seats for the selected movie and show. If the selected show is unavailable, an alternate show can be suggested.

### Booking Confirmation

After successful booking and payment processing, the booking status is updated and ticket details are generated for the customer.

## Routing

The application supports routing based on Show Type:

- PremiumShowQueue
- StandardShowQueue

Premium shows are routed to the PremiumShowQueue, while standard shows are routed to the StandardShowQueue.

## SLA

The Movie Ticket Booking case has an SLA configuration with:

- Goal: 1 day
- Deadline: 2 days
- Priority increase on SLA breach

## Project Evidence

The `Blueprint` folder contains the Pega Blueprint file used to create the application.

The `Documentation` folder contains the completed project submission document.

The `Screenshots` folder contains screenshots demonstrating the implementation of the ten user stories.
