# PokéDex – React + Vite

This is a simple and fast React project bootstrapped with [Vite](https://vitejs.dev/) that fetches data from the [PokéAPI](https://pokeapi.co/) and displays a list of Pokémon as stylish cards. It also includes a search bar with debounced input to improve performance during search.

## ✨ Features

- ⚛️ **React** with [Vite](https://vitejs.dev/) for lightning-fast builds and hot module replacement (HMR)
- 🔍 **Search functionality** with **debouncing** to reduce unnecessary API calls
- 🎴 **Card-based layout** to visually present Pokémon data
- 🌐 Live **API integration** using [PokéAPI](https://pokeapi.co/)

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or newer recommended)
- npm or yarn

### Installation

1. Clone the repository :

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. Install dependencies :

   ```bash
   npm install 
   # or
   yarn
   ```
3. Start the development server :

   ```bash
   npm run dev
   # ok
   yarn dev
   ```
   The app should be running at http://localhost:5173


## 🚀 Tech Stack

- ⚛️ **React** – Frontend library for building UIs

- ⚡ **Vite** – Build tool for fast development

- 🧪 **PokéAPI** – Public Pokémon RESTful API

- 🌐 **Axios** or native **fetch** – For making HTTP requests

- 🧹 **ESLint** – Linter for maintaining code quality



## 🛠 Available Scripts

Run these commands in the project root:

```bash
npm run dev        # Start the development server
npm run build      # Build for production
npm run preview    # Preview production build
npm run lint       # Run ESLint for code quality
```


## 🔍 Search with Debounce

The search input uses a custom debounce hook to delay the API call until the user stops typing. This:

- Reduces unnecessary API requests  
- Improves performance  
- Provides a smoother user experience  
