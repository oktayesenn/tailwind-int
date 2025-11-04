# Activity 17: @apply with Multiple Components

**Objective:** Create multiple component classes using `@apply` for reusable patterns.

**Tasks:**
1. In the `<style>` tag, create `.card { @apply bg-white rounded-lg shadow-lg p-6; }` - replace the existing utility classes on the card `<div>` elements with this class
2. In the `<style>` tag, create `.badge { @apply inline-flex items-center px-3 py-1 rounded-full text-sm font-semibold; }` - replace utilities on the `<span>` element with this class
3. In the `<style>` tag, create `.input-field { @apply border-2 border-gray-300 rounded-lg px-4 py-2 focus:border-blue-500 focus:outline-none w-full; }` - replace utilities on both `<input>` elements with this class
4. Replace the existing utility classes in the HTML with your new custom classes (card, badge, input-field)
5. Create `.badge-success { @apply bg-green-100 text-green-800; }` variant - add this to the badge `<span>` element along with the badge class

**Key Concepts:**
- Creating multiple component classes
- Organizing `@apply` classes
- Component variants with `@apply`
- Combining utilities in custom classes

