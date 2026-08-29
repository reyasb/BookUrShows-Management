# Application Overview

## Application Name

CineWave Movie Ticket Booking Management

## Primary Case Type

Movie Ticket Request

## Objective

Automate the end-to-end movie ticket booking process from customer request submission through successful booking confirmation.

## Business Objectives

- Automate movie ticket booking.
- Reduce manual booking effort.
- Validate customer and booking information.
- Ensure requested tickets do not exceed available seats.
- Automatically calculate total booking cost.
- Obtain customer confirmation before processing tickets.
- Route bookings according to show type.
- Maintain booking information for tracking.
- Apply booking SLA requirements.
- Automatically notify customers after successful booking.

## Main Workflow

Customer submits booking request.

The system validates the booking information and moves the request to availability verification.

The Booking Agent checks seat availability and ticket pricing.

The system calculates the total cost.

The customer reviews the booking details and confirms or cancels the request.

Confirmed bookings are routed to the appropriate work queue and processed by the Booking Agent.

The system records seat numbers and generates a Ticket ID.

After successful completion, a confirmation notification is sent to the customer.
