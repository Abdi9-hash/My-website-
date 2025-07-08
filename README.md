# My-website-
"Official website for QuickSalesHub – showcasing products and services
{
  "name": "home-service-hub",
  "version": "1.0.0",
  "scripts": {
    "dev": "next dev",
    "build": "next build && next export",
    "start": "next start",
    "export": "next export",
    "deploy": "gh-pages -d out"
  },
  "dependencies": {
    "next": "^14.0.0",
    "react": "^18.2.0",
    "react-dom": "^18.2.0"
  },
  "devDependencies": {
    "gh-pages": "^6.0.0"
  }
}
/** @type {import('next').NextConfig} */
const nextConfig = {
  output: 'export',
  images: {
    unoptimized: true,
  },
  reactStrictMode: true,
  trailingSlash: true,
  basePath: "/home-service-hub"
};

module.exports = nextConfig;
