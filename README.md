# WEB-DESIGN-ASSIGNMENT-TWO-
# author Gassimu Karbo Bulliie (LIMKOKWING STUDENT)
# Farm4Uself

A farm-to-city produce marketplace for Sierra Leone, starting with Freetown and the Western Area.
Farmers list their crops, buyers browse and message the farmer directly. No middleman.

**This is a front-end demonstration.** There is no backend, no database and no real accounts.

## How to run it

1. Unzip the project and keep the `images` folder next to the HTML files.
2. Open the `Farm4Uself` folder in VS Code.
3. Install the **Live Server** extension, right-click `index.html` and choose **Open with Live Server**.

You can also double-click `index.html`. Everything works offline, apart from the WhatsApp links.

## Project structure

```
Farm4Uself/
├── index.html              Home: hero search, fresh listings, how it works, price board preview
├── browse-produce.html     Search, filter and sort all listings
├── sell-produce.html       Demo seller login, dashboard and product form
├── market-prices.html      Price board with category tabs and a sample trend chart
├── about.html              Mission, problem, approach
├── contact.html            Contact form (demo) and contact details
├── how-it-works.html       Steps for buyers and farmers
├── farmer-profile.html     Sample farmer profile
├── listing-directory.html  Every listing in one searchable table
├── images/                 All photos (photo-01.jpg ...)
└── README.md
```

Each page is one HTML file with its own inline `<style>` and `<script>`. There are no separate CSS or JavaScript files. Pages link to each other with ordinary relative links.

## What works

- Navigation, mobile menu, active-page highlighting and a "Skip to content" link.
- Search, category, distance, price and availability filters, and sorting on Browse Produce.
- Search and category filter on the Listing Directory.
- Hero search on the homepage, which opens Browse Produce with your search.
- **Seller demo:** Log In, Create Account, Continue as Guest and Forgot Password all work as demonstrations. They only check that fields are filled in. Nothing is verified, created or sent.
- **Seller dashboard:** overview, My Products (edit, mark unavailable, delete), Add New Produce with photo upload and a live listing preview, Orders, and My Profile.
- **Demo orders:** "Details & Order" on a demo listing gives a review step before confirming.
- "Message Farmer", "Contact Farmer" and "Request Produce" open WhatsApp on +232 73 025 826 with a ready-typed message. Change this number by searching for `23273025826` in the HTML files.
- The Contact page shows a link to the Farm4Uself Facebook page.

## What is sample data

- The built-in listings, farmers, prices, harvest dates, response rates, the Musa Conteh profile and the price chart are **examples**, not real people or real prices. Listings are marked "Sample listing".
- The farmer names are placeholders. Do not present them as real farmers.
- The contact email, office and opening hours on the Contact page are placeholders.

## Where data is stored

- Demo listings and orders you create are kept in your browser's **localStorage** (keys `f4u_demo_listings` and `f4u_demo_orders`).
- They survive page changes and refreshes. They are **not shared** with other browsers or devices, and clearing browser data removes them.
- Passwords, usernames and accounts are never stored. Order phone numbers and addresses are not stored either.
- Uploaded photos are shrunk to 800 pixels before saving. If browser storage is full, publishing shows an error instead of pretending it worked.
- After a refresh you return to the login screen, but your listings remain.

## Known limits

- No real login, payments, delivery, database or server-side checks. A real launch needs a proper backend with accounts, private orders and validation.
- Every sample card's "View Details" opens the same sample farmer profile.
- A few photos are small (under 400 pixels wide), so the site shows them whole on a soft background instead of enlarging them. The homepage hero photo is also small and would look sharper if replaced with a larger one.
- The homepage hero and the Sell page background use photos with limited resolution.

## Testing status

Checked with scripts (no browser): page scripts have no syntax errors, every internal link and image path exists, each page builds its content, and the seller flow (demo login, publishing, saving, search, delete, empty states and order review) works in a simulated page.

**Not yet checked in a real browser:** the visual design, mobile and tablet layouts, the footer position on short and long pages, the mobile menu, photo upload and compression, and scroll animations. Please check these in Live Server.

## Photos

The photos were supplied by the project owner. Before any public launch, confirm you have the right to use them commercially, or replace them with your own. Keep the file names, or update the paths in the HTML files.

## Accessibility

Form fields have labels, images have alt text, focus outlines are visible, links work with the keyboard, and animations switch off for people who prefer reduced motion. Colour contrast has not been checked with a tool.



## screenshort
<img width="1920" height="5791" alt="Screenshot 2026-10-23 at 03-46-38 Home – Farm4Uself" src="https://github.com/user-attachments/assets/a3178427-92c1-4d3b-8bf7-223993f48271" />

<img width="1920" height="6731" alt="Screenshot 2026-10-23 at 04-30-48 Browse Produce – Farm4Uself" src="https://github.com/user-attachments/assets/4e0180aa-b695-45c4-ae8b-326c6326168b" />

<img width="1920" height="2713" alt="Screenshot 2026-10-23 at 03-47-36 Market Prices – Farm4Uself" src="https://github.com/user-attachments/assets/7d9e6311-be0b-40b2-a435-5e6c5b2fb471" />

<img width="1920" height="1038" alt="Screenshot 2026-10-23 at 03-47-18 Sell Your Produce – Farm4Uself" src="https://github.com/user-attachments/assets/8c5f9b9a-cb11-42e7-8427-d7784fd2108d" />

<img width="1920" height="1793" alt="Screenshot 2026-10-23 at 04-22-02 Farmer Profile – Farm4Uself" src="https://github.com/user-attachments/assets/ac3ba462-b2d3-4f8f-afb1-c901d22de477" />


<img width="1920" height="1657" alt="Screenshot 2026-10-23 at 03-47-50 About – Farm4Uself" src="https://github.com/user-attachments/assets/862ef35c-9bf3-4459-bf9b-d40b40acc3bc" />

<img width="1920" height="1465" alt="Screenshot 2026-10-23 at 04-03-53 Contact – Farm4Uself" src="https://github.com/user-attachments/assets/6da765c2-ad0d-479f-8395-fda7af5d720c" />










