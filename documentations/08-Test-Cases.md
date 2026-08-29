# Test Cases

## TC-01: Successful Booking

Input:

- Valid customer information
- Future show date
- Valid show time
- Available seats
- Number of tickets within capacity
- Show Type = Premium
- Booking Status = Confirmed

Expected Result:

- Booking proceeds.
- Case routes to PremiumShowQueue.
- Seats are allocated.
- Ticket ID is generated.
- Booking Confirmation Status = Confirmed.
- Case completes successfully.
- Confirmation notification is sent.

---

## TC-02: Standard Show Booking

Show Type = Standard

Expected Result:

Case routes to:

StandardShowQueue

---

## TC-03: Invalid Email

Enter an invalid Customer Email.

Expected Result:

Email validation prevents submission.

---

## TC-04: Past Show Date

Enter a past Show Date.

Expected Result:

Validation prevents submission.

---

## TC-05: Zero Tickets

Number of Tickets = 0

Expected Result:

Validation prevents submission.

---

## TC-06: Insufficient Seats

Available Seats Count = 2

Number of Tickets = 5

Expected Result:

Booking cannot proceed.

---

## TC-07: Cancelled Booking

Booking Status = Cancelled

Expected Result:

Case is resolved as cancelled.

No ticket is processed.

No successful booking confirmation is sent.

---

## TC-08: Cost Calculation

Ticket Price = 200

Number of Tickets = 3

Expected Result:

Total Cost = 600
