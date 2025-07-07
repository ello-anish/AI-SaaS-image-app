# 🤖 AI SaaS Image Platform

An AI-powered SaaS platform for advanced image processing and transformation. This application includes features like image restoration, recoloring, object removal, generative fill, and more, all integrated with a secure payment and credit system.

## 🛠️ Tech Stack

* **Framework**: Next.js
* **Language**: TypeScript
* **Styling**: Tailwind CSS & Shadcn
* **Database**: MongoDB
* **Authentication**: Clerk
* **Image Management**: Cloudinary
* **Payments**: Stripe

## 🚀 Quick Start

Follow these steps to set up and run the project locally on your machine.

### Prerequisites

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/en)
* [npm](https://www.npmjs.com/) (Node Package Manager)

### 1. Clone the Repository

```bash
git clone [https://github.com/ello-anish/AI-SaaS-image-app.git](https://github.com/ello-anish/AI-SaaS-image-app.git)
cd AI-SaaS-image-app
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Set Up Environment Variables

Create a new file named `.env.local` in the root of your project and add your credentials.

```env
# Next.js
NEXT_PUBLIC_SERVER_URL=

# MongoDB
MONGODB_URL=

# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
WEBHOOK_SECRET=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

# Cloudinary
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=

# Stripe
STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
```

### 4. Run the Project

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.
