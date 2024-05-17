This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

### 1. Set Up Your Next.js Project
First, ensure you have a Next.js project set up. If not, you can create one using:

```bash
npx create-next-app@latest my-stripe-app

```

### 2. Install Stripe Packages
Install the necessary Stripe packages for both the client-side and server-side:

```bash
npm install @stripe/stripe-js stripe
```

### 3. Configure Environment Variables
Create a `.env.local` file at the root of your project to store your Stripe secret and public keys:

```plaintext
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=your-publishable-key
STRIPE_SECRET_KEY=your-secret-key
```

### 4. Run Your Next.js Application
Start your Next.js application using:

```bash
npm run dev
```

Navigate to `http://localhost:3001/checkout` to see your checkout page. When you click the checkout button, it will create a checkout session and redirect you to Stripe's checkout page.


