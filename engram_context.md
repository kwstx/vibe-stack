# Engram Context: Vibe Stack

This file serves as a persistent memory bank for this project.
When using Engram with Cursor, this file acts as the "Source of Truth" for established patterns.

## Project Rules
1.  **Strict Styling**: Always use `cn()` from `@/lib/utils` for merging Tailwind classes.
2.  **Icons**: Use `lucide-react` for all icons.
3.  **Components**: Keep components small and atomic in `@/components`.
4.  **No Hallucinations**: Do not invent Tailwind classes (e.g., `text-brand-blue`). Use the CSS variables defined in `globals.css` (primary, secondary, etc).

## Known Regressions (Do Not Repeat)
- The "Hydration Error" caused by using `window` in Server Components. Always check `typeof window !== 'undefined'` or use `useEffect`.
- Do not make the "Gradient Text" selectable, it causes layout shifts on mobile.
