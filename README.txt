BOOK BANK FAST DIGITAL CARD

Files:
- index.html
- book-bank-logo.jpg (optimized logo)

GitHub + Cloudflare Pages:
1. Create a GitHub repository named book-bank-card.
2. Upload BOTH files to the repository root.
3. Cloudflare Dashboard > Workers & Pages > Create application > Pages > Connect to Git.
4. Authorize GitHub and select the repository.
5. Production branch: main.
6. Framework preset: None / No framework.
7. Build command: leave blank if allowed (or use `exit 0` if required).
8. Build output directory: repository root (often shown as /).
9. Deploy and use the resulting pages.dev URL for the QR code.

Important:
- Keep the pages.dev URL stable after printing the QR.
- Google Maps and Reviews buttons currently use the same link supplied by the owner. Replace the Reviews button href when a direct review link is available.
- Shop hours are shown as 10:00 AM–8:30 PM; confirm before printing.
- No external JavaScript, CSS framework, or web fonts are used, to keep the page lightweight.
