# Homepage Layout

This document outlines the layout and requirements for the homepage of our travel and accommodation platform.

## Header

* **Logo:** Centered or left-aligned.
    * (SVG/PNG file provided).
* **Menu:**
    * **Become a Partner →**
        * Dropdown with WhatsApp links:
            * Hotel Owner
            * Apartment Host
            * Airport Pickup
            * Tourist Guide
            * Trip Planner
    * **About Us:** (single page, no contact form).
* **Language/Currency Selectors:** Top-right (🌐 + 💱).
* **Design:** Solid background color (no images).

## Hero Section

* **Background:** Full-screen image (Umayyad Mosque with a luxury aesthetic).
* **Text:** "More Than a Stay — A Journey to Remember".
* **Search Box:**
    * **Fields:** Destination, Check-in/out, Number of Guests.
    * **CTA:** "Search" (triggers listings page).

## Featured Destinations

* **Title:** "Top-Rated Experiences Waiting for You".
* **Layout:** Horizontal scroll (Swiper.js carousel).
* **Card Contents:**
    * Photo + Name + Location + Tagline + "Book Now" button.

## Key Functional Sections

* **Step Journey:**
    * **Discover:** Browse stays/trips. Optional "Request a Trip Plan" (Trip planning page).
    * **Book:** Secure online payment (Stripe/PayPal).
    * **Enjoy:** Confirmation voucher + support access.
* **Services Grid:**
    * **Items:** Hotels, Apartments, Trip Planner, Airport Pickup, Tour Guides.
    * **Layout:** 3-column grid (mobile-responsive).
* **Testimonials:**
    * Carousel or static grid.
    * **Sample text:** "Seamless experience from booking to check-out!" – Leila, Berlin.

## Footer

* **Links:** Home | Explore | Become a Partner | About | Blog.
* **Legal:** Privacy Policy | Terms | Impressum (German compliance).

## 4. Technical Requirements

### Frontend

* **Framework:** React.js (Next.js)
* **Languages:** HTML/CSS/JS, RTL support for Arabic.
* **Libraries:** Swiper.js (carousels), Tailwind/Bootstrap (styling).

### Backend

* **Database:** Firebase (MVP) or Node.js + MongoDB.
* **Payments:** Stripe API (Swiss account in Euro).
* **Emails:** SendGrid/Postmark (transactional emails).

### Admin Dashboard

* **Features:**
    * View bookings (Pending/Confirmed).
    * Manual status updates (via WhatsApp confirmation).
    * Refund button (triggers Stripe API).

## 5. Design Assets Needed

* **Logo:** SVG/PNG (transparent background).
* **Hero Image:** High-resolution image of the Umayyad Mosque with a luxury aesthetic.
