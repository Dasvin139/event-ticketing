# Event Ticketing & Check-in: PRD

## Problem

Running an event's ticketing and entry process is challenging because organizers often struggle with manual ticket management, payment tracking, duplicate tickets, and slow entry verification. Event organizers spend significant time managing registrations and monitoring attendance, while entry staff face difficulties verifying tickets quickly. Attendees experience long queues and booking-related confusion. Venue managers also struggle to monitor real-time attendance and crowd capacity. These problems highlight the need for a centralized event ticketing system with secure digital tickets, QR-code verification, and real-time attendance tracking.

## Users

- **Organizer:** creates events and ticket types, sees sales and attendance. Needs **easy event management, real-time sales tracking, and attendance reports.**
- **Attendee:** browses events, books tickets, receives a QR ticket. Needs **a simple booking experience, secure payments, instant ticket confirmation, and easy access to tickets.**
- **Entry staff:** scans tickets at the gate. Needs **fast QR-code scanning, instant ticket validation, and duplicate-ticket detection.**


## v1 scope

- Users can register and log in, with roles: organizer, attendee, staff
- Organizer can create, edit and publish an event (date, venue, capacity)
- Organizer can define ticket types with a price and quantity
- Attendee can browse events and view event details
- Attendee can book up to 4 tickets, and two people can never book the last ticket
- Attendee can see their tickets, each with a QR code, under "My tickets"
- Staff can scan a QR code to check a person in, and a second scan of the same ticket is rejected
- Organizer can see tickets sold per type and how many people have checked in

## Later

- Real payments in test mode (Razorpay)
- Live dashboard updates
- Email confirmation with the ticket
- CSV export of the attendee list
- Scanning that keeps working when the network drops

## Out of scope

- Refunds and cancellations
- Venue manager accounts
- Seat maps
- Ticket resale or transfer
- Mobile app
