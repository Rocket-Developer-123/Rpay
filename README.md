# RPAY

RPAY is a mobile-optimized virtual UPI and fintech payment sandbox powered by its native simulated digital asset, **Kinex (K)**. It provides a realistic payment experience for peer-to-peer transfers, merchant checkouts, QR payments, and instant settlements—without using real money, bank accounts, cards, or financial services.

## Live application

[Launch RPAY](https://virtual-upi.onrender.com/)

## Highlights

- **100% risk-free simulation:** Kinex has no monetary value and cannot be deposited, withdrawn, bought, sold, or exchanged.
- **Instant settlements:** Simulated peer-to-peer transfers are reflected immediately in the recipient's balance.
- **Dynamic QR payments:** Generate amount-locked UPI-style payment links and QR codes for merchant checkout flows.
- **Global directory:** Find users by their RPAY handle or name without synchronizing contacts.
- **PIN authorization:** Confirm payments with a four-digit PIN through the payment interface.
- **Security simulation:** Demonstrates fraud monitoring and operator-level account freeze workflows.
- **Browser-based experience:** Runs in a modern browser and is designed for mobile screens, with light and dark themes.
- **Sign-up bonus:** New handles receive a simulated K 10,000 starting balance.

## How it works

1. **Register a handle** — Create a `name@rpay` identity and receive the simulated K 10,000 bonus.
2. **Connect or scan** — Search the directory for a recipient or scan a dynamic merchant QR code.
3. **Authorize and pay** — Enter the four-digit PIN and see the Kinex balance settle instantly.

## Project structure

This repository contains the RPAY landing page and interactive product preview:

- `index.html` — Complete responsive landing page, styling, inline SVG assets, interactive phone preview, feature sections, FAQ, and footer.
- `1789966012698.png` — Optional Kinex coin artwork used by the page when available.
- `1789965264550.png` — Optional ecosystem artwork used by the page when available.

## Run locally

RPAY is a static HTML site and does not require a build step or package installation.

```bash
# Clone the repository
git clone https://github.com/Rocket-Developer-123/Rpay.git
cd Rpay

# Serve the site locally (Python 3)
python3 -m http.server 8000
```

Then open <http://localhost:8000> in your browser. Opening `index.html` directly also works for the static landing page, although a local server is recommended for consistent browser behavior.

## Technology

- Semantic HTML
- CSS with responsive layouts, animations, themes, and reduced-motion support
- Vanilla JavaScript
- Inline SVG icons and decorative graphics
- Google Fonts: Sora and Figtree

## Sandbox notice

RPAY and Kinex (K) are intended for learning, demonstration, and testing. They do not represent real money or a real payment network. Do not use the project for real financial transactions or submit sensitive financial information.

## License

No license is currently specified for this repository. Contact the repository owner before redistributing or using the project outside the repository.
