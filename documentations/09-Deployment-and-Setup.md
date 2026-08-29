# Setup and Deployment

## Platform

Pega Platform

## Application

CineWave Movie Ticket Booking Management

## Primary Case

Movie Ticket Request

## Blueprint

The application was designed using Pega Blueprint and generated into Pega App Studio.

## Application Import

The Pega application can be deployed/imported using the appropriate Pega application package/export generated from the development environment.

## Required Components

- CineWave application
- Movie Ticket Request case type
- Movie data object
- Show data object
- Customer data
- Booking Agent
- Ticket data
- Work queues
- Business rules
- SLA configuration
- Booking confirmation correspondence

## Validation After Deployment

After deployment, verify:

1. Application opens successfully.
2. Movie Ticket Request can be created.
3. Booking form accepts valid information.
4. Invalid information is rejected.
5. Availability validation works.
6. Total Cost is calculated.
7. Customer confirmation works.
8. Cancellation works.
9. Premium routing works.
10. Standard routing works.
11. Ticket ID is generated.
12. Seat Numbers are recorded.
13. SLA is active.
14. Confirmation notification is generated after successful booking.
