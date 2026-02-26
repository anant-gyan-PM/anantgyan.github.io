=============================================================================
ANANT GYAN - PROFESSIONAL PORTFOLIO WEBSITE
=============================================================================

PROJECT OVERVIEW:
This is a complete React 19 + Tailwind CSS 4 portfolio website for Anant Gyan,
a Product Manager specializing in GTM Strategy, Product Operations, and Fintech.

=============================================================================
FILE STRUCTURE:
=============================================================================

client/
├── public/                          # Static assets served at root
├── src/
│   ├── pages/
│   │   ├── Home.tsx                # Main landing page
│   │   ├── CaseStudies.tsx         # Detailed case studies page
│   │   ├── Insights.tsx            # Thought leadership articles
│   │   └── NotFound.tsx            # 404 page
│   ├── components/
│   │   ├── ui/                     # shadcn/ui components
│   │   ├── Map.tsx                 # Google Maps integration
│   │   ├── ErrorBoundary.tsx       # Error handling
│   │   └── ManusDialog.tsx         # Dialog component
│   ├── contexts/
│   │   └── ThemeContext.tsx        # Theme provider
│   ├── hooks/
│   │   ├── useComposition.ts       # Custom hooks
│   │   ├── useMobile.tsx
│   │   └── usePersistFn.ts
│   ├── lib/
│   │   └── utils.ts                # Utility functions
│   ├── App.tsx                     # Main app component with routing
│   ├── main.tsx                    # React entry point
│   ├── index.css                   # Global styles and Tailwind config
│   └── const.ts                    # Shared constants
├── index.html                      # Main HTML entry point
├── package.json                    # Dependencies and scripts
├── tsconfig.json                   # TypeScript configuration
├── vite.config.ts                  # Vite build configuration
└── tailwind.config.ts              # Tailwind CSS configuration

=============================================================================
MAIN ENTRY POINT:
=============================================================================

index.html - The main HTML file that loads the React application
- Located in: client/index.html
- Loads the React app from client/src/main.tsx
- Contains meta tags for SEO and responsiveness

=============================================================================
KEY PAGES:
=============================================================================

1. HOME PAGE (client/src/pages/Home.tsx)
   - Hero section with professional headshot and key metrics
   - About section with expertise areas
   - Professional experience timeline (6 positions)
   - Education section (MBA + Bachelor's degrees)
   - Featured case studies grid
   - Thought leadership articles preview
   - Contact section

2. CASE STUDIES PAGE (client/src/pages/CaseStudies.tsx)
   - YouTube-style layout with expandable case study cards
   - ELEVATE Wisconsin: Financial literacy education program
   - Google Gemini: AI query optimization engine
   - CryptoSmartlife: Fintech platform with security architecture
   - Detailed achievements, challenges, and solutions for each

3. INSIGHTS PAGE (client/src/pages/Insights.tsx)
   - Four thought leadership articles with custom thumbnails
   - Building GTM Strategy for EdTech Products
   - Operational Excellence in Fintech
   - Web3 Innovation: Opportunities and Challenges
   - Fintech Compliance: Building Trust Through Regulation
   - Full article content with proper spacing and formatting

=============================================================================
STYLING & DESIGN:
=============================================================================

- Framework: Tailwind CSS 4 with custom design tokens
- Component Library: shadcn/ui
- Typography: Playfair Display (headings), Lora (body)
- Color Scheme: Custom theme with primary, secondary, accent colors
- Responsive Design: Mobile-first approach with breakpoints
- Dark/Light Theme: Configurable via ThemeContext

=============================================================================
IMAGES & ASSETS:
=============================================================================

All images are hosted on CDN (Manus CDN) and referenced via URLs:
- Professional headshot in hero section
- ELEVATE Wisconsin financial literacy image
- Google Gemini system architecture diagram
- CryptoSmartlife security architecture diagram
- Article thumbnail images (4 custom generated images)
- Case study thumbnails

=============================================================================
DEPENDENCIES:
=============================================================================

Key packages included:
- React 19
- React Router (Wouter)
- Tailwind CSS 4
- shadcn/ui components
- Lucide React (icons)
- TypeScript
- Vite (build tool)

=============================================================================
DEVELOPMENT:
=============================================================================

To run locally:
1. Install dependencies: npm install
2. Start dev server: npm run dev
3. Build for production: npm run build
4. Preview production build: npm run preview

=============================================================================
DEPLOYMENT:
=============================================================================

This portfolio is deployed on Manus platform with:
- Automatic HTTPS
- Custom domain support
- CDN for static assets
- Zero-downtime deployments

Live URL: Available through Manus Management UI

=============================================================================
CONTACT & INFORMATION:
=============================================================================

Name: Anant Gyan
Title: Product Manager
Specialization: GTM Strategy | Product Operations | Fintech
Email: Available in Contact section
LinkedIn: Available in Contact section

=============================================================================
LAST UPDATED: February 26, 2026
=============================================================================
