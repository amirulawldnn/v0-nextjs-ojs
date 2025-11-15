# Next.js Project

This is a modern Next.js project template ready for development and deployment.

## Getting Started

### Prerequisites
- Node.js 18.17 or later
- npm, yarn, pnpm, or bun

### Installation

1. Clone the repository:
\`\`\`bash
git clone <your-repo-url>
cd <your-repo-name>
\`\`\`

2. Install dependencies:
\`\`\`bash
npm install
# or
yarn install
# or
pnpm install
# or
bun install
\`\`\`

3. Run the development server:
\`\`\`bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
\`\`\`

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Project Structure

\`\`\`
├── app/                  # Next.js app directory
│   ├── layout.tsx       # Root layout
│   ├── page.tsx         # Home page
│   └── globals.css      # Global styles
├── components/          # Reusable components
│   └── ui/             # UI component library (shadcn/ui)
├── hooks/              # Custom React hooks
├── lib/                # Utility functions
├── public/             # Static files
└── styles/             # Global styles
\`\`\`

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## Technologies Used

- **Next.js 16** - React framework
- **TypeScript** - Type safety
- **Tailwind CSS** - Utility-first CSS
- **shadcn/ui** - Accessible component library

## Deployment

### Deploy with Vercel (Recommended)

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com).

1. Push your code to GitHub
2. Import your repository on [Vercel](https://vercel.com)
3. Vercel will automatically deploy your application

### Other Deployment Options

- **Docker** - Build a Docker image for containerized deployment
- **Self-hosted** - Deploy to your own server

Check out the [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## Learn More

- [Next.js Documentation](https://nextjs.org/docs)
- [Tailwind CSS](https://tailwindcss.com)
- [shadcn/ui](https://ui.shadcn.com)
- [TypeScript Handbook](https://www.typescriptlang.org/docs/)

## License

MIT License - feel free to use this project for your own purposes.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
