# Design Guidelines: Simple Next.js Database Website

## Design Approach
**System-Based Approach** using principles from modern productivity tools (Notion, Linear, Airtable) with emphasis on clean data presentation and efficient interactions.

This is a utility-focused application where clarity, efficiency, and data readability are paramount. The design prioritizes functional simplicity with modern aesthetics.

## Core Design Elements

### Typography
- **Font Family**: Inter (via Google Fonts CDN)
- **Hierarchy**:
  - Page titles: text-3xl font-bold
  - Section headers: text-xl font-semibold
  - Form labels: text-sm font-medium
  - Body text: text-base
  - Helper text: text-sm text-gray-600

### Layout System
**Spacing Primitives**: Use Tailwind units of 2, 4, 6, 8, and 12 consistently
- Container: max-w-4xl mx-auto px-4
- Section spacing: py-8 to py-12
- Card padding: p-6
- Form field spacing: space-y-4
- Button padding: px-4 py-2

### Component Library

**Navigation**
- Clean top header with logo/title on left
- Minimal navigation links on right
- Sticky positioning (sticky top-0)
- Subtle border bottom for separation

**Data Display**
- Table view with alternating row backgrounds for readability
- Clear column headers with font-semibold
- Responsive cards on mobile (stack vertically)
- Empty states with helpful messaging

**Forms**
- Full-width input fields with clear labels above
- Input styling: border, rounded corners, focus ring
- Submit button: prominent, right-aligned
- Validation messages below fields

**Cards**
- Rounded corners (rounded-lg)
- Subtle borders or shadows for depth
- Consistent internal padding (p-6)
- Hover states for interactive cards

**Buttons**
- Primary: Solid background for main actions
- Secondary: Outlined for less emphasis
- Danger: For delete/destructive actions
- Icon buttons for table row actions

**Empty States**
- Centered layout with icon/illustration placeholder
- Helpful message encouraging first action
- Primary CTA button to add first entry

## Page Structure

**Homepage/Dashboard**
- Clean hero section with title and brief description
- Primary CTA button to add new entry
- Data table/grid displaying entries below
- Search/filter bar above data display (if needed)

**Form Pages**
- Centered form container (max-w-2xl)
- Clear page title
- Form fields with consistent spacing
- Submit and cancel buttons at bottom

## Images
**No hero image required** - This is a data-focused application. Use clean typographic hero instead with title, description, and CTA button.

## Visual Treatment Notes
- Maintain ample whitespace for breathing room
- Use subtle shadows sparingly for depth
- Consistent border-radius across all components
- Focus on readability with clear contrast ratios
- No distracting animations - subtle transitions only (hover states, focus rings)

## Accessibility
- Clear focus indicators on all interactive elements
- Proper label/input associations
- Semantic HTML for tables and forms
- ARIA labels where needed
- Keyboard navigation support throughout

This design creates a professional, efficient interface that makes data management intuitive while maintaining visual polish.