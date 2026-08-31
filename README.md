# BookUrShows

BookUrshows is a Pega-based movie ticket booking application that automates the complete booking lifecycle from customer request submission to successful ticket confirmation.

## Overview

The application allows customers to:

- Submit movie ticket booking requests
- Select movie, show date, show time, and show type
- Specify the number of tickets
- Check show and seat availability
- View the calculated booking cost
- Confirm or cancel a booking
- Receive an automated booking confirmation

Booking Agents can verify availability, process bookings, allocate seats, and manage ticket confirmation.

## Business Objective

The main objective of BookUrShows is to simplify and automate the movie ticket booking process while improving booking accuracy, seat availability validation, cost calculation, routing, and customer communication.

## Case Type

**Movie Ticket Request**

## Case Lifecycle

```text
Submit Movie Ticket Request
          ↓
Check Show Availability
          ↓
Calculate Booking Cost
          ↓
Review Booking Details
          ↓
Confirm Booking Request
          ↓
Route by Show Type
          ↓
Process Ticket Booking
          ↓
Generate Ticket ID & Seat Numbers
          ↓
Complete Booking
          ↓
Send Booking Confirmation
