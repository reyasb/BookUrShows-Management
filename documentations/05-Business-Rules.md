# Business Rules

## Validation Rules

1. All mandatory booking fields must be completed.
2. Customer Email must be valid.
3. Show Date cannot be in the past.
4. Number of Tickets must be greater than zero.
5. Number of Tickets cannot exceed Available Seats Count.
6. Booking can proceed only when Seat Availability Status is Available.

## Calculation Rule

Total Cost = Ticket Price × Number of Tickets

## Customer Decision

If Booking Status = Confirmed:

Continue to Booking Execution.

If Booking Status = Cancelled:

Resolve the case as cancelled.

## Queue Routing

If Show Type = Premium:

PremiumShowQueue

If Show Type = Standard:

StandardShowQueue

## Successful Booking

A successful booking requires:

Booking Status = Confirmed

AND

Booking Confirmation Status = Confirmed

The system then maintains Ticket ID and Seat Numbers.
