---
name: composition-patterns
description: React composition patterns that scale. Use when designing reusable components, refactoring components with too many boolean props, building component libraries, or when user mentions "too many props", "boolean props", "how do I make this reusable".
---

# React Composition Patterns

Avoid boolean prop proliferation with compound components, state lifting, slot pattern, asChild.

## Patterns
1. Compound Components - parent + named sub-components sharing context
2. Lift State - consumer controls state, not the component
3. Slot Pattern - children replace internal parts
4. Render Props - share logic without dictating structure
5. asChild (Radix Slot) - change underlying element keeping styles