# TicketManagerService

The ticket management service is responsible for managing the tickets available for sale in each event registered in the TicketFlow application. It allows users to view available tickets, purchase tickets and reserve tickets for future purchases.

### Endpoints

* **/events/{id}/tickets** (GET) - endpoint to list all available tickets for a specific event.
* **/events/{id}/tickets/{ticketId}/buy** (GET) - endpoint to buy a ticket.
* **/events/{id}/tickets/{ticketId}/reserve** (PUT) - endpoint to reserve a ticket.

### Dependencies
* Spring Boot
*	Spring Data JPA
*	Flyway
*	MongoDB
*	PostgreSQL
