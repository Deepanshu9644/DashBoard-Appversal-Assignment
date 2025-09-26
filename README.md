# DashBoard-Appversal-Assignment

This project is a pixel-perfect analytics dashboard designed to track Apple Search Ads performance, faithfully implemented based on a Figma design. It provides real-time metrics, interactive charts, and detailed data tables with a responsive layout, modern UI, and smooth animations for an enhanced user experience.

## Live Demo

A live demo of the application is available at the following URL:

[**Live Demo URL**](https://dashboard-appversal.netlify.app/)

## Figma Design Reference

The application was designed to meticulously follow the specifications from the following Figma file:

[**Figma Design Link**]https://www.figma.com/design/HdQf17TQGkKEmYL5hbjc4T/Task?node-id=1-2&t=VpyyaVAzDdHwlqzS-0

---
✨ Features

Responsive Design: Works seamlessly on desktop, tablet, and mobile.

Interactive Dashboard: Displays KPIs at a glance with a clean and intuitive layout.

State Management: Centralized and predictable state handled by Redux Toolkit.

Data Visualization:

Trends Line Chart with gradient fill (via Recharts).

Interactive World Map Heatmap with zoom, pan, and tooltips.

Dynamic Data Tables:

Top List Table with sortable and color-coded cells.

Biggest Changes Table with inline bar charts for performance shifts.

Smooth Animations: Built using Framer Motion for fluid transitions.

Reusable Component Architecture: Modular React components ensure scalability.

🛠 Tech Stack

React 18+ – Functional components & hooks

TypeScript – Static typing for better DX

Redux Toolkit – Scalable and efficient state management

Tailwind CSS – Utility-first, responsive styling

Recharts – Elegant charting library

Framer Motion – Powerful animations

React Table (Concepts) – For building interactive tables

#📂 Project Structure
/
├── public/
├── src/
│   ├── app/
│   │   └── store.ts             # Redux store configuration
│   ├── components/
│   │   ├── ui/                  # Shared UI components 
│   │   ├── BiggestChanges.tsx
│   │   ├── Dashboard.tsx
│   │   ├── Header.tsx
│   │   ├── Sidebar.tsx
│   │   ├── Storefronts.tsx
│   │   ├── Summary.tsx
│   │   ├── TopList.tsx
│   │   └── Trends.tsx
│   ├── features/
│   │   └── dashboard/
│   │       └── dashboardSlice.ts # Redux slice for dashboard
│   ├── App.tsx                  # Main app component
│   ├── constants.tsx            # Icons, constants, mock data
│   ├── index.html
│   ├── index.tsx                # App entry point
│   └── types.ts                 # TypeScript type definitions
└── README.md

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

Make sure you have Node.js and a package manager (npm or yarn) installed on your machine.

-   Node.js (v16 or later recommended)
-   npm (`npm install -g npm`) or yarn (`npm install -g yarn`)

3.  **Install dependencies:**
    This project uses CDN-based imports defined in an `importmap` in `index.html`, so no `npm install` is required for the core libraries. For a typical local setup, you would run:
    ```sh
    npm install
    ```
    or
    ```sh
    yarn install
    ```

### Running the Application

To start the development server, run:

```sh
npm start
```

or

```sh
yarn start
```
