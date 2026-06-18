# Database Design

## Ticket Table

| Field             | Type     | Description                         |
| ----------------- | -------- | ----------------------------------- |
| ticket_id         | Integer  | Unique ticket ID                    |
| title             | String   | Incident title                      |
| description       | Text     | Incident description                |
| category          | String   | Application, Database, Network      |
| severity          | String   | Critical, High, Medium, Low         |
| status            | String   | Open, In Progress, Resolved, Closed |
| assigned_engineer | String   | Engineer handling ticket            |
| created_at        | DateTime | Ticket creation time                |
| updated_at        | DateTime | Last updated time                   |
| resolution_notes  | Text     | Resolution details                  |

## Categories

* Application
* Database
* Network
* Infrastructure
* Security

## Severity Levels

* Critical
* High
* Medium
* Low

## Status

* Open
* In Progress
* Resolved
* Closed

