# Data Model

## Movie Ticket Request

Key properties:

- Customer Name
- Customer Email
- Movie
- Movie Name
- Genre
- Show
- Show Date
- Show Time
- Show Type
- Number of Tickets
- Seat Availability Status
- Available Seats Count
- Ticket Price
- Total Cost
- Booking Status
- Booking Confirmation Status
- Seat Numbers
- Ticket ID

## Movie Data Object

Properties:

- Movie Name
- Genre

The Movie object is reusable across multiple booking requests.

## Show Data Object

Properties:

- Movie Name / Movie Reference
- Show Date
- Show Time
- Show Type
- Seat Capacity
- Available Seats Count
- Ticket Price

The Show object is maintained independently and can be reused by multiple booking requests.

## Additional Data

The application also contains supporting data for:

- Customer
- Booking Agent
- Ticket
- Work Queue
- Booking Confirmation Correspondence
