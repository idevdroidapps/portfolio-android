# Jim Campbell - Android Engineer Portfolio

This is the source code for my professional portfolio website, built with [Astro](https://astro.build/) and deployed on [Cloudflare Workers](https://workers.cloudflare.com/).

**Live Site:** [portfolio-android.idevdroidapps.workers.dev](https://portfolio-android.idevdroidapps.workers.dev/)


## 👨‍💻 About Me

I am a Principal-level **Android Engineer** with over 12 years of experience building high-performance mobile and automotive applications. I specialize in Kotlin, Clean Architecture, and Kotlin Multiplatform (KMP), with a recent focus on agentic AI systems and automation pipelines.

## 🚀 Key Features

- **Project Showcase**: Detailed history of my professional work experience, listed in reverse chronological order.
- **Integrated Resume**: Seamless access to my professional resume (PDF) directly within the site.
- **Modern Tech Stack**: Built with Astro 5 for superior performance and SEO.
- **Responsive Design**: Fully optimized for mobile, tablet, and desktop viewing.
- **Clean Architecture**: Follows best practices for modularity and maintainability.

## 🛠️ Tech Stack

- **Framework**: [Astro 5](https://astro.build/)
- **Styling**: Vanilla CSS with Material Design 3 influences.
- **Content**: Markdown-driven content collections for projects.
- **Deployment**: [Cloudflare Workers](https://developers.cloudflare.com/workers/static-assets/)

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                           | Action                                           |
| :-------------------------------- | :----------------------------------------------- |
| `npm install`                     | Installs dependencies                            |
| `npm run dev`                     | Starts local dev server at `localhost:4321`      |
| `npm run build`                   | Build your production site to `./dist/`          |
| `npm run preview`                 | Preview your build locally, before deploying     |
| `npm run astro ...`               | Run CLI commands like `astro add`, `astro check` |
| `npm run build && npm run deploy` | Deploy your production site to Cloudflare        |

## 📂 Project Structure

- `src/content/projects/`: Contains the markdown files for each professional experience.
- `src/pages/`: Astro pages defining the site routes.
- `src/layouts/`: Reusable page layouts.
- `public/`: Static assets including images and the PDF resume.

---
*Built with ❤️ by Jim Campbell*
