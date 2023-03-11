## Byte Step - Blog/Website Builder with AirTable

A blog builder using AirTable. 


### Step 1. Set up AirTable table

**Please note that cases are not important here**

1. "Status" - Single Select with **one "Published" option.** This is very important as ByteStep will only display the published blog post.
2. "Title" - Single Line Text 
3. "Content" - Long Text (Markdown)
4. "Banner" - Attachment (for images)

Once all set it should look like this:

<img width="720" alt="Screen Shot 2023-03-10 at 6 15 10 PM" src="https://user-images.githubusercontent.com/4682613/224459763-3f9239fc-04bf-4774-aac0-5ee692a4a72b.png">


### Step 2. Create a Personal Access Token 

You can create a personal access token at [https://airtable.com/create/tokens](https://airtable.com/create/tokens)

Make sure you add a scope **data.records:read**

<img width="720" alt="Screen Shot 2023-03-10 at 6 31 46 PM" src="https://user-images.githubusercontent.com/4682613/224460403-ea878638-6f7f-4895-a372-ef5e43128ede.png">


### Step 3. Copy and Paste the token (and you're all set!)






## Getting Started

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
