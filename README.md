# Blumap Travels - Premium Travel Booking Website

A modern, immersive travel booking platform built with React, Next.js, Tailwind CSS, and Razorpay integration.

## Features

- 🌍 **25+ Travel Packages** - Domestic and International destinations
- 🏨 **Detailed Itineraries** - Day-by-day travel plans with inclusions/exclusions
- 💳 **Razorpay Payment Integration** - Secure checkout workflow
- 📱 **Fully Responsive** - Mobile, tablet, and desktop optimized
- 🎨 **Premium UI/UX** - Clean, minimalist design with smooth animations
- 📸 **High-Quality Images** - Professional travel photography from Unsplash
- 🔍 **Search & Filter** - Advanced package discovery
- 📧 **Contact Management** - Inquiry forms and customer support

## Tech Stack

- **Frontend**: React 18 + Next.js 14
- **Styling**: Tailwind CSS 3
- **Icons**: Lucide React
- **Payment**: Razorpay API
- **Date Handling**: date-fns
- **Language**: TypeScript

## Getting Started

### Installation

```bash
npm install
```

### Environment Variables

Create a `.env.local` file:

```
NEXT_PUBLIC_RAZORPAY_KEY_ID=your_razorpay_key_id
NEXT_PUBLIC_API_URL=http://localhost:3000
```

### Development

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

### Build

```bash
npm run build
npm run start
```

## Project Structure

```
├── src/
│   ├── app/
│   │   ├── layout.tsx
│   │   ├── page.tsx
│   │   ├── globals.css
│   │   └── ...
│   ├── pages/
│   │   ├── index.tsx (Home)
│   │   ├── about.tsx (About Us)
│   │   ├── packages.tsx (Packages Directory)
│   │   ├── package/[id].tsx (Package Detail)
│   │   ├── contact.tsx (Contact Us)
│   │   ├── privacy.tsx (Privacy Policy)
│   │   ├── terms.tsx (Terms & Conditions)
│   │   └── checkout.tsx (Checkout)
│   ├── components/
│   │   ├── Navbar.tsx
│   │   ├── Footer.tsx
│   │   ├── Hero.tsx
│   │   ├── PackageCard.tsx
│   │   ├── ImageCarousel.tsx
│   │   └── ...
│   ├── data/
│   │   └── packages.ts (Mock package data)
│   ├── utils/
│   │   ├── razorpay.ts
│   │   └── constants.ts
│   └── styles/
│       └── globals.css
└── public/
    └── ...
```

## Pages

1. **Home** - Hero section, trending destinations, featured packages, testimonials
2. **Packages** - Directory listing with filtering (Domestic/International)
3. **Package Detail** - Full itinerary, images, pricing, booking
4. **About Us** - Company mission, values, trust badges, team
5. **Contact Us** - Inquiry form, support details, map
6. **Privacy Policy** - Legal text
7. **Terms & Conditions** - Legal text

## Payment Integration

The Razorpay integration handles:
- Secure checkout modal/iframe
- Order creation
- Payment verification
- Success/failure states
- Transaction tracking

## Contributing

This is a commercial project. Please ensure all code follows the design system and brand guidelines.

## License

Proprietary - Blumap Travels Private Limited
