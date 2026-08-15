---
"@refinedev/mui": patch
---

Fix Breadcrumb links to render their inner element with MUI's Link component, so styling props like `sx`, `underline`, `color` and `variant` are applied instead of being spread onto a plain `<span>` as inert attributes.