# Web App Generation Guidelines (Strict Mode)

## Route & Page Rules
- All routes must be valid, resolvable, and part of the routing system
- No dummy buttons or unlinked pages allowed
- Each button or link must map to an existing route or handler

## Backend Logic
- Every action (click, form, navigation) must have backend logic or mocked logic
- Use real or mock APIs; no placeholders
- Avoid 404s at all costs — handle errors gracefully

## UX Standards
- Use realistic flows: authentication, dashboard, CRUD, payments
- Validate all inputs with error and success feedback
- Show fallback states: loading, empty, and error

## Code Structure
- File system routing must reflect the UI structure (e.g., Next.js App Router)
- Each route must render meaningful UI content and call logic

## Security & Realism
- Follow basic auth and API security patterns
- Avoid fictional features — only build what real apps would need
