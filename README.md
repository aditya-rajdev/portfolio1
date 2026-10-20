# GRT Technology — Premium Light Glassmorphism Website

Responsive React + TypeScript + Vite website with Tailwind CSS and Lucide icons. The interface is intentionally light, with frosted white glass surfaces, blue/lavender gradients, responsive navigation, portfolio filtering, a rotating placeholder testimonial, reveal motion and an inquiry form.

## Requirements
- Node.js 20+ recommended
- npm

## Run locally
```bash
npm install
cp .env.example .env.local
npm run dev
```
Open the local URL printed by Vite.

## Production build
```bash
npm run build
npm run preview
```

## Configure contact details before publishing
1. Copy `.env.example` to `.env.local`.
2. Set `VITE_CONTACT_EMAIL` to the real business email.
3. Set `VITE_WHATSAPP_NUMBER` to the real number with country code and digits only, e.g. `919876543210`.
4. For direct online form submissions, create a form with a provider such as Formspree and set `VITE_FORMSPREE_ENDPOINT` to its endpoint. Without an endpoint, the form validates and prepares an email using the visitor's mail app; it does not silently claim to send a message to a server.
5. Replace social links, privacy/terms destinations and all placeholder contact information with verified company details.
6. Replace the concept portfolio images and testimonial placeholders with approved real work/reviews. Project examples are explicitly marked as concepts.

## Notes
- Portfolio filters are functional.
- Mobile menu, smooth anchor navigation, testimonial controls, form validation/loading/error states, mailto fallback and WhatsApp configuration prompt are included.
- Unsplash images are remote demo assets; replace or self-host for production control and performance.
- Stats are capability indicators/placeholders, not claims of company achievements.
- Privacy and terms links currently show a setup reminder. Publish real legal pages before going live.
