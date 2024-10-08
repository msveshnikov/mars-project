# Mars Project Modernization (build by [AutoCode](https://autocode.work) in 20 minutes)

## Overview

This project modernizes and resurrects the Mars application using contemporary technologies and best practices, offering an  immersive and interactive experience for exploring the Red Planet. Converted from old Delphi code.

# DEMO

https://mars-project-autocode.onrender.com/

## Project Structure

-   `public/js/web.js`: Main application logic (for Browser)
-   `public/css/styles.css`: Custom styles for the application
-   `public/images/hero.avif`: Hero image for landing page
-   `index.js`: Entry point for the Express server
-   `views/*.ejs`: EJS templates for dynamic content
-   `eslint.config.mjs`: ESLint configuration for code quality
-   `Dockerfile`: Container configuration for deployment
-   `docker-compose.yml`: Multi-container Docker setup
-   `prometheus.yml`: Prometheus configuration for monitoring
-   `grafana-dashboard.json`: Grafana dashboard for visualizing metrics

## Features

-   Interactive 3D Mars terrain visualization
-   Real-time weather simulation with dedicated weather view
-   Responsive design for various devices
-   Server-side rendering with EJS templates
-   Data visualization tools for Mars statistics
-   Dynamic theming based on Mars time of day
-   Multi-language support for global accessibility
-   Containerized deployment with Docker
-   Automated CI/CD pipeline
-   Prometheus and Grafana integration for monitoring and analytics
-   WebSocket integration for real-time updates
-   Dark mode toggle for improved user experience

## Technology Stack

-   Frontend: HTML5, CSS3, JavaScript (ES6+)
-   Backend: Node.js with Express.js
-   3D Rendering: Three.js
-   Templating: EJS
-   Linting: ESLint with custom configuration
-   CSS Framework: Tailwind CSS
-   Containerization: Docker
-   CI/CD: GitHub Actions
-   Monitoring: Prometheus and Grafana

## Getting Started

1. Clone the repository
2. Install dependencies: `npm install`
3. Start the development server: `npm run dev`

## Development

-   Use ESLint for code linting with custom rules
-   Use Git flow for version control
-   Utilize EJS templates for server-side rendering
-   Implement responsive design using Tailwind CSS
-   Follow accessibility guidelines (WCAG 2.1)
-   Write unit and integration tests using Jest

## Deployment

-   Build and run Docker containers: `docker-compose up --build`
-   CI/CD pipeline automatically deploys to staging and production environments
    Monitor application performance using Prometheus and Grafana
-   Use environment variables for configuration management

## Future Enhancements

-   Virtual Reality (VR) support using WebXR
-   Augmented Reality (AR) features for mobile devices
-   Collaborative exploration features with WebRTC
-   Integration with NASA APIs for real-time Mars data
-   WebGL-based terrain generation for custom Mars landscapes
-   Voice commands and natural language processing for navigation
-   Machine learning models for predictive Mars weather forecasting
-   Integration with satellite imagery APIs for real-time surface updates
-   Implement WebAssembly for performance-critical computations
-   Add support for 3D printing of custom Mars terrain models
-   Implement social sharing features for discoveries and screenshots
-   Create an API for third-party developers to extend functionality

## Contributing

Please read CONTRIBUTING.md for details on our code of conduct and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgments

-   NASA for providing Mars data and imagery
-   OpenAI for AI-assisted development
-   The open-source community for invaluable tools and libraries

# TODO

-   get rid of any i18n or multilanguage
-   get rid of PWA fully
-   make Data Visualizations small (on main page)
-   make weather map colorful (from green to red)