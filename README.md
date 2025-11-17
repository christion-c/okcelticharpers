# OK Celtic Harpers
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)]()
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)]()
[![React](https://img.shields.io/badge/react-18-blue)]()
[![Vite](https://img.shields.io/badge/vite-5-purple)]()

A web application built with **React** and **Vite**, designed to provide digital sheet music to musicians during live concerts. The goal is to offer a reliable, readable, and easily navigable interface for performers using tablets or laptops on stage.

---

## Table of Contents
- [About](#about)
- [Features](#features)
- [Demo / Screenshots](#demo--screenshots)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running Locally](#running-locally)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Deployment](#deployment)
- [Testing](#testing)
- [Future Improvements](#future-improvements)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## About

The OK Celtic Harpers application digitizes sheet music access for musicians performing on stage. It removes the need for paper, reduces disruptions during performances, and provides a dependable and organized way to present music in real time.

---

## Features

- Upload and manage sheet music files (PDF, images, or other supported formats)
- Create and organize set lists for concerts
- Full-screen performance mode for distraction-free reading
- Quick navigation between pieces
- Mobile and tablet-friendly interface
- Zoom and pan controls for readability
- Optional metadata for each piece (title, composer, key, etc.)

---

## Demo / Screenshots

Include screenshots or a demo link here if available:


---

## Tech Stack

- **React 18**
- **Vite 5**
- **JavaScript / TypeScript (optional)**
- **CSS Modules / Tailwind / Your Preferred Styling Method**
- Optional:
  - PDF.js (if rendering PDFs directly)
  - Local storage or backend API (depending on your setup)

---

## Getting Started

### Prerequisites

- Node.js (version 16 or higher recommended)
- npm or yarn

### Project Structure
  okcelticharpers/
├── public/               # Static public assets
├── src/
│   ├── components/       # Reusable UI components
│   ├── pages/            # Page-level components
│   ├── assets/           # Images, icons, fonts
│   ├── styles/           # CSS or style modules
│   ├── utils/            # Helper utilities, data functions
│   └── App.jsx           # Root application component
├── package.json
├── vite.config.js
└── README.md


### Installation

```bash
git clone https://github.com/christion-c/okcelticharpers.git
cd okcelticharpers
npm install
# or:
yarn
```

### Running Locally
npm run dev
# or:
yarn dev

### Testing
npm install -D vitest @testing-library/react
npm run test

