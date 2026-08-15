---
"@refinedev/antd": patch
"@refinedev/mantine": patch
---

Fix notification type rendering in the antd and mantine notification providers: antd now uses the `notification[type]()` shortcut methods so `success` and `error` notifications get their proper icon and color, and mantine maps each type to distinct color/icon props instead of collapsing every non-success type into red styling.