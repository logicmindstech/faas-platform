# Funnel-as-a-Service (FaaS) Infrastructure Engine

A premium, high-conversion marketing funnel system built entirely with native web technologies. This project is structured as an architectural blueprint to replace complex tool stacks with serverless speed, clean data capture pipelines, and custom pitch-black presentation layers.

## 🚀 Features

- **Pure Architecture Performance:** 100% dependency-free. Built using raw HTML5, native Javascript (ES6), and vanilla CSS.
- **Unified 600px Responsive Layout:** Strict structural width guidelines to ensure zero design or text misalignment.
- **Formspree Background Sync Engine:** AJAX integrations that securely pass buyer data (leads, mobile numbers, and bank verification hashes) silently to your backend processors without forcing external redirect validation screens.
- **Google Sheets Database Workflow:** Automated row compilation mapped cleanly for frictionless lead management and auditing.
- **Pure Pitch Black Aesthetic:** Centered layouts, white text readability contrast, and distinct vibrant portfolio orange accents (`#FF5A00`).

---

## 📂 File Architecture

The system relies on five cohesive files saved side-by-side in the project root directory:

```text
├── index.html            # Core Landing Page (Lead Capture Framework)
├── thankyou.html         # Premium Offer Page (Upsell Engine)
├── checkout.html         # Secure Infrastructure License Checkout (Order Form)
├── payment-details.html  # Bank Transfer Coordination & Transaction Submission Desk
├── customer-care.html    # Success Desk Confirmation & Support Mail Router
└── style.css             # Universal Centralized Stylesheet Layout Core
```

---

## 🛠️ Testing Locally & Offline Flow

Because this project runs without external design compilation environments or server dependencies, you can inspect click paths completely offline:

1. Clone or extract this bundle to your local environment.
2. Double-click `index.html` to run it directly inside any desktop or mobile browser.
3. Submit a test email to advance through the pages. 

*Note: Native JavaScript `.catch()` state engines are active inside the controllers. If you are offline, form lookup processes will fail silently and automatically push your browser down the conversion line to let you audit layout states smoothly.*

---

## 🔌 Connection Setup (Formspree Activation)

To route form inputs straight to your personal email or Google Sheets tracking systems, configure your unique Formspree keys inside the form wrappers:

1. Log into your **Formspree Dashboard** and create a new project endpoint handler.
2. Locate the `action="..."` parameters inside these three specific files:
   - **`index.html`:** Form wrapper block collects incoming subscriber logs.
   - **`checkout.html`:** Form collects Name and Mobile parameters.
   - **`payment-details.html`:** Textarea collects manual bank receipt confirmation hashes.
3. Replace the placeholder values (`YOUR_FORMSPREE_ID_HERE`) with your active target Formspree endpoint identification token code.

---

## 🌐 Free Production Deployment (GitHub Pages)

To launch this architecture live to public traffic:

1. Push your folder repository contents straight onto your GitHub profile:
   ```bash
   git add .
   git commit -m "Deploy FaaS Architecture Bundle"
   git push origin main
   ```
2. Open your GitHub Repository dashboard, navigate to **Settings** ──> **Pages**.
3. Set your Source option parameters to **Deploy from a branch**.
4. Set your deployment branch pointer mapping coordinate from `None` directly onto **`main`**, then hit **Save**.
5. Your public production live link layout URL will be successfully dispatched in under 60 seconds!
