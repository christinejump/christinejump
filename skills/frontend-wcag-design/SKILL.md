---
name: frontend-design
description: Create distinctive, production-grade frontend interfaces with high design quality. Use this skill when the user asks to build web components, pages, artifacts, posters, or applications (examples include websites, landing pages, dashboards, React components, HTML/CSS layouts, or when styling/beautifying any web UI). Generates creative, polished code and UI design that avoids generic AI aesthetics.
license: Complete terms in LICENSE.txt
---

This skill guides creation of distinctive, production-grade frontend interfaces that avoid generic "AI slop" aesthetics. Implement real working code with exceptional attention to aesthetic details and creative choices.

The user provides frontend requirements: a component, page, application, or interface to build. They may include context about the purpose, audience, or technical constraints.

## Design Thinking

Before coding, understand the context and commit to a BOLD aesthetic direction:
- **Purpose**: What problem does this interface solve? Who uses it?
- **Tone**: Pick an extreme: brutally minimal, maximalist chaos, retro-futuristic, organic/natural, luxury/refined, playful/toy-like, editorial/magazine, brutalist/raw, art deco/geometric, soft/pastel, industrial/utilitarian, etc. There are so many flavors to choose from. Use these for inspiration but design one that is true to the aesthetic direction.
- **Constraints**: Technical requirements (framework, performance, accessibility).
- **Differentiation**: What makes this UNFORGETTABLE? What's the one thing someone will remember?

**CRITICAL**: Choose a clear conceptual direction and execute it with precision. Bold maximalism and refined minimalism both work - the key is intentionality, not intensity.

Then implement working code (HTML/CSS/JS, React, Vue, etc.) that is:
- Production-grade and functional
- Visually striking and memorable
- Cohesive with a clear aesthetic point-of-view
- Meticulously refined in every detail

## Frontend Aesthetics Guidelines

Focus on:
- **Typography**: Choose fonts that are beautiful, unique, and interesting. Avoid generic fonts like Arial and Inter; opt instead for distinctive choices that elevate the frontend's aesthetics; unexpected, characterful font choices. Pair a distinctive display font with a refined body font.
- **Color & Theme**: Commit to a cohesive aesthetic. Use CSS variables for consistency. Dominant colors with sharp accents outperform timid, evenly-distributed palettes.
- **Motion**: Use animations for effects and micro-interactions. Prioritize CSS-only solutions for HTML. Use Motion library for React when available. Focus on high-impact moments: one well-orchestrated page load with staggered reveals (animation-delay) creates more delight than scattered micro-interactions. Use scroll-triggering and hover states that surprise.
- **Spatial Composition**: Unexpected layouts. Asymmetry. Overlap. Diagonal flow. Grid-breaking elements. Generous negative space OR controlled density.
- **Backgrounds & Visual Details**: Create atmosphere and depth rather than defaulting to solid colors. Add contextual effects and textures that match the overall aesthetic. Apply creative forms like gradient meshes, noise textures, geometric patterns, layered transparencies, dramatic shadows, decorative borders, custom cursors, and grain overlays.

NEVER use generic AI-generated aesthetics like overused font families (Inter, Roboto, Arial, system fonts), cliched color schemes (particularly purple gradients on white backgrounds), predictable layouts and component patterns, and cookie-cutter design that lacks context-specific character.

Interpret creatively and make unexpected choices that feel genuinely designed for the context. No design should be the same. Vary between light and dark themes, different fonts, different aesthetics. NEVER converge on common choices (Space Grotesk, for example) across generations.

**IMPORTANT**: Match implementation complexity to the aesthetic vision. Maximalist designs need elaborate code with extensive animations and effects. Minimalist or refined designs need restraint, precision, and careful attention to spacing, typography, and subtle details. Elegance comes from executing the vision well.
## Accessibility (Required — WCAG 2.2 Level AA)

Every interface built with this skill MUST conform to WCAG 2.2 Level AA. Accessibility is not optional and is never sacrificed for aesthetics. Bold design and full accessibility are fully compatible.

**The four principles (POUR):**
- **Perceivable** — all content and UI can be perceived by all users
- **Operable** — all functionality is keyboard-accessible and navigable
- **Understandable** — content and operation are clear and predictable
- **Robust** — works with current and future assistive technologies

**Non-negotiable requirements (Level AA):**

| Requirement | Rule |
|-------------|------|
| Color contrast — body text | Minimum 4.5:1 ratio |
| Color contrast — large text (18pt+ or 14pt bold) | Minimum 3:1 ratio |
| Color contrast — UI components and focus indicators | Minimum 3:1 ratio |
| Keyboard navigation | All interactive elements reachable and operable by keyboard |
| Focus visible | Keyboard focus indicator always visible (never `outline: none` without a styled replacement) |
| Focus order | Logical, meaningful tab order that preserves content meaning |
| Images | All `<img>` elements have descriptive `alt` text; decorative images use `alt=""` |
| Semantic HTML | Use correct elements (`<button>`, `<nav>`, `<main>`, `<header>`, headings hierarchy, etc.) |
| ARIA | Only use ARIA when semantic HTML is insufficient; never use ARIA to override incorrect semantics |
| Form labels | Every input has an associated `<label>` or `aria-label` |
| Error identification | Errors are described in text, not color alone |
| Resize text | Content remains functional at 200% zoom without horizontal scrolling |
| Motion | Respect `prefers-reduced-motion` — provide reduced/no-motion alternatives for animations |
| Color not sole indicator | Never use color as the only means of conveying information |
| Touch targets | Minimum 24×24px (AA); aim for 44×44px (AAA best practice) |
| Language | `<html lang="...">` set correctly |

**In practice:**
- Test color choices with a contrast checker before finalizing palettes
- Custom fonts must remain legible — test at 16px minimum body size
- Animation micro-interactions must have a `@media (prefers-reduced-motion: reduce)` override
- CSS-only visual effects that remove focus outlines MUST replace them with a visible styled equivalent

Full specification: https://www.w3.org/TR/WCAG22/


Remember: Claude is capable of extraordinary creative work. Don't hold back, show what can truly be created when thinking outside the box and committing fully to a distinctive vision.
