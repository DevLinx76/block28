# React Router Workshop

This workshop focuses on building a simple React application with navigation between different routes using React Router. The goal is to understand the basics of routing in React applications without hooks.

## Overview

Participants will build an application with two primary routes: `/blue` and `/red`. Each route renders a component with the background color specified in the route. The workshop emphasizes using React Router components to enable seamless navigation between these routes.

## Project Setup

### Initialize the Project

1. **Create a New React App**: Use Vite for a fast development setup.
    ```sh
    npm create vite@latest
    ```
    Follow the prompts to name your project and select React with JavaScript.

2. **Install Dependencies**: Navigate to your project directory and install the necessary packages.
    ```sh
    cd <project-name>
    npm install
    ```

3. **Install React Router**: Add `react-router-dom` to your project.
    ```sh
    npm install react-router-dom
    ```

4. **Start Development Server**: Launch your application.
    ```sh
    npm run dev
    ```

### Configure Styling

Replace the content of `index.css` with the provided CSS to style the application.

### Router Configuration

Wrap your `App` component in `BrowserRouter` within `main.jsx` to enable routing.

### Build Navbar and Routes

Implement navigation and routing in `App.jsx` using `Routes`, `Route`, and `Link` components from `react-router-dom`. Create separate components for the Blue, Red, and Home pages, and route to these components based on the URL.

## Key Features

- **Navigation Bar**: Includes links to Home, Blue, and Red routes.
- **Dynamic Routing**: Displays different components based on the current route without refreshing the page.
- **CSS Styling**: Utilizes CSS for layout and design, adhering to the provided styles.

## Deployment

After building the application, deploy it to a hosting platform such as Netlify or Vercel. Ensure the deployed application loads without errors and that routing works as expected.

## Stretch Goals

1. Refactor the navigation bar and main container into separate components.
2. Add more routes and components to explore further.
3. Implement a footer with links to all routes, ensuring it remains at the bottom of the page.
4. Enhance the application's appearance with additional CSS styling.

## Deployment Guidelines

- Ensure the application is fully functional and free of errors before deployment.
- Test the application thoroughly in various browsers to confirm that routing behaves correctly.
- Choose a deployment platform and follow their guidelines for deploying React applications.

## Criteria Checklist

- [ ] **Deployed**: The application is accessible and error-free post-deployment.
- [ ] **Nav Bar**: Contains at least three links (Red, Blue, Home).
- [ ] **Routes Change**: Clicking each link updates the view without refreshing the browser, changes the URL accordingly, and displays the correct color view.

## Resources

- [React Documentation](https://reactjs.org/docs/getting-started.html): For understanding React concepts.
- [Vite Documentation](https://vitejs.dev/guide/): To learn more about Vite's features and advantages.
- [FSA API Documentation](https://fsa-starter-api.herokuapp.com/documentation): Detailed API endpoints and functionality.


## Conclusion

This React Router workshop demonstrates the power of client-side routing in single-page applications (SPAs). By completing this workshop, participants gain a foundational understanding of navigating between different components and managing application state based on the URL path.

## Further Learning

- Explore more advanced features of React Router, such as nested routes, route parameters, and programmatic navigation.
- Dive into the `useParams` and `useNavigate` hooks to handle dynamic routing and navigation actions in more complex applications.
- Consider implementing authentication flows and protected routes to further enhance your understanding of real-world routing scenarios.

## Feedback and Contributions

Your feedback and contributions are highly valued. If you have suggestions for improving this workshop or want to contribute additional exercises or features, please feel free to open an issue or pull request in the project repository.

Thank you for participating in the React Router workshop. Happy coding!
