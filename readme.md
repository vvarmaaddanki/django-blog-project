# Django Blog Management System

A full-featured blog management web application built with *Python and Django*. 
The project demonstrates practical backend development concepts including authentication, 
authorization, database relationships, CRUD operations, comments, search, media handling, 
and role-based dashboards.

## 🚀 Project Overview

This application provides a complete blogging platform where users can register, 
authenticate, create and manage blog posts, browse posts by category, search for content, 
and interact through comments.

The project also includes a dashboard with role-based access control for managing users, 
categories, and blog posts.

## ✨ Key Features

### 👤 User Management
- User registration and login
- User logout
- Profile management
- Secure authentication
- Role-based access control

### 📝 Blog Management
- Create blog posts
- Edit existing posts
- Delete posts
- View individual blog posts
- Draft/published post management
- SEO-friendly post slugs
- Featured images and media handling

### 🗂️ Category Management
- Create categories
- Edit categories
- Delete categories
- Browse posts by category

### 💬 Comment System
- Users can comment on blog posts
- Comment management
- Authentication-based commenting

### 🔎 Search
- Search blog posts
- Search results based on post content
- Category-based filtering

### 📊 Dashboard
- User management
- Blog post management
- Category management
- Role-based dashboard access
- CRUD operations through dashboard

### 🔐 Security & Authorization
- Django authentication system
- Login-required views
- Permission-based access
- Role-based authorization
- Protected dashboard functionality

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Backend programming |
| Django | Web framework |
| SQLite | Development database |
| HTML5 | Frontend structure |
| CSS3 | Styling |
| Bootstrap | Responsive UI |
| JavaScript | Frontend interactions |
| Git | Version control |
| GitHub | Source code management |

## 🏗️ Project Architecture

The project follows Django's MVT (Model-View-Template) architecture.

```text
Django Blog
│
├── Models
│   ├── Blog
│   ├── Category
│   ├── Comment
│   └── User
│
├── Views
│   ├── Authentication
│   ├── Blog
│   ├── Categories
│   ├── Comments
│   └── Dashboard
│
├── Templates
│   ├── Blog pages
│   ├── Authentication pages
│   └── Dashboard pages
│
└── Static / Media
    ├── CSS
    ├── JavaScript
    └── Uploaded images

## ✨ Key Features

- User registration, login and logout
- Create, edit and delete blog posts
- Category-based blog organization
- Post search functionality
- Slug-based URLs for blog posts
- User comments with authentication
- Role-based access control
- Custom dashboard for managing posts, users and categories
- Django admin customization
- Image upload and media handling
- Form validation and error handling
- Responsive web interface

---

## 🛠️ Tech Stack

*Backend*
- Python
- Django
- Django ORM

*Frontend*
- HTML5
- CSS3
- JavaScript
- Bootstrap

*Database*
- SQLite (development)
- PostgreSQL (production-ready)

*Tools*
- Git
- GitHub
- VS Code

---

## 🔐 Authentication & Authorization

The application implements Django's authentication and authorization system, including:

- User registration and login
- Secure logout
- Password validation
- Role-based permissions
- Django Groups and Permissions
- Protected views using authentication decorators
- Separate access levels for users and administrators

---

## 📊 Dashboard

The project includes a custom dashboard for managing the blogging platform.

Administrators/authorized users can:

- Manage blog posts
- Create and manage categories
- Manage registered users
- Review and manage comments
- Edit or delete existing content
- Access role-based dashboard functionality

---

## 🔎 Search & Content Management

Users can search for blog posts and browse content by category.

The application uses Django's ORM and query filtering to retrieve and organize blog content efficiently.

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/vvarmaddanki/django-blog-project.git
cd django-blog-project

