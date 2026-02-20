# Portfolio — Badhon Nandi

A modern, responsive portfolio website built with Next.js 15, TypeScript, Tailwind CSS, and Framer Motion.

## ✨ Features

- **Next.js 15 App Router** — latest stable framework
- **TypeScript** — full type safety
- **Tailwind CSS** — utility-first styling
- **Framer Motion** — smooth, professional animations
- **Dark/Light Mode** — system-aware with toggle
- **Responsive** — mobile-first design
- **SEO Optimized** — OpenGraph, metadata, semantic HTML
- **Accessible** — ARIA labels, keyboard nav, semantic structure
- **Scroll Progress** — indicator bar at top
- **Back to Top** — button appears on scroll
- **Custom 404** — branded error page
- **Single Data File** — all content in `lib/data.ts`

## 📁 Project Structure

```
portfolio/
├── app/
│   ├── about/page.tsx
│   ├── contact/page.tsx
│   ├── experience/page.tsx
│   ├── projects/page.tsx
│   ├── globals.css
│   ├── layout.tsx
│   ├── not-found.tsx
│   └── page.tsx
├── components/
│   ├── home/
│   │   ├── AboutSnippet.tsx
│   │   ├── CTASection.tsx
│   │   ├── ExperienceSnapshot.tsx
│   │   ├── FeaturedProjects.tsx
│   │   ├── Hero.tsx
│   │   └── SkillsSection.tsx
│   ├── BackToTop.tsx
│   ├── FadeIn.tsx
│   ├── Footer.tsx
│   ├── Navbar.tsx
│   ├── ProjectCard.tsx
│   ├── ScrollProgress.tsx
│   └── ThemeProvider.tsx
├── lib/
│   ├── data.ts        ← Edit all your content here
│   └── utils.ts
└── public/
    └── resume.pdf     ← Add your resume here
```

## 🚀 Getting Started

### Prerequisites
- Node.js 18.17+
- npm / pnpm / yarn

### Installation

```bash
# Clone or download this project
cd portfolio

# Install dependencies
npm install

# Start development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## ✏️ Customization

**All content lives in `lib/data.ts`** — edit this single file to customize:

- Your name, title, university, contact info
- Skills and proficiency levels
- Projects (title, description, tech stack, links)
- Work experience (role, org, responsibilities, achievements)
- Education details

## 🌐 Deploy to Vercel

### Option 1: Vercel CLI
```bash
npm i -g vercel
vercel
```

### Option 2: GitHub Integration
1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → New Project
3. Import your repository
4. Click Deploy — zero config needed!

### Environment Variables (Optional)
If you add a contact form backend, set:
```env
CONTACT_FORM_ENDPOINT=https://...
```

## 📝 Adding Your Resume

Place your resume PDF at `public/resume.pdf` — the Resume button in the navbar and About page will automatically link to it.

## 🎨 Theming

Colors are defined in `tailwind.config.ts`:
- **ink** — neutral warm gray palette (backgrounds, text)
- **clay** — warm amber accent (`#c8a97e`)
- **sage** — muted green (`#7a9e7e`)
- **slate** — muted blue (`#6b7fa3`)

To change the accent color, replace `clay` references with your preferred hue.

## 📄 License

MIT — feel free to use this as a template for your own portfolio.
# badhonnandi
