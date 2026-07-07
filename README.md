# llitc-aacnwa-web
The shortcut web site for the Allergy &amp; Asthma Clinic of Northwest Arkansas

# Structure:
  - hugo.toml — site config with clinic info, phone, address, menu anchor links
  - themes/aacnwa/ — custom Hugo theme
  - assets/css/input.css — Tailwind v4 source with @theme custom colors and @source directives
  - static/css/styles.css — compiled Tailwind output (25 KB)

# Page sections (matching the reference site):
  1. Top utility bar — phone number + Patient Portal + Pay Your Bill
  2. Sticky header — logo with heart icon, clinic name, full navigation, "Make Appointment" CTA
  3. Hero — navy blue gradient, tagline, two CTAs (appointment + phone call)
  4. Awards row — "Best of NWA" badges for 2019–2025
  5. Services cards — Allergy Testing, Patient Education, Health Resources
  6. Providers — Dr. Tina Merritt + Heather Sams PA-C with avatar placeholders
  7. Conditions treated — 8-item grid with checkmarks
  8. Testimonials — 3 patient quotes on dark blue background
  9. Contact section — address/phone on left, appointment request form on right
  10. Footer — 3-column: brand, contact, quick links

  Color palette: Navy #1a4f7a, Teal #17a589, Gold #e8b84b

  To develop locally, run both:
  # Terminal 1 — watch Tailwind
  tailwindcss -i assets/css/input.css -o static/css/styles.css --watch

  # Terminal 2 — Hugo dev server
  hugo server
