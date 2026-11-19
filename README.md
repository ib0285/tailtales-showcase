# TailTales

**Upload a photo of your pet and turn it into an AI-generated adventure scene.**

> **Status:** Fully built web application, not publicly launched. Source code is private; available on request.

**Timeline:** Project, 2025

## Before / After

One uploaded photo of a pet, and two of the adventure scenes generated from it.

| Original photo | Scene: Jetpack over the city | Scene: Graduation day |
|---|---|---|
| ![Original pet photo](images/original.jpg) | ![AI-generated jetpack scene](images/scene-jetpack.jpg) | ![AI-generated graduation scene](images/scene-graduation.jpg) |

## Screenshots

**Landing page**

![Landing page](screenshots/01-landing.png)

**Choose your adventure**

![Choose your adventure scene cards](screenshots/02-choose-adventure.png)

**Sign in with Google or continue as a guest**

![Sign-in card](screenshots/03-sign-in.png)

**Photo upload**

![Photo upload page](screenshots/04-upload.png)

**Mobile**

<img src="screenshots/05-landing-mobile.png" alt="Landing page on a phone" width="320">

## Key features

- **Photo upload:** drag and drop or browse for a clear photo of a dog or cat (JPG or PNG, up to 10 MB).
- **Choose an adventure scene:** pick from a set of themed scenes such as Beach Adventure, Mountain Hiking, Northern Lights, Birthday Party and Surfing California.
- **AI-generated scenes** created with Replicate image models from the uploaded photo.
- **Google or guest sign-in** through Firebase Authentication.
- **1 free scene** with no sign-up required to try it.
- **Gallery** of generated scenes, kept for signed-in users.
- **Stripe checkout integration** for unlocking more scenes (built, not activated).

## Tech stack

From the project's `package.json`:

- **Frontend:** React 18, Vite, TypeScript, Tailwind CSS, Radix UI components, TanStack Query, Framer Motion
- **Backend:** Node.js with Express, Multer for uploads, Sharp for image handling
- **Authentication:** Firebase Auth (Google and anonymous guest sign-in)
- **Database:** Neon serverless Postgres with Drizzle ORM
- **AI image generation:** Replicate
- **Payments:** Stripe (integration built, not activated)
- **Built on:** Replit

## My role

Product idea, design and full-stack build by Bakhytzhan Ibrayev.

## Source code

The source code is private and is not included in this repository. It is available on request.
