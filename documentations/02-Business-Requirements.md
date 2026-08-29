# Business Requirements

## BR-01: Submit Movie Ticket Request

Customers must be able to submit:

- Customer Name
- Customer Email
- Movie Name
- Show Date
- Show Time
- Show Type
- Number of Tickets

## BR-02: Validate Booking Information

All mandatory information must be completed.

Customer Email must use a valid email format.

Show Date cannot be in the past.

Number of Tickets must be greater than zero.

## BR-03: Check Show Availability

The Booking Agent must verify:

- Seat Availability Status
- Available Seats Count

Booking can proceed only when seats are available.

## BR-04: Calculate Booking Cost

Total Cost must be calculated automatically.

Formula:

Total Cost = Ticket Price × Number of Tickets

## BR-05: Customer Confirmation

The customer must review booking information and select:

- Confirmed
- Cancelled

Confirmed requests continue to ticket processing.

Cancelled requests are resolved without ticket processing.

## BR-06: Ticket Processing

Successful bookings must maintain:

- Booking Confirmation Status
- Seat Numbers
- Ticket ID

## BR-07: Queue Routing

Premium shows must be routed to:

PremiumShowQueue

Standard shows must be routed to:

StandardShowQueue

## BR-08: SLA

Goal: 1 day

Deadline: 2 days

The case should be flagged when the goal is missed and priority should increase when the deadline is missed.

## BR-09: Confirmation Notification

Successful bookings must generate an automated confirmation notification containing booking details.
