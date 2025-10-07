GameHub
Discover and explore video games by genre, platform, and more. Search, filter, and browse with a responsive UI and light/dark themes.


Live demo: 


Tech stack
    React 18 + TypeScript
    Vite
    Chakra UI (design system + dark/light mode)
    React Router
    Axios (API client)
    Vercel (hosting)


Features
    Game discovery with search
    Filter by genre and platform
    Sort results (e.g., relevance/rating/release date)
    Responsive layout
    Dark/light mode
    Fast dev/build with Vite

Project structure
    Adjust as needed to match your repo.

.
├─ src
│ ├─ assets/
│ ├─ components/
│ │ ├─ NavBar.tsx
│ │ ├─ ColorModeSwitch.tsx
│ │ └─ SearchInput.tsx
│ ├─ hooks/
│ │ ├─ useGames.ts
│ │ └─ useGenres.ts
│ ├─ services/
│ │ └─ api-client.ts
│ ├─ utils/
│ │ └─ image-url.ts
│ ├─ main.tsx
│ ├─ App.tsx
│ └─ index.css
├─ vite.config.ts
├─ tsconfig.json
└─ package.json


Getting started

    Prerequisites
        Node.js 18+ (recommended)
        npm, pnpm, or yarn
        Clone and install
        git clone https://github.com/YOUR-USER/GameHub.git
        cd GameHub
        npm install
        Environment variables
        Create a .env file at the project root (never commit it). If you’re using RAWG:
        VITE_RAWG_API_KEY=your_rawg_api_key

        
Notes:
    In Vite, only variables prefixed with VITE_ are exposed to your app.
    If you’re using a different API, adapt the variable name accordingly.
    
    Run locally
        npm run dev
        Open http://localhost:5173
    
    Build and preview
        npm run build
        npm run preview

        
