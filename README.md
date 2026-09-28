# sportsync-co.github.io

The public Astro marketing site for **Sportsync** at `sportsync.co`.

Sportsync is building a sports network and operations platform for athletes, teams, leagues, coaches, referees, scouts, recruiters, analysts and performance staff. The public site explains the product direction: social feed/discovery, verified sports identity and attestations, regional boards, recruiting, groups, team/league management, scheduling/assignments, internationalization and reputation.

## Authority boundary

This repository is public marketing content, not the machine-contract or private product-policy authority.

- shared machine contracts: `sportsync-co/ssc-interfaces`
- private product/architecture/operations/legal docs: `sportsync-co/sportsync-docs`
- deterministic external developer/API/MCP docs: `sportsync-co/ssc-docs`
- implementation: individual `ssc-*` repositories

Public claims should remain traceable to those sources and should distinguish planned/in-development capabilities from production-shipped behavior.

## Development

Use Node.js 22.22.1 or newer.

```sh
npm ci
npm run dev
npm run build
```

Astro writes the production site to `dist/`. The committed GitHub Actions workflow builds pull requests and deploys the default branch to GitHub Pages.

## Public routing

The apex domain is `sportsync.co`. Product navigation follows the organization infrastructure contract:

- `auth.sportsync.co`
- `user.sportsync.co`
- `org.sportsync.co`
- `api.sportsync.co`
- `admin.sportsync.co`
- `api-admin.sportsync.co`

## Content standard

Do not publish credentials, customer data, private operational details, attestation evidence, personal data, or unreviewed legal language from this public repository.
