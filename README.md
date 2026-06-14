# JK’s Lifestyle — Jeeva Karunya Website

A comprehensive digital presence for JK's Lifestyle (Jeeva Karunya Lifestyle), showcasing its philosophy, products, and community initiatives.

## 📂 Project Structure

```text
jklifestyle/
├── index.html                    # Main landing page (single-file design)
├── style.css                     # Global styles and layout
├── assets/
│   ├── css/
│   │   ├── navbar.css            # Navigation bar styles
│   │   ├── hero.css              # Hero section styles
│   │   ├── About.css             # About JK's Lifestyle
│   │   ├── Organic_Food.css      # Organic food initiatives
│   │   ├── Natural_Products.css  # Natural products
│   │   ├── Dress.css             # Dress and apparel
│   │   ├── Events.css            # Event showcase
│   │   ├── Community.css         # Community programs
│   │   ├── Gallery.css           # Image galleries
│   │   ├── Contact.css           # Contact & footer
│   │   └── Footer.css            # Footer styles
│   ├── images/
│   │   ├── hero_bg.png             # Hero background
│   │   ├── profile_1.png         # Profile picture 1
│   │   ├── profile_2.png         # Profile picture 2
│   │   ├── organic_1.jpg
│   │   ├── organic_2.jpg
│   │   ├── organic_3.jpg
│   │   ├── organic_4.jpg
│   │   ├── dress_1.jpg
│   │   ├── dress_2.jpg
│   │   ├── dress_3.jpg
│   │   ├── dress_4.jpg
│   │   ├── event_1.jpg
│   │   ├── event_2.jpg
│   │   ├── event_3.jpg
│   │   ├── event_4.jpg
│   │   ├── community_1.jpg
│   │   ├── community_2.jpg
│   │   ├── community_3.jpg
│   │   ├── community_4.jpg
│   │   ├── event1.png
│   │   ├── event2.png
│   │   ├── event3.png
│   │   ├── event4.png
│   │   ├── dress1.png
│   │   ├── dress2.png
│   │   ├── dress3.png
│   │   ├── dress4.png
│   │   ├── natural1.png
│   │   ├── natural2.png
│   │   ├── natural3.png
│   │   ├── natural4.png
│   │   ├── organic1.png
│   │   ├── organic2.png
│   │   ├── organic3.png
│   │   ├── organic4.png
│   │   ├── organic5.png
│   │   ├── organic6.png
│   │   └── organic7.png
│   ├── logo.png                    # Brand logo
│   └── slider_bg.jpg             # Slider background
├── js/
│   ├── script.js                 # Main scripts
│   └── aos.js                    # Animation on scroll
└── icons/
    ├── home.svg
    ├── profile.svg
    ├── leaf.svg
    ├── dress.svg
    ├── calendar.svg
    └── mail.svg
```

## ✨ Key Features

### 1. Single-File Responsive Design
- **index.html**: Contains all sections including Navbar, Hero, About JK’s, Organic Food, Natural Products, Dress, Events, Community, Gallery, Contact, and Footer
- **Responsive Breakpoints**: Mobile-first design with media queries for tablets and desktops
- **Smooth Scrolling**: Smooth transitions for section navigation
- **Animation on Scroll**: Uses [AOS (Animation on Scroll)](https://github.com/michalsnik/aos) library for modern entrance animations

### 2. Navigation System
- **Sticky Navbar**: Always visible at the top with transparent background on load, solid background on scroll
- **Smooth Navigation**: Anchors link to sections with smooth scrolling effect
- **Responsive Menu**: Hamburger menu for mobile devices with off-canvas slide-in animation
- **Logo Integration**: JK’s Lifestyle logo displayed prominently

### 3. Page Sections
#### Hero Section
- Full-width image background (`hero_bg.png`)
- Slider with multiple slides (max 5)
- Headline: "JK’s Lifestyle — Jeeva Karunya"
- Subtitle: "Nourishing Body, Uplifting Spirit, Preserving Earth"
- CTA buttons: "View Our Products" (scrolls to products) and "Get in Touch" (scrolls to contact)

#### About JK’s
- Personal profile of founder, JK (Jeyaprakash)
- Two profile images (`profile_1.png`, `profile_2.png`)
- Sections: Founder's Journey, Mission, Vision, Values, Approach
- Social Media links (WhatsApp, Facebook, Instagram, Twitter/X, Threads)

#### Organic Food
- Highlights Jeeva Karunya’s organic farming and store
- Showcases chemical-free produce and harvest yields
- Panchakavya-nourished products
- Image gallery with lightbox popups (grid layout)

#### Natural Products
- Wide range of natural and wellness products
- Products organized by category (Beauty, Personal Care, Home Care, Health, Wellness, Organic Food)
- Image showcase with hover effects

#### Dress
- Showcases traditional and modern dress collections
- Natural, eco-friendly, sustainable materials
- Sections: Dress Collections, Fabric Details, Craftsmanship
- Image gallery with lightbox popups

#### Events & Initiatives
- Features past events and ongoing initiatives
- Organized by category: Cultural, Educational, Social, Wellness, Environmental
- Image gallery with lightbox popups

#### Community Programs
- Highlights community development work
- Organized by category: Education, Skill Development, Environmental, Social Welfare
- Image gallery with lightbox popups

### 4. Rich Media Support
- **Image Carousels**: Smooth sliding animations for product showcases
- **Image Galleries**: Multiple image galleries throughout the site
- **Lightbox Popups**: Click to view larger images with overlay and close button
- **Hover Effects**: Interactive image reveals on hover

### 5. Contact & Footer
- **Contact Form**: Fields for Name, Email, Phone, Subject, Message
- **Social Links**: WhatsApp, Facebook, Instagram, X/Twitter, Threads, LinkedIn, Telegram
- **Business Info**: Address, Phone, Email
- **Footer**: Copyright, privacy policy, terms of use links

## 🎨 Design System

### Color Palette
```css
/* Primary */
--indigo: #1B1F3B;
--gold: #C9922A;
--gold-lt: #E8B84B;
--maroon: #6B2737;
--cream: #F7F2E8;
--sage: #8B9E7E;
--sage-lt: #B5C8A8;
--white: #FFFFFF;
--text-dark: #1A1A2E;
--text-mid: #4A4A6A;
--text-light: #9A9ABB;
```

### Typography
- **Headings**: 'Playfair Display', Georgia, serif
- **Body**: 'Inter', system-ui, sans-serif
- **Font Sizes**: Responsive with clamp() for optimal readability across devices

### CSS Architecture
- **Modular CSS**: Separate files for each section ensure maintainability
- **Custom Properties**: Global variables for colors, fonts, spacing, and transitions
- **Utility Classes**: Common utilities for layout, spacing, and typography
- **Animations**: Custom CSS transitions and AOS for scroll animations

## ⚡ Performance Features

- **Lazy Loading**: Images are loaded naturally without JavaScript intervention
- **Optimized Images**: All images are optimized for web use
- **Smooth Animations**: CSS-based transitions for better performance
- **Responsive Design**: Adapts to all screen sizes without layout shifts

## 🛠️ Setup & Usage

1. **Clone the repository** (or download the ZIP)
2. **Open `index.html`** in your web browser
3. **Customize images** in the `assets/images/` folder
4. **
