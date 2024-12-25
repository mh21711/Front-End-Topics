# Front-End Development Topics

## JavaScript Core Concepts

### Closures, Scope, and Hoisting
- **Closures**: Functions that "remember" the variables from their lexical scope even when executed outside that scope.
- **Scope**: Determines the accessibility of variables (e.g., global, function, or block scope).
- **Hoisting**: JavaScript's default behavior of moving declarations to the top of the code during the compilation phase.

### Promises and Async/Await
- **Promises**: Objects that represent the eventual completion or failure of an asynchronous operation.
- **async/await**: Syntactic sugar for working with Promises, making asynchronous code look synchronous.

### Event Loop and Callbacks
- Describes how JavaScript handles asynchronous operations using the call stack, callback queue, and microtask queue.

### Prototypes and Inheritance
- **Prototypes**: JavaScript's mechanism for inheritance, allowing objects to share methods.
- **Inheritance**: Enables objects to inherit properties and methods from other objects.

### Module Systems (ESM, CommonJS)
- **ESM (ES Modules)**: Modern JavaScript modules using `import/export`.
- **CommonJS**: Older module system used in Node.js with `require/module.exports`.

---

## React and State Management

### React Lifecycle and Hooks (useEffect, useMemo, etc.)
- **React Lifecycle**: The phases of a React component (Mounting, Updating, Unmounting).
- **Hooks**: Functions like `useEffect`, `useState`, and `useMemo` to manage side effects, state, and performance.

### Context API and State Management (Redux, Zustand, etc.)
- **Context API**: React's built-in state management for sharing data between components.
- **Redux/Zustand**: Third-party libraries for advanced state management.

### React Performance Optimization
- Techniques such as memoization, lazy loading, and avoiding unnecessary re-renders.

### Server-Side Rendering (Next.js)
- Pre-rendering pages on the server for better performance and SEO using frameworks like Next.js.

### Dynamic Routing and Code Splitting
- **Dynamic Routing**: Creating routes at runtime (e.g., `[id].js` in Next.js).
- **Code Splitting**: Splitting code into smaller chunks to load only what's needed.

### Lazy Loading and Code Splitting
- Loading components or resources only when needed to improve performance.

---

## Web Performance

### Critical Rendering Path
- Steps the browser takes to render a web page, focusing on minimizing render-blocking resources.

### Web Vitals (LCP, FID, CLS)
- Core metrics for web performance:
  - **LCP (Largest Contentful Paint)**: Measures loading performance.
  - **FID (First Input Delay)**: Measures interactivity.
  - **CLS (Cumulative Layout Shift)**: Measures visual stability.

### Caching Strategies
- Techniques for caching data to reduce load times (e.g., HTTP caching, service workers).

### CDN Optimization
- Using Content Delivery Networks to serve static assets faster by reducing latency.

---

## CSS and Design

### Responsive Design
- Techniques for building web pages that work on devices of all sizes (media queries, relative units).

### CSS-in-JS (Styled Components, Emotion)
- Embedding CSS styles directly within JavaScript components for dynamic styling.

### Flexbox and Grid Systems
- **Flexbox**: For 1D layouts (rows/columns).
- **CSS Grid**: For 2D layouts (grids with rows and columns).

### Theming and Design Systems
- Creating consistent UI themes and reusable components with tools like Material-UI or custom design systems.

### Component Design Principles
- Principles like reusability, modularity, and separation of concerns when building UI components.

---

## Advanced Architectures

### Monorepo Architectures
- Managing multiple projects (e.g., libraries, apps) within a single repository.

### Micro-Frontends
- Breaking down a front-end app into smaller, independently deployable units.

### State Management Best Practices
- Guidelines for managing state effectively (e.g., avoid overusing global state).

---

## Testing and Debugging

### Unit Testing (Jest, React Testing Library)
- Writing tests for individual components or functions.

### End-to-End Testing (Cypress, Playwright)
- Testing the entire application workflow from start to finish.

### Mocking APIs
- Simulating API responses during testing to isolate app functionality.

### Code Coverage Analysis
- Measuring how much of the codebase is covered by tests.

---

## APIs and Security

### REST vs GraphQL
- **REST**: Standard API design using endpoints.
- **GraphQL**: Flexible query language for APIs.

### Authentication (OAuth, JWT)
- Methods for authenticating users securely (OAuth for third-party login, JWT for tokens).

### Error Handling and Retry Mechanisms
- Techniques for managing errors and retrying failed requests in a robust way.

### WebSockets
- Real-time, bidirectional communication between the client and server.

---

## Build Tools and Deployment

### Webpack, Vite, or Rollup
- Tools for bundling and optimizing front-end assets.

### Code Splitting and Tree Shaking
- **Code Splitting**: Dividing code into smaller chunks.
- **Tree Shaking**: Removing unused code from bundles.

### CI/CD Integration
- Automating build, test, and deployment pipelines.

### Linting and Formatting (ESLint, Prettier)
- Tools for enforcing coding standards and formatting.

---

## Browser and Storage

### CORS and Security (XSS, CSRF)
- Handling cross-origin requests and securing apps from common vulnerabilities.

### Local Storage, Session Storage, Cookies
- Storing data on the client side with different scopes and lifetimes.

### Browser Rendering Mechanism
- How the browser parses HTML, CSS, and JavaScript to render a web page.

---

## Progressive Web Apps (PWAs)

### Progressive Web Apps (PWAs)
- Web apps with offline capabilities, push notifications, and installability.

---

## Accessibility

### Accessibility Standards and Best Practices (ARIA, WCAG)
- Ensuring your app is usable by people with disabilities, following standards like WCAG.
