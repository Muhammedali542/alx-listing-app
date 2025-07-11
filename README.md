# ALX Listing App

A modern, responsive Airbnb clone listing page built with React and TypeScript, designed to showcase property listings with a clean and intuitive user interface.

## Project Overview

The ALX Listing App is a frontend application that replicates the core functionality of Airbnb's property listing interface. This project demonstrates modern web development practices, including component-based architecture, TypeScript integration, and responsive design principles.

### Goals
- Create a pixel-perfect replica of Airbnb's listing page design
- Implement responsive design for optimal viewing across all devices
- Demonstrate proficiency in React, TypeScript, and modern CSS techniques
- Build reusable components following best practices
- Implement proper state management and data flow

## Project Structure

```
alx-listing-app/
├── public/
│   └── assets/           # Static assets (images, icons, fonts)
├── src/
│   ├── components/       # Reusable UI components
│   │   ├── common/       # Shared components (Header, Footer, Button, etc.)
│   │   ├── layout/       # Layout components (Sidebar, Navigation, etc.)
│   │   └── specific/     # Feature-specific components
│   ├── interfaces/       # TypeScript type definitions and interfaces
│   │   ├── index.ts      # Main interface exports
│   │   └── types.ts      # Custom type definitions
│   ├── constants/        # Application constants and configuration
│   │   ├── index.ts      # Main constants exports
│   │   └── config.ts     # Configuration constants
│   ├── pages/            # Page components
│   ├── hooks/            # Custom React hooks
│   ├── utils/            # Utility functions
│   └── styles/           # Global styles and CSS modules
├── package.json
├── tsconfig.json
├── tailwind.config.js
└── README.md
```

### Directory Purpose

- **`components/`**: Contains all reusable UI components organized by functionality. Components are built with reusability and maintainability in mind.

- **`interfaces/`**: Houses TypeScript interfaces and type definitions that ensure type safety throughout the application. This includes property listing types, user interfaces, and API response schemas.

- **`constants/`**: Stores application-wide constants such as API endpoints, configuration values, default settings, and static data that doesn't change during runtime.

- **`public/assets/`**: Contains static assets like images, icons, fonts, and other media files that are served directly by the web server.

## Features

- 🏠 **Property Listings**: Display property cards with images, pricing, and basic information
- 🔍 **Search Functionality**: Filter and search through available properties
- 📱 **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- 🎨 **Modern UI**: Clean, modern interface following Airbnb's design principles
- ⚡ **Performance**: Optimized loading and rendering for smooth user experience
- 🔒 **Type Safety**: Full TypeScript implementation for robust code

## Technologies Used

- **React 18** - Modern React with hooks and functional components
- **TypeScript** - Type-safe JavaScript for better development experience
- **Tailwind CSS** - Utility-first CSS framework for rapid styling
- **Next.js** - React framework for production-ready applications
- **ESLint & Prettier** - Code linting and formatting for consistent code quality

## Getting Started

### Prerequisites

Before running this project, make sure you have the following installed:

- **Node.js** (version 16.0.0 or higher)
- **npm** (version 7.0.0 or higher) or **yarn**
- **Git** for version control

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/alx-listing-app.git
   cd alx-listing-app
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```
   or if you're using yarn:
   ```bash
   yarn install
   ```

3. **Set up environment variables:**
   ```bash
   cp .env.example .env.local
   ```
   Edit `.env.local` with your configuration values.

### Running the Development Server

To start the development server:

```bash
npm run dev
```

or with yarn:

```bash
yarn dev
```

The application will be available at [http://localhost:3000](http://localhost:3000).

### Building for Production

To create a production build:

```bash
npm run build
```

To start the production server:

```bash
npm start
```

### Available Scripts

- `npm run dev` - Starts the development server
- `npm run build` - Creates a production build
- `npm start` - Starts the production server
- `npm run lint` - Runs ESLint to check code quality
- `npm run lint:fix` - Fixes linting issues automatically
- `npm run type-check` - Runs TypeScript type checking

## Development Guidelines

### Code Style

- Follow TypeScript best practices
- Use functional components with hooks
- Implement proper error handling
- Write meaningful component and variable names
- Add comments for complex logic

### Component Structure

```typescript
// Component template
import React from 'react';
import { ComponentProps } from '@/interfaces';

interface Props extends ComponentProps {
  // Component-specific props
}

const ComponentName: React.FC<Props> = ({ prop1, prop2 }) => {
  // Component logic
  
  return (
    <div className="component-container">
      {/* Component JSX */}
    </div>
  );
};

export default ComponentName;
```

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **ALX Software Engineering Program** for the project requirements and guidance
- **Airbnb** for the design inspiration
- **React Community** for the excellent documentation and resources

## Contact

For questions or support, please contact:
- **Email**: muhammedali54254715@gmail.com
- **GitHub**: [@Muhammedali542](https://github.com/Muhammedali542)
- **LinkedIn**: [Muhamed Ali](www.linkedin.com/in/muhamed-ali-b51605224)

---

**Happy Coding!** 🚀
