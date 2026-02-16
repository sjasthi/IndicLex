# ICS325 – Capstone Project
## IndicLex – Multilingual Dictionary Management & Search Platform

### **Course:** ICS325 – Web Application Development

### **Project Name:** IndicLex – Multilingual Dictionary Management & Search Platform

---

## 1. Project Overview

IndicLex is a full-stack web application designed to manage, analyze, and search across multiple multilingual dictionaries. The project simulates a real-world enterprise-level data-driven application, allowing students to practice modern web application development using PHP, MySQL, JavaScript, jQuery, Bootstrap, HTML, and CSS.

Students will design, implement, and deploy a system that supports:

- Multi-language dictionaries
- Advanced search functionality
- Admin dashboards
- Reporting & analytics
- Responsive user interface

---

## 2. Technology Stack

**Frontend:**
- HTML5
- CSS3
- JavaScript
- jQuery
- Bootstrap

**Backend:**
- PHP

**Database:**
- MySQL

---

## 3. Functional Requirements

### 3.1 User Roles

#### A. Visitor (Public User)
- View list of dictionaries and metadata
- Perform searches:
  - Within a selected dictionary
  - Across all dictionaries
- Search patterns:
  - Exact match
  - Prefix
  - Suffix
  - Substring
- View search results with translations

#### B. Admin User
- Secure login system
- Dictionary management:
  - Upload new dictionaries
  - Create dictionaries manually
  - Update dictionary metadata
  - Delete dictionaries
- Word entry management:
  - Add entries
  - Edit entries
  - Delete entries
  - Bulk import & export
- Reporting dashboard:
  - Total number of dictionaries
  - Word count per dictionary
  - Total word count across all dictionaries
  - Language-wise statistics
- Export functionality:
  - CSV
  - JSON
  - Excel (optional)

---

## 4. Database Design Requirements

Students must design normalized MySQL tables.

**Core Tables:**
1. dictionaries
2. dictionary_entries
3. users
4. preferences
---

## 5. Search Features

- Exact word match
- Prefix matching
- Suffix matching
- Substring matching
- Search within a dictionary
- Search across all dictionaries
- Word Length Matching  (Integration with http://ananya.telugupuzzles.com)

---

## 6. UI / UX Requirements

- Fully responsive design
- Bootstrap-based UI
- Clean layouts
- Support for JQuery datatables (for the admin)
- Intuitive navigation
- Mobile & desktop support

**Required Pages:**

**Public:**
- Home Page with Hero section
- Dictionary Catalog
- Search Interface
- Search Results

**Admin:**
- Login
- Dashboard
- Dictionary Manager
- CRUD support for dictionary entries
- CRUD support for Dictionaries
- Uploading a dictionary (excel file)
- Exporting of a dictionary (into HTML)
- Entry Manager
- Reports Page
- Import / Export Page

---

## 7. Advanced Features

- Autocomplete search
- Visualizations (Bar Charts, Pie Charts)
- Role-based authorization
- Performance optimization
- Bulk uploads with validation

---

## 8. Deliverables

- Fully functional web application
- Source code (GitHub)
- Technical documentation
- Self-Evaluation Spreadsheet (from each team members)
---

## 9. Learning Outcomes

- Full-stack development mastery
- Database schema design
- Secure backend development
- Search algorithm implementation
- Professional UI engineering
- Real-world application experience
