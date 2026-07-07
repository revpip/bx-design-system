# Typography Tokens

## Philosophy

Typography should feel confident, editorial and easy to read. Business owners should be able to scan quickly and understand what matters.

## Primary Font

Use a modern system stack initially:

```css
Inter, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif
```

## Scale

| Token | Size | Usage |
|---|---:|---|
| `small` | `0.875rem` | Meta, labels, helper text |
| `base` | `1rem` | Body text |
| `large` | `1.25rem` | Lead paragraphs |
| `xl` | `2rem` | Section headings |
| `hero` | `clamp(3rem, 8vw, 6.8rem)` | Homepage hero |

## Rules

- Keep paragraphs short.
- Avoid dense blocks of text in dashboards.
- Use large headings to create confidence.
- Use sentence case, not shouty title case everywhere.
- Numbers should be prominent and easy to compare.
