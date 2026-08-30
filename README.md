# NIP Movie Ticket Booking

## Project Overview

The Movie Ticket Booking application is a Pega Platform-based application designed to manage the complete movie ticket booking process.

The application allows customers to submit booking requests, search for movies and shows, check availability, calculate booking cost, review booking details, process payments, generate tickets, and receive booking confirmation.

## Project Details

- **Project:** Movie Ticket Booking
- **Platform:** Pega Platform
- **Application:** NIP-MovieTicket-Roshini-K
- **Case Type:** Movie Ticket Booking
- **Student:** Roshini K
- **Course:** AI & DS
- **College:** Bannari Amman Institute of Technology

## User Stories

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

## Application Workflow

The application follows this general flow:

Submit Request  
→ Search Movie and Show  
→ Check Show Availability  
→ Suggest Alternate Show if unavailable  
→ Calculate Booking Cost  
→ Review Booking Details  
→ Confirm Booking  
→ Process Payment  
→ Generate Ticket  
→ Send Ticket  
→ Booking Confirmation

## Data Objects

### Movie

- Movie Name
- Genre
- Duration
- Language

### Show

- Movie
- Show Date
- Show Time
- Ticket Price
- Seat Capacity
- Available Seats

## Key Features

- Movie ticket request submission
- Movie and show selection
- Show availability checking
- Alternate show suggestion
- Automatic booking cost calculation
- Booking review
- Payment processing
- Ticket generation
- Booking confirmation
- SLA management
- Show-type based routing

## Repository Structure

```text
Blueprint/
    MovieTicketBooking.blueprint

Documentation/
    MovieTicket_Roshini_K.docx

Screenshots/
    US-001-Submit-Movie-Ticket-Request.png
    US-002-Check-Show-Availability.png
    ...
    US-010-Route-by-Show-Type.png

Pega/
    Application-Details.md
