# react-component-library

A reusable React component library built with TypeScript and Tailwind CSS. Designed for consistency, accessibility, and ease of use across multiple projects.

## Components

### Inputs
- `Button` — variants: primary, secondary, ghost, danger; sizes: sm, md, lg
- `Input` — with label, error state, helper text
- `Select` — searchable dropdown with keyboard navigation
- `Checkbox` / `Radio` / `Toggle`
- `DatePicker`

### Layout
- `Card` — with header, body, footer slots
- `Modal` — accessible, focus-trapped dialog
- `Drawer` — slide-in side panel
- `Tabs` — horizontal and vertical variants
- `Accordion`

### Feedback
- `Toast` — success, error, warning, info notifications
- `Badge` — status indicators
- `Spinner` / `Skeleton` — loading states
- `EmptyState`

### Navigation
- `Navbar`
- `Sidebar`
- `Breadcrumb`
- `Pagination`

## Tech Stack

- **React 18** + **TypeScript**
- **Tailwind CSS** — styling
- **Radix UI** — accessible primitives
- **Storybook** — component docs and playground

## Installation

```bash
npm install @madhu/react-ui
```

## Usage

```tsx
import { Button, Input, Modal } from '@madhu/react-ui';

function App() {
  return (
    <Button variant="primary" size="md" onClick={() => {}}>
      Click me
    </Button>
  );
}
```

## Development

```bash
git clone https://github.com/madhuveeraprasath-a/react-component-library.git
cd react-component-library
npm install
npm run storybook
```

## Design Principles

- **Accessible by default** — ARIA attributes, keyboard navigation, focus management
- **Composable** — small, single-responsibility components that compose well
- **Typed** — full TypeScript support with IntelliSense
- **Themeable** — CSS variables for colors, spacing, and typography

## License

MIT
