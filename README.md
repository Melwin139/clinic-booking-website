# CareWell Clinic – Appointment Booking Website (Demo)

A fast, mobile-friendly website for a neighbourhood clinic. Patients pick a service, doctor, date and time slot, then confirm the booking with one tap on **WhatsApp**. No backend, no login, no payment gateway needed, which is ideal for small clinics in India.

**Live demo:** https://melwin139.github.io/clinic-booking-website/

> CareWell Clinic is fictional. This is a portfolio project showing the kind of website I build for clinics, coaching classes and local businesses.

## Features

- **Live "Open now / Closed now" status** with the next opening time, worked out from the clinic's timings
- **Smart slot picker**: only shows slots for days the chosen doctor works, hides past times for today, greys out booked slots
- **Doctor filtering by service**: picking "Child health" only shows the paediatrician
- **Form validation**, including a 10-digit Indian mobile number check
- **WhatsApp booking**: opens a pre-filled message with all booking details to the clinic's number
- Floating WhatsApp chat button, FAQ section, responsive layout for phones
- Easy to customise: services, doctors, timings and WhatsApp number live in one config block at the top of the script

## Tech

HTML5, CSS3 (Grid, Flexbox, custom properties) and vanilla JavaScript. No frameworks or build step; deploys free on GitHub Pages or Netlify.

## Run locally

Open `index.html` in a browser.

## Customise for a real clinic

Edit the config block at the top of the `<script>`:

```js
const CLINIC_WHATSAPP = "91XXXXXXXXXX";
const HOURS = { 1: [[9,13],[17,21]], /* ... */ };
const SERVICES = [ /* ... */ ];
const DOCTORS = [ /* ... */ ];
```

## Author

**Melwin Naigam**, Web Developer, Pune · [Portfolio](https://melwin139.github.io) · [LinkedIn](https://www.linkedin.com/in/melwinaigam)
