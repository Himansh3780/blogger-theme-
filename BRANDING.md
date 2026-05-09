# Branding Guidelines for Huvlio

> **Comprehensive brand guidelines for professional, consistent, and memorable branding**

---

## Table of Contents

1. [Brand Overview](#brand-overview)
2. [Brand Identity](#brand-identity)
3. [Logo Usage](#logo-usage)
4. [Color Palette](#color-palette)
5. [Typography](#typography)
6. [Voice & Tone](#voice--tone)
7. [Design Elements](#design-elements)
8. [Component Library](#component-library)
9. [Do's & Don'ts](#dos--donts)
10. [Implementation Guide](#implementation-guide)

---

## Brand Overview

### Brand Purpose
Huvlio empowers content creators and bloggers to build professional, SEO-optimized online presences through beautiful, branded design.

### Brand Mission
To provide accessible, powerful tools that help creators tell their stories effectively and reach their audience.

### Core Values
- **Professional:** Quality and excellence in everything we do
- **Accessible:** Simple, understandable, inclusive
- **Creative:** Bold, innovative, inspiring
- **Trustworthy:** Reliable, transparent, honest
- **Community-focused:** Supporting creators together

### Brand Personality
- Modern yet professional
- Approachable yet authoritative
- Creative yet practical
- Playful yet serious (when needed)
- Bold yet balanced

---

## Brand Identity

### Brand Story

Huvlio was created to solve a problem: great bloggers deserve better tools. Whether you're a tech writer, business expert, creative artist, or thought leader, your ideas deserve a platform that looks as good as your content reads.

We believe professional branding isn't just for big companies. Independent creators should have access to beautiful, functional design that amplifies their message and builds their authority.

### Target Audience

**Primary:**
- Content creators (age 25-50)
- Business bloggers
- Tech writers
- Thought leaders
- Entrepreneurs

**Secondary:**
- Agencies
- Publishers
- Educators
- Journalists
- Content marketers

### Brand Positioning

**"The professional blogger's design partner"**

Huvlio is positioned as:
- Not a template service, but a design philosophy
- Not basic, but sophisticated
- Not difficult, but intuitive
- Not generic, but customizable

---

## Logo Usage

### Logo Versions

#### Primary Logo (Full)
- Use for main branding
- Clear space around logo
- Preferred logo version
- Use when space allows

#### Logo Mark (Symbol Only)
- Use for favicons
- Use in small spaces
- Use for app icons
- Simplified, recognizable

#### Logo Lockup (Horizontal)
- Use for headers
- Use for banners
- Standard presentation
- Balanced proportion

#### Logo Lockup (Vertical)
- Use for sidebars
- Use for mobile headers
- Space-constrained layouts
- Vertical arrangement

### Clear Space

Maintain minimum clear space (minimum: 1/4 of logo height)

```
Always maintain clear space:
[Clear Space] | LOGO | [Clear Space]
      ↑                     ↑
   1/4 height         1/4 height
```

### Size Guidelines

- **Minimum:** 120px width (digital), 0.5" (print)
- **Maximum:** No maximum
- **Standard:** 200-400px (most uses)

**Avoid:**
- ❌ Stretching/distorting
- ❌ Rotating
- ❌ Adding effects/shadows
- ❌ Changing colors
- ❌ Using deprecated versions
- ❌ Too small (unreadable)

### Color Applications

**Logo colors:**
- Primary (full color) - standard use
- White (for dark backgrounds)
- Dark (for light backgrounds)
- Single color (for constrained uses)

---

## Color Palette

### Primary Colors

#### Huvlio Blue
```
Name: Huvlio Blue
Hex: #2563EB
RGB: 37, 99, 235
HSL: 217°, 96%, 53%
CMYK: 84, 58, 0, 8
Use: Primary brand color, CTAs, links
```

#### Deep Navy
```
Name: Deep Navy
Hex: #1E3A8A
RGB: 30, 58, 138
HSL: 217°, 64%, 33%
CMYK: 78, 58, 0, 46
Use: Headers, emphasis, dark mode background
```

### Secondary Colors

#### Vibrant Purple
```
Name: Vibrant Purple
Hex: #7C3AED
RGB: 124, 58, 237
HSL: 258°, 90%, 58%
CMYK: 48, 76, 0, 7
Use: Accents, highlights, secondary CTAs
```

#### Success Green
```
Name: Success Green
Hex: #10B981
RGB: 16, 185, 129
HSL: 160°, 84%, 39%
CMYK: 91, 0, 30, 27
Use: Success messages, positive actions
```

#### Warning Orange
```
Name: Warning Orange
Hex: #F59E0B
RGB: 245, 158, 11
HSL: 38°, 92%, 50%
CMYK: 0, 36, 96, 4
Use: Warning messages, alerts
```

#### Error Red
```
Name: Error Red
Hex: #EF4444
RGB: 239, 68, 68
HSL: 0°, 91%, 60%
CMYK: 0, 71, 71, 6
Use: Errors, destructive actions
```

### Neutral Colors

#### Off-White
```
Name: Off-White
Hex: #F9FAFB
RGB: 249, 250, 251
Use: Light backgrounds, secondary surfaces
```

#### Light Gray
```
Name: Light Gray
Hex: #E5E7EB
RGB: 229, 231, 235
Use: Borders, dividers
```

#### Medium Gray
```
Name: Medium Gray
Hex: #9CA3AF
RGB: 156, 163, 175
Use: Secondary text
```

#### Dark Gray
```
Name: Dark Gray
Hex: #374151
RGB: 55, 65, 81
Use: Body text, primary text
```

#### Almost Black
```
Name: Almost Black
Hex: #111827
RGB: 17, 24, 39
Use: Headlines, dark mode text
```

### Using Colors Effectively

**Color hierarchy:**
```
Primary (Blue):       High emphasis, CTAs, links
Secondary (Purple):   Accents, highlights
Neutral (Gray):       Text, backgrounds
Success (Green):      Positive feedback
Warning (Orange):     Alerts, caution
Error (Red):          Errors, destructive
```

**Contrast & Accessibility:**
- Text on background contrast ratio: 4.5:1 minimum
- Large text (18pt+): 3:1 minimum
- Test with accessibility tools
- Use WebAIM contrast checker

**Dark Mode:**
```css
:root {
  /* Light mode */
  --text-primary: #111827;
  --text-secondary: #9CA3AF;
  --bg-primary: #FFFFFF;
  --bg-secondary: #F9FAFB;
}

@media (prefers-color-scheme: dark) {
  :root {
    /* Dark mode */
    --text-primary: #F9FAFB;
    --text-secondary: #9CA3AF;
    --bg-primary: #111827;
    --bg-secondary: #1F2937;
  }
}
```

---

## Typography

### Font Families

#### Primary Font: Poppins
- Family: Poppins (Google Fonts)
- Usage: Headlines, navigation, emphasis
- Characteristics: Modern, geometric, friendly
- Weights: 400, 500, 600, 700

```html
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap" rel="stylesheet">

<style>
  .heading {
    font-family: 'Poppins', sans-serif;
    font-weight: 600;
  }
</style>
```

#### Secondary Font: Inter
- Family: Inter (Google Fonts)
- Usage: Body text, UI elements
- Characteristics: Clean, readable, professional
- Weights: 400, 500, 600

```html
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&display=swap" rel="stylesheet">

<style>
  body {
    font-family: 'Inter', sans-serif;
    font-weight: 400;
  }
</style>
```

### Type Scale

**Mobile (< 768px):**
```
H1: 24px / 32px (Poppins, 700)
H2: 20px / 28px (Poppins, 600)
H3: 18px / 26px (Poppins, 600)
H4: 16px / 24px (Poppins, 500)
Body: 14px / 22px (Inter, 400)
Caption: 12px / 18px (Inter, 400)
```

**Desktop (≥ 768px):**
```
H1: 36px / 44px (Poppins, 700)
H2: 28px / 36px (Poppins, 600)
H3: 24px / 32px (Poppins, 600)
H4: 20px / 28px (Poppins, 500)
Body: 16px / 24px (Inter, 400)
Caption: 14px / 20px (Inter, 400)
```

### Typography Rules

**Headlines:**
- Use Poppins font
- Bold, confident appearance
- Maximum 65 characters per line
- Clear hierarchy

**Body Text:**
- Use Inter font
- 14-16px size
- 1.5-1.7 line height
- 45-75 characters per line for readability

**Emphasis:**
```html
<!-- Strong emphasis -->
<strong>Important text</strong>

<!-- Regular emphasis -->
<em>Italicized text</em>

<!-- Code -->
<code>code snippet</code>
```

---

## Voice & Tone

### Brand Voice

**Huvlio sounds:**
- Knowledgeable but not condescending
- Friendly but professional
- Clear and direct
- Inspiring and empowering
- Confident and helpful

**Huvlio doesn't sound:**
- ❌ Boring or corporate
- ❌ Overly casual or slang-heavy
- ❌ Pompous or pretentious
- ❌ Negative or dismissive
- ❌ Vague or unclear

### Tone Variations

**Encouraging (default):**
> "Ready to create your most professional blog yet? Let's get started!"

**Professional (formal content):**
> "Implement structured data markup to improve search engine visibility and enhance your search results appearance."

**Friendly (casual content):**
> "Here's the cool part—Huvlio handles the technical stuff so you can focus on what you do best: creating amazing content."

**Educational (tutorials):**
> "Follow these five steps to optimize your blog for search engines and start attracting more organic traffic."

### Writing Guidelines

**Do:**
- ✅ Use active voice ("Optimize your blog" not "Your blog should be optimized")
- ✅ Use second person ("you") when speaking to users
- ✅ Use concrete examples
- ✅ Keep sentences short (15-20 words avg)
- ✅ Use formatting (bullets, bold) for scannability
- ✅ Be specific (not "many" but "73%")

**Don't:**
- ❌ Use complex jargon without explanation
- ❌ Use exclamation marks excessively
- ❌ Use all caps (except acronyms)
- ❌ Use slang or dated language
- ❌ Be passive or wishy-washy
- ❌ Use negative framing when positive is possible

### Copy Examples

**Product Features:**
```
❌ "This feature is nice"
✅ "Create stunning blog posts in minutes with our intuitive editor"
```

**Error Messages:**
```
❌ "Error"
✅ "Looks like something went wrong. Please try again or contact support."
```

**Success Messages:**
```
❌ "Success"
✅ "Your blog has been published! View it now"
```

**Calls to Action:**
```
❌ "Submit"
✅ "Publish Your Blog"
✅ "Start Optimizing"
✅ "View the Guide"
```

---

## Design Elements

### Spacing System

**Base unit:** 4px

```
xs: 4px    (spacing-xs)
sm: 8px    (spacing-sm)
md: 16px   (spacing-md)
lg: 24px   (spacing-lg)
xl: 32px   (spacing-xl)
2xl: 48px  (spacing-2xl)
3xl: 64px  (spacing-3xl)
```

**Implementation:**
```css
:root {
  --space-xs: 4px;
  --space-sm: 8px;
  --space-md: 16px;
  --space-lg: 24px;
  --space-xl: 32px;
  --space-2xl: 48px;
  --space-3xl: 64px;
}

.component {
  margin: var(--space-md);
  padding: var(--space-lg);
}
```

### Border Radius

```
Tight: 2px    (small UI elements)
Small: 4px    (buttons, inputs)
Medium: 8px   (cards, containers)
Large: 12px   (large cards, modals)
Full: 9999px  (badges, rounded elements)
```

### Shadow System

**Subtle:** `0 1px 2px rgba(0,0,0,0.05)`
**Light:** `0 1px 3px rgba(0,0,0,0.1), 0 1px 2px rgba(0,0,0,0.06)`
**Medium:** `0 4px 6px rgba(0,0,0,0.1), 0 2px 4px rgba(0,0,0,0.06)`
**Heavy:** `0 20px 25px rgba(0,0,0,0.15), 0 10px 10px rgba(0,0,0,0.05)`

### Icons

**Style:** Modern, minimal, 24px base
**Source:** Heroicons, Feather Icons, or Material Design
**Color:** Match text color or use brand colors
**Sizing:** 16px, 24px, 32px, 48px

---

## Component Library

### Buttons

**Primary Button:**
```html
<button class="btn btn-primary">
  Primary Action
</button>
```

```css
.btn-primary {
  background-color: var(--primary-blue);
  color: white;
  padding: 12px 24px;
  border-radius: 6px;
  font-weight: 600;
  cursor: pointer;
  transition: all 0.2s;
}

.btn-primary:hover {
  background-color: var(--primary-dark);
}
```

**Secondary Button:**
```html
<button class="btn btn-secondary">
  Secondary Action
</button>
```

### Cards

```html
<div class="card">
  <div class="card__header">
    <h3 class="card__title">Card Title</h3>
  </div>
  <div class="card__content">
    <!-- Content here -->
  </div>
  <div class="card__footer">
    <!-- Footer content -->
  </div>
</div>
```

```css
.card {
  background: white;
  border-radius: 8px;
  box-shadow: 0 1px 3px rgba(0,0,0,0.1);
  overflow: hidden;
  transition: all 0.2s;
}

.card:hover {
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}

.card__header {
  padding: 24px;
  border-bottom: 1px solid #E5E7EB;
}

.card__content {
  padding: 24px;
}
```

### Forms

**Input Fields:**
```html
<label class="form-group">
  <span class="form-label">Your Name</span>
  <input 
    type="text" 
    class="form-input" 
    placeholder="Enter your name"
  />
</label>
```

```css
.form-input {
  width: 100%;
  padding: 12px 16px;
  border: 1px solid #E5E7EB;
  border-radius: 6px;
  font-family: inherit;
  font-size: 16px;
  transition: all 0.2s;
}

.form-input:focus {
  outline: none;
  border-color: var(--primary-blue);
  box-shadow: 0 0 0 3px rgba(37, 99, 235, 0.1);
}
```

---

## Do's & Don'ts

### Logo

**Do:**
- ✅ Use approved logo files
- ✅ Maintain clear space
- ✅ Use on appropriate backgrounds
- ✅ Scale proportionally
- ✅ Keep the overall shape

**Don't:**
- ❌ Stretch or distort
- ❌ Rotate at angles
- ❌ Add effects/shadows
- ❌ Change colors
- ❌ Use outdated versions
- ❌ Make too small

### Colors

**Do:**
- ✅ Use brand color palette
- ✅ Maintain color contrast
- ✅ Use colors consistently
- ✅ Test accessibility
- ✅ Consider dark mode

**Don't:**
- ❌ Mix with other color schemes
- ❌ Use low contrast combinations
- ❌ Randomly change colors
- ❌ Use too many colors
- ❌ Ignore accessibility

### Typography

**Do:**
- ✅ Use Poppins for headers
- ✅ Use Inter for body
- ✅ Maintain type scale
- ✅ Use proper line height
- ✅ Keep font weight hierarchy

**Don't:**
- ❌ Add custom fonts without approval
- ❌ Use too many font weights
- ❌ Make text too small
- ❌ Use all caps for body text
- ❌ Mix typefaces randomly

### Voice & Tone

**Do:**
- ✅ Sound knowledgeable and helpful
- ✅ Use active voice
- ✅ Be specific with examples
- ✅ Speak directly to users
- ✅ Match brand personality

**Don't:**
- ❌ Sound condescending
- ❌ Use overly technical jargon
- ❌ Be vague or indirect
- ❌ Use slang or outdated language
- ❌ Contradict brand values

---

## Implementation Guide

### Web Implementation

**1. Add Fonts:**
```html
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
```

**2. Define CSS Variables:**
```css
:root {
  /* Colors */
  --primary-blue: #2563EB;
  --primary-dark: #1E3A8A;
  --secondary-purple: #7C3AED;
  --success-green: #10B981;
  --warning-orange: #F59E0B;
  --error-red: #EF4444;
  --text-primary: #111827;
  --text-secondary: #9CA3AF;
  --bg-light: #F9FAFB;
  --bg-white: #FFFFFF;
  
  /* Spacing */
  --space-xs: 4px;
  --space-sm: 8px;
  --space-md: 16px;
  --space-lg: 24px;
  --space-xl: 32px;
  
  /* Fonts */
  --font-heading: 'Poppins', sans-serif;
  --font-body: 'Inter', sans-serif;
}
```

**3. Create Component Classes:**
```css
.btn-primary {
  background: var(--primary-blue);
  color: white;
  padding: var(--space-md) var(--space-lg);
  border-radius: 6px;
  font-family: var(--font-body);
  font-weight: 600;
}

h1 {
  font-family: var(--font-heading);
  font-size: 36px;
  font-weight: 700;
  color: var(--text-primary);
}
```

### Blogger Implementation

**1. Edit Template HTML:**
- Go to Theme > Edit HTML
- Add CSS variables in `<style>` tag
- Apply classes to elements

**2. Update Header Section:**
```xml
<b:section id="header" ...>
  <b:widget id="Header1" type="Header">
    <b:includable id="main">
      <!-- Header content -->
    </b:includable>
  </b:widget>
</b:section>
```

**3. Style Posts:**
```css
.post {
  background: var(--bg-white);
  padding: var(--space-lg);
  border-radius: 8px;
  margin-bottom: var(--space-lg);
}

.post-title {
  font-family: var(--font-heading);
  font-size: 28px;
  color: var(--text-primary);
}
```

---

## Resources

- **Fonts:** [Google Fonts](https://fonts.google.com)
- **Icons:** [Heroicons](https://heroicons.com)
- **Colors:** [Tailwind Colors](https://tailwindcss.com/docs/customizing-colors)
- **Design:** [Figma](https://figma.com)
- **Testing:** [WebAIM Contrast](https://webaim.org/resources/contrastchecker/)

---

**Version:** 1.0  
**Last Updated:** May 9, 2026  
**Created for:** Huvlio Blogger Theme by Himanshu
