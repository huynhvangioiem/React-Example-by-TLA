# React Hooks Learning Project

An interactive learning platform for React hooks, concepts, and best practices. Built with React 19, TypeScript, and Vite, featuring a modern UI powered by TailwindCSS.

**Live Demo:** [https://huynhvangioiem.github.io/React-Example-by-TLA/](https://huynhvangioiem.github.io/React-Example-by-TLA/)

## Project Overview

This project provides a structured educational experience for learning React, organized into three main sections:

### 1. Hello React (Fundamentals)

- **JSX** - JavaScript XML syntax basics
- **Components & Props** - Building reusable components
- **State & Events** - Managing component state and handling events
- **Conditional Rendering & Lists** - Dynamic content rendering
- **Component Composition** - Composing components together

### 2. React Hooks

- **useState** - State management in functional components
- **useEffect** - Side effects and component lifecycle
- **useCallback** - Memoizing callback functions
- **useMemo** - Memoizing expensive calculations
- **useRef** - Persistent mutable values and DOM access
- **useContext** - Sharing data without prop drilling
- **useReducer** - Complex state management with reducers
- **Custom Hooks** - Creating reusable hook patterns (useDebounce, useLocalStorage)

### 3. Built-in React APIs

- **React.memo** - Component memoization for performance
- **React.lazy** - Code splitting and lazy loading
- **React.Suspense** - Loading states and fallback UI
- **Error Boundaries** - Graceful error handling in component trees

Each example includes:

- Detailed explanations and overview
- Interactive live demonstrations
- Code snippets with syntax highlighting
- Best practices and common pitfalls
- Real-world use cases

## Getting Started

### Prerequisites

- Node.js (version 20 or higher)
- npm (version 10 or higher) or yarn

### Installation

1. Clone the repository:

```bash
git clone https://github.com/huynhvangioiem/React-Example-by-TLA.git
cd reactjs-example
```

2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

## Project Structure

```
reactjs-example/
├── src/
│   ├── components/
│   │   ├── examples/      # Example implementations (17 categories)
│   │   ├── home/          # Home page components
│   │   ├── ui/            # Reusable UI components
│   │   ├── Header.tsx     # Site header
│   │   ├── Footer.tsx     # Site footer
│   │   ├── ExampleHeader.tsx
│   │   ├── ExampleSidebar.tsx
│   │   └── NavigationCard.tsx
│   ├── pages/             # Page components (18 routes)
│   ├── lib/               # Utility functions
│   ├── App.tsx            # Router configuration
│   └── main.tsx           # Application entry point
├── public/                # Static assets
├── index.html             # HTML entry point
├── vite.config.ts         # Vite configuration
├── tsconfig.json          # TypeScript configuration
├── tailwind.config.ts     # TailwindCSS configuration
├── components.json        # UI components configuration
└── package.json           # Project dependencies and scripts
```

## Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the project for production (includes TypeScript build)
- `npm run preview` - Preview the production build
- `npm run lint` - Run ESLint for code quality

## Technologies Used

- **React** (v19) - Latest version with improved features
- **TypeScript** (v5.7) - For type safety and better developer experience
- **Vite** (v6.2) - Fast build tool and development server
- **TailwindCSS** (v4.0) - Utility-first CSS framework
- **React Router DOM** (v7.4) - For client-side routing
- **Radix UI** - For accessible UI components
- **Lucide React** - For beautiful icons
- **Class Variance Authority** - For type-safe component variants

## Features

- **Interactive Examples** - Live, editable demos for each concept
- **Sidebar Navigation** - Easy navigation within each topic
- **Responsive Design** - Works on desktop and mobile devices
- **Type Safety** - Full TypeScript implementation
- **Modern React** - Uses React 19 with latest patterns and best practices
- **Accessible UI** - Built with Radix UI primitives
- **Custom Animations** - Smooth transitions with tw-animate-css

## Contributing

Feel free to contribute to this project by:

1. Forking the repository
2. Creating a feature branch (`git checkout -b feature/amazing-feature`)
3. Committing your changes (`git commit -m 'Add some amazing feature'`)
4. Pushing to the branch (`git push origin feature/amazing-feature`)
5. Creating a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- React Team for the amazing framework
- Vite Team for the blazing fast build tool
- TailwindCSS Team for the utility-first CSS framework
- All contributors who help improve this project
