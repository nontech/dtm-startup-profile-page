# DTM Startup Profile Landing Page - Style Guide

## Brand Overview

This style guide is for creating a startup profile landing page aligned with the Deep Tech Momentum (DTM) brand identity. DTM is Europe's largest, invite-only growth engine for Deep Tech, connecting top-tier startups, investors, and industry leaders.

## Color Palette

### Primary Colors

- **Deep Purple**: `#7c3aed` (violet-600) - Primary brand color
- **Tech Green**: `#10b981` (emerald-500) - Success states and highlights
- **Innovation Orange**: `#f59e0b` (amber-500) - Call-to-action accents

### Neutral Colors

- **Charcoal**: `#1f2937` (gray-800) - Primary text
- **Slate**: `#475569` (slate-600) - Secondary text
- **Light Gray**: `#f8fafc` (slate-50) - Background
- **Pure White**: `#ffffff` - Cards and sections
- **Border Gray**: `#e2e8f0` (slate-200) - Borders and dividers

## Typography

### Font Stack

- **Primary**: System font stack via Tailwind CSS default
- **Headings**: `font-bold` or `font-extrabold`
- **Body**: `font-normal` or `font-medium`

### Heading Hierarchy

- **H1**: `text-4xl md:text-5xl lg:text-6xl font-extrabold` - Hero titles
- **H2**: `text-3xl md:text-4xl font-bold` - Section titles
- **H3**: `text-2xl md:text-3xl font-bold` - Subsection titles
- **H4**: `text-xl md:text-2xl font-semibold` - Card titles
- **H5**: `text-lg font-semibold` - Small headings

### Body Text

- **Large Body**: `text-lg md:text-xl` - Hero descriptions
- **Regular Body**: `text-base` - Standard content
- **Small Body**: `text-sm` - Captions and metadata

## Spacing & Layout

### Container Widths

- **Full Width**: `w-full`
- **Constrained**: `max-w-7xl mx-auto px-4 sm:px-6 lg:px-8`
- **Content Width**: `max-w-4xl mx-auto`
- **Narrow Width**: `max-w-2xl mx-auto`

### Spacing Scale

- **Micro**: `space-y-2` (8px)
- **Small**: `space-y-4` (16px)
- **Medium**: `space-y-6` (24px)
- **Large**: `space-y-8` (32px)
- **XL**: `space-y-12` (48px)
- **XXL**: `space-y-16` (64px)

### Section Padding

- **Section**: `py-12 md:py-16 lg:py-20`
- **Card**: `p-6 md:p-8`
- **Small Card**: `p-4 md:p-6`

## Components

### Buttons

#### Primary Button

```html
<button
  class="bg-blue-800 hover:bg-blue-900 text-white font-semibold py-3 px-6 rounded-lg transition-colors duration-200 shadow-lg hover:shadow-xl"
>
  Primary Action
</button>
```

#### Secondary Button

```html
<button
  class="bg-white hover:bg-gray-50 text-blue-800 font-semibold py-3 px-6 rounded-lg border-2 border-blue-800 transition-colors duration-200"
>
  Secondary Action
</button>
```

#### Ghost Button

```html
<button
  class="text-blue-800 hover:text-blue-900 font-semibold py-2 px-4 rounded-lg hover:bg-blue-50 transition-colors duration-200"
>
  Ghost Action
</button>
```

### Cards

#### Standard Card

```html
<div
  class="bg-white rounded-xl shadow-lg hover:shadow-xl transition-shadow duration-300 p-6 md:p-8"
>
  <!-- Card content -->
</div>
```

#### Feature Card

```html
<div
  class="bg-gradient-to-br from-blue-50 to-violet-50 rounded-xl p-6 md:p-8 border border-blue-100"
>
  <!-- Feature content -->
</div>
```

### Icons

#### Icon Sizing

- **Small**: `size-4` (16px)
- **Medium**: `size-5` (20px)
- **Large**: `size-6` (24px)
- **XL**: `size-8` (32px)
- **Hero**: `size-12` (48px)

#### Icon Colors

- **Primary**: `text-blue-800`
- **Secondary**: `text-slate-600`
- **Accent**: `text-emerald-500`
- **Muted**: `text-slate-400`

## Gradients

### Background Gradients

- **Hero**: `bg-gradient-to-br from-blue-900 via-blue-800 to-violet-900`
- **Section**: `bg-gradient-to-r from-blue-50 to-violet-50`
- **Card**: `bg-gradient-to-br from-white to-blue-50`

### Text Gradients

```html
<span
  class="bg-gradient-to-r from-blue-800 to-violet-600 bg-clip-text text-transparent"
>
  Gradient Text
</span>
```

## Shadows

### Shadow Scale

- **Small**: `shadow-sm`
- **Medium**: `shadow-md`
- **Large**: `shadow-lg`
- **XL**: `shadow-xl`
- **2XL**: `shadow-2xl`

### Interactive Shadows

- **Hover**: `hover:shadow-xl`
- **Focus**: `focus:shadow-lg focus:ring-2 focus:ring-blue-500 focus:ring-offset-2`

## Animations & Transitions

### Standard Transitions

- **Color**: `transition-colors duration-200`
- **Shadow**: `transition-shadow duration-300`
- **Transform**: `transition-transform duration-200`
- **All**: `transition-all duration-200`

### Hover Effects

- **Scale**: `hover:scale-105`
- **Lift**: `hover:-translate-y-1`
- **Glow**: `hover:shadow-xl`

## Responsive Design

### Breakpoints

- **Mobile**: Default (no prefix)
- **Tablet**: `md:` (768px+)
- **Desktop**: `lg:` (1024px+)
- **Large Desktop**: `xl:` (1280px+)

### Responsive Patterns

- **Text**: `text-base md:text-lg lg:text-xl`
- **Spacing**: `py-8 md:py-12 lg:py-16`
- **Grid**: `grid-cols-1 md:grid-cols-2 lg:grid-cols-3`

## Brand Voice & Messaging

### Tone

- **Professional**: Authoritative yet approachable
- **Innovative**: Forward-thinking and cutting-edge
- **European**: Emphasizing European tech sovereignty
- **Collaborative**: Community-focused and partnership-driven

### Key Messaging Themes

- Deep Tech Innovation
- European Tech Sovereignty
- Startup-Investor Connections
- Community-Driven Growth
- Actionable Insights
- Give-First Mentality

## Usage Guidelines

### Do's

- Use consistent spacing and typography scales
- Maintain high contrast for accessibility
- Implement smooth transitions and hover effects
- Use the established color palette
- Follow the component patterns
- Ensure responsive design across all devices

### Don'ts

- Don't use colors outside the established palette
- Don't mix different button styles inconsistently
- Don't ignore responsive design principles
- Don't use excessive animations that distract
- Don't compromise on accessibility standards

## Technical Implementation

### Framework

- **CSS Framework**: Tailwind CSS v4 (via CDN)
- **Icons**: Lucide Icons
- **Responsive**: Mobile-first approach
- **Browser Support**: Modern browsers (ES6+)

### Performance

- Optimize images and use appropriate formats
- Minimize CSS and JavaScript
- Use CDN for external resources
- Implement lazy loading for images

This style guide ensures consistency with the DTM brand while providing flexibility for creating engaging startup profile pages.
