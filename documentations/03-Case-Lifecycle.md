# Case Lifecycle

## Case Type

Movie Ticket Request

## Stage 1: Booking Request

### Submit Movie Ticket Request

Customer provides:

- Customer Name
- Customer Email
- Movie Name
- Show Date
- Show Time
- Show Type
- Number of Tickets

Mandatory fields and input validation are applied.

---

## Stage 2: Availability

### Check Show Availability

Booking Agent verifies:

- Seat Availability Status
- Available Seats Count
- Ticket Price
- Number of Tickets

Booking proceeds only when:

Seat Availability Status = Available

AND

Available Seats Count >= Number of Tickets

### Calculate Booking Cost

The system calculates:

Total Cost = Ticket Price × Number of Tickets

---

## Stage 3: Approval

### Review Booking Details

The customer can review:

- Movie Name
- Show Date
- Show Time
- Show Type
- Number of Tickets
- Ticket Price
- Total Cost

### Confirm Booking Request

Customer selects:

- Confirmed
- Cancelled

Confirmed requests continue.

Cancelled requests are resolved.

---

## Stage 4: Booking Execution

### Route Work Queue

Show Type determines routing.

Premium → PremiumShowQueue

Standard → StandardShowQueue

### Process Ticket Booking

Booking Agent:

- Allocates seats
- Records Seat Numbers
- Generates Ticket ID
- Updates Booking Confirmation Status

---

## Completion

Successful booking:

- Booking Status = Confirmed
- Booking Confirmation Status = Confirmed
- Ticket ID generated
- Seat Numbers recorded
- Case resolved successfully
- Confirmation notification sent
