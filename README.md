## Project Overview

This document outlines the Product Requirements Document (PRD) for the development of the Dhara Landing Page. The project aims to create a pixel-perfect landing page for the Dhara supply chain financing application using SvelteKit and Tailwind CSS. The landing page serves as the primary entry point for potential users and must effectively convey Dhara's value proposition.

## Design Reference

The design specifications for the landing page are detailed in the following Figma file:

- **Dhara Website:** [Figma Link](https://www.figma.com/design/H3RlTOuGCU6OctkLzokVf2/Ganak-%26-Dhara-COPY?node-id=3-2297&t=F0ZNjcJh9S2lmYu5-0)

- **Live Website:** [https://dhara-website.netlify.app/](https://dhara-website.netlify.app/).

## Development Tools

The development of this landing page utilizes the following tools:

- **SvelteKit:** A framework for building reactive web applications with Svelte.
- **Tailwind CSS:** A utility-first CSS framework for rapid custom design creation.

## Deliverables

The project will deliver:

- A fully functional landing page for Dhara, adhering strictly to the design specifications outlined in the Figma file.
- A well-organized, documented, and easily maintainable codebase for the landing page.

## Development Process

The development process encompasses several key stages:

1. **UI Component Development:**
   - Develop reusable Svelte components for various UI elements on the landing page.
   - Ensure pixel-perfect alignment with the Figma design by leveraging Svelte's built-in styling capabilities or a CSS preprocessor like Sass for granular control. Additionally, employ layout components and utilities from Tailwind CSS to streamline the process.

2. **Layout and Routing:**
   - Structure the landing page layout using SvelteKit's routing capabilities.
   - Define clear navigation paths and organize content sections effectively to guide users through the landing page.
   - Consider using SvelteKit's built-in data fetching capabilities to retrieve any dynamic content required for the landing page.

3. **Content Integration:**
   - Integrate text content, images, and other media elements following the Figma design.
   - Ensure the content is clear, concise, and effectively communicates Dhara's value proposition.
   - Leverage Svelte's reactivity for any dynamic content updates that might be required.

4. **Responsiveness:**
   - Implement responsive design techniques to ensure the landing page adapts seamlessly to different screen sizes and devices.
   - Utilize Tailwind CSS's built-in responsiveness features to achieve optimal results.
   - Conduct thorough testing across various devices and browsers to guarantee a consistent user experience.

5. **Interactivity:**
   - Incorporate basic interactivity features to enhance user experience, such as button clicks for triggering actions like form submissions or navigation, form submissions for capturing user information or feedback, and subtle animations (if applicable) to draw attention to specific elements or guide the user flow.
   - Ensure interactivity is implemented efficiently using Svelte's event handling mechanisms and lifecycle hooks.

## Code Quality & Maintainability Tips

Contributors to the Dhara Landing Page project should aim for high-quality, maintainable code. Here are some tips:

- **Use TypeScript**: Improve error detection and developer efficiency with TypeScript's static typing.

- **Keep Code Clean**: Prioritize clarity and simplicity. Use meaningful names, keep functions focused, and organize code logically.

- **Lint with ESLint**: Use ESLint with Svelte plugins to maintain coding standards and avoid common errors.

- **Format with Prettier**: Ensure consistent code style with Prettier, supporting Svelte for uniformity.

- **Organize Code Well**: Structure the codebase clearly. Use the `components/block` folder for components like navbar and footer, and the `components/ui` folder specifically for [shadcn-svelte](https://www.shadcn-svelte.com/docs) components. Personal components should not be placed in the `components/ui` folder.


Following these tips will help improve the project's code quality and ease future contributions.


## Success Criteria

The success of the landing page will be measured against the following criteria:

- The landing page visually matches the Figma design with pixel-perfect accuracy.
- The landing page is responsive and functions flawlessly across different devices and browsers.
- The landing page effectively communicates the value proposition of Dhara and compels users to learn more about the application.
- The codebase is well-structured, documented, and easy to maintain, promoting future development and collaboration.

## Additional Notes

This readme focuses solely on the development of the Dhara landing page. Further functionalities or features specific to the full-fledged Progressive Web App (PWA) will be addressed in separate documentation.

[![Netlify Status](https://api.netlify.com/api/v1/badges/1289829d-ba6d-41a3-8e21-d962bc89f263/deploy-status)](https://app.netlify.com/sites/dhara-website/deploys)
