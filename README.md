# 🎂 Birthday 18th

A modern birthday website built with Astro, Tailwind CSS, GSAP, and Supabase. Features include a birthday landing page, interactive gallery, wish submission system, and blog support.

![Preview](./src/assets/demo/preview.png)

## ✨ Features

- 🎉 Interactive birthday landing page
- 💌 Wish submission form
- 🖼️ Photo gallery
- 📝 Blog posts support
- ☁️ Supabase integration
- 📱 Fully responsive design
- ⚡ Fast performance with Astro
- 🎨 Smooth animations with GSAP

## 🛠️ Tech Stack

- [Astro](https://astro.build/)
- [Tailwind CSS](https://tailwindcss.com/)
- [GSAP](https://gsap.com/)
- [Supabase](https://supabase.com/)

## 📂 Project Structure

```text
.
├── database/
│   └── schema.sql
├── public/
│   ├── favicon.svg
│   └── profile.jpg
├── src/
│   ├── assets/
│   │   ├── demo/
│   │   ├── services/
│   │   └── *.svg
│   ├── components/
│   │   ├── About.astro
│   │   ├── Bars.astro
│   │   ├── Button.astro
│   │   ├── CallToAction.astro
│   │   ├── Footer.astro
│   │   ├── FormGallery.astro
│   │   ├── FormMakeAWish.astro
│   │   ├── Gallery.astro
│   │   ├── Header.astro
│   │   ├── Hero.astro
│   │   ├── MakeAWish.astro
│   │   ├── MarkdownPost.astro
│   │   └── Marquee.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── lib/
│   │   └── supabase.js
│   ├── pages/
│   │   ├── posts/
│   │   │   ├── post-1.md
│   │   │   ├── post-2.md
│   │   │   └── post-3.md
│   │   ├── blog.astro
│   │   └── index.astro
│   ├── styles/
│   │   └── global.css
│   └── config.ts
├── .env.example
├── astro.config.mjs
├── package.json
├── tsconfig.json
└── README.md
```

## 🚀 Getting Started

Clone the repository:

```bash
git clone <repository-url>
cd birthday18th
```

Install dependencies:

```bash
pnpm install
```

Create your environment file:

```bash
cp .env.example .env
```

Configure your Supabase credentials:

```env
PUBLIC_SUPABASE_URL=your_supabase_url
PUBLIC_SUPABASE_KEY=your_supabase_anon_key
```

Run the development server:

```bash
pnpm run dev
```

Open:

```text
http://localhost:4321
```

## 🗄️ Database Setup

Run the SQL schema located in:

```text
database/schema.sql
```

inside your Supabase SQL Editor to create the required tables.

## 🧞 Available Commands

| Command         | Description                          |
| --------------- | ------------------------------------ |
| `pnpm install`   | Install dependencies                 |
| `pnpm run dev`   | Start development server             |
| `pnpm run build` | Build project for production         |
| `pnpm run preview` | Preview production build locally   |

## 📸 Screenshots

Add your project screenshots here.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
