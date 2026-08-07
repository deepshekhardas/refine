---
"@refinedev/core": minor
---

feat: convert `MetaQuery` and `GraphQLQueryOptions` to interfaces to support TypeScript declaration merging. Consumers can now augment `MetaQuery` via `declare module "@refinedev/core"` to get typed `meta` properties across all data hooks.
