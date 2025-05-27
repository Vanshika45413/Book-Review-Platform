# Bookshelf App

A modern React + TypeScript application for managing and reviewing books.  
Built with Vite, featuring modular components, React Context for state management, and clean API integration.

---

## Project Overview

This app provides users with the ability to:

- Browse a collection of books with detailed views  
- Add new books to the collection  
- Review books with ratings and comments  
- Manage shortlisted/favorite books  
- Navigate through multiple pages including home, book list, book details, add book, and user profile  

The project architecture emphasizes reusable components, clear separation of concerns, and scalable state management.

---

## Tech Stack

- **Frontend:** React 18, TypeScript, Vite, Tailwind CSS (optional)  
- **State Management:** React Context API  
- **Routing:** React Router (if applicable)  
- **API:** RESTful API calls via centralized `services/api.ts`  
- **Build Tool:** Vite  
- **TypeScript:** Strict typing with custom interfaces in `types.ts`

---

## Project Structure

├── bookshelves/ # Bookshelf feature domain
│ ├── components/ # UI components for bookshelf
│ │ ├── common/ # Shared reusable components
│ │ ├── BookCard.tsx # Book display card component
│ │ ├── Layout.tsx # Page layout component
│ │ ├── ReviewCard.tsx # Review display card component
│ │ └── ReviewForm.tsx # Review submission form
│ ├── contexts/ # React Context providers
│ │ └── BookReviewContext.tsx
│ └── ... # Additional feature logic/files
├── pages/ # App pages (routes)
│ ├── AddBookPage.tsx
│ ├── BookDetailPage.tsx
│ ├── BookListPage.tsx
│ ├── HomePage.tsx
│ └── UserProfilePage.tsx
├── public/ # Static assets served directly
│ └── images/
│ └── 1984.jpg
├── services/ # API and external service integrations
│ └── api.ts
├── .env.local # Local environment variables
├── .gitignore # Git ignore rules
├── App.tsx # Root React component
├── constants.tsx # Application-wide constants
├── index.html # Main HTML entry point
├── index.tsx # React DOM rendering entry
├── metadata.json # App metadata (version, info)
├── package.json # NPM package config & dependencies
├── package-lock.json # Exact dependency versions
├── README.md # Project documentation (this file)
├── tsconfig.json # TypeScript configuration
├── types.ts # Global TypeScript types and interfaces
└── vite.config.ts # Vite build config

yaml
Copy
Edit

---

## Usage

- Navigate between pages using the app navigation  
- Add new books via the Add Book page  
- View detailed book info on the Book Detail page  
- Submit and view reviews  
- Manage favorites or shortlisted books

---
