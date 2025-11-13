# Portfolio Site - Project Context

## Overview
A modern, interactive personal portfolio website for Usman Javed, Senior Software Engineer specializing in .NET, Azure, and cloud-native applications.

## Architecture Overview

### Frontend Stack
- **HTML5**: Semantic markup with modern structure
- **CSS3**: Advanced styling with CSS custom properties (variables), animations, gradients, and responsive design
- **Vanilla JavaScript**: No frameworks, pure JavaScript for optimal performance
- **Google Fonts**: Inter font family for modern typography

### Design System
- **Theme Support**: Light/Dark mode toggle with localStorage persistence
- **Color Palette**: CSS custom properties for consistent theming
- **Responsive Design**: Mobile-first approach with breakpoints at 480px, 768px, and 1024px
- **Animation Library**: Custom fade-in-up animations with staggered timing

## Current Features

### 1. Hero Section
- **Animated Background**: Floating gradient orbs with parallax effect
- **Dynamic Typography**: Large, bold headline with gradient accent
- **Call-to-Action Buttons**: Primary and secondary button styles
- **Scroll Indicator**: Animated mouse icon encouraging exploration

### 2. Statistics Dashboard
- **Animated Counters**: Numbers count up when section comes into view
- **Key Metrics**: 5 years experience, 15+ projects delivered, 3+ SaaS products launched, 20+ technologies mastered
- **Visual Cards**: Hover effects with elevation changes

### 3. About Section
- **Professional Summary**: Detailed background and expertise
- **Highlighted Keywords**: Color-coded technical terms
- **Inspirational Quote**: Developer quote with styled formatting

### 4. Experience Highlights
- **Achievement Cards**: Grid layout showcasing key accomplishments
- **Icon System**: Emoji icons for visual interest
- **Hover Interactions**: Cards lift on hover with shadow effects

### 5. Projects Showcase
- **Featured Project**: Large card with split layout (content + visual) - Enterprise SaaS Platform
- **Workplace Projects Section**: Professional projects with detailed descriptions
  - Fuel Data ETL Pipeline (1000+ stations, millions of records/second)
  - Fuel Analytics Dashboard (real-time monitoring, alarms, analytics)
  - Alarm Engine with Deadband & Persistence (7200× performance improvement)
- **Personal Projects Section**: Side projects and experiments
  - YouTube Automation System (AI-powered content generation)
- **Project Categories**: Clearly separated workplace and personal projects with icons
- **Technology Tags**: Styled badges for tech stack
- **Performance Metrics**: Visual indicators for impressive achievements
- **Project Highlights**: Key features listed with checkmarks
- **External Links**: GitHub and project links

### 6. Tech Stack & Skills
- **Categorized Skills**: Organized by Languages, Frameworks, Cloud, AI & Integrations, Blockchain, Certifications, and Specializations
- **Animated Progress Bars**: Visual skill level indicators with shimmer effect
- **Interactive Tags**: Hoverable tech badges
- **Certifications & Credentials Section**: Interactive badge display featuring WES Verified International Academic Qualifications (Credly badge), IBM Blockchain Essentials, and IBM Blockchain Foundation Developer certifications
- **Specializations Grid**: Key competencies in card format

### 7. Contact Section
- **Contact Cards**: Email, LinkedIn, and GitHub with icons
- **Interactive Links**: Hover effects and smooth transitions
- **Resume Download**: Prominent CTA button

### 8. Navigation
- **Sticky Navbar**: Fixed header with glassmorphism effect
- **Smooth Scrolling**: Animated scroll to sections
- **Active Link Highlighting**: Current section indicator
- **Mobile Menu**: Responsive hamburger menu (structure in place)
- **Theme Toggle**: Sun/moon icon with smooth transition

### 9. Interactive Features
- **Intersection Observer**: Animations trigger on scroll into view
- **Parallax Effects**: Background elements move at different speeds
- **3D Tilt Effect**: Project cards tilt on mouse movement
- **Scroll to Top Button**: Appears after scrolling 500px
- **Keyboard Shortcuts**: Ctrl/Cmd+K to toggle theme
- **Easter Egg**: Konami code for fun interaction

### 10. Performance Optimizations
- **Minimal Dependencies**: Only Google Fonts as external resource
- **Efficient Animations**: CSS transforms and opacity for GPU acceleration
- **Lazy Loading**: Intersection Observer for on-demand animations
- **LocalStorage**: Theme preference persistence
- **Performance Monitoring**: Console logs for page load metrics (dev mode)

## File Structure
```
portfolio/
├── index.html          # Main HTML structure
├── style.css           # Complete styling and animations
├── script.js           # Interactive JavaScript features
├── project_context.md  # This file
├── favicon.png         # Site favicon (if exists)
└── resume.pdf          # Downloadable resume (if exists)
```

## Design Principles

### Visual Design
1. **Modern Aesthetics**: Gradient backgrounds, smooth animations, clean typography
2. **Accessibility**: Semantic HTML, ARIA labels, keyboard navigation
3. **Professional**: Balanced use of colors, proper whitespace, clear hierarchy
4. **Engaging**: Interactive elements, hover effects, smooth transitions

### User Experience
1. **Fast Loading**: Minimal dependencies, optimized assets
2. **Responsive**: Works seamlessly on all device sizes
3. **Intuitive Navigation**: Clear sections, smooth scrolling, visual feedback
4. **Engaging Content**: Animated counters, progress bars, interactive cards

### Technical Excellence
1. **Clean Code**: Well-commented, organized, maintainable
2. **Modern Standards**: ES6+ JavaScript, CSS Grid/Flexbox, HTML5
3. **Browser Compatible**: Works on modern browsers
4. **Performance**: Efficient animations, lazy loading, optimized rendering

## Color Scheme

### Light Mode
- Primary: #0066ff (Blue)
- Secondary: #00d4ff (Cyan)
- Accent: #ff3366 (Pink)
- Background: #ffffff (White)
- Text: #1a1a2e (Dark)

### Dark Mode
- Background: #0f1419 (Near Black)
- Card Background: #1a1f2e (Dark Blue-Gray)
- Text: #e2e8f0 (Light Gray)
- Borders: #2d3748 (Medium Gray)

### Gradients
- Primary: Purple to Pink (#667eea → #764ba2)
- Secondary: Pink to Red (#f093fb → #f5576c)
- Blue: Light Blue to Cyan (#4facfe → #00f2fe)

## Key Achievements Highlighted

1. **Experience**: 5+ years in software engineering
2. **Portfolio**: 15+ projects delivered
3. **Product Development**: 3+ SaaS products launched (AI Resume Generator, YouTube Automation, Enterprise Platform)
4. **Technical Versatility**: 20+ technologies mastered across backend, cloud, AI, and blockchain
5. **Performance Optimization**: 7200x improvement (3 hours → 25 seconds)
6. **Scale**: ETL pipeline handling 1000+ fuel stations with millions of records/second

## Upcoming / In-Progress Features

### Portfolio Site Enhancements
- [ ] Add a blog section for technical articles
- [ ] Integrate GitHub API to show live repository stats
- [ ] Add testimonials/recommendations section
- [x] Include certifications and education section (COMPLETED - WES badge integrated)
- [ ] Add a contact form with email integration
- [ ] Implement more advanced animations (GSAP library)
- [ ] Add project case studies with detailed breakdowns
- [ ] Include a timeline of career progression
- [ ] Add language translation support
- [ ] Implement analytics tracking

### Pakistan Stock Market Fear & Greed Index
- [x] Phase 1: Calculation engine working (COMPLETED)
- [x] Phase 2: Build public website with gauge visualization (COMPLETED - Live at https://www.psx-fear-greed.com/)
- [ ] Phase 3: Add real social media scraping (Twitter, Facebook, Reddit)
- [ ] Phase 4: Add API endpoints and monetization

## Technical Details

### JavaScript Features
- **Theme Management**: Toggle and persist user preference
- **Smooth Scrolling**: Native smooth scroll with offset for fixed navbar
- **Intersection Observer API**: Efficient scroll-based animations
- **Counter Animation**: Custom number counting algorithm
- **Parallax Scrolling**: Background elements with depth effect
- **3D Transforms**: Mouse-based card tilt effect
- **Dynamic Scroll-to-Top**: Appears/disappears based on scroll position
- **Active Navigation**: Highlights current section in navbar
- **Performance Logging**: Development-mode metrics

### CSS Techniques
- **CSS Custom Properties**: Themable design system
- **CSS Grid & Flexbox**: Modern layout techniques
- **CSS Animations**: Keyframe animations for smooth effects
- **CSS Transforms**: Hardware-accelerated animations
- **Pseudo-elements**: ::before and ::after for decorative elements
- **CSS Filters**: Blur effects for glassmorphism
- **Media Queries**: Responsive breakpoints
- **CSS Gradients**: Linear gradients for backgrounds and text

### Accessibility Features
- Semantic HTML5 elements
- ARIA labels on interactive elements
- Keyboard navigation support
- Focus states on interactive elements
- Sufficient color contrast ratios
- Responsive font sizing
- Print-friendly styles

## Browser Support
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Deployment
- Hosted on GitHub Pages (ujavedodl.github.io)
- No build process required (vanilla HTML/CSS/JS)
- Instant deployment via git push

## Maintenance Notes

### Regular Updates
- Update project descriptions as new work is completed
- Refresh statistics (years of experience, project count)
- Add new technologies to skills section as learned
- Update resume.pdf when resume changes
- Refresh contact information if needed

### Performance Monitoring
- Monitor page load times
- Check for console errors
- Test on various devices and browsers
- Validate HTML/CSS periodically
- Optimize images if added

## Deprecated / Removed Features
- Old static header (replaced with sticky glassmorphism navbar)
- Basic light theme only (now has dark mode)
- Simple card layouts (upgraded to interactive 3D cards)
- Basic fade-in animations (now has complex intersection observer system)
- Static statistics (now has animated counters)
- Simple tag display (now has interactive, hoverable tags with progress bars)

## Credits
- **Design & Development**: Usman Javed
- **Font**: Inter by Rasmus Andersson (Google Fonts)
- **Inspiration**: Modern portfolio design trends, Brittany Chiang's portfolio, and various developer portfolios

## Project Details

### Workplace Projects

#### 1. Enterprise SaaS Platform (Featured)
- Leading development of large-scale operational data management solution
- Microservices architecture with real-time processing
- Handles millions of data points daily
- Tech: .NET Core, Azure, SQL Server, Angular, Redis

#### 2. Fuel Data ETL Pipeline
- Collects data from 1000+ fuel stations
- Processes millions of records per second
- Real-time transformation and Azure SQL ingestion
- Zero data loss with advanced batching
- Tech: C#, Azure Functions, SQL Server, Azure Service Bus

#### 3. Fuel Analytics Dashboard
- High-end business intelligence platform
- Real-time tank level monitoring
- Reconciliation reports and delivery tracking
- Critical and warning alarm systems
- Detailed operational data for compliance
- Tech: ASP.NET MVC, SQL Server, Power BI, Azure, SignalR, Chart.js

#### 4. Alarm Engine with Deadband & Persistence
- 7200× performance improvement (3 hours → 25 seconds)
- Advanced deadband logic to prevent false alarms
- Persistence mechanisms for data integrity
- Tech: C#, Azure Functions, SQL Server, Redis Cache

### Personal Projects

#### 1. AI Resume Generator SaaS
- Full-stack SaaS platform for AI resume generation
- OpenAI GPT integration for content
- ElevenLabs voice synthesis
- Stripe payment integration
- Complete monetization model
- Tech: C# .NET, OpenAI API, ElevenLabs, Stripe, Azure, SQL Server

#### 2. YouTube Automation System (AutoTube)
- End-to-end AI-powered content pipeline
- Automated creation, voicing, and captioning
- GPT and ElevenLabs integration
- Automated uploads to YouTube
- **Live SaaS Platform:** [https://autotube.org/](https://autotube.org/)
- Features: Single video generation, bulk generation, smart autoclipper, trend intelligence, multi-channel management
- Tech: Python, OpenAI GPT, ElevenLabs, YouTube API, FFmpeg

#### 3. Decentralized Applications (dApps)
- Blockchain-based applications
- Smart contract development
- Web3 integrations
- Distributed ledger technology
- IBM Blockchain certified
- Tech: Solidity, Smart Contracts, Web3.js, Ethereum, Blockchain

#### 4. Pakistan Stock Market Fear & Greed Index
- First-ever Pakistan Stock Market (PSX) Fear and Greed Index
- Multi-source data aggregation and sentiment analysis
- Real-time calculation engine with automated hourly updates
- Advanced normalization using z-score methodology
- **Live Website:** [https://www.psx-fear-greed.com/](https://www.psx-fear-greed.com/)
- Tech: Python, Yahoo Finance API, RSS feeds, Google Trends API, PostgreSQL (Neon), GitHub Actions
- **Data Sources:**
  - Market Data: Yahoo Finance (KSE-100 index)
  - News Sentiment: RSS feeds from Pakistani business news
  - Google Trends: PSX-related searches in Pakistan
  - Social Media: Twitter, Facebook, Reddit (Phase 2)
- **Calculation Components (100% total):**
  - Momentum (25%): 14-day rate of change
  - Volatility (20%): 30-day volatility (inverted)
  - News (20%): RSS sentiment analysis
  - Social (20%): Social media sentiment
  - Trends (15%): Google Trends interest
- **Normalization Process:**
  - Calculate z-score against 90-day baseline
  - Clip to [-5, 5] range
  - Scale to [0, 100] with 50 as neutral
  - Invert fear signals (volatility)
- **Deployment:** Automated hourly execution via GitHub Actions
- **Database:** PostgreSQL (Neon) with `fg_index_readings` table
- **Status:** Phase 2 Complete (public website live), Phase 3 In Progress (real social media scraping)
- **Monitoring:**
  - Check calculation logs: `pm2 logs psx-sentiment`
  - View recent readings: `SELECT * FROM fg_index_readings ORDER BY timestamp DESC LIMIT 5;`
- **Troubleshooting:**
  - **Database Connection Issues:** Verify DATABASE_URL in .env, check Neon database is active, test with `npm run test-db`
  - **Yahoo Finance Issues:** KSE-100 symbol might not be available, check console logs for alternative symbols, consider fallback to PSX website scraping
  - **News RSS Issues:** Some feeds might be down, check individual feed URLs, system continues with available feeds
  - **PM2 Issues:** Check status with `pm2 status`, view logs with `pm2 logs psx-sentiment`, restart with `pm2 restart psx-sentiment`

## New Additions from CV Review

### Key Achievements Added
1. **AI SaaS Development**: Multiple AI-powered products with OpenAI, Stripe, ElevenLabs
2. **Blockchain & Web3**: dApps with smart contracts, IBM certified
3. **Financial Systems**: Dashboards processing millions of financial transactions

### Technologies Added
- **Frameworks**: WinForms, jQuery
- **Cloud**: Azure Data Factory, Git
- **AI & APIs**: OpenAI API, ElevenLabs, Stripe, YouTube API, Jira API, Power BI
- **Blockchain**: Solidity, Smart Contracts, Web3.js, Ethereum
- **Data & Analytics**: Yahoo Finance API, RSS feeds, Google Trends API, PostgreSQL, GitHub Actions, Sentiment Analysis

### Metrics Enhanced
- Alarm Engine: Now shows 300K+ events processed
- Stats Dashboard: Updated to reflect professional achievements:
  - 5 Years Experience
  - 15+ Project Count
  - 3+ SaaS Products Launched
  - 20+ Technologies Mastered

### Professional Highlights
- Actively seeking Senior Software Engineer roles
- Ready for immediate onboarding
- IBM Blockchain Essentials & Foundation Developer certified
- Multilingual: English (C1), Urdu (Native), Basic Chinese (A1)
- Freelance experience on PeoplePerHour (2017-2020)

## Version History
- **v2.5** (2025-01-XX): Added live website links for PSX Fear & Greed Index (https://www.psx-fear-greed.com/) and AutoTube (https://autotube.org/), updated portfolio with enhanced project descriptions and live links, marked Phase 2 of PSX project as complete
- **v2.4** (2025-01-XX): Added Pakistan Stock Market Fear & Greed Index project documentation - first-ever PSX sentiment analysis tool with multi-source data aggregation, automated hourly updates via GitHub Actions, and advanced normalization methodology
- **v2.3** (2025-11-07): Added Certifications & Credentials section with WES Verified International Academic Qualifications badge (Credly integration), IBM Blockchain certifications, responsive certification cards with hover effects
- **v2.2** (2025-11-04): Added CV-based achievements: AI Resume Generator SaaS, Blockchain/dApps, Financial Systems, 300K+ events metric, expanded tech stack with blockchain & AI tools
- **v2.1** (2025-11-04): Added Fuel Data ETL project, updated Fuel Analytics Dashboard, reorganized into Workplace/Personal sections
- **v2.0** (2025-11-04): Complete modern redesign with animations, dark mode, interactive features
- **v1.0** (Previous): Basic portfolio with simple styling

---

Last Updated: January 2025


