# Next.js Custom Controls

A collection of reusable React components built with Next.js and TypeScript.

## Components

### GenericTable
A flexible, reusable table component that works with any data type.

**Features:**
- Generic type support
- Built-in loading and empty states
- Customizable row rendering
- Automatic object property display

**Usage:**
```tsx
<GenericTable
  data={yourData}
  headers={['Column 1', 'Column 2']}
  loading={false}
  getItemKey={(item) => item.id}
/>
```

### System Controls
- **Button** - Customizable button component
- **FormInput** - Form input with label and validation
- **Modal** - Overlay modal component
- **RadioGroup** - Radio button group
- **Table** - Base table component

## Getting Started

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view the application.