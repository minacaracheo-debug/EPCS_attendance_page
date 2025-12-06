# Attendance Dashboard

- A Nuxt.js-based attendance tracking application with calendar integration.
- Allows the user to initiate a check-in action and confirm a check-out.
- Displays the current time.
- Shows current attendance status ("Checked In," "Checked Out," or "Not Checked In").
- Displays a monthly calendar highlighting present days green and future upcoming days blue.

## Features

- ✅ Check-in/Check-out functionality
- 📅 Calendar view with attendance tracking
- 📱 Mobile-responsive design
- 🎨 Modern UI with Tailwind CSS

## Conceptual Overview
- Mobile-first application designed to streamline attendance tracking for staff or participants.
- Its primary goal is to provide a reliable, easy-to-use check-in and check-out for their shift or scheduled activity, while also offering a calendar view of their past attendance and upcoming schedule.

## User Roles
- Students/Participant: The primary user. Can check in, check out, view their work time for the day, and review their past attendance and future schedule on the dashboard.
- Administrator: A user who would have access to the participant check-in route and potentially manage and view attendance records for multiple users.

## Third Party Integrations
- Used on the Attendance Dashboard to render the customizable, monthly calendar view and visually track attendance and scheduled days.

## Tech Stack

- **Nuxt 4** - Vue.js framework
- **Tailwind CSS v4** - Styling
- **FullCalendar** - Calendar component
- **TypeScript** - Type safety

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

```bash
# Install dependencies
npm install

# Start development server
npm run dev
```

The application will be available at `http://localhost:3000`

### Build for Production

```bash
# Build the application
npm run build

# Preview production build
npm run preview
```

## Project Structure

```
attendance_dash/
├── assets/
│   └── css/
│       └── main.css          # Global styles and Tailwind imports
├── components/
│   ├── AttendanceCard.vue    # Main attendance card component
│   ├── CalendarSection.vue    # Calendar display component
│   ├── CheckoutModal.vue     # Checkout confirmation modal
│   └── HamburgerMenu.vue     # Navigation menu
├── layouts/
│   └── default.vue           # Default layout with header
├── pages/
│   ├── index.vue             # Home/attendance page
│   └── participant-checkin.vue # Participant check-in page
├── app.vue                   # Root component
└── nuxt.config.ts            # Nuxt configuration
```

## Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run generate` - Generate static site
- `npm run preview` - Preview production build

