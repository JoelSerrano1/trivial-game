# Trivial Game

A trivia game built with Next.js 15, React 19, TypeScript and Tailwind CSS.

## Features

- Interactive trivia gameplay
- Game configuration screen
- Real-time game flow
- Responsive UI with Tailwind CSS

## Tech Stack

- **Framework:** Next.js 16
- **UI:** React 19, TypeScript
- **Styling:** Tailwind CSS 4
- **Package Manager:** pnpm

## Getting Started

### Prerequisites
- Node.js (v18+)
- pnpm (recommended)

### Installation

1. Clone the repository
`ash
git clone https://github.com/JoelSerrano1/trivial-game.git
cd trivial-game
`

2. Install dependencies
`ash
pnpm install
# or npm install
`

3. Set up environment variables
`ash
cp .env.example .env
`
Edit .env with your API URL if needed.

4. Run development server
`ash
pnpm dev
# or npm run dev
`

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Scripts

`ash
pnpm dev     # Start dev server
pnpm build   # Build for production
pnpm start   # Start production server
`

## Project Structure

`
src/
├── app/           # Next.js App Router pages
├── components/    # React components
└── ...
`

## License
MIT

