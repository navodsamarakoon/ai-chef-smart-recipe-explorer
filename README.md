# 🍳 AI Chef – Smart Recipe Explorer

> A modern recipe discovery web application built with Vue 3, TypeScript, Tailwind CSS, Pinia, and the DummyJSON Recipes API.

## 🌐 Live Demo

🔗 **Live Demo:** YOUR_VERCEL_LINK

## 📂 GitHub Repository

🔗 **GitHub:** https://github.com/navodsamarakoon/ai-chef-smart-recipe-explorer

---

## 📖 About the Project

AI Chef – Smart Recipe Explorer is a modern frontend web application designed to make discovering and exploring recipes simple, interactive, and enjoyable.

The application allows users to:

- 🔎 Search for recipes
- 🍽️ Browse recipe collections
- 🏷️ Filter recipes
- 📖 View detailed recipe information
- ❤️ Save favorite recipes
- ⭐ Explore recipe ratings
- 📱 Use the application across different screen sizes

The project was developed as a university GUI Programming project with a focus on modern frontend development, API integration, reusable components, responsive design, and user experience.

---

## ✨ Features

### 🔎 Recipe Search

Users can search through recipes using keywords.

### 🏷️ Recipe Filtering

Recipes can be filtered based on available recipe attributes.

### 📖 Recipe Details

Each recipe has a dedicated detail view containing information such as:

- Recipe name
- Ingredients
- Instructions
- Preparation information
- Cooking information
- Tags
- Cuisine
- Difficulty

### ❤️ Favorites

Users can mark recipes as favorites and access their preferred recipes more easily.

### 📱 Responsive Interface

The interface is designed to work across:

- Desktop
- Laptop
- Tablet
- Mobile

---

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Vue 3 | Frontend framework |
| TypeScript | Type safety and maintainability |
| Tailwind CSS | Responsive UI styling |
| Pinia | State management |
| Vue Router | Client-side navigation |
| Vite | Development and build tool |
| DummyJSON Recipes API | Recipe data |

---

## 🏗️ Application Architecture

```text
                  ┌─────────────────────┐
                  │       User          │
                  └──────────┬──────────┘
                             │
                             ▼
                  ┌─────────────────────┐
                  │     Vue 3 SPA       │
                  │                     │
                  │  Components / Views │
                  └──────────┬──────────┘
                             │
             ┌───────────────┼───────────────┐
             ▼               ▼               ▼
         Pinia Store    Vue Router     UI Components
             │
             ▼
      Recipe Application State
             │
             ▼
       DummyJSON Recipes API
