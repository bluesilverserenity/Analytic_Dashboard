# Analytic_Dashboard

A responsive, static business dashboard built with HTML, CSS, JavaScript, and inline SVG charts. The interface includes an overview, analytics, reports, and account settings, with navigation that adapts to desktop and mobile screens.

## Features

- Business overview with sales, users, orders, and conversion metrics
- Weekly sales line chart and recent-orders table
- Analytics page with revenue metrics, sales bar chart, traffic sources, and top products
- Reports page with quick report cards and date-range controls
- Settings page with profile and account-management options
- Collapsible sidebar for smaller screens
- Responsive layouts for mobile, tablet, and desktop

## Pages

| Page      | File             | Description                                                 |
| --------- | ---------------- | ----------------------------------------------------------- |
| Home      | `home.html`      | Dashboard overview, weekly sales chart, and recent orders   |
| Analytics | `analytics.html` | Revenue analytics, traffic sources, and product performance |
| Reports   | `reports.html`   | Report shortcuts and report date-range form                 |
| Settings  | `settings.html`  | Profile details and account settings                        |

## Project Structure

```text
Analytic_Dashboard/
|-- home.html
|-- analytics.html
|-- reports.html
|-- settings.html
|-- script.js
|-- css/
|   |-- reusable.css
|   |-- home.css
|   |-- analytics.css
|   |-- reports.css
|   `-- settings.css
`-- assests/
    |-- codes/
    |   `-- resources.txt
    |-- icons/
    `-- images/
```

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript
- Inline SVG
- Google Fonts

No framework, package manager, database, or build tool is required.

## Getting Started

### Prerequisites

- A modern web browser
- An optional local web server

### Run locally

Clone the repository:

```bash
git clone https://github.com/bluesilverserenity/Analytic_Dashboard.git
cd Analytic_Dashboard
```

Open `home.html` directly in a browser, or start a local server:

```bash
python -m http.server 8000
```

Then visit <http://localhost:8000/home.html>.

## Usage

Use the sidebar to navigate between:

- Home
- Analytics
- Reports
- Settings

On smaller screens, use the hamburger button to open the sidebar and the close button to hide it.

## Demo Data and Behavior

This project is a frontend prototype. Sales figures, orders, traffic percentages, and profile information are static sample data embedded in the HTML. The search field, report actions, profile controls, and settings options do not currently connect to a backend or persist data.

## Assets

The `assests` folder contains the profile and report images used by the interface:

- `assests/images/nature.jpg`
- `assests/icons/`
- `assests/codes/resources.txt` contains the project font and color reference values

## Browser Support

The dashboard is designed for current versions of Chrome, Edge, Firefox, and Safari.

## Contributing

Contributions are welcome:

1. Fork the repository.
2. Create a feature branch.
3. Make and test your changes.
4. Open a pull request.

## License

No license has been specified for this project.
