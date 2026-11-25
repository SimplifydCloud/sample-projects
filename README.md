# Build something interesting on Simplifyd Cloud

Working demo apps you can fork, deploy, and make your own. Each app is an independent public GitHub template with realistic demo content, setup instructions, deployment settings, a license, and automated checks.

| Sample | Stack | Try it | Deploy |
| --- | --- | --- | --- |
| [Launchpad](https://github.com/SimplifydCloud/sample-react-launchpad) | React + Vite | Plan a launch, move tasks, watch progress, export your board | [![Deploy to Simplifyd Cloud](https://simplifyd.com/deploy-button.svg)](https://console.cloud.simplifyd.com/deploy?repo=https%3A%2F%2Fgithub.com%2FSimplifydCloud%2Fsample-react-launchpad) |
| [Atlas](https://github.com/SimplifydCloud/sample-nextjs-atlas) | Next.js App Router | Explore six African cities, save a shortlist, build a day plan | [![Deploy to Simplifyd Cloud](https://simplifyd.com/deploy-button.svg)](https://console.cloud.simplifyd.com/deploy?repo=https%3A%2F%2Fgithub.com%2FSimplifydCloud%2Fsample-nextjs-atlas) |
| [Signal](https://github.com/SimplifydCloud/sample-laravel-signal) | Laravel 13 + Blade + PostgreSQL | Submit ideas, vote, search, and explore a roadmap | [![Deploy to Simplifyd Cloud](https://simplifyd.com/deploy-button.svg)](https://console.cloud.simplifyd.com/deploy?repo=https%3A%2F%2Fgithub.com%2FSimplifydCloud%2Fsample-laravel-signal) |

## Start here

1. Click a **Deploy to Simplifyd Cloud** button to open that app’s stack, choose a workspace and project, and review the services.
2. Confirm, then deploy the services from the canvas (Signal’s database before its web service). The buttons use public container images and incur normal Simplifyd usage charges.
3. To customise an app, open its repository and choose **Use this template → Create a new repository**, then follow its README.

React and Next.js need no API keys or backend. Their saved state stays in your browser. Signal uses SQLite locally and managed PostgreSQL for a persistent cloud deployment. Its Docker Compose option lets you try it without installing PHP.

The deploy buttons use prebuilt container images and need no GitHub build setup. For source-based deployment, managed GitHub builds need to be enabled on your Simplifyd installation. React and Next.js also support static-site deployment from GitHub or a built zip; every app includes a Dockerfile.

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
