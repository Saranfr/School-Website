# ABC Academy - School Website

A modern, responsive school website built with Next.js, React, and Tailwind CSS featuring interactive animations and a clean design.

## Features

- **Responsive Design**: Optimized for all devices and screen sizes
- **Interactive Animations**: Smooth animations using Framer Motion
- **Modern UI**: Clean design with Tailwind CSS
- **Sections Include**:
  - Hero section with call-to-action
  - About us with statistics
  - Academic programs
  - Faculty profiles
  - Upcoming events
  - Photo gallery
  - Contact form with information

## Technology Stack

- **Frontend**: React, Next.js 14, TypeScript
- **Styling**: Tailwind CSS
- **Animations**: Framer Motion
- **Icons**: Heroicons

## Getting Started

1. **Install Dependencies**:
   ```bash
   npm install
   ```

2. **Run Development Server**:
   ```bash
   npm run dev
   ```

3. **Open Browser**:
   Navigate to [http://localhost:3000](http://localhost:3000)

## Project Structure

```
school-website/
├── app/
│   ├── globals.css
│   ├── layout.tsx
│   └── page.tsx
├── components/
│   ├── Header.tsx
│   ├── Hero.tsx
│   ├── About.tsx
│   ├── Academics.tsx
│   ├── Faculty.tsx
│   ├── Events.tsx
│   ├── Gallery.tsx
│   ├── Contact.tsx
│   └── Footer.tsx
├── public/
├── package.json
├── tailwind.config.js
└── next.config.js
```

## Customization

- **Colors**: Modify the color scheme in `tailwind.config.js`
- **Content**: Update text content in each component file
- **Images**: Add actual images to the `public` folder and update image paths
- **Contact Form**: Integrate with a backend service or email provider

## Deployment

The website can be deployed on platforms like:
- Vercel (recommended for Next.js)
- Netlify
- AWS Amplify
- Any hosting service that supports Node.js

## Future Enhancements

- Content Management System (CMS) integration
- Backend API for contact form
- Student/parent portal
- Online admission system
- Blog section
- Multi-language support

## License

This project is open source and available under the MIT License.