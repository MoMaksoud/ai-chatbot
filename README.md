Here is an updated **README.md** file for your project based on the files you uploaded:

---

# Chat Application (React + Vite)

This is a **real-time chat application** built using **React, Vite, Supabase, and Google Generative AI**. The project provides a responsive user interface with modern features such as authentication, real-time messaging, and AI integration.

## Features

- 🔥 **Real-time Chat:** Uses Supabase for instant updates.
- 🔑 **Authentication:** User login and signup functionality.
- 🤖 **AI Integration:** Powered by Google's Generative AI.
- 🎨 **Tailwind CSS:** Beautiful and responsive UI.
- ⚡ **Fast & Lightweight:** Built with Vite for optimized performance.

## Tech Stack

- **Frontend:** React, Vite, Tailwind CSS, Framer Motion
- **Backend:** Supabase (Database + Auth)
- **AI:** Google Generative AI
- **Build Tools:** Vite, ESLint, Prettier
- **Routing:** React Router

## Installation & Setup

### Prerequisites

- **Node.js** (Latest LTS recommended)
- **Git** installed on your machine

### Steps

1. **Clone the repository:**
   ```sh
   git clone <repo_url>
   cd <repo_name>
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

3. **Set up environment variables:**  
   Create a `.env` file in the root directory and add the following:
   ```sh
   VITE_GEMINI_API_KEY=your_google_api_key
   VITE_SUPABASE_URL=your_supabase_url
   VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
   ```

4. **Run the development server:**
   ```sh
   npm run dev
   ```
   The app will be available at **http://localhost:5173/chat**

5. **Build for production:**
   ```sh
   npm run build
   ```

6. **Preview production build:**
   ```sh
   npm run preview
   ```

## Project Structure

```
/frontend
├── public/           # Static assets
├── src/
│   ├── components/   # Reusable React components
│   ├── pages/        # Page components
│   ├── hooks/        # Custom hooks
│   ├── utils/        # Helper functions
│   ├── styles/       # Tailwind CSS styles
│   ├── main.jsx      # Entry point
│   └── App.jsx       # Main App component
├── .env              # Environment variables (ignored in Git)
├── .gitignore        # Ignored files
├── package.json      # Project metadata and dependencies
├── vite.config.js    # Vite configuration
└── README.md         # Project documentation
```

## Linting & Code Quality

To check for code quality issues, run:

```sh
npm run lint
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

---

Let me know if you want to add or modify anything! 🚀
