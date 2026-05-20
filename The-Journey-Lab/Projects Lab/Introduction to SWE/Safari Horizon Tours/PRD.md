📄 Product Requirements Document: Safari Horizon Tours
1. Project Overview
The goal is to build a high-quality, multi-page informational website for a Kenyan safari company. 
The site must be built using pure HTML, prioritizing semantic tags to ensure accessibility and clear structure.
2. Objectives
Provide a seamless navigation experience across 5 distinct pages.Present Kenyan safari packages using structured lists and tables.
Showcase visual content through external image links.
3. Core Requirements
Semantic HTML: Use tags like <header>, <nav>, <main>, <section>, <article>, and <footer>.
Consistent UI: The navigation menu and footer must be identical across all pages to provide a cohesive user experience.
Assets: Use absolute URLs for images (e.g., from Unsplash or Pexels).
Interactivity: Use internal anchors (e.g., href="#itinerary") for long-page navigation.
4. Site Map & Page Content
PageFilenameKey Content ElementsHomeindex.htmlHero image, company mission, "Why Choose Us" section, and links to top tours.About Usabout.htmlHistory of the company, team descriptions, and core values.Tourstours.htmlA table comparing price/duration; nested lists for daily itineraries.Gallerygallery.htmlA grid-like layout of safari images with descriptive alt text.Contactcontact.htmlA form with inputs for name, email, tour selection (dropdown), and message.5. Shared Component SpecificationsHeader & NavigationEvery page must contain the following navigation links in a <nav> block:HomeAbout UsToursGalleryContactFooterThe footer must contain:Company Name: Safari Horizon ToursCopyright: © 2025Address: 123 Safari Way, Nairobi, KenyaContact: +254 700 000 000 | info@safarihorizon.co.ke6. Technical Implementation TipsTables for Comparison: Use <table>, <thead>, and <tbody> on the tours.html page to compare "Maasai Mara Express" vs. "Amboseli Adventure."Forms: In contact.html, ensure you use proper labels:HTML<label for="name">Full Name:</label>
<input type="text" id="name" name="name" required>
Internal Anchors: On the Tours page, you can create a "Back to Top" link using <a href="#top"> and setting id="top" on the body or header.7. Success CriteriaAll links in the navigation menu work correctly (no 404s).Images load correctly via external URLs.The code passes HTML validation (properly nested tags).The "Safari" theme is consistent in the text and image choices.