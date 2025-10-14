# Usage Examples

This project currently has no published APIs. Use the examples below as a starting point and update them as you add real modules and components.

## Installing

```bash
# replace with your actual package name once published
npm install your-package-name
# or
pnpm add your-package-name
# or
yarn add your-package-name
```

## Importing modules

```ts
import { sum, average, Variance } from 'your-lib'
```

## Basic examples

### Summation
```ts
import { sum } from 'your-lib'
console.log(sum(2, 3)) // 5
```

### Average
```ts
import { average } from 'your-lib'
console.log(average([1, 2, 3])) // 2
```

### Variance class
```ts
import { Variance } from 'your-lib'
const v = new Variance([1, 2, 3])
console.log(v.value())
```
