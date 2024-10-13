#!/bin/bash

# BookShare Setup Script

echo "Starting BookShare setup..."

# Supabase Setup
echo "Setting up Supabase..."
echo "Please create an account on Supabase and set up your 'book_share' table and storage buckets manually."

# Firebase Setup
echo "Setting up Firebase..."
echo "Please create an authentication instance in your Firebase project manually."

# Installation
echo "Installing project dependencies..."
npm install
yarn install
pnpm install
bun install

# Running the Development Server
echo "Starting the development server..."
npm run dev
yarn dev
pnpm dev
bun dev

echo "Open http://localhost:3000 in your browser to see the application in action."

# Editing the Application
echo "You can start editing the page by modifying app/page.tsx. The page auto-updates as you edit the file."

# Fonts Optimization
echo "This project uses next/font to automatically optimize and load Inter, a custom Google Font, enhancing the visual appeal of the application."

echo "BookShare setup complete!"
