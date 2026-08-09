---
"@refinedev/mui": patch
---

Fix `Breadcrumb` links losing MUI styling. `LinkRouter` now renders the MUI `Link` component (via `component` prop) instead of spreading `sx`, `color`, `variant`, and `underline` props onto a plain `<span>`, restoring the pre-v5-migration styling behavior.
