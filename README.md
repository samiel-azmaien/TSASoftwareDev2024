# MoodCasts — TSA Software Development Prototype

![Status](https://img.shields.io/badge/status-archived_prototype-6B7280?style=flat-square)
![Next.js](https://img.shields.io/badge/Next.js-13-black?style=flat-square&logo=nextdotjs&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-prototype-FFCA28?style=flat-square&logo=firebase&logoColor=111827)

MoodCasts is a TSA Software Development prototype exploring podcast recommendations and conversational wellness support through a Next.js progressive web app and Firebase-backed design.

> **Wellness disclaimer:** this prototype is not medical care, crisis support, or a substitute for a qualified professional. A production version would require clinical-safety review and clear crisis-routing behavior.

## Feature status

| Area | Status |
|---|---|
| Responsive Next.js/PWA shell | Implemented prototype |
| Firebase authentication UI | Implemented prototype |
| Chat and recommendation interfaces | Frontend calls present |
| Backend conversational functions | Stubbed/commented out |
| MindCasts and settings screens | Placeholder state |
| Automated tests and production deployment | Not included |

## Stack

- Next.js 13, React 18, and TypeScript
- Tailwind CSS and Material Tailwind
- Firebase authentication/hosting configuration
- Recoil state management
- Next-PWA
- Python function stubs and an OpenAPI draft

## Local development

```bash
cd frontend
pnpm install
pnpm dev
```

The checked-in Firebase client configuration is intended as public application configuration, not a server secret. Any real deployment still needs restrictive Firebase security rules, authorized domains, and appropriately restricted API keys.

## Attribution

This repository is a fork of [`abishekprabakar/TSASoftwareDev2024`](https://github.com/abishekprabakar/TSASoftwareDev2024). The visible commit history is attributed to the upstream collaborators; consult the upstream repository and team records for contribution details. This README does not claim sole authorship.

## Project status

The repository is preserved as an archived prototype. It should not be presented as a functioning mental-health application until the backend, safety model, tests, and deployment have been completed and reviewed.

## License

The package and API files contain conflicting license references, but no root license file is included. Verify the upstream licensing terms before reuse.
