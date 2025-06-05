# 🚀 Portfolio – A Modern Dynamic Portfolio with Admin Dashboard

Welcome to **Portfolio**, a fully dynamic, modern, and feature-rich portfolio solution built for developers, designers, and creators!  
Showcase your work and manage your content with an elegant admin dashboard.

---

## 🌟 Features

### 🖥️ Frontend – Public Portfolio Site

1. **Hero Section**
   - Stylish animated intro (Framer Motion / GSAP)
   - Name, designation, short intro, CTA buttons (Contact / Resume)
   - Optional: Typewriter effect for roles

2. **About Section**
   - Personal image, bio, & key highlights (dynamic from DB)

3. **Skills Section**
   - Dynamic skill categories
   - Animated progress bars/tags
   - Filter by category (Frontend / Backend / DevOps etc.)

4. **Projects Section**
   - Showcase projects with image, title, tags, description
   - GitHub & Live Demo links
   - Tech stack icons
   - Category filter, hover effects, modals, etc.

5. **Experience / Work Timeline**
   - Vertical timeline layout
   - All entries from DB

6. **Blogs Section** _(Optional)_
   - List of blogs (Markdown supported)
   - MDX or Notion API integration

7. **Contact Section**
   - Email form (EmailJS or API route with Nodemailer)
   - Social media links (dynamic)

8. **Resume Download**
   - Resume stored in storage (Cloudinary/Firebase/server)

---

### 🛠️ Admin Dashboard (/admin)

- **Authentication:** Secure admin login (JWT-based or NextAuth.js, Credentials Provider)
- **Protect all admin routes**
- **Dashboard Features:**  
    | Feature    | Actions                             |
    |------------|-------------------------------------|
    | About      | Edit bio, image                     |
    | Skills     | Add / Edit / Delete                 |
    | Projects   | CRUD + Upload images                |
    | Experience | CRUD entries                        |
    | Socials    | Update social links                 |
    | Blogs      | Write in Markdown                   |
    | Resume     | Upload new file                     |

- **Rich text editor:** (react-quill or TipTap)
- **File uploads:** (Cloudinary / local storage)
- **UI:** Tailwind UI (free) or shadcn/ui

---

## 🔐 Tech Stack

- **Framework & Language:**  
  Next.js 15 (App Router), TypeScript

- **Styling:**  
  TailwindCSS, shadcn/ui (Radix + Tailwind)

- **Animations:**  
  Framer Motion, Lottie

- **Forms & Validation:**  
  React Hook Form, Zod

- **Auth:**  
  NextAuth.js (Credentials Provider)

- **Database:**  
  MongoDB Atlas (free tier)

- **ORM:**  
  Mongoose or DrizzleORM

- **Image Handling:**  
  Next/Image, Cloudinary

- **File Uploads:**  
  Cloudinary / UploadThing

---

## 🧩 Bonus Ideas

- **Dark/Light Theme Toggle**  
  Persist user preference (localStorage/cookies)

- **Internationalization (i18n)**  
  Multi-language support (next-intl)

- **Page Transitions**  
  Framer Motion layout transitions

- **SEO Friendly**  
  next-seo or manual metadata management

---

## ✨ Demo

> _Coming Soon!_  
> Or, clone and run locally to explore all features.

---

## 📦 Getting Started

```bash
git clone https://github.com/yourusername/portfolio
cd portfolio
npm install
npm run dev
```

---

## 📫 Contact

- [LinkedIn](https://www.linkedin.com/in/yourusername/)
- [Twitter](https://twitter.com/yourusername)
- [Email](mailto:yourmail@gmail.com)

---

> _Built with ❤️ using Next.js, TypeScript, and the latest modern web technologies._
