# EventEase 

A simple event management system â€” organizers create events, participants RSVP and get a QR code, staff scan it at the door. Built with Node.js, Express, and SQLite.

## Run it

```bash
npm install
npm start
```

Open **http://localhost:3000**.

## Login

| Role | Email | Password |
|------|-------|----------|
| Admin | `admin@eventease.al` | `admin123` |
| Organizer | `org@eventease.al` | `org123` |
| Participant | `user@eventease.al` | `user123` |

## Features

- Register / login with roles (participant, organizer, staff, admin)
- Organizers create & manage events
- Participants RSVP and confirm attendance
- QR code per confirmed attendee, scanned at entry
- Admin panel for users & events