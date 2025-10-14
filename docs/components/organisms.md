# Organisms

Complex components composed of molecules and atoms (e.g., `Navbar`, `DataTable`).

### Example: `Navbar`
- **Props**:
  - `logo: ReactNode`
  - `links: Array<{ href: string; label: string }>`
- **Accessibility**: Use `nav` landmark and keyboard navigation
- **Example**:
```tsx
<Navbar logo={<Logo />} links={[{ href: '/', label: 'Home' }]} />
```
