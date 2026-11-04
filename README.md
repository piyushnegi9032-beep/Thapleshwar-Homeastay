# Thapleshwar Homestay — Next.js

This is the Next.js App Router conversion of the existing Thapleshwar Homestay website. It preserves the visual design, logo, homestay photograph, bilingual toggle, rooms, nearby places, contact details, Google Maps links and WhatsApp enquiry flow.

## Requirements
- Node.js 20.9 or newer
- npm

## Run locally
```bash
npm install
npm run dev
```
Open http://localhost:3000.

## Production build
```bash
npm run build
npm start
```

## Deploy to Vercel
1. Create a GitHub repository and upload this project.
2. In Vercel, choose **Add New → Project** and import the repository.
3. Keep the framework preset as **Next.js** and use the default build settings.
4. Add the environment variable `NEXT_PUBLIC_SITE_URL` with your real public website URL (for example, `https://www.yourdomain.in`). Do not leave the example domain in production.
5. Deploy. Add your custom domain in Vercel and update DNS as instructed by Vercel.

## Current features
- Responsive layout and frosted-glass visual treatment
- Thapleshwar Homestay emblem in the header, footer and favicon
- English/Hindi language toggle
- WhatsApp enquiry to +91 90840 64440
- Google Maps location and directions using 30.129512, 79.265243
- SEO metadata and LodgingBusiness structured data
- Dynamic `robots.txt` and `sitemap.xml` once `NEXT_PUBLIC_SITE_URL` is configured

## Booking and database
WhatsApp is the active booking method. Supabase is intentionally not connected yet; it can be added when online availability, reservation records, guest management or payment workflows are required.

## Business details
**Name:** Thapleshwar Homestay  
**Address:** Thapla, PO - Kheti, Uttarakhand 246440  
**Phone / WhatsApp:** +91 90840 64440  
**Additional mobile:** +91 9837959395  
**Coordinates:** 30.129512, 79.265243

## Before launch
- Set `NEXT_PUBLIC_SITE_URL` to the real domain.
- Confirm the Google Business Profile name, phone and address match the website.
- Verify the site in Google Search Console and submit `/sitemap.xml`.
- Test the site on mobile and desktop, including the WhatsApp and map links.
- Confirm the final Hindi wording and actual room/amenity details before publishing.
