# Full Stack Development Lab Journal

## Introduction
This repository documents my learning journey through 12 practical lab exercises in the Full Stack Development curriculum. Each lab focuses on specific backend, database, and frontend technologies—ranging from **Node.js and Express** to **Sequelize and React**—culminating in a complete full-stack web application.

This journal includes:
- The **objectives** of each lab  
- The **concepts and tools** explored  
- **Libraries and frameworks** implemented  
- My **personal reflections** and **learnings**

---

## Lab-Wise Work Summary

### Lab 1 — Getting Started with Node.js and Express
- Initialized a Node.js project using `npm init`.  
- Created a simple web server using Express.js.  
- Added basic API routes to handle GET and POST requests.  

**Concepts:** Node.js environment setup, Express routing, HTTP request-response cycle.  

---

### Lab 2 — Working with Utility Libraries (Lodash)
- Installed Lodash using `npm install lodash`.  
- Practiced functions like `_.chunk`, `_.merge`, and `_.uniq` for data handling.  
- Integrated Lodash utilities into API responses for cleaner logic.  

**Concepts:** Package installation via npm, modular coding, utility functions for data operations.  

---

### Lab 3 — Error Handling, Callbacks & Event Emitters
- Implemented centralized error handling middleware.  
- Practiced callback-based asynchronous functions.  
- Used Node’s built-in `EventEmitter` to trigger and listen to custom events.  

**Concepts:** Asynchronous programming, middleware pattern, event-driven architecture.  

---

### Lab 4 — Reminder App using Timers and Events
- Utilized `setTimeout` and `setInterval` for scheduling reminders.  
- Linked event emitters to trigger notifications.  
- Built API endpoints for creating, listing, and removing reminders.  

**Concepts:** Timers in Node.js, asynchronous scheduling, API development.  

---

### Lab 5 — Routing and File Streams
- Organized routes using `express.Router()` for modularity.  
- Worked with file read/write streams using `fs.createReadStream` and `fs.createWriteStream`.  
- Connected readable and writable streams using `.pipe()` for efficient data transfer.  

**Concepts:** Modular Express routing, file I/O, streaming data efficiently.  

---

### Lab 6 — Automating Tasks with Cron Jobs
- Integrated `node-cron` to automate repetitive tasks.  
- Scheduled console logs and data cleanup jobs at set intervals.  
- Monitored scheduled jobs for reliability.  

**Concepts:** Background job scheduling, cron expressions, process automation.  

---

### Lab 7 — Connecting Sequelize with Database
- Installed and configured Sequelize ORM with PostgreSQL.  
- Established database connection using Sequelize configuration files.  
- Tested database connection and handled connection errors.  

**Concepts:** ORM integration, database connectivity, Sequelize setup.  

---

### Lab 8 — Creating User Model and Performing CRUD
- Defined a `User` model with `username`, `email`, and `password` attributes.  
- Performed create, read, update, and delete operations using Sequelize methods.  
- Logged query results for verification.  

**Concepts:** ORM-based CRUD operations, model definition, query handling.  

---

### Lab 9 — Sequelize Associations
- Built one-to-one association between User and Profile models.  
- Defined one-to-many relationships between User and Posts.  
- Implemented many-to-many relationships using junction tables for Students and Courses.  

**Concepts:** Data modeling, foreign key relationships, association mapping in Sequelize.  

---

### Lab 10 — React Project Setup
- Initialized React application using `npx create-react-app`.  
- Organized folder structure for components and assets.  
- Practiced using `useState` and `useEffect` for managing component state and lifecycle.  

**Concepts:** React setup, hooks, component lifecycle management.  

---

### Lab 11 — Building Components and Client Routing
- Created reusable React components such as Home, About, and Contact.  
- Implemented navigation using `react-router-dom`.  
- Shared data between parent and child components using props.  

**Concepts:** Component-based architecture, routing, props-based communication.  

---

### Lab 12 — Integrating Frontend and Backend
- Connected React frontend with Node.js backend using `axios`.  
- Fetched API data and rendered it dynamically on the client side.  
- Enabled CORS in Express to allow secure cross-origin requests.  

**Concepts:** API integration, asynchronous data fetching, CORS configuration, full-stack communication.  

---

## Challenges & Learnings

### 1. API Integration
Initially struggled with CORS configuration and managing asynchronous API requests.  
Later learned to handle loading and error states in React efficiently.

### 2. File Streaming
Understanding buffers and data chunks was challenging.  
Practicing with `.pipe()` clarified how Node handles large data streams effectively.

### 3. ORM Associations
Converting SQL join logic into Sequelize relationships took time.  
Eventually mastered `include`, `where`, and `attributes` options to fine-tune queries.

### 4. State Management
Distinguishing between **props** and **context** was confusing.  
Implementing a Context API simplified global state sharing (like authentication).

---

## Conclusion
This journal reflects my complete journey from setting up a basic Node.js server to deploying a full-stack application integrated with React and PostgreSQL.  
Each lab strengthened my understanding of backend logic, database management, and frontend interactivity—helping me gain real-world insight into **MERN/PERN stack development**.
