<div align="center">
  <br />

[//]: # (    <a href="" target="_blank">)

[//]: # (      <img src="public/readme-hero.webp" alt="Project Banner">)

[//]: # (    </a>)
  <br />

  <div>
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
<img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />

[//]: # (<img src="https://img.shields.io/badge/GSAP-88CE02?style=for-the-badge&logo=greensock&logoColor=white" />)
[//]: # (<img src="https://img.shields.io/badge/Zustand-614A1F?style=for-the-badge&logo=zustand&logoColor=white" />)
  </div>

<h3 align="center">Movie App</h3>

</div>

## 📋 <a name="table">Table of Contents</a>

1. ✨ [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)

## <a name="introduction">✨ Introduction</a>

This web application is a modern movie discovery platform that presents users with access to thousands of movies fetched from an external movie API. It provides a clean and responsive interface where users can browse popular movies and explore detailed content effortlessly. To enhance performance and user experience, the app features a well-implemented debounced search bar, ensuring efficient API requests while allowing users to search for movies smoothly without unnecessary network calls.

In addition to browsing and searching, the application tracks user search activity in real time. Each movie search updates a persistent search count, which is then used to generate a Trending Movies section showcasing the top five most searched movies within the app. This feature highlights popular user interests dynamically and adds a data-driven layer to the experience, making the platform both interactive and insightful.

## <a name="tech-stack">⚙️ Tech Stack</a>
- React
is a declarative, component-based JavaScript library used to build the user interface of the application. It enables efficient rendering through its virtual DOM and reusable component architecture, while React Hooks simplify state management, side effects, and lifecycle handling for a responsive and scalable frontend.


- Tailwind CSS
is a utility-first CSS framework used to design the application’s UI with speed and consistency. It allows rapid styling through composable utility classes, supports responsive design and state variants, and leverages just-in-time compilation to keep the final CSS bundle lightweight and performant.


- Appwrite
is an open-source backend-as-a-service platform that powers the application’s data layer. It is used to store and manage movie search analytics, track search counts, and retrieve the top trending movies based on user activity. Appwrite provides a secure, scalable database, SDK integration, and real-time-ready infrastructure that seamlessly connects the frontend with persistent backend data.

## <a name="features">🔋 Features</a>

👉 **Trending Movies**: Displays the top five most searched movies in the application, ranked dynamically based on user search frequency. Search counts are tracked and stored using Appwrite, allowing the trending section to update as user interest changes over time.

👉 **All Movies Listing**: Fetches and displays a curated list of movies from an external API, showing up to 20 movies per page on initial load. This provides users with immediate access to popular content while maintaining fast load times and smooth browsing.

👉 **Debounced Search Bar**: Features a well-optimized, debounced search input that allows users to search for movies efficiently. By delaying API requests until the user pauses typing, the app reduces unnecessary network calls, improves performance, and delivers a seamless search experience.

👉 **Search Analytics Tracking**: Every successful movie search is recorded and persisted using Appwrite. The app intelligently increments search counts for existing movies or creates new records for first-time searches, enabling accurate analytics and trending calculations.

👉 **External Movie API Integration**: Implements reusable React components, hooks, and clean separation of concerns, making the codebase easy to maintain, extend, and scale as new features are added.

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone [git remote URL]
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser to view the project.