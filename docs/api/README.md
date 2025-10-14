# Public API Reference

> Status: Bootstrap templates. Replace placeholders as you add code.

## Conventions
- Document only stable, public modules, functions, and classes
- Use TypeScript-style signatures even if using JavaScript
- Include parameters, return types, thrown errors, and usage examples
- Add notes on performance and edge cases when relevant

## Index
- [Modules](./modules.md)
- [Functions](./functions.md)
- [Classes](./classes.md)

---

## Function Template

### `doSomething(input: string): Promise<Result>`
- **Description**: Short, imperative summary of what the function does
- **Parameters**:
  - **input**: string — description
- **Returns**: Promise<Result> — description
- **Throws**: Error — conditions when errors can be thrown
- **Examples**:
```ts
const result = await doSomething('hello')
console.log(result.value)
```

## Class Template

### `class Processor`
- **Description**: What instances represent or manage
- **Constructor**: `new Processor(options: ProcessorOptions)`
- **Methods**:
  - `run(): Promise<void>` — description
  - `cancel(): void` — description
- **Examples**:
```ts
const p = new Processor({ concurrency: 4 })
await p.run()
```

## Module Template

### `@lib/module-name`
- **Description**: Module purpose in 1–2 sentences
- **Exports**: `foo`, `bar`, `Baz`
- **See also**: related modules or guides
