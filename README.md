# Central Cricket Academy Website

Static site: HTML5 + CSS3 + vanilla JavaScript.

## Structure
- index.html: page markup
- css/style.css: all styles
- js/script.js: business info (CFG block at top), content arrays, gallery, form validation
- images/: put your real photos here

## Edit business info
Open js/script.js and fill the CFG block (phone, whatsapp, email, hours, social links).
Add coaches, testimonials and gallery photos in the arrays below it.

## Supabase backend
1. Supabase Dashboard > SQL Editor: paste and run supabase-setup.sql (creates the admission_enquiries table, insert-only for visitors).
2. Enquiries appear in Table Editor > admission_enquiries.
3. Keys are in js/script.js (CFG.supabase). Only the publishable key belongs there, never the secret/service_role key.

## Deploy on Netlify
1. Go to app.netlify.com, Add new site, Deploy manually.
2. Drag and drop this folder (unzipped).
Or push this repo to GitHub and import it in Netlify (no build command, publish directory ".").
