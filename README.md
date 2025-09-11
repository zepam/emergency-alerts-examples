# Multilingual Emergency Alerts Examples

This repository provides a simple web-based demonstration of multilingual emergency alerts. It is designed to showcase how critical public safety messages can be presented in multiple languages for improved accessibility and community safety. This demo is an example of a possible implementation of the FCC's [Multilingual Wireless Emergency Alert Guidance](https://www.fcc.gov/sites/default/files/WEA-Multilingual-Fillable-Alert-Templates-Guidance-2025.pdf) released on July 18, 2025.

## Features

- **Interactive Web Page**: Select different types of emergency alerts (Flood, Extreme Wind, Fire, Boil Water Notice, 911 Outage) and view their messages in English and several other languages.
- **Languages Supported**: Includes translations for Spanish, Haitian Creole, Vietnamese, Arabic, Chinese (traditional), Chinese (simplified), Korean, Russian, Ukrainian, Tagalog, Hindi, and Korean.
- **Gold Standard Messages**: All alert messages are sourced from `evaluation_gold_standards.json`, which contains standardized templates for each alert type and language. These templates are from the FCC's [Wireless Emergency Alerts; Amendments to Part 11 of the Commission's Rules Regarding the Emergency Alert System](https://www.fcc.gov/document/fcc-adopts-implementation-requirements-multilingual-wea-template)

## Files

- `index.html`: Main web page for viewing and interacting with emergency alerts.
- `evaluation_gold_standards.json`: Contains the alert templates in multiple languages.
- `README.md`: Project documentation.
- `LICENSE`: License information.

## Usage

1. Open `index.html` in your browser.
2. Select an alert type from the dropdown menu.
3. View the English message and its translations side-by-side.

## Deployment

To deploy the site on GitHub Pages:

1. Push the repository to GitHub.
2. In your repository settings, enable GitHub Pages and set the source to the `main` branch.
3. Access your site at `https://<your-username>.github.io/emergency-alerts-examples/`.

## Contributing

Contributions for additional languages or improvements to the alert templates are welcome. Please submit a pull request or open an issue.

## License

See `LICENSE` for details.
