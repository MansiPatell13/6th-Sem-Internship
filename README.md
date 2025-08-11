# MERN Stack Web Development Internship 2025 – Project Overview

Welcome to the GitHub repository for my Web Development Internship 2025 at **Zidio Development**!  
This repository documents the daily progress, tasks, and learning outcomes from my internship journey, focusing on full-stack web development using the **MERN Stack** (MongoDB, Express.js, React.js, Node.js) and modern development practices.

---

## 📌 Introduction

Starting from **June 16, 2025**, I began an intensive internship at **Zidio Development**, aimed at strengthening my skills in full-stack web development.  
This program provides hands-on experience with real-world projects, tools, and team collaboration aligned with industry practices.

### The internship focuses on:
- Developing dynamic web applications using the MERN stack  
- RESTful API creation and integration  
- Component-based frontend development with React.js  
- Backend services using Node.js and Express.js  
- Working with MongoDB for data modeling and persistence  
- Utilizing tools like GitHub, Postman, Figma, and deployment platforms  
- Agile teamwork, daily updates, and task management

This README is regularly updated to reflect my day-by-day learning and progress throughout the internship.

---
##  Day-by-Day Progress

---

##  Week 1

---

### Day 1 – June 16, 2025

#### Internship Kickoff & Orientation
- Attended onboarding session by the Zidio Development team.
- Gained insights into the company’s services, project workflow, and tech ecosystem.
- Understood internship structure, deliverables, and communication channels.

#### Skills Assessment & Team Formation
- Completed a baseline assessment to evaluate familiarity with HTML, CSS, JS (ES6+), and React.
- Assigned to a 6-member team and introduced to our first full-stack web project.

#### Tools & Stack Overview
- **Frontend**: React.js, Tailwind CSS / Bootstrap  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB  
- **Dev Tools**: GitHub, Postman, Figma, Slack/Discord, Google Meet

---

### Day 2 – June 17, 2025

#### Project Exploration & Tech Deep Dive
- Walked through the project scope, functionality goals, and user flow with mentor.
- Studied the following libraries:
  - JWT (authentication), Multer (file handling), SheetJS (Excel), Chart.js, Three.js (visuals), jsPDF & html2canvas (exports)

#### Team Planning & Module Division
- Split tasks across frontend, backend, DB schema, and UI logic.
- Outlined responsibilities and finalized our roadmap:
  - **Week 1**: Auth + Dashboard UI  
  - **Week 2**: File Upload + DB Setup  
  - **Week 3**: Charts + Axis  
  - **Week 4**: History + Export  
  - **Week 5**: Admin Panel + Deployment

---

### Day 3 – June 18, 2025

#### Project Setup & Initial Layout
- Set up backend server with **Express.js** and connected MongoDB using **Mongoose**.
- Installed key dependencies: `dotenv`, `cors`, `axios`, `nodemon`.

#### Frontend Bootstrapping
- Initialized frontend using **Vite + React**, and configured **Tailwind CSS**.
- Created folder structure: `components/`, `pages/`, `services/`, `context/`, `assets/`
- Designed responsive **navbar** and layout for the dashboard.

#### Auth Strategy Discussion
- Finalized use of **JWT** and **bcrypt** for authentication.
- Planned token storage, session management, and protected route handling.

---

### Day 4 – June 19, 2025

#### JWT & User Authentication Setup
- Implemented secure user authentication using **JWT** and **bcrypt**.
- Created backend routes for:
  - **/api/register** – User registration with password hashing.
  - **/api/login** – User login with JWT token generation.
- Added middleware for protected routes to verify JWT tokens.
- Stored JWT in local storage and planned secure token flow on the frontend.

---

### Day 5 – June 20, 2025

#### Landing Page + Auth Modules
- Designed and built the **Landing Page UI** using Tailwind CSS with a modern, responsive layout.
- Developed **Sign In**, **Sign Up**, and **Forgot Password** components with:
  - Controlled input forms
  - Error handling and form validation logic
- Set up basic routing between pages using **React Router**.

---

## Week 2

---

### Day 6 – June 23, 2025

#### Connecting Frontend with Backend (Auth)
- Integrated frontend forms with backend API using **Axios**.
- Implemented user authentication flow:
  - Register and login requests sent to backend
  - Token received, stored, and used to access protected dashboard routes
- Displayed login/signup success and error feedback using toast notifications.
- Verified frontend and backend coordination through test user sessions.
### Day 7 – June 24, 2025

#### File Upload Backend Setup
- Installed and configured **Multer** for handling file uploads in Express.js.
- Created API endpoint **/api/upload** to accept Excel files.
- Added validation to restrict upload to Excel file types (.xls, .xlsx).
- Planned folder structure for storing uploaded files temporarily.

---

### Day 8 – June 25, 2025

#### Excel Parsing with SheetJS
- Integrated **SheetJS (xlsx library)** into backend.
- Implemented logic to:
  - Read uploaded Excel files
  - Convert sheet data to JSON format
- Tested Excel parsing using sample files with varied structures.
- Began defining data model schema to store parsed Excel data.

---

### Day 9 – June 26, 2025

#### MongoDB Integration for Uploaded Data
- Designed MongoDB schemas for storing:
  - User-uploaded Excel file metadata
  - Parsed sheet data as JSON arrays
- Connected Excel parsing logic to save results in MongoDB collections.
- Tested data persistence and retrieval via Mongoose queries.
- Planned indexes for optimized data retrieval for charts.

---

### Day 10 – June 27, 2025

#### Frontend Integration for File Upload
- Built a **file upload component** in React with Tailwind styling.
- Integrated Axios calls to backend **/api/upload** route.
- Added loading states, success/error handling, and toast notifications.
- Displayed parsed Excel sheet preview on successful upload.
- Validated front-to-back data flow end-to-end.

---

## Week 3

---
### Day 11 – June 30, 2025

#### Chart Rendering Setup
- Began integrating **Chart.js** into the frontend for data visualization.
- Installed Chart.js and configured it with React components.
- Created dynamic chart components to render:
  - Bar charts
  - Line charts
  - Pie charts
- Implemented basic props to accept dynamic datasets for chart rendering.
- Designed UI for **axis selection**:
  - Dropdowns for users to choose X and Y columns from uploaded Excel data.
- Tested chart rendering with static and fetched data to verify visuals and responsiveness.

### Day 12 – July 1, 2025

#### Dynamic Axis Binding & Data Selection
- Implemented dropdown-based axis selection using column headers from parsed Excel data.
- Built logic to dynamically bind user-selected columns to chart axes.
- Improved UI responsiveness and validation for unsupported data types.
- Added fallback messaging for empty or incompatible datasets.

---

### Day 13 – July 2, 2025

#### Chart Enhancements & Styling
- Enhanced chart components with:
  - Tooltips, legends, custom color schemes
  - Gridlines and axis labels
- Added toggles for users to switch chart types (bar, line, pie) on the fly.
- Integrated loading indicators and error messages for chart rendering.
- Ensured responsiveness across devices using Tailwind utilities.

---

### Day 14 – July 3, 2025

#### 3D Visualization Exploration with Three.js
- Installed and configured **Three.js** in the React environment.
- Built a basic 3D scatterplot using dummy coordinates.
- Researched libraries like `react-three-fiber` for seamless React-Three integration.
- Assessed feasibility of using 3D charts for visualizing multi-dimensional Excel data.

---

### Day 15 – July 4, 2025

#### Data Testing & Component Refinement
- Performed end-to-end testing using multiple Excel file formats.
- Fixed edge cases: missing headers, null values, non-numeric columns.
- Refactored chart components into reusable modules.
- Finalized axis selection + chart rendering as stable core features.

---

## Week 4

---
### Day 16 – July 7, 2025

#### History Saving System (Phase 1)
- Started implementing the **history-saving feature** for user sessions.
- Designed MongoDB schema to store:
  - Uploaded file metadata
  - Selected chart type
  - Axis configuration
  - Timestamp and user ID
- Created backend API endpoint `/api/history/save` to store chart sessions.

#### UI Work
- Added a "Save Session" button on the dashboard.
- Displayed toast notifications for save success/failure.
- Planned frontend layout for viewing saved histories.

### Day 17 – July 8, 2025

#### Viewing Saved History
- Created frontend page to display user’s saved chart sessions.
- Implemented API call to `/api/history/user/:id` to fetch saved charts.
- Rendered session list with:
  - Chart type preview
  - Upload date
  - Axis configurations
- Added option to reload saved session into the dashboard for further edits.

---

### Day 18 – July 9, 2025

#### Export Feature: PDF & Image Downloads
- Integrated **jsPDF** and **html2canvas** to capture chart visualizations.
- Built download buttons for:
  - Exporting charts as PNG images.
  - Generating PDFs with chart snapshots and axis details.
- Tested export functionality with different chart types and sizes.
- Handled scaling issues for high-resolution downloads.

---

### Day 19 – July 10, 2025

#### AI Integration Exploration
- Researched possible AI features for the dashboard:
  - Auto-suggestions for chart types based on data patterns.
  - Predictive insights from uploaded datasets.
- Started experimenting with simple statistical analysis for:
  - Detecting numeric vs. categorical columns
  - Recommending suitable chart types
- Discussed backend vs. frontend approaches for integrating AI modules.

---

### Day 20 – July 11, 2025

#### Implementing AI Chart Suggestions
- Developed initial backend logic to analyze uploaded Excel data.
- Created API endpoint `/api/ai/suggest-chart`:
  - Analyzes data columns
  - Returns recommended chart types (e.g., bar, pie, scatter)
- Built frontend logic to:
  - Display AI suggestions after upload
  - Allow users to accept or override recommendations
- Tested with various datasets to validate suggestion accuracy.

---

## Week 5 

---

### Day 21 – July 14, 2025

#### Admin Panel: Initial Design and Routes
- Planned admin features and UI layout with the mentor.
- Designed routes and protected admin endpoints in the backend:
  - `/api/admin/login`, `/api/admin/users`, `/api/admin/blogs`, `/api/admin/tags`.
- Added middleware to verify admin role from JWT token.

### Day 22 – July 15, 2025

#### Admin UI: Component Scaffolding
- Built React components for the admin dashboard: `AdminLayout`, `UsersList`, `BlogsList`, `TagManager`.
- Implemented client-side routing for admin pages using React Router and role-based route guards.

### Day 23 – July 16, 2025

#### Backend: Admin Actions
- Implemented backend logic for admin actions:
  - Fetch all users, block/unblock users, delete users.
  - Fetch all blogs, delete blog posts, mark posts as reviewed.
- Added pagination for admin endpoints to handle large datasets.

### Day 24 – July 17, 2025

#### Testing: Unit and Integration
- Wrote unit tests for key backend services (authentication, blog CRUD) using Jest.
- Performed integration testing of admin endpoints using Postman collections.
- Fixed issues found during testing: token expiry handling, role verification edge cases.

### Day 25 – July 18, 2025

#### Deployment Preparation
- Prepared production readiness checklist:
  - Environment variables management, CORS policy, logging, and rate limiting considerations.
- Containerization research: drafted Dockerfile for backend and basic deployment plan.

---

## Week 6 — Blogging App

---

### Day 28 – July 21, 2025

#### Blogging App Boilerplate
- Created dedicated repository structure for the blogging application.
- Implemented reusable project templates for frontend and backend:
  - **Frontend**: Vite + React, Tailwind setup, base layout and authentication pages.
  - **Backend**: Express skeleton, central routes, and error handling middleware.

---

### Day 29 – July 22, 2025

#### Authentication: Extended Features
- Designed refresh token strategy for improved session management.
- Added password reset workflow endpoints:
  - `/api/auth/forgot-password`
  - `/api/auth/reset-password`
- Implemented server-side rate limiting for authentication endpoints to mitigate brute-force attempts.

---

### Day 30 – July 23, 2025

#### Frontend Authentication Integration
- Connected login, signup, and reset password UI to backend endpoints using Axios.
- Implemented global authentication context to manage user info and tokens across the app.
- Added protected-route higher-order component and admin-route wrapper for role-based access.

---

### Day 31 – July 24, 2025

#### Security Hardening
- Added input validation on both frontend and backend using Joi for request validation.
- Implemented `helmet` and `express-rate-limit` on the backend for additional security measures.

---

### Day 32 – July 25, 2025

#### DevOps: Continuous Integration Basics
- Configured GitHub Actions workflow to run linting and backend tests on push.
- Set up ESLint and Prettier configurations for consistent code style.

---

## Week 7 

---

### Day 35 – July 28, 2025

#### Blog Schema Design
- Finalized blog schema in MongoDB using Mongoose.
- Defined fields: `title`, `slug`, `content` (Quill Delta or HTML), `excerpt`, `authorId`, `tags`, `categories`, `coverImageUrl`, `likes[]`, `comments[]`, `createdAt`, `updatedAt`, `status`.
- Added indexes for `slug`, `tags`, and full-text search on `title` and `content`.

---

### Day 36 – July 29, 2025

#### Blog APIs Implementation
- Implemented RESTful blog APIs:
  - `GET /api/blogs` (with pagination, sort, filter options)
  - `GET /api/blogs/:slug`
  - `POST /api/blogs` (protected)
  - `PUT /api/blogs/:id` (author or admin)
  - `DELETE /api/blogs/:id` (author or admin)
- Added query parameters for tag/category filtering and keyword search.

---

### Day 37 – July 30, 2025

#### Rich Text Editor Integration (React Quill)
- Integrated React Quill in CreateBlog and EditBlog components.
- Implemented content saving strategy to store both sanitized HTML and Quill Delta.
- Added content sanitization before saving to prevent XSS.

---

### Day 38 – July 31, 2025

#### Image Upload Support
- Implemented Cloudinary integration for image uploads from the editor and for cover images.
- Created backend route `POST /api/uploads/image` to upload files to Cloudinary and return secure URLs.

---

### Day 39 – August 1, 2025

#### Testing Blog CRUD
- Performed end-to-end tests for blog creation, edit, and deletion flows.
- Validated permission checks to ensure only owners or admins can edit or delete their posts.

---

## Week 8 

---

### Day 42 – August 4, 2025

#### Blog UI: List & Single View
- Built Home page UI to list blogs with excerpts, tags, author, and publish date.
- Implemented SingleBlog page displaying full content, cover image, author details, and metadata.

---

### Day 43 – August 5, 2025

#### Like System
- Implemented like/unlike functionality:
  - `POST /api/blogs/:id/like` toggles like status for authenticated users.
  - Backend stores user IDs in `likes` array and prevents duplicate likes.
- Frontend shows live like count and toggle state with optimistic UI updates.

---

### Day 44 – August 6, 2025

#### Comment System
- Implemented comment posting and retrieval:
  - `POST /api/blogs/:id/comments` — add a comment.
  - `GET /api/blogs/:id/comments` — list comments with pagination.
  - `DELETE /api/blogs/:id/comments/:commentId` — delete comment (author or admin only).
- Added support for nested replies (single-level) and timestamps.

---

### Day 45 – August 7, 2025

#### UI Polishing & UX
- Added smooth transitions for like and comment actions.
- Improved mobile responsiveness for comment input and action buttons.
- Added validation and moderation indicators for flagged or removed comments.

---

### Day 46 – August 8, 2025

#### Search & Filter Controls (Initial)
- Added frontend controls for searching by keyword and filtering by tags and category on the Home page.
- Implemented debounced search input to reduce unnecessary API calls.

---

## Week 9 

---

### Day 49 – August 11, 2025

#### Profile Management
- Implemented Profile page displaying authored blogs, saved/blogmarked posts, and account settings.
- Added API endpoints:
  - `GET /api/users/:id/blogs` — fetch authored posts.
  - `GET /api/users/:id/saved` — fetch bookmarked posts.
  - `PUT /api/users/:id` — update profile details.
- Integrated Cloudinary for profile picture uploads.

---

### Day 50 – August 12, 2025

#### Advanced Search & Filtering Enhancements
- Extended `GET /api/blogs` to accept complex query parameters:
  - `?q=` keyword search (full-text)
  - `?tags=` tag1,tag2
  - `?category=` categoryName
  - `?author=` authorId
  - `?sort=` popular | newest | oldest
- Implemented combined search + filter UI on the Home page, including a multi-select tag dropdown and clear filters option.

---

### Day 51 – August 13, 2025

#### Backend Query Optimization
- Added MongoDB indexes for frequently searched fields to improve performance.
- Optimized aggregation pipelines for combined filters and sorting.
- Reduced response times for large datasets.

---

### Day 52 – August 14, 2025

#### UI Enhancements
- Styled profile page for responsive design and mobile usability.
- Added interactive filter chips for quick filter removal.
- Improved dropdown accessibility for keyboard navigation.

---

### Day 53 – August 15, 2025

#### Testing & Bug Fixes
- Validated profile updates, ensuring correct server responses and data persistence.
- Fixed search and filter edge cases.
- Ensured filters persist after navigation and page reloads.



_This document will be updated daily to reflect the continued learning and contributions throughout the internship at Zidio Development._
