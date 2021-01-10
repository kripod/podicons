# podicons <span aria-hidden="true">🗜️</span>

Handwritten 24×24px SVG icons with compressibility in mind

## Rules <span aria-hidden="true">📐</span>

- 2px stroke
- 1px corner radius

### Base shapes in order of preference

1. [16×16px _square_](./outline/square.svg) with no elements outside
2. [18×18px _circle_](./outline/circle.svg) with no elements outside
3. [12×12px _square-small_](./outline/square-small.svg)
4. [14×14px _circle-small_](./outline/circle-small.svg)

### Format

- Colors are inherited via `currentColor`
- Attributes should be sorted as defined in the [latest SVG standard](https://www.w3.org/TR/SVG2/)
- Results shall be minified using [SVGO](https://github.com/svg/svgo):
  ```bash
  npx svgo --config=.svgo.yml --input=outline/icon.svg
  ```

### Starter templates

#### Outline

```svg
<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" stroke="currentColor" stroke-width="2"></svg>
```
