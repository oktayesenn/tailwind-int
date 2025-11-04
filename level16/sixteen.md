# Activity 16: Introduction to @apply

**Objective:** Learn the basics of the `@apply` directive to extract component classes.

**Tasks:**
1. The `<style>` tag with Tailwind directives is already set up - you'll add your `@apply` classes here
2. In the `<style>` tag, create a `.btn-primary` class using: `@apply bg-blue-500 text-white px-6 py-3 rounded-lg;`
3. Add hover state to the same class: `@apply hover:bg-blue-600;` (combine with the previous utilities)
4. Your complete `.btn-primary` class should include both base styles and hover state
5. Add the `btn-primary` class (without the dot) to the second `<button>` element's `class` attribute - replace the empty class

**Key Concepts:**
- `@apply` directive syntax
- Extracting repeated utility combinations
- Creating custom component classes
- When to use `@apply` vs utility classes

**Note:** You'll need to add a `<style>` tag with `@tailwind base;`, `@tailwind components;`, and `@tailwind utilities;` directives.

