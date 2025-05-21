# lectic-se

## Empowering Reflective Learning and Development

The lectic-se Platform is a web application designed to enhance the learning experience for students engaged with Lectica-inspired developmental frameworks, particularly within courses like "Change Management with AI." It provides an interactive and engaging bilingual (English and Swedish) environment for students to work with VCoLs (Virtuous Cycles of Learning) and related assignments, while offering educators robust tools for content management, assignment, and progress tracking.

This project is inspired by the profound developmental insights of Lectica and aims to make these accessible and actionable, with a user experience influenced by the clean and modern aesthetic of schools like Berghs School of Communication.

**Target Domain:** [lectic.se](https://lectic.se) (when deployed)

## Core Features

### For Students:
* **Personalized Dashboard:** Overview of VCoLs, assignments, and developmental progress.
* **Interactive VCoL Player:** Engage with VCoL content through guided steps, reflections, and scenario inputs.
* **AI-Assisted Reflection:** An AI coach provides Socratic prompts to deepen thinking during VCoL exercises (not evaluative).
* **Assignment Submissions:** Streamlined process for submitting work.
* **Personal Journal:** A private space for ongoing reflections and insights.

### For Educators:
* **Admin Dashboard:** Manage students, courses, and content.
* **VCoL Builder/Importer:** Create and manage digital versions of Lectica VCoLs.
* **Assignment Creator:** Design and assign tasks aligned with Lectica principles.
* **Student Progress Tracking:** Monitor student engagement and review submissions.
* **Feedback Tools:** Provide constructive feedback (potential for AI assistance in drafting).

## Key Characteristics
* **Bilingual Support:** Fully localized for English (`en`) and Swedish (`sv`) users.
* **Interactive & Engaging:** Designed to immerse students in their personal development journey.
* **AI-Enhanced:** Leveraging AI to support reflection and provide personalized nudges.

## Tech Stack
* **Frontend:** Next.js 15 (App Router) with TypeScript
* **Styling:** Tailwind CSS
* **Internationalization (i18n):** Next.js built-in i18n with sub-path routing
* **Backend & Database:** **Supabase** (PostgreSQL, Authentication, Storage, Edge Functions)
* **AI Integration:** Anthropic Claude API (or similar) for coaching and text processing.
* **Deployment:** Vercel

## Design Philosophy
* Clean, modern, and professional, inspired by [Berghs.se](https://www.berghs.se/).
* Intuitive navigation and user experience.
* Emphasis on clarity, engagement, and fostering deep reflection.

## Getting Started

**(Development setup instructions will go here and should be updated as the project progresses)**

1.  Clone the repository:
    ```bash
    git clone [https://github.com/](https://github.com/)[your-github-username]/lectic-se.git
    cd lectic-se
    ```
2.  Install dependencies:
    ```bash
    npm install
    # or
    yarn install
    ```
3.  Set up environment variables (create a `.env.local` file based on `.env.example` if provided):
    ```env
    # Supabase Project URL and Anon Key
    NEXT_PUBLIC_SUPABASE_URL=your_supabase_project_url
    NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key

    # Other API keys (e.g., for AI services)
    # ANTHROPIC_API_KEY=your_anthropic_api_key
    ```
4.  Run the development server:
    ```bash
    npm run dev
    # or
    yarn dev
    ```
    Open [http://localhost:3000](http://localhost:3000) (or `http://localhost:3000/en` and `http://localhost:3000/sv` after i18n setup) to view it in the browser.

## Contributing

This project is currently not accepting external contributions. (This can be updated later if you decide to open source parts of it or accept contributions).

## This is information from

[Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

## License

Copyright (c) 2025 [Nils Boldt-Christmas](https://github.com/nilsbc/)

All Rights Reserved.

Refer to the [LICENSE](LICENSE) file for more details.

---
*This README is a starting point and should be updated as the project evolves.*