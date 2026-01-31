# Rishi & Marilyn's Wedding Invitation

A beautiful, responsive, and interactive wedding invitation application built with React and Tailwind CSS.
This application is designed to run as a standalone HTML file without needing a complex Node.js build process.

## Features
- **Countdown Timer**: Real-time countdown to the wedding date.
- **Event Schedule**: Detailed itinerary of the wedding events.
- **RSVP Form**: Interactive form for guests to confirm attendance (requires Firebase).
- **Admin Panel**: Secure(ish) area for the host to view RSVPs.

## Setup
1. **Open `index.html`**: Simply open the file in any modern web browser.
2. **Firebase Config**: Update the `window.__firebase_config` object in `index.html` with your actual Firebase project details.

## Data Storage Note
- **GitHub**: Stores the **code** and **website files**.
- **Firebase**: Stores the **RSVP data** (guest names, messages).
*Note: You must set up a free Firebase project for the RSVPs to be saved permanently. Without it, the app runs in "Mock Mode" and data is not saved.*

## Technologies
- **React**: UI Library (loaded via ESM CDN).
- **Tailwind CSS**: Styling (loaded via CDN).
- **Firebase**: Backend for Auth and Database.
- **Lucide React**: Icon library.
