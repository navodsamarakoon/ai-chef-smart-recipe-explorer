# 🍳 AI Chef – Smart Recipe Explorer

> A modern and responsive recipe discovery web application built with Vue 3, TypeScript, Tailwind CSS, Pinia, Vue Router, and the DummyJSON Recipes API.

---

## 📖 Overview

**AI Chef – Smart Recipe Explorer** is a modern frontend web application designed to provide users with a simple and interactive way to discover, search, filter, and explore recipes.

The application was developed as a university **GUI Programming project**, with a focus on modern frontend development principles such as:

- Component-based architecture
- Responsive user interface design
- REST API integration
- State management
- Client-side routing
- Type-safe development
- Reusable UI components
- User-friendly interaction

The current version focuses on the **frontend experience and recipe exploration**.

> 🚀 An extended version of AI Chef is being developed separately with an online-learning recommendation system using machine learning.

---

## ✨ Features

### 🔎 Recipe Search

Users can search for recipes using keywords and quickly find relevant recipes.

### 🏷️ Recipe Filtering

Recipes can be explored using different filtering options to help users discover recipes based on their preferences.

### 🍽️ Recipe Exploration

The application provides a collection of recipes that users can browse through an interactive interface.

### 📖 Recipe Details

Users can open an individual recipe to view detailed information, including:

- Recipe name
- Ingredients
- Instructions
- Cuisine
- Difficulty
- Meal type
- Preparation information
- Cooking information
- Tags
- Recipe image

### ❤️ Favorites

Users can mark recipes as favorites and easily access their preferred recipes.

### 📱 Responsive Design

The interface is designed to provide a consistent experience across:

- Desktop
- Laptop
- Tablet
- Mobile devices

### ⚡ Dynamic Data

Recipe information is retrieved dynamically from the DummyJSON Recipes API rather than being hard-coded into the application.

---

# 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| **Vue 3** | Frontend framework |
| **TypeScript** | Type-safe development |
| **Tailwind CSS** | Responsive UI styling |
| **Pinia** | State management |
| **Vue Router** | Client-side navigation |
| **Vite** | Development server and build tool |
| **DummyJSON Recipes API** | Recipe data source |

---

# 🏗️ Application Architecture

The application follows a modern component-based frontend architecture.

```text
                    ┌───────────────────┐
                    │       User        │
                    └─────────┬─────────┘
                              │
                              ▼
                    ┌───────────────────┐
                    │    Vue 3 SPA      │
                    └─────────┬─────────┘
                              │
             ┌────────────────┼────────────────┐
             │                │                │
             ▼                ▼                ▼
       Vue Components    Vue Router        Pinia Store
             │                │                │
             └────────────────┼────────────────┘
                              │
                              ▼
                    ┌───────────────────┐
                    │  Recipe Service   │
                    └─────────┬─────────┘
                              │
                              ▼
                    ┌───────────────────┐
                    │ DummyJSON Recipes │
                    │       API         │
                    └───────────────────┘
