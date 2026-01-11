# AI powered Resume Quality Checker

## Introduction

AI-powered Resume Analyzer built using React, React Router, and Puter.js. It enables users to authenticate seamlessly, upload and store resumes securely, and evaluate them against job descriptions using AI-driven analysis.

The system provides ATS scores, job-specific feedback, and intelligent resume matching, all delivered through a modern, reusable, and responsive user interface. The application is entirely serverless, with authentication, storage, and AI capabilities handled directly in the browser via Puter.js.

## ⚙️ Tech Stack

**Frontend & Routing**

- *React* - A widely used open-source JavaScript library for building dynamic user interfaces using reusable components and a virtual DOM.
- *React Router v7* - Advanced routing solution for React, supporting nested routes, loaders/actions, error boundaries, code splitting, and SSR.

**Backend-less platform**

- *Puter.com* - An open-source, privacy-first internet operating system that acts as a personal cloud for file storage, apps, and AI services.
- *Puter.js* - A lightweight client-side SDK that provides serverless authentication, storage, database access, and AI capabilities (GPT, Claude, OCR, DALL·E) directly in the browser.

**Styling & UI**

- *Tailwind CSS* - Utility-first CSS framework for rapid UI development.
- *shadcn/ui* - Modern, accessible UI components built on top of Tailwind CSS.

**Development & State Management**

- *TypeScript* - Adds static typing to JavaScript for better reliability and maintainability.
- *Vite* - High-performance development server and build tool with instant HMR.
- *Zustand* - Lightweight and efficient global state management for React applications.

## Features

- *Resume Upload & Secure Storage* - Users can upload, manage, and store multiple resumes safely in one place.
- *AI-Driven Resume Matching* - Analyze resumes against job descriptions and receive ATS scores with tailored feedback.
- *Reusable & Modular UI* - Clean, consistent, and maintainable UI components designed for scalability.
- *Code Reusability & Clean Architecture* - Modular codebase structured for readability and long-term maintenance.
- *Cross-Device Compatibility* - Fully responsive design optimized for desktops, tablets, and mobile devices.
- *Modern UI/UX* - Sleek and professional interface built with Tailwind CSS and shadcn/ui.

## How to Run Locally

## Step-1 : Clone the Repository

     git clone https://github.com/adrianhajdin/ai-resume-analyzer.git
     cd ai-resume-analyzer

## Step-2 : Install Dependencies

    npm install

## Step-3 : Run the Development Server

    npm run dev

  Open http://localhost:5173 in your browser to view the application.
