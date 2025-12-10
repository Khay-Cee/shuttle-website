# ShuttleSmart

A modern, responsive web application for intelligent shuttle service management and booking.

## About ShuttleSmart

ShuttleSmart is a comprehensive platform designed to simplify shuttle service operations in schools and enhance user experience.ShuttleSmart provides an intuitive interface for seamless interface for real-time shuttle tracking.

## Tech Stack

- **Frontend Framework**: React 19
- **Build Tool**: Vite
- **Routing**: React Router DOM
- **Styling**: CSS
- **Development**: Node.js & npm
- **Code Quality**: ESLint

## Project Structure

```
frontend-web/
├── src/
│   ├── components/          # Reusable React components
│   │   ├── Header.jsx
│   │   ├── Footer.jsx
│   │   ├── HeroHome.jsx
│   │   ├── HeroAbout.jsx
│   │   ├── HeroContact.jsx
│   │   ├── HeroDemo.jsx
│   │   ├── FeaturesSection.jsx
│   │   ├── HowItWorksSection.jsx
│   │   ├── ReliabilitySection.jsx
│   │   ├── HistorySection.jsx
│   │   ├── WhyBuiltSection.jsx
│   │   ├── TimelineSection.jsx
│   │   ├── DataProtectionSection.jsx
│   │   ├── ContactFormSection.jsx
│   │   └── CTA.jsx
│   ├── pages/               # Page components
│   │   ├── HomePage.jsx
│   │   ├── AboutPage.jsx
│   │   ├── DemoPage.jsx
│   │   └── ContactPage.jsx
│   ├── App.jsx              # Main app component
│   ├── main.jsx             # Entry point
│   └── index.css            # Global styles
├── public/                  # Static assets
├── package.json             # Project dependencies
├── vite.config.js           # Vite configuration
├── eslint.config.js         # ESLint rules
├── index.html               # HTML template
└── README.md               # This file
```

## Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js** (v16 or higher)
- **npm** (v7 or higher) - comes with Node.js

You can check your versions by running:
```bash
node --version
npm --version
```

## Installation

1. **Clone the repository** (if you haven't already):
   ```bash
   git clone <repository-url>
   cd shuttle-website/frontend-web
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

## Running the Project

### Development Server

Start the development server with hot module replacement (HMR):

```bash
npm run dev
```

The application will be available at `http://localhost:5173` (or the next available port if 5173 is in use).

### Building for Production

Create an optimized production build:

```bash
npm run build
```

The compiled files will be generated in the `dist/` directory.

### Preview Production Build

Preview your production build locally:

```bash
npm run preview
```

### Lint Code

Check code quality and style issues:

```bash
npm run lint
```

To fix linting issues automatically:

```bash
npm run lint -- --fix
```

## Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server with HMR |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build locally |
| `npm run lint` | Run ESLint to check code quality |

## Pages

- **Home** - Landing page with hero section and key features
- **About** - Learn about ShuttleSmart's mission, history, and why we built it
- **Demo** - Interactive demo of the platform
- **Contact** - Get in touch with our team

## Development Workflow

1. Create a new branch for your feature:
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. Make your changes and test locally with `npm run dev`

3. Lint your code:
   ```bash
   npm run lint
   ```

4. Commit your changes:
   ```bash
   git add .
   git commit -m "Description of your changes"
   ```

5. Push and create a pull request:
   ```bash
   git push origin feature/your-feature-name
   ```

## Performance

This project uses Vite for fast development and optimized production builds. Key optimizations include:

- Fast Hot Module Replacement (HMR) during development
- Optimized bundle splitting for better caching
- Minified and optimized production builds
- Lazy loading of routes for improved performance

## ESLint Configuration

This project includes ESLint for code quality. The configuration enforces:

- React best practices
- React hooks rules
- React refresh compatibility

For more information, see the [ESLint configuration guide](https://eslint.org).

## Contributing

We welcome contributions! Please follow these guidelines:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Write or update tests as needed
5. Ensure your code passes linting (`npm run lint`)
6. Submit a pull request

## License

This project is part of the ShuttleSmart initiative.

## Support

For questions, issues, or suggestions, please reach out to us through:

- **Contact Page**: Visit our [Contact](/) page
- **Email**: Through the contact form on our website
- **GitHub Issues**: Open an issue in the repository

## Troubleshooting

### Port 5173 is already in use

Vite will automatically use the next available port. You can also specify a port manually:

```bash
npm run dev -- --port 3000
```

### Dependencies installation fails

Try clearing the npm cache:

```bash
npm cache clean --force
npm install
```

### Build fails

Ensure all dependencies are installed and up to date:

```bash
npm install
npm run build
```

---

Happy coding! 🚀 For more information, visit our website or contact us through the contact form.
