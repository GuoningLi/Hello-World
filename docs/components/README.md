# Components

Use this section to document UI components.

## Conventions
- Prefer writing prop types using TypeScript syntax
- List default values and whether a prop is required
- Include interactive examples and accessibility notes
- Note keyboard behavior and ARIA attributes where applicable

## Index
- [Atoms](./atoms.md)
- [Molecules](./molecules.md)
- [Organisms](./organisms.md)

---

## Component Template

### `Button`
- **Description**: Concise description of the component and its primary use cases
- **Props**:
  - `variant: 'primary' | 'secondary'` — visual style, default: `'primary'`
  - `disabled?: boolean` — disable interactions, default: `false`
  - `onClick?: (event: MouseEvent) => void` — click handler
- **Accessibility**:
  - Keyboard: Enter/Space activates
  - ARIA: use `aria-pressed` for toggle buttons
- **Examples**:
```tsx
<Button variant="primary" onClick={() => console.log('clicked')}>Save</Button>
```
