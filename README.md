# Promptify – Prompts generator for Devs (UI)

A simple tool to generate and share development prompts for inspiration and learning.
> Think. Prompt. Build.

## 🗓️ MVP Scope

| **Feature**                      | **Priority** | **Description**                              |
|----------------------------------|--------------|----------------------------------------------|
| User Registration/Login          | High         | With JWT + refresh tokens                    |
| Create, edit, and delete prompts | High         | Each post has a title, description, and tags |
| List prompts with pagination     | High         | Display a public list filterable by tags     |
| Upvote requests                  | High         | Simple, no-duplicate voting system           |
| Save favorite prompts            | Medium       | Users save posts to their profile            |
| Comments in prompts              | Medium       | Basic, non-threaded comments                 |
| AI to suggest new prompts        | Low          | Integration with OpenAI API for suggestions  |

## 🔧 Used Technologies
-   **React**: Main Frontend Library.
-   **Vite**: As quick bundler.
-   **TypeScript**: Superset of JavaScript that adds static typing.
-   **DaisyUI**: Clean and Quick Styles

<!--
React Router (rutas si es SPA)
Axios o fetch (para llamadas al backend)
React Query o SWR (opcional para manejo de datos/estado)
Heroicons o Lucide (iconos bonitos)
Zod o Yup (opcional para validación de formularios)
clsx o classnames (opcional para manejo de clases condicionales)
eslint + prettier (linter y formato de código) -->

## 🛠️ Main Frontend UI Resources  

### 🟢 High priority:
-   Home page
-   Sign up / Login
-   User dashboard
-   Create/Edit/Delete prompts
-   Prompt detail
-   View prompt, tags, author
-   General search
-   Prompt list with tag filters
-   Pagination
-   Simple form with validation

### 🟡 Medium priority:
-   Vote and mark as favorite
-   Favorites list
-   Vote and comment history
-   View comments and add one

### 🔵 Low priority:
-   Generate prompt with AI (optional)
-   Show generated result with save button
-   Button to open modal or page with topic input

<!--
Bonus opcionales para destacar
-   SEO básico React Helmet
-   Tests básicos (Jest + React Testing Library + Supertest)
-   Deploy automático en Vercel + Railway
-   Notificaciones tipo toast para UX (react-toastify o similar)
-   Rate limiting / seguridad básica (express-rate-limit)
-->
<!-- 
1.   **Deploy**:
    -   *Frontend*: TBD
-->