---
name: react-best-practices
description: React and Next.js performance optimization guidelines from Vercel Engineering. Use this skill whenever the user is writing, reviewing, or refactoring React or Next.js code — including components, pages, data fetching, bundle size, re-renders, or performance improvements.
---

# Vercel React Best Practices

70 rules across 8 categories: waterfalls, bundle size, server performance, re-renders, rendering, JS performance, advanced patterns.

## Categories
1. Eliminating Waterfalls (CRITICAL) - async-parallel, async-suspense-boundaries
2. Bundle Size (CRITICAL) - bundle-barrel-imports, bundle-dynamic-imports
3. Server Performance (HIGH) - server-cache-react, server-parallel-fetching
4. Client Data (MEDIUM-HIGH) - client-swr-dedup
5. Re-renders (MEDIUM) - rerender-memo, rerender-dependencies
6. Rendering (MEDIUM) - rendering-content-visibility, rendering-conditional-render
7. JS Performance (LOW-MEDIUM) - js-index-maps, js-early-exit
8. Advanced (LOW) - advanced-use-latest