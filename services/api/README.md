# ClimateOS API Service (Stub)

Goals for the first milestone:

1. Expose `GET /health` for uptime checks
2. Expose `POST /scenarios` to accept climate intervention payloads and echo them back for now
3. Wire basic OpenAPI schema + contract tests
4. Prepare slots for auth (API key or OIDC) once consumers are ready

Implementation can start with FastAPI/Express/Cloudflare Workers—whatever best fits the pilot deployment. For now this folder only documents the intent.
