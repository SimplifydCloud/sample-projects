# Build something interesting on Simplifyd Cloud

Working demo apps you can fork, deploy, and make your own. Each app is an independent public GitHub template with realistic demo content, setup instructions, deployment settings, a license, and automated checks.

| Sample | Stack | Try it | Simplifyd deployment |
| --- | --- | --- | --- |
| [Launchpad](https://github.com/SimplifydCloud/sample-react-launchpad) | React + Vite | Plan a launch, move tasks, watch progress, export your board | Static site · `dist` |
| [Atlas](https://github.com/SimplifydCloud/sample-nextjs-atlas) | Next.js App Router | Explore six African cities, save a shortlist, build a day plan | Static site · `out` |
| [Signal](https://github.com/SimplifydCloud/sample-laravel-signal) | Laravel 13 + Blade + PostgreSQL | Submit ideas, vote, search, and explore a roadmap | Laravel app · PHP 8.4 · port 8080 |

## Start here

1. Open a sample and click **Use this template → Create a new repository**.
2. Follow its README to run locally or connect your repository to Simplifyd Cloud.
3. Try the main interaction, change something, and deploy again.

React and Next.js need no API keys or backend. Their saved state stays in your browser. Signal uses SQLite locally and managed PostgreSQL for a persistent cloud deployment. Its Docker Compose option lets you try it without installing PHP.

Managed GitHub builds need to be enabled on your Simplifyd installation. Every frontend can also be uploaded as a built zip, and every app includes a Dockerfile.

## Launchpad · Give your next launch a home

[![Launchpad](https://raw.githubusercontent.com/SimplifydCloud/sample-react-launchpad/main/docs/preview.png)](https://github.com/SimplifydCloud/sample-react-launchpad)

An interactive task board with three stages, team filters, search, live launch readiness, JSON export, and browser persistence. Start here to test a React static site.

## Atlas · A weekend somewhere new

[![Atlas](https://raw.githubusercontent.com/SimplifydCloud/sample-nextjs-atlas/main/docs/preview.png)](https://github.com/SimplifydCloud/sample-nextjs-atlas)

An editorial explorer with original SVG city artwork, static city routes, saved shortlists, and downloadable itineraries. Shows Next.js server and client components in a static export. Activities and budgets are fictional demo content.

## Signal · Good ideas grow together

[![Signal](https://raw.githubusercontent.com/SimplifydCloud/sample-laravel-signal/main/docs/preview.png)](https://github.com/SimplifydCloud/sample-laravel-signal)

A database-backed community feedback board with validation, anonymous voting, roadmap filters, and deployment readiness checks. Start here to test Laravel, migrations, and managed PostgreSQL.

## Included in every app

- Responsive design and useful starting content.
- Reproducible dependency lockfiles.
- Local setup and exact Simplifyd deployment settings.
- CI, Dependabot updates, and an MIT license.
- Source files you can understand and customise.

These are learning and deployment samples. Read each app's documented persistence and anonymous-user behaviour before extending it into your product.
