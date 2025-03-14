# Fractal

A modern Next.js application with Supabase integration and shadcn/ui components.

## Features

- Next.js 14 with App Router
- TypeScript
- Supabase Integration
- shadcn/ui Components
- Dark Mode Support
- Tailwind CSS

## Getting Started

1. Clone the repository:
\`\`\`bash
git clone https://github.com/Riles4/fractal.git
cd fractal
\`\`\`

2. Install dependencies:
\`\`\`bash
npm install
\`\`\`

3. Create a \`.env.local\` file in the root directory with your Supabase credentials:
\`\`\`
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
\`\`\`

4. Run the development server:
\`\`\`bash
npm run dev
\`\`\`

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Project Structure

- \`app/\` - Next.js app router pages and layouts
- \`components/\` - React components including shadcn/ui components
- \`lib/\` - Utility functions and configurations
- \`public/\` - Static assets

## Available Scripts

- \`npm run dev\` - Run development server
- \`npm run build\` - Build for production
- \`npm start\` - Start production server
- \`npm run lint\` - Run ESLint

## Learn More

To learn more about the technologies used in this project:

- [Next.js Documentation](https://nextjs.org/docs)
- [Supabase Documentation](https://supabase.io/docs)
- [shadcn/ui Documentation](https://ui.shadcn.com)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)