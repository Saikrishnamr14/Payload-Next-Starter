# Payload Next Starter

A modern, production-ready starter template built on Next.js 15, React 19, and Payload CMS 3—featuring TypeScript, Tailwind CSS, shadcn/ui, ESLint, and Prettier. Developed for rapid, scalable, and stylish web projects.

---

## 🚀 Project Summary

Payload Next Starter combines robust headless CMS functionality with the latest advancements in Next.js and React. Designed for developers who demand an elegant codebase, beautiful UI, type safety, and a lightning-fast dev experience, this starter helps you launch dynamic, content-driven sites with ease[2][4][5].

---

## 📦 Features

- **Next.js 15** (App Router) for seamless frontend and API development
- **React 19** for fast, modern UI building
- **Payload CMS 3**—powerful and extensible headless CMS
- **TypeScript** for end-to-end type safety
- **Tailwind CSS** for utility-first design
- **shadcn/ui**—accessible, stylish UI components
- **ESLint & Prettier** for code consistency and formatting
- **Node.js** server runtime
- Ready for deployment and customization

---

## 🗂 Project Structure

```
├── app/                 # Next.js entry point & pages
├── components/          # React/UI components (includes shadcn/ui)
├── lib/                 # Utilities and helpers
├── payload/             # Payload CMS config & collections
├── public/              # Static assets
├── styles/              # Tailwind/global styles
├── types/               # TypeScript type definitions
├── .eslintrc.js         # ESLint configuration
├── .prettierrc          # Prettier configuration
├── next.config.js       # Next.js configuration
├── payload.config.ts    # Payload config
└── ...
```

---

## 🛠 Getting Started

1. **Clone the repo**

   ```bash
   git clone https://github.com/Saikrishnamr14/payload-next-starter.git
   cd payload-next-starter
   ```

2. **Install dependencies**

   ```bash
   npm install
   # or
   yarn install
   ```

3. **Setup environment variables**

   Create a `.env.local` file at the root with:

   ```
   # Next.js
   NEXT_PUBLIC_SITE_URL=http://localhost:3000

   # Payload CMS
   PAYLOAD_SECRET=your-secret-key
   MONGODB_URI=your-mongodb-uri
   ```

4. **Run development server**

   ```bash
   npm run dev
   ```

   - Visit your site at [http://localhost:3000](http://localhost:3000)
   - Access Payload Admin at [http://localhost:3000/admin](http://localhost:3000/admin)

---

## 🛡 Tooling

- **Lint:**  
  ```bash
  npm run lint
  ```
- **Format:**  
  ```bash
  npm run format
  ```
- **Build:**  
  ```bash
  npm run build
  ```

---

## 📚 Documentation

- [Next.js Docs](https://nextjs.org/docs)
- [Payload CMS Docs](https://payloadcms.com/docs)
- [Tailwind CSS Docs](https://tailwindcss.com/docs)
- [shadcn/ui Docs](https://ui.shadcn.com/docs)

---

## 🤝 Contributing

PRs and issues welcome!  
Repo: [github.com/Saikrishnamr14/payload-next-starter](https://github.com/Saikrishnamr14/payload-next-starter)

---
