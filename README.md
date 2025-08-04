# Turkey Creek Cycles - Legend

A modern, responsive website for Turkey Creek Cycles, showcasing custom motorcycle builds, services, and company information.

## About

Turkey Creek Cycles is a custom motorcycle shop specializing in Harley-Davidson builds, performance upgrades, and custom fabrication. This website serves as their digital presence, featuring:

- Custom motorcycle gallery
- Service offerings
- Company history and information
- Interactive chatbot for customer inquiries
- Contact information and location details

## Preview

- **Website**: [Turkey Creek Cycles](https://kiernan-dev.github.io/tcc-react-legend/)

## Tech Stack

- **Frontend**: React 18 + TypeScript
- **Styling**: Tailwind CSS with custom animations
- **UI Components**: Radix UI + shadcn/ui
- **Routing**: Wouter
- **State Management**: TanStack Query
- **Backend**: Express.js + TypeScript
- **Database**: Drizzle ORM with PostgreSQL
- **Build Tool**: Vite
- **Deployment**: GitHub Pages

## Project Structure

```
tcc-react-legend/
├── client/                 # Frontend React application
│   ├── public/            # Static assets and images
│   │   └── images/        # Motorcycle photos and branding
│   └── src/
│       ├── components/    # React components
│       │   ├── ui/        # Reusable UI components
│       │   └── chatbot/   # AI chatbot integration
│       ├── pages/         # Page components
│       ├── hooks/         # Custom React hooks
│       └── lib/           # Utilities and configurations
├── server/                # Backend Express server
├── shared/                # Shared types and schemas
└── dist/                  # Build output
```

## Development

### Prerequisites

- Node.js (v18+)
- pnpm (recommended) or npm

### Installation

```bash
# Clone the repository
git clone https://github.com/kiernan-dev/tcc-react-legend.git
cd tcc-react-legend

# Install dependencies
pnpm install
```

### Running the Development Server

```bash
# Start the development server
pnpm run dev
```

The application will be available at `http://localhost:5173`

### Building for Production

```bash
# Build the application
pnpm run build

# Preview the production build
pnpm run preview
```

## Deployment

This project is configured for deployment to GitHub Pages:

```bash
# Deploy to GitHub Pages
pnpm run deploy
```

The site is automatically deployed to: https://kiernan-dev.github.io/tcc-react-legend/

## Features

- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Interactive Gallery**: Showcase of custom motorcycle builds with detailed images
- **Service Information**: Comprehensive list of services offered
- **AI Chatbot**: Interactive customer support powered by AI
- **Performance Optimized**: Fast loading with modern web technologies
- **SEO Friendly**: Proper meta tags and structured content

## Design System

The website uses a custom design system based on:
- **Colors**: Custom TCC brand colors with dark theme
- **Typography**: Inter font family for clean, modern text
- **Components**: Consistent UI components using Radix UI primitives
- **Animations**: Smooth transitions and hover effects using Framer Motion

## License

This project is private and proprietary to Turkey Creek Cycles.

---

Built with ❤️ for the motorcycle community