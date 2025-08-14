# Restaurant Management System - Frontend

This is the frontend for the Restaurant Management System, built with React and Vite. It provides a modern, responsive interface for admins, staff, and customers to interact with the restaurant's backend system.

## Features
- Admin dashboard: manage menu, tables, staff, reservations, orders, feedback, and analytics
- Customer portal: browse menu, place orders, reserve tables, view order history, give feedback
- Staff (waiter/chef) views: manage assigned tables, kitchen orders, and billing
- Real-time updates and notifications (where supported)
- Beautiful UI with Chakra UI and PrimeReact components

## Getting Started

### Prerequisites
- Node.js (v18 or above recommended)
- Backend API running (see `../backend/README.md`)

### Setup & Run
1. Install dependencies:
	```sh
	npm install
	```
2. Start the development server:
	```sh
	npm run dev
	```
3. Open [http://localhost:5173](http://localhost:5173) in your browser.

### Build for Production
```sh
npm run build
```

### Linting
```sh
npm run lint
```

## Project Structure
- `src/components/` - Reusable UI components
- `src/pages/` - Main pages for each user role
- `src/assets/images/` - Images and icons
- `public/` - Static files

## Notes
- Make sure the backend API is running and accessible for full functionality.
- Configure any required environment variables (see `.env.example` if present).

---
For backend setup, see the `../backend/README.md` file.
