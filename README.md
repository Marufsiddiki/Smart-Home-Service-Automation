<div align="center">

# SERVO

### Smart home services, matched to the right people.

Book trusted home services, compare recommended providers, and follow each request from booking to completion.

**[Explore the app](https://ai.studio/apps/42913c7f-dd24-4429-b425-f3992d65af1f)** | **Built with React, TypeScript, and Vite**

</div>

---

## About

SERVO is a service-booking experience for customers, technicians, and dispatch administrators. It brings service discovery, request booking, provider recommendations, and job coordination into one responsive app. The sample experience is centered on Dhaka and includes demo data so you can explore the different roles right away.

## Highlights

- **Three role-based experiences** for customers, service providers, and administrators, including quick demo sign-in.
- **Service discovery and booking** with categories, descriptions, preferred dates and times, urgency, and location.
- **Guided request analysis** that suggests a service category, urgency, risks, and next steps from the issue description.
- **Provider recommendations** ranked by service fit, availability, distance, rating, price, and workload.
- **Job coordination tools** for request tracking, notifications, in-app chat, and provider navigation.
- **Service completion flows** with payment and receipt screens, work-proof upload, and digital warranty views.
- **Persistent demo session and accounts** stored in the browser with `localStorage`.

> **Prototype notice:** This repository is a front-end demo. Its sample providers, bookings, matching data, and role accounts are not backed by a production database or dispatch service. Payment, map, chat, and related screens demonstrate app flows; connect real services and add server-side authentication before using this with real customers.

## Get started

### Prerequisites

- Node.js 20 or newer
- npm

### Run locally

```bash
git clone https://github.com/Marufsiddiki/Smart-Home-Service-Automation.git
cd Smart-Home-Service-Automation
npm install
npm run dev
```

Open the local URL printed by Vite (by default, `http://localhost:3000`).

### Available scripts

| Command | Description |
| --- | --- |
| `npm run dev` | Start the Vite development server. |
| `npm run build` | Bundle the app for production. |
| `npm run preview` | Preview the production build locally. |
| `npm run lint` | Run the TypeScript compiler without emitting files. |

## Try the demo

Use **Quick Login** on the sign-in screen to enter as a customer, provider, or administrator. The seeded demo accounts are also available:

| Role | Email | Password |
| --- | --- | --- |
| Customer | `fahimalom013@gmail.com` | `customer123` |
| Provider | `rahim.electronics@smartfix.bd` | `provider123` |
| Administrator | `admin@servo.bd` | `admin123` |

These credentials are for the local prototype only. Do not reuse them in a deployed environment.

## Technology

- React 19 and TypeScript
- Vite 6
- Tailwind CSS 4
- Lucide icons and Motion

## Project structure

```text
src/
|-- components/   Role views, booking flows, and interface modals
|-- data/         Demo accounts, providers, requests, and service data
|-- services/     Request analysis and provider matching
|-- types/        Shared TypeScript models
`-- utils/        Shared helpers
public/           Static assets
```

## Configuration

The app's demo flows do not require external credentials. `.env.example` is provided as a template for AI Studio-related `GEMINI_API_KEY` and `APP_URL` settings; do not commit real credentials. Copy it to `.env.local` only if your own integration requires those values.

## Contributing

Contributions and suggestions are welcome. For a change, create a branch, make and test the update, then open a pull request with a concise description of the behavior changed.

## License

No license has been specified for this repository yet.
