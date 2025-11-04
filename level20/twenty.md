# Activity 20: Complete Component Library with @apply

**Objective:** Build a complete component library using `@apply` to demonstrate mastery.

**Tasks:**
1. In the `<style>` tag, create:
   - `.btn { @apply px-6 py-2 rounded-lg text-white font-medium transition; }` (base)
   - `.btn-primary { @apply bg-blue-500 hover:bg-blue-600; }`
   - `.btn-secondary { @apply bg-gray-500 hover:bg-gray-600; }`
   - `.btn-danger { @apply bg-red-500 hover:bg-red-600; }`
   Replace button utilities in HTML with these classes (add both `btn` and variant class)

2. In the `<style>` tag, create `.card { @apply bg-white rounded-lg shadow p-6; }` - replace utilities on card `<div>` elements

3. In the `<style>` tag, create `.form-group { @apply space-y-4; }` for the form, and `.form-input { @apply border-2 border-gray-300 rounded-lg px-4 py-2 w-full focus:border-blue-500 focus:outline-none; }` for inputs - replace utilities accordingly

4. In the `<style>` tag, create:
   - `.badge { @apply px-3 py-1 rounded-full text-sm font-semibold; }` (base)
   - `.badge-info { @apply bg-blue-100 text-blue-800; }`
   - `.badge-success { @apply bg-green-100 text-green-800; }`
   Replace badge utilities in HTML with these classes

5. Replace all utility classes throughout the HTML with your custom `@apply` classes to build a complete component library

**Key Concepts:**
- Building a component library
- Creating base classes and variants
- Organizing `@apply` classes logically
- Best practices for using `@apply`
- When to use `@apply` vs utility classes

**Final Challenge:** Create a complete dashboard using all your custom `@apply` classes!

