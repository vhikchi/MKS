# MKS PPIC System

Production Planning and Inventory Control System built with React + Vite + TypeScript.

## Features

- 🎯 **PPIC Module**: Production scheduling (Loom & Extruder), SO tracking, SPK management
- 📦 **Stock Module**: Real-time inventory tracking for MKS & RCM warehouses
- 💼 **Marketing Module**: Sales order management, pricing calculators
- 👥 **Admin Module**: User management with permission-based access control
- 🌙 **Dark Mode**: Toggle between light and dark themes
- 📱 **Responsive**: Mobile-friendly interface
- 📄 **PDF Export**: Export Gantt charts and reports
- 🔄 **Google Sheets Integration**: Sync data with Google Sheets

## Tech Stack

- **React 18** - UI library
- **TypeScript** - Type safety
- **Vite** - Build tool & dev server
- **TailwindCSS** - Styling
- **Zustand** - State management
- **React Router** - Navigation
- **TanStack Query** - Data fetching & caching
- **React Hook Form + Zod** - Form validation
- **Lucide React** - Icons

## Getting Started

### Prerequisites

- Node.js 18+ and npm/yarn/pnpm

### Installation

\`\`\`bash
# Install dependencies
npm install

# Copy environment variables
cp .env.example .env.local

# Start development server
npm run dev
\`\`\`

The app will open at [http://localhost:3000](http://localhost:3000)

### Build for Production

\`\`\`bash
npm run build
npm run preview
\`\`\`

## Project Structure

\`\`\`
src/
├── app/              # App configuration & providers
├── features/         # Feature modules (auth, ppic, stock, etc.)
├── components/       # Shared UI components
├── lib/              # Third-party configs
├── hooks/            # Global hooks
├── services/         # API services
├── store/            # Global state
├── utils/            # Utility functions
├── types/            # TypeScript types
├── styles/           # Global styles
└── config/           # App configuration
\`\`\`

## Default Credentials

- **Username**: admin
- **Password**: 123

## License

Proprietary - MKS Internal Use Only
