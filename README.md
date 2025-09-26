SweetCrumbsBakeryPart2 - Sweet Crumbs Bakery
Sweet Crumbs Bakery Website Project

A comprehensive, responsive e-commerce website for Sweet Crumbs Bakery, enabling online cake ordering and business promotion. This project demonstrates modern web development practices with a focus on user experience, accessibility, and responsive design.

📁 Project File Structure
sweet-crumbs-bakery/
├── index.html        # Landing page with company overview
├── menu.html         # Product catalog and shopping cart system
├── gallery.html      # Visual portfolio of bakery products
├── payment.html      # Checkout and order processing
├── contact.html      # Business contact information
├── css/
│   └── style.css     # Main stylesheet with responsive design
├── images/           # Product imagery directory
│   ├── chocolate fudge cake.jpg
│   ├── red velvet cake.jpg
│   └── ... (11 total product images)
└── README.md         # Project documentation

🎯 Feature Overview
Core Website Pages

Home Page (index.html)

Company narrative, including establishment history (founded 2018)

Mission statement emphasizing quality and customer experience

Strategic business goals and sustainability commitments

Clean, welcoming design with hierarchical information architecture

Menu & Ordering System (menu.html)

Extensive product catalog with 20 specialty cakes

Interactive shopping cart with real-time price calculations

Quantity selection and validation constraints

Dynamic cart management (add/remove items)

Persistent cart state using LocalStorage API

Visual Gallery (gallery.html)

High-quality product photography showcasing 11 cake varieties

Accessible image captions with proper semantic markup

Responsive image scaling for optimal viewing across devices

Consistent layout with elegant hover effects

Checkout Process (payment.html)

Comprehensive order summary with itemized pricing

Flexible delivery options (pickup/delivery with R25 fee)

Multiple payment methods (card, EFT, cash)

Form validation with clear error messages

Order confirmation with redirection workflow

Contact Information (contact.html)

Complete business details including operating hours

Geographic location in Durban, South Africa

Multiple contact channels (phone, email, social media)

Integrated navigation back to homepage

🛠️ Technical Implementation
Frontend Technologies

HTML5: Semantic markup with ARIA landmarks for accessibility

CSS3: Flexbox and Grid layouts for responsive design

JavaScript ES6+: Client-side interactivity and cart functionality

LocalStorage API: Persistent cart management

Responsive Design

Mobile-first approach with three main breakpoints:

Desktop: 1200px+ (3-column grid layout)

Tablet: 768px (2-column adaptive layout)

Mobile: 480px (single-column optimized layout)

Ensures optimal viewing experience across all devices

Accessibility Features

Semantic HTML5 elements (<nav>, <main>, <section>, <article>)

ARIA attributes for screen reader compatibility (aria-label, aria-live)

Keyboard navigation for interactive elements

Color contrast compliant with WCAG 2.1 guidelines

Advanced JavaScript Functionality

Shopping Cart Management

const cartItem = {
  name: "Product Name",
  price: 250, // ZAR
  quantity: 1
};
localStorage.setItem("cartItems", JSON.stringify(cart));


Order Processing Workflow

Multi-step form validation with conditional fields

Dynamic pricing calculation including delivery fees

Payment method-specific form sections (card/EFT)

Comprehensive order confirmation summary

🎨 Design System & Visual Identity

Color Palette

Primary: #000000 (Black) – Professional foundation

Accent: #f5d76e (Gold) – Warm, bakery-appropriate highlight

Neutral: #ffffff (White) – Clean background

Text: #333333 (Dark Gray) – Optimal readability

Typography

Headings: Playfair Display – Elegant serif font

Body Text: Poppins – Clean, sans-serif font

Responsive font sizing with relative units (em/rem)

Interactive Elements

Hover effects with smooth CSS transitions

Card-based layouts with subtle shadows

Consistent button styling across all pages

Visual feedback for user interactions

📊 Business Context

Sweet Crumbs Bakery Profile

Established: 2018 in Durban, South Africa

Specialization: Artisan cakes, pastries, and custom creations

Market Position: Premium quality with community-focused values

Growth Strategy: From home-based kitchen to established bakery

Operational Details

Location: 123 Dlaks Street, Durban, 4001

Contact: 031 123 4567 | orders@sweetcrumbs.co.za

Operating Hours:

Monday–Friday: 7:30 AM – 5:00 PM

Saturday: 8:00 AM – 3:00 PM

Sunday: Closed

Social Media: Active on Instagram and Facebook

🚀 Deployment Instructions

Local Development

Extract project files to a dedicated directory.

Ensure all HTML files maintain relative paths.

Populate images/ directory with product photos.

Open index.html in a modern browser.

Production Considerations

Web server configuration for clean URLs

SSL certificate for secure transactions

Cross-browser testing

Optimized image assets for performance

🔍 Technical Requirements Assessment

Browser Compatibility

Chrome 60+, Firefox 55+, Safari 12+, Edge 79+

Performance

Fast initial page load

Efficient JavaScript for cart operations

Responsive images with appropriate sizing

Minimal external dependencies

📚 References

Mozilla Developer Network. (2023). CSS Grid Layout. MDN Web Docs. Link

Marcotte, E. (2010). Responsive Web Design. A List Apart. Link

W3C. (2014). HTML5: A vocabulary and associated APIs. Link

W3C. (2018). Web Content Accessibility Guidelines (WCAG) 2.1. Link
