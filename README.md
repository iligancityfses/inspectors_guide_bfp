# Fire Safety Inspectors Guide

A web application to help fire safety inspectors of the Bureau of Fire Protection in the Philippines. This tool is based on the Revised RA 9514 IRR 2019 (Fire Code of the Philippines).

## Features

- Select building occupancy type
- Input number of stories/floors
- Input dimensions for each floor
- Calculate occupant load automatically
- Generate fire safety requirements based on building data

## Tech Stack

- Next.js
- React
- TypeScript
- Tailwind CSS

## Getting Started

### Prerequisites

- Node.js 14.x or later
- npm or yarn

### Installation

1. Clone the repository
2. Install dependencies:

```bash
npm install
# or
yarn install
```

3. Run the development server:

```bash
npm run dev
# or
yarn dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## Deployment on Vercel

This application is designed to be easily deployed on Vercel.

1. Push your code to a GitHub repository.
2. Go to [Vercel](https://vercel.com) and sign up/login.
3. Click "New Project" and import your GitHub repository.
4. Vercel will automatically detect that it's a Next.js project.
5. Click "Deploy" and your application will be live in minutes.

## About the Fire Code

The Revised Fire Code of the Philippines (RA 9514 IRR 2019) establishes requirements for fire safety in buildings based on occupancy type, building size, and other factors. This application helps inspectors determine which requirements apply to a specific building.

## Disclaimer

This tool provides general guidance based on the Fire Code of the Philippines. For comprehensive and official assessment, please consult with certified fire safety professionals or your local Bureau of Fire Protection office.
