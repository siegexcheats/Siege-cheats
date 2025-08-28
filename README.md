Siege Training Shop - README

This template is for selling **legal digital training materials** and playful viewer items (in-jokes). It intentionally does NOT include or promote cheats or hacks.

PayPal integration (demo):
- The bundle includes `checkout.js` which loads the PayPal SDK with a placeholder `YOUR_CLIENT_ID_HERE`.
- To enable real checkout:
  1. Create a PayPal Business account at https://www.paypal.com/business
  2. Go to developer.paypal.com -> My Apps & Credentials -> Create App -> get the Live Client ID
  3. Replace 'YOUR_CLIENT_ID_HERE' in `checkout.js` with your Client ID.
  4. Optionally change currency or prices in `checkout.js` (currently CAD).
- Test in sandbox by using `client-id=sb` for the SDK URL (PayPal sandbox).

Customization:
- Edit `index.html` product titles, descriptions, prices, and images in `/assets`.
- Deploy on GitHub Pages, Netlify, or Vercel.

Legal note:
- Do NOT sell or distribute cheating software, account-stealing tools, or anything that violates game terms of service.
