# Components Guide

Document UI components, their props/inputs, and usage examples here.

## Conventions

- Components should be documented with: Purpose, Props, Defaults, Events/Callbacks, Accessibility, and Examples.
- Include minimal runnable examples and note any required providers or global styles.

## Example Template

### `Button`

- Purpose: Triggers an action when clicked.
- Props:
  - `label` (string, required): Visible text.
  - `variant` ("primary" | "secondary" | "ghost", default: "primary"): Visual style.
  - `disabled` (boolean, default: false): Non-interactive state.
- Accessibility:
  - Uses `role="button"` and proper focus outlines.
- Example (React):

```tsx
import { Button } from './components/Button'

export default function Example() {
  return (
    <div>
      <Button label="Save" variant="primary" />
      <Button label="Cancel" variant="ghost" />
    </div>
  )
}
```
