# leadsDoIt Notes App

Welcome to the LeadsDoIt Notes App, a lightweight and dynamic web application built with Vue 3 and Vite. This project is designed to provide a seamless experience for managing notes efficiently, utilizing the latest web technologies for rapid development and high performance.

## Tech

- **Vue 3**
- **Vite**
- **Vuex**
- **SASS**

## Structure

- `./`: The root directory of the Vue.js application created with Vite.
- `src/`: Main directory containing the application's source code.
  - `assets/`: Contains static files like styles, images, and global SCSS helpers.
    - `styles/`: SCSS files for styling components and views.
      - `components/`: SCSS files corresponding to individual Vue components.
      - `helpers/`: SCSS utilities like mixins and variables.
  - `components/`: Reusable Vue components.
  - `constants/`: Constants and enums used throughout the application.
  - `router/`: Vue Router configuration files for handling routing.
  - `store/`: Vuex store management, including state, actions, mutations, and getters.
  - `services/`: Service functions to handle external interactions such as API calls or local storage manipulation.
  - `views/`: Vue components that represent different pages or routes in the application.
- `index.html`: Entry-point HTML file for the application.

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```
