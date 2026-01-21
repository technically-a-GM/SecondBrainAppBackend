📌 Second Brain App

A Second Brain web app that helps you store, organize, and retrieve knowledge from notes and social platforms like YouTube and Twitter/X using embeddings-based semantic search — just like your personal AI-powered memory.

🚀 Features

✅ Save & manage personal notes
✅ Store content from social platforms (YouTube, Twitter/X links/posts)
✅ Generate embeddings to represent knowledge semantically
✅ Fast semantic search (search by meaning, not exact keywords)
✅ Clean and responsive UI built with React
✅ Type-safe development using TypeScript

🧠 Why Second Brain?

We consume tons of content daily — videos, tweets, articles, notes — but later we forget where we saw something.

This app acts like your personal knowledge hub, allowing you to:

store anything useful

build a structured memory system

search and retrieve knowledge instantly

🛠️ Tech Stack

Frontend: React + TypeScript

UI: (Add your UI framework if used — Tailwind / Material UI / Chakra etc.)

Embedding & Search: Embeddings-based semantic matching

State Management: (Redux/Zustand/Context API – if applicable)

Build Tooling: Vite / CRA (based on what you used)

📸 Screenshots

<img width="1919" height="846" alt="image" src="https://github.com/user-attachments/assets/650a0e0a-8d76-4a84-b0cd-164e3be23ff4" />

📂 Project Structure
src/
 ├── components/       # Reusable UI components
 ├── pages/            # App pages (Home, Notes, Search, etc.)
 ├── hooks/            # Custom React hooks
 ├── utils/            # Helper functions
 ├── services/         # API calls / embedding functions
 ├── types/            # TypeScript types/interfaces
 └── App.tsx

⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>

2️⃣ Install dependencies
npm install

3️⃣ Run the app
npm run dev


App will run on:

http://localhost:5173/

🔍 Embeddings + Semantic Search (How it works)

This app uses embeddings to store each note/post as a vector representation.

When you search:

search query is converted to an embedding vector

similarity is computed with stored vectors

most relevant results are returned

This enables:

✅ searching by meaning
✅ retrieving information even if words don’t match exactly

Example:

saved note: "React state management with Zustand"

search: "lightweight store for React"
➡️ still matches due to semantic similarity.

🧩 Supported Content Types

📒 Notes (plain text)

▶️ YouTube content (video links + metadata)

🐦 Twitter/X content (tweets/threads + links)
