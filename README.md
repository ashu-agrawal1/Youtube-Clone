# Youtube Clone Project

## Features

1. **Hamburger Menu**

   - implemented a hamburger menu with a home icon, providing a seamless navigation experience. Clicking the home icon redirects users to the home page without triggering a full page reload, enhancing the overall responsiveness and user interface of the project

2. **Search Box**

   - Utilizes a live API from YouTube for real-time search results.
   - Implements debouncing to optimize search requests.
   - Includes caching mechanisms for improved performance.

3. **Video Cards**

   - Utilizes a live API from YouTube for real-time data for thumbnails, description, viewcount etc.
   - incorporated the YouTube embed functionality to seamlessly integrate and display videos within the project interface upon clicking on any video cards

4. **Comments Section**

   - Implements a comments section with hard-coded comments due to YouTube API limitations on nested comments.
   - Utilizes the concept of recursion to display nested comments.

5. **Live Chat**
   - Implements a real-time live chat feature.
   - Challenges addressed in the "Challenges" section below.


## Technology Stacks

### Frontend

- **React.js**: A declarative, efficient, and flexible JavaScript library for building user interfaces.
- **Redux**: A predictable state container for managing the application's state.
- **React-router-dom**: A standard library for routing in React.
- **Tailwind CSS**: A utility-first CSS framework for rapid UI development.


## Chat Feature Implementation

- Utilizes **Redux store** for managing live chat data.
  - Creates a `chatSlice.js` to handle chat-related state and logic.
  - Adds `chatSlice` to the Redux store (e.g., `store.js`).
  - Enables the sending of custom messages within the live chat.
