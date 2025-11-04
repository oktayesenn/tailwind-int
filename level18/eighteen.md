# Activity 18: @apply with Responsive Design

**Objective:** Use `@apply` with responsive breakpoints for adaptive components.

**Tasks:**
1. In the `<style>` tag, create `.container-responsive { @apply px-4 md:px-8 lg:px-12 py-8; }` - replace the utilities on the outer `<div>` element with this class
2. This is already done in step 1 - the class includes responsive padding
3. In the `<style>` tag, create `.text-responsive { @apply text-base md:text-lg lg:text-xl font-bold; }` - replace the utilities on the `<h1>` element with this class
4. In the `<style>` tag, create `.grid-responsive { @apply grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4; }` - replace the utilities on the grid `<div>` element with this class
5. Replace all the existing utility classes in the HTML with your new custom classes (container-responsive, text-responsive, grid-responsive)

**Key Concepts:**
- Using responsive prefixes with `@apply`
- Creating responsive component classes
- Combining multiple breakpoints
- Responsive design patterns with `@apply`

