# Real-Time Poll Frontend (Vue 3)

This is the frontend for a real-time polling web application built with Vue 3 and Vite. It allows hosts to create live polls and participants to vote in real time, with results updating instantly on the screen.

This was developed as a group project for a software engineering course. My main contributions were on the frontend: building Vue components, handling API integration, and working on UI/UX details.

## Tech Stack

- Vue 3 (Composition API)
- JavaScript
- Vite
- HTML5, CSS3
- Axios (or Fetch) for API calls

## Features

- Create and join live polls
- Real-time vote updates
- Results view for hosts and participants
- Responsive layout for desktop and mobile

## Accessibility (WCAG)

I worked with the following accessibility practices in mind:

- Semantic HTML landmarks (`<main>`, `<header>`, `<nav>`, etc.) where appropriate
- Proper `<button>` and `<a>` usage for interactive elements
- Form inputs associated with `<label>` elements
- Text alternatives (`alt` attributes) for meaningful images/icons
- Keyboard-friendly interactions for core flows (navigating, voting)
- Attention to color contrast and readable typography aimed at WCAG 2.1 AA

## Getting Started

### Prerequisites

- Node.js (LTS version recommended)
- npm or yarn

### Install and Run

```bash
# clone the repo
git clone https://github.com/Sabrine001/realtime-poll-frontend.git
cd realtime-poll-frontend

# install dependencies
npm install

# run dev server
npm run dev


