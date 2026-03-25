# VideoBelajar-Full

A premium, high-performance video learning platform built with **React**, **Vite**, and **Tailwind CSS**. This project features a modern feature-based architecture, full mobile responsiveness, and clean, human-written code.

## Key Features

- **Fully Responsive**: Optimized for all devices, from mobile phones to high-resolution desktops.
- **Premium UI/UX**: Modern design with consistent branding, smooth transitions, and intuitive navigation.
- **Scalable Architecture**: Organized using a feature-based structure for easy maintenance and expansion.
- **Clean Code**: Refactored to remove AI-generated artifacts and comments, adhering to professional coding standards.
- **Complete Flow**: Includes course browsing, product details, payment checkout, and student dashboards.

##  Tech Stack

- **Frontend**: React 18+
- **Build Tool**: Vite
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Routing**: React Router DOM

## Project Structure

```bash
video-belajar-full/
├── app/                  # Main React Application
│   ├── src/
│   │   ├── assets/       # Static assets (images, logos)
│   │   ├── components/   # Shared UI components (Button, Accordion, etc.)
│   │   ├── features/     # Feature-based modules (home, courses, checkout, auth)
│   │   ├── layouts/      # Global layouts (Navbar, Footer, Sidebar)
│   │   ├── pages/        # Route-level page components
│   │   ├── App.jsx       # Root component & Routing
│   │   └── main.jsx      # Entry point
│   ├── tailwind.config.js
│   └── vite.config.js
└── README.md             # This file
```

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

1. Navigate to the application directory:
   ```bash
   cd app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

### Building for Production

To create a production-ready bundle:
```bash
npm run build
```

The output will be generated in the `app/dist/` directory.

## License

This project is for educational purposes. All rights reserved.
