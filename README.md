# Orbit website

Standalone static source for Orbit's homepage, Privacy Policy, Terms of Service, support documentation, and Google OAuth callback relay.

GitHub Pages publishes the repository root. The pages use relative links so the site works at both the default project URL and a future custom domain.

## Public routes

- `/` — product homepage
- `/privacy/` — Privacy Policy
- `/terms/` — Terms of Service
- `/support/` — support and troubleshooting
- `/auth/callback/` — Google OAuth callback relay

## Local preview

Run any static HTTP server from the repository root. For example:

```sh
npx serve .
```

Do not add provider credentials, OAuth client secrets, Stripe keys, environment files, or user data to this repository.
