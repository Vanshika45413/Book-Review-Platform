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

## Project Structure├── bookshelves/
│ ├── components/
│ │ ├── common/
│ │ ├── BookCard.tsx
│ │ ├── Layout.tsx
│ │ ├── ReviewCard.tsx
│ │ └── ReviewForm.tsx
│ ├── contexts/
│ │ └── BookReviewContext.tsx
│ └── ...
├── pages/
│ ├── AddBookPage.tsx
│ ├── BookDetailPage.tsx
│ ├── BookListPage.tsx
│ ├── HomePage.tsx
│ └── UserProfilePage.tsx
├── public/
│ └── images/
│ └── 1984.jpg
├── services/
│ └── api.ts
├── .env.local
├── .gitignore
├── App.tsx
├── constants.tsx
├── index.html
├── index.tsx
├── metadata.json
├── package.json
├── package-lock.json
├── README.md
├── tsconfig.json
├── types.ts
└── vite.config.ts

---

## Usage

- Navigate between pages using the app navigation  
- Add new books via the Add Book page  
- View detailed book info on the Book Detail page  
- Submit and view reviews  
- Manage favorites or shortlisted books

---
