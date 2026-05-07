# EcoPath | Real-Time Air & Climate Intelligence

> Stop reading just a number. EcoPath tells you **WHY** your air is bad and exactly what to do about it — powered by Gemini AI and live web search.

## 🌍 Overview

EcoPath is an **AI-powered agentic dashboard** that delivers real-time air quality analysis, pollution source detection, and personalized health protocols for your city. Instead of just showing you an AQI number, EcoPath leverages cutting-edge Gemini AI and live web search to provide actionable intelligence about your local air quality.

### Key Features

- 🔍 **Real-Time AQI Analysis** – Understand current air quality with live data
- 🤖 **AI-Powered Intelligence** – Gemini AI agent analyzes pollution patterns and sources
- 📍 **Pollution Source Detection** – Identifies what's causing poor air quality in your area
- 💊 **Personalized Health Protocols** – Get tailored health advisories based on current conditions
- 🌐 **Live Web Search Integration** – Current environmental news and relevant data
- 📊 **Agentic Dashboard** – Interactive interface for climate insights

## 🚀 Getting Started

### Prerequisites

- Node.js 16+ 
- npm or yarn
- Gemini API key (from [Google AI Studio](https://makersuite.google.com/app/apikey))

### Installation

```bash
# Clone the repository
git clone https://github.com/linux290/EcoPath-Real-Time-Air-Climate-Intelligence-Agent.git
cd EcoPath-Real-Time-Air-Climate-Intelligence-Agent

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env.local
# Edit .env.local with your API keys
```

### Configuration

Create a `.env.local` file in the root directory:

```env
VITE_GEMINI_API_KEY=your_gemini_api_key_here
VITE_API_BASE_URL=your_api_base_url
```

### Running Locally

```bash
# Development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

The app will be available at `http://localhost:5173` (or as indicated by your dev server).

## 🏗️ Project Structure

```
EcoPath-Real-Time-Air-Climate-Intelligence-Agent/
├── src/
│   ├── main.jsx              # React entry point
│   ├── components/           # Reusable UI components
│   ├── pages/               # Page components
│   ├── hooks/               # Custom React hooks
│   ├── services/            # API & external service integrations
│   └── styles/              # Global styles
├── public/                  # Static assets
│   ├── favicon.svg
│   ├── apple-touch-icon.png
│   ├── og-image.png
│   └── site.webmanifest
├── index.html               # HTML entry point
├── vite.config.js          # Vite configuration
└── package.json            # Dependencies & scripts
```

## 🎨 Design System

EcoPath uses a carefully curated design system built with modern web standards:

### Typography

- **Syne** (700, 800, 900) – Bold, geometric display font for headings
- **DM Sans** – Clean, modern body font with excellent readability
- **DM Mono** – Monospace for data readouts and AQI values

### Color Palette

```css
--color-bg: #0d1f16           /* Deep forest background */
--color-surface: rgba(255, 255, 255, 0.06)
--color-border: rgba(255, 255, 255, 0.10)
--color-green: #4ade80        /* Primary accent */
--color-slate: #94a3b8        /* Secondary text */
```

### Performance Optimizations

- DNS prefetching for Gemini API
- Smooth scroll behavior
- Custom scrollbar styling
- Optimized font loading via Google Fonts
- Antialiased text rendering

## 🔌 API Integration

### Gemini AI Agent

EcoPath uses the [Gemini API](https://ai.google.dev/) to:
- Analyze air quality data contextually
- Provide personalized health recommendations
- Detect pollution patterns and sources
- Generate actionable insights

### Live Data Sources

The app integrates with real-time environmental data providers to fetch current AQI, pollutant levels, and weather conditions.

## 🛠️ Tech Stack

- **Frontend Framework:** React + Vite
- **AI/ML:** Google Gemini API
- **Styling:** CSS (with CSS Variables)
- **Fonts:** Google Fonts (Syne, DM Sans, DM Mono)
- **Build Tool:** Vite
- **Package Manager:** npm/yarn

## 📱 SEO & Social

The project is fully optimized for search engines and social sharing:

- **Open Graph** – LinkedIn, Facebook social preview
- **Twitter Card** – Large image preview on Twitter/X
- **Meta Tags** – Complete SEO metadata
- **Manifest** – PWA support with custom theme color (#1a3a2a)

## 🔒 Privacy & Security

- No personal data collection without explicit consent
- Secure API key management via environment variables
- HTTPS-ready deployment
- Content Security Policy ready

## 📚 Documentation

- [Gemini AI Documentation](https://ai.google.dev/docs)
- [Vite Documentation](https://vitejs.dev/)
- [React Documentation](https://react.dev/)

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License — see the LICENSE file for details.

## 🙋 Support

Found an issue or have a suggestion? 

- Open an [issue](https://github.com/linux290/EcoPath-Real-Time-Air-Climate-Intelligence-Agent/issues)
- Start a [discussion](https://github.com/linux290/EcoPath-Real-Time-Air-Climate-Intelligence-Agent/discussions)
- Contact the maintainer

## 🌱 About EcoPath

EcoPath was built with the vision of making air quality data **actionable and understandable** for everyone. By combining real-time data, AI intelligence, and personalized health protocols, we're helping communities breathe easier and make informed decisions about their health and environment.

---

**Made with ♻️ by EcoPath Intelligence**
