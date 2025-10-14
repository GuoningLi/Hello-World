# Molecules

Combinations of atoms (e.g., `InputWithLabel`, `Card`).

### Example: `InputWithLabel`
- **Props**:
  - `label: string`
  - `id: string`
  - `value: string`
  - `onChange: (value: string) => void`
- **Accessibility**: `label` should be linked to input via `id`
- **Example**:
```tsx
<InputWithLabel id="email" label="Email" value="" onChange={setEmail} />
```
