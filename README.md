# 🎓 CollegeFind - College Listing & Search

CollegeFind is a modern college discovery platform that helps students search, compare, and explore colleges across India. The project is built as a production-oriented MVP focusing on usability, responsive design, and scalable architecture.

## 🚀 Features

### 🏠 Home Page
- Hero section with search bar
- College Predictor section
- Popular college categories
- Compare Colleges quick access
- Responsive navigation
- Footer with useful links

### 🔍 College Listing & Search
- Search colleges by name
- Search by course
- Filter by:
  - Stream
  - Annual Fees
  - Location
  - Rating
  - College Type
- Sorting options
- Pagination
- Responsive card layout

Each college card displays:
- College Name
- Location
- Fees
- Rating
- Courses
- Save Button
- Compare Button
- View Details Button

### 🎯 College Predictor
Students can enter:
- Exam Name
- Rank

The system recommends colleges based on rank and exam.

### ⚖ Compare Colleges
Users can:
- Select up to 3 colleges
- Compare:
  - Fees
  - Ratings
  - Placements
  - Location

## 🛠 Tech Stack

Frontend
- HTML5
- CSS3
- JavaScript

Backend (Planned)
- Node.js
- Express.js

Database
- MongoDB

Authentication
- JWT Authentication

## 📁 Project Structure

CollegeFind/
│
├── index.html              # Home Page
├── college.html            # College Detail Page
├── compare.html            # Compare Colleges
├── predictor.html          # College Predictor
├── css/
│   └── style.css
├── js/
│   ├── app.js
│   ├── search.js
│   ├── filter.js
│   └── compare.js
├── backend/
│   ├── routes/
│   ├── models/
│   ├── controllers/
│   └── server.js
└── README.md
