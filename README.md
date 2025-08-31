# Assistant-Teacher-Syllabus-
Features

📑 All subjects & topics stored in data/subjects.json

🔎 Client-side search across subjects, sections, and topics

🖥️ Built with Next.js App Router

🎨 Tailwind CSS styling with responsive UI

🌍 100% static export (works on any host)

Getting Started
1. Clone the repository
git clone https://github.com/your-username/assistant-teacher-syllabus-site.git
cd assistant-teacher-syllabus-site

Install dependencies
npm install

Run the development server
npm run dev

Build for Production
npm run build

This will build and export the static site into the out/ folder.

Preview locally:

npx serve out

Project Structure
app/                 # Next.js App Router pages
  layout.tsx
  page.tsx
  subjects/[slug]/page.tsx
components/          # UI components
data/subjects.json   # All syllabus content here
lib/subjects.ts      # Helper functions
styles/globals.css   # Tailwind global styles
public/              # Static files

Editing Content

Open data/subjects.json

Add/Edit subjects → sections → topics

Rebuild (npm run build) to update static site

Deployment
Vercel (recommended)

Push this repo to GitHub.

Import into Vercel
.

Set:

Build Command: npm run build

Output Directory: out

Deploy → Done ✅

Netlify

Build command: npm run build

Publish directory: out

GitHub Pages
npm run build
git add out -f
git commit -m "Deploy to GitHub Pages"
git subtree push --prefix out origin gh-pages

Then enable Pages in repo settings → branch: gh-pages

📜 License

MIT License. Free to use, modify, and share.

👉 Replace https://github.com/your-username/... with your actual repo URL.
