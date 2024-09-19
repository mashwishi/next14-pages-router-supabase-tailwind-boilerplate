# Next.js 14 Pages Router Supabase Tailwind Boilerplate

A simple boilerplate for starting a Next.js 14 pages router project with Supabase authentication, Tailwind CSS, and TypeScript support.

## Features

- **Next.js 14** - Latest Next.js framework with server-side rendering, file-based routing, and more.
- **Supabase Auth** - Ready-to-use authentication via Supabase.
- **Tailwind CSS** - Utility-first CSS framework.
- **TypeScript** - Static type checking for JavaScript.

## Getting Started

### 1. Clone the Repository

```
git clone https://github.com/mashwishi/NextSupabase-Tailwind-Boilerplate.git
```

### 2. Install Dependencies

```
npm install
```

### 3. Set up Supabase

Follow the official [Supabase Next.js guide](https://supabase.com/docs/guides/auth/server-side/nextjs?queryGroups=router&router=pages) to configure your Supabase project and authentication.

### 4. Configure Environment Variables

Create a `.env.local` file in the root directory and add your Supabase project credentials:

```
NEXT_PUBLIC_SUPABASE_URL=your-supabase-url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your-supabase-anon-key
```

### 5. Run the Development Server

```
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Additional Resources

- [Next.js Documentation](https://nextjs.org/docs/getting-started/installation#automatic-installation)
- [Supabase Auth Guide](https://supabase.com/docs/guides/auth/server-side/nextjs?queryGroups=router&router=pages)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)

## License

This project is licensed under the MIT License.
