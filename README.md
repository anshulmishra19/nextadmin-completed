
## CRM Frontend Challenge - Chakr Innovation

This project is a frontend implementation of a CRM (Customer Relationship Management) tool built with Next.js, React, and Shadcn UI components. The goal was to replicate parts of the Twenty.com CRM interface, focusing on design, functionality, and usability.

Features Implemented

1. Side Navigation
Implemented a sidebar with tabs for Prospects, Companies, Settings, Search, Notifications, and Tasks.
Grouped navigation items logically and displayed user and organization information.
2. Command Bar
Added a command bar triggered by Command + K, similar to Twenty.com.
Users can search and navigate directly to pages within the app.
Implemented search functionality for prospects and companies.
Integrated task creation directly from the command bar.
3. People Page
Recreated Twenty.com's People Page with an interactive table of prospects.
Stored example prospects in memory with the ability to add, edit, and delete rows.
Implemented sorting and filtering of table columns.
Enabled inline cell editing and supported custom column types (text, checkbox, date, number).
Displayed detailed prospect information on the left side when clicked, with tabs for Tasks, Notes, and Emails.
4. Settings Page
Implemented a Settings menu with sections for Profile and Appearance.
Profile section included basic user configuration options.
Appearance section allowed users to switch between Light, Dark, Purple Light, and Purple Dark themes, with UI changes reflecting theme selections.
Added other relevant settings as needed.
5. Tasks
Created a to-do list where users can manage their tasks.
Associated tasks with prospects for visibility within the prospect view.
Tech Stack
Next.js for server-side rendering and routing.
React for building UI components.
Shadcn UI for consistent and aesthetic UI components.
TypeScript for type safety.
usehooks-ts for custom React hooks.
TanStack Query for data fetching and caching.
TanStack Table for displaying tabular data.
dayjs for date manipulation.
Additional Libraries
clsx for conditional class names.
lodash-es for utility functions.
immer for immutable state updates.






This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

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

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
