# 📅 Appointment Booking Website (Clinic / Salon)

## Overview
A complete appointment booking website for a salon or clinic. Features a beautiful
hero section, service selection cards, a multi-step booking form with time slots,
team profiles, and an FAQ accordion — with full form validation and confirmation screen.

## Features
- Service selection cards (click to select, auto-fills booking form)
- Multi-step booking form with progress indicator
- Interactive time slot picker (with unavailable slots marked)
- Full form validation before submission
- Confirmation screen with generated booking reference number
- Team member profiles
- FAQ accordion (show/hide answers)
- Email reminder notification logic (frontend demo)
- Mobile responsive design

## Technologies Used
| Tool | Purpose |
|------|---------|
| HTML5 | Structure |
| CSS3 | Styling, Grid, Flexbox |
| JavaScript (Vanilla) | Time slot selection, form validation, FAQ toggle |
| WordPress + Bookly | Real booking backend (WordPress version) |
| Zapier / WP Mail | Email notifications (WordPress version) |

## Project Structure
```
08_appointment_booking/
│
├── index.html     ← Complete standalone website
└── README.md
```

## How to Run

### Standalone
```
Double-click index.html to open in any browser.
```

### WordPress Deployment
1. Install WordPress on your hosting
2. Install **Bookly** plugin (free version):
   - Add services: Haircut, Coloring, Facial, etc.
   - Add staff members
   - Configure working hours and days off
   - Enable email notifications (confirmation + reminder)
3. Install **Elementor** for page design
4. Insert the **[bookly-form]** shortcode on your booking page
5. Configure payment:
   - Enable WooCommerce integration for online payment
   - Or set to "Pay at location" for offline payment
6. Configure email reminders:
   - Bookly → Settings → Notifications
   - Set 24-hour reminder email + SMS via Twilio

## Zapier Automation (optional)
- Trigger: New Bookly appointment created
- Action: Send Slack notification to team
- Action: Add to Google Calendar
- Action: Send WhatsApp reminder (via Twilio)
