# Functions

Document free functions and static helpers.

## sum(a: number, b: number): number {#sum}
- **Description**: Adds two numbers
- **Parameters**:
  - **a**: number — first addend
  - **b**: number — second addend
- **Returns**: number — sum of `a` and `b`
- **Example**:
```ts
import { sum } from 'your-lib'
console.log(sum(2, 3)) // 5
```

## average(values: number[]): number {#average}
- **Description**: Computes the arithmetic mean
- **Parameters**:
  - **values**: number[] — non-empty array of numbers
- **Returns**: number — arithmetic mean
- **Notes**: Returns `NaN` for an empty array (recommend validating input)
- **Example**:
```ts
import { average } from 'your-lib'
console.log(average([1, 2, 3])) // 2
```
