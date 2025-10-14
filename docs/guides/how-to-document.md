# How to Document Public APIs and Components

A concise checklist and templates for adding high-quality documentation.

## Principles
- Audience-first: write for the user of your API/component, not the implementer
- Be explicit: types, defaults, edge cases, and failure modes
- Show, don’t tell: include runnable examples for common tasks
- Keep current: update docs in the same PR as code changes

## For Functions
1. Name and signature (TypeScript-style)
2. Description (1–2 sentences)
3. Parameters: name, type, description, default, required?
4. Returns: type and meaning
5. Errors/Throws: when and why
6. Examples: at least one copy-pastable snippet
7. Constraints/Notes: performance, side effects, I/O, security

## For Classes
1. Purpose and responsibilities
2. Constructor signature and semantics
3. Public methods and properties (with signatures)
4. Examples covering typical lifecycle
5. Thread-safety/statefulness notes if relevant

## For Components
1. Description and primary use cases
2. Props table (name, type, required, default, description)
3. Examples (basic, with state, edge cases)
4. Accessibility (keyboard, ARIA, focus management)
5. Theming/responsiveness notes

## Templates

### Function
```md
### `name(paramA: TypeA, paramB?: TypeB): ResultType`
- **Description**: ...
- **Parameters**:
  - `paramA: TypeA` — ...
  - `paramB?: TypeB` — ... (default: ...)
- **Returns**: `ResultType` — ...
- **Throws**: `Error` — ...
- **Example**:
```ts
const result = name('foo')
```
```

### Class
```md
### `class Foo`
- **Description**: ...
- **Constructor**: `new Foo(options: Options)`
- **Methods**:
  - `bar(): string` — ...
- **Example**:
```ts
const foo = new Foo({})
foo.bar()
```
```

### Component
```md
### `ComponentName`
- **Description**: ...
- **Props**:
  - `propA: string` — ... (default: ...)
  - `propB?: number` — ...
- **Accessibility**: ...
- **Examples**:
```tsx
<ComponentName propA="hello" />
```
```
