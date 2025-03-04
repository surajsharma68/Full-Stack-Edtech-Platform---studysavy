# Studysavy – Personalized Learning EdTech Platform

## 🌐 Website Link
[Studysavy](https://studysavy.vercel.app/)

---

## Introduction

**Studysavy** is a cutting-edge EdTech platform thoughtfully designed to meet the growing demand for **personalized learning journeys**. This **web-based system** dynamically tailors content, engagement, and learning paths according to the unique needs of each learner. It effectively addresses the challenge of accommodating diverse learning preferences, making high-quality education more accessible and personalised.

---

## Key Features and Innovations

- ✅ **Personalized Learning Journeys:**  
  Courses and learning content are tailored to each student's preferences, pace, and progress.

- ✅ **Real-Time Progress Tracking:**  
  Both learners and educators can monitor progress, performance, and engagement in real time.

- ✅ **User-Friendly Interface:**  
  Designed for users of all technical backgrounds with an intuitive, accessible UI.

- ✅ **MERN Stack Technology:**  
  Built using the modern and scalable **MERN stack**:
    - **M**ongoDB for flexible data storage
    - **E**xpressJS for server-side logic
    - **R**eactJS for an engaging front-end
    - **N**odeJS for robust backend functionality

---

## System Architecture

### Front-End (ReactJS)
- ReactJS powers a responsive, dynamic UI.
- Focused on ease of navigation and intuitive design.

### Back-End (NodeJS & ExpressJS)
- Backend handles business logic, authentication, and APIs.
- Supports secure user management, instructor features, and real-time data handling.

### Database (MongoDB)
- Flexible schema allows for storage of structured and unstructured data.
- Stores user data, course materials, progress, and feedback.
- Supports varied media types like **videos, images, PDFs**, etc.

---

## Functionalities (Front-End Pages)

### For Students

- **Homepage:** Overview of Studysavy and links to key sections.
- **Course List:** Browse all available courses with ratings and descriptions.
- **Wishlist:** Save interesting courses for future enrolment.
- **Cart & Checkout:** Secure purchase and enrolment via Razorpay.
- **Course Content:** Access enrolled course materials (videos, PDFs, etc.).
- **User Edit Details:** Edit profile and personal information.
- **User Details:** View profile summary and account data.

### For Instructors

- **Dashboard:** Overview of courses, ratings, and student feedback.
- **Insights:** Detailed analytics on course engagement (views, clicks, etc.).
- **Course Management:** Create, update, delete, and manage course pricing and materials.
- **Profile Management:** Edit personal and professional profile details.

---

## Core Backend Features

- 🔐 **User Authentication & Authorization**  
    - Email/password-based login.
    - OTP verification for added security.
    - Password reset via email.

- 📚 **Course Management System**  
    - Instructors can create, update, and delete courses.
    - Students can browse, rate, and review courses.

- 💳 **Payment Integration**  
    - Seamless checkout experience via **Razorpay**.

- ☁️ **Cloud-Based Media Storage**  
    - Course content stored using **Cloudinary**, ensuring scalability for images, videos, and documents.

- 📝 **Markdown Support**  
    - Course content formatted using Markdown for clean, readable displays on the front end.

---

## API Endpoint Overview

### POST Endpoints
| Endpoint | Functionality |
|---|---|
| `/api/auth/signup` | Create student/instructor account |
| `/api/auth/login` | Authenticate and generate JWT token |
| `/api/auth/verify-otp` | Validate OTP for secure login |
| `/api/auth/forgot-password` | Send password reset link via email |
| `/api/courses` | Create a new course |
| `/api/courses/:id/rate` | Add student ratings to a course |

### GET Endpoints
| Endpoint | Functionality |
|---|---|
| `/api/courses` | Fetch all available courses |
| `/api/courses/:id` | Fetch details of a specific course |

### PUT Endpoints
| Endpoint | Functionality |
|---|---|
| `/api/courses/:id` | Update existing course details |

### DELETE Endpoints
| Endpoint | Functionality |
|---|---|
| `/api/courses/:id` | Remove a course |

---
