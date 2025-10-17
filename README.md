# SubtractApp 💳

A simple, client-side web app to detect potential recurring subscriptions from your bank statements (CSV or PDF exports). It analyzes transactions locally in your browser, identifies monthly-ish charges, and provides cancellation guides for common services. No data is stored or sent anywhere – 100% private.

Built to help you review and manage subscriptions easily. Note: This is not financial advice; always verify charges manually.

## 🚀 Live Demo

[Try SubtractApp Now](https://govosmc.github.io/subtractapp)

## 💰 Features

- Upload bank statements (CSV or PDF) for instant, client-side analysis
- Detects potential recurring charges based on transaction patterns
- Calculates estimated monthly totals and potential savings
- Generates downloadable audit reports
- Provides cancellation links/guides for popular services (e.g., Netflix, Spotify)
- Bank-level security: All processing happens in your browser, nothing stored
- Optional premium tiers for advanced support (via Stripe)

## 📊 How It Works

1. Upload your bank export.
2. The app parses transactions and groups similar debits occurring roughly monthly.
3. Review the list of potential subscriptions.
4. Get guides to cancel unwanted ones.
5. Download a report for your records.

Limitations: PDF parsing may vary by bank format; CSV is recommended for accuracy. No automatic cancellations – this is a detection tool.

## 🛠 Tech Stack

- Pure HTML/CSS/JavaScript
- No dependencies (uses CDNs for PapaParse and pdf.js)
- 100% client-side processing

## Getting Started

### Deployment
1. Fork this repository.
2. Enable GitHub Pages in settings (source: main branch, root folder).
3. Access at `https://your-username.github.io/subtractapp`.

### Local Development
1. Clone the repo: `git clone https://github.com/miltonnitsche/subtractapp.git`
2. Open `index.html` in your browser.

No build steps needed – it's static!

## Usage

- Drag/drop or select a CSV/PDF bank statement.
- View detected subscriptions and totals.
- Click "Cancel Guide" for links to service cancellation pages.
- Download the report as HTML.

For premium features (e.g., monitoring), sign up via the app and set up Stripe payment links in the code.

## Contributing

Contributions welcome! Please:
- Open an issue for bugs or feature requests.
- Submit PRs for improvements (e.g., more common subscription mappings).
- Follow standard code style.

## License

MIT License – see [LICENSE](LICENSE) for details.

## 📧 Contact

Questions? Email: hello@subtractapp.com

Built with ❤️ to help people save money.
