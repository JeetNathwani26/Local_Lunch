# Local Lunch AI Development Skill

## Mission

Build and maintain the Local Lunch brand website consistently with the approved specifications.

## Required Workflow

Before implementing a feature:

1. Read `docs/00-project-overview.md`.
2. Read the relevant specification files.
3. Confirm the change fits the existing architecture.
4. Implement only the requested scope.
5. Test the change.
6. Update documentation when a design or architecture decision changes.

## Technology Rules

- Use React with TypeScript.
- Use Vite for the application build.
- Use Tailwind CSS for styling.
- Prefer native browser APIs and existing utilities over unnecessary dependencies.

## Component Rules

- Keep components small and focused.
- Give every component one primary responsibility.
- Extract reusable UI instead of duplicating markup.
- Keep content/data separate from presentation where practical.
- Prefer composition over deeply nested conditional logic.

## Function Rules

- Each function must have one clear responsibility.
- Use descriptive names.
- Type parameters and return values.
- Keep side effects explicit.
- Add one concise comment when creating a new function explaining its purpose.
- Do not create helper functions that are used only to hide simple expressions.
- Reuse existing functions before creating a duplicate.

## Styling Rules

- Follow the documented design system.
- Prefer Tailwind utility classes.
- Keep spacing and typography consistent.
- Avoid arbitrary values unless they represent a documented design requirement.
- Maintain visible hover, focus and active states where appropriate.

## Responsive Rules

Implement mobile-first behavior.

Required target ranges:

- Mobile: 320px–767px
- Tablet: 768px–1023px
- Desktop: 1024px+

Layouts must not depend on a single viewport width.

## Accessibility Rules

- Use semantic HTML.
- Provide meaningful alt text for informative images.
- Ensure interactive elements are keyboard accessible.
- Use visible focus states.
- Use labels for form controls.
- Respect prefers-reduced-motion.
- Do not use animation as the only way to communicate state.

## Performance Rules

- Optimize image dimensions and formats.
- Lazy-load non-critical imagery.
- Avoid unnecessary client-side JavaScript.
- Avoid unnecessary re-renders.
- Keep the initial page lightweight.

## SEO Rules

Each page should define:

- Title
- Meta description
- Canonical URL strategy
- Semantic heading structure
- Open Graph metadata where required

## AI Implementation Rules

AI-generated code is accepted only after checking it against the specifications. Do not invent new pages, components, dependencies or interactions without documenting the requirement first.
