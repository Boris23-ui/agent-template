# Project Agent Guide

This project is a [APP_TYPE] app with a [FRONTEND_STACK] frontend and [BACKEND_STACK] backend.

## Product goal
Describe the user-facing value in 2–4 sentences.

## Architecture
- Frontend: ...
- Backend: ...
- Database: ...
- External services: ...

## Critical rules
- Never expose secrets in client code
- Keep API keys server-side
- Validate inputs before writing to storage or DB
- Preserve architecture and existing conventions
- Prefer small, reviewable changes
- Run typecheck/tests before shipping

## Commands
```bash
npm install
npm run typecheck
npm run test
npm run build
```

## Workflow
1. Read the relevant files before changing code
2. Write or update tests for behavior changes
3. Keep the change small and bounded
4. Verify checks before shipping
5. Review for scope creep before finalizing
