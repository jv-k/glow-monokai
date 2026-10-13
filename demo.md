# Monokai for Glow

## A theme for the whole document

> Headings, links, quotes, lists, and code use the same colours as Mojokai for micro.

- Pink list markers keep long notes easy to scan.
- [Links](https://github.com/charmbracelet/glow) pair yellow targets with green text.
- `Inline code` uses the same yellow as strings.

| Element | Colour |
| --- | --- |
| Heading | Pink |
| Link text | Green |
| Code | Yellow |

## Syntax highlighting

```typescript
type Theme = {
  name: string;
  active: boolean;
};

const monokai: Theme = {
  name: "Monokai",
  active: true,
};

export function applyTheme(theme: Theme): string {
  return theme.active ? `Using ${theme.name}` : "Theme disabled";
}
```
