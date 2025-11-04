# Activity 19: @apply with Pseudo-classes and States

**Objective:** Use `@apply` with hover, focus, and other pseudo-class states.

**Tasks:**
1. In the `<style>` tag, create `.btn-interactive { @apply bg-blue-500 text-white px-6 py-3 rounded-lg; }` - base button styles
2. Add hover and focus to `.btn-interactive`: `@apply hover:bg-blue-600 focus:ring-2 focus:ring-blue-500 focus:outline-none;` - combine with base styles
3. Add transitions and active state to `.btn-interactive`: `@apply active:scale-95 transition-all duration-300;` - combine all in one class
4. In the `<style>` tag, create `.link-hover { @apply text-blue-500 hover:text-blue-700 underline; }` - replace utilities on the `<a>` element with this class
5. In the `<style>` tag, create `.input-focus { @apply border-2 border-gray-300 rounded-lg px-4 py-2 focus:border-blue-500 focus:outline-none focus:ring-2 focus:ring-blue-200 w-full; }` - replace utilities on the `<input>` element with this class

**Key Concepts:**
- Combining states with `@apply`
- Pseudo-classes in `@apply`
- Transition and animation utilities
- Interactive component patterns

