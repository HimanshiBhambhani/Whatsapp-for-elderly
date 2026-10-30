---
name: Accessible Communication System
colors:
  surface: '#fff8f1'
  surface-dim: '#e0d9d1'
  surface-bright: '#fff8f1'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#faf2ea'
  surface-container: '#f4ede5'
  surface-container-high: '#eee7df'
  surface-container-highest: '#e8e1d9'
  on-surface: '#1e1b17'
  on-surface-variant: '#3f4946'
  inverse-surface: '#33302b'
  inverse-on-surface: '#f7f0e7'
  outline: '#6f7976'
  outline-variant: '#bec9c5'
  surface-tint: '#1c695f'
  primary: '#00453d'
  on-primary: '#ffffff'
  primary-container: '#075e54'
  on-primary-container: '#8dd5c8'
  inverse-primary: '#8cd4c7'
  secondary: '#006b5f'
  on-secondary: '#ffffff'
  secondary-container: '#8cf1e1'
  on-secondary-container: '#006f64'
  tertiary: '#00471c'
  on-tertiary: '#ffffff'
  tertiary-container: '#006129'
  on-tertiary-container: '#3fe374'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#a8f0e3'
  primary-fixed-dim: '#8cd4c7'
  on-primary-fixed: '#00201c'
  on-primary-fixed-variant: '#005047'
  secondary-fixed: '#8ff4e3'
  secondary-fixed-dim: '#72d8c8'
  on-secondary-fixed: '#00201c'
  on-secondary-fixed-variant: '#005047'
  tertiary-fixed: '#66ff8e'
  tertiary-fixed-dim: '#3de273'
  on-tertiary-fixed: '#002109'
  on-tertiary-fixed-variant: '#005322'
  background: '#fff8f1'
  on-background: '#1e1b17'
  surface-variant: '#e8e1d9'
typography:
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 26px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.5px
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  margin-mobile: 1.25rem
  gutter-md: 1rem
  touch-target-min: 3.5rem
  stack-gap-lg: 1.5rem
  stack-gap-sm: 0.75rem
---

## Brand & Style

The design system is centered on **radical accessibility** and **cognitive ease**, specifically optimized for elderly users or those requiring assistive interfaces. The personality is helpful, dependable, and patient. 

The aesthetic leverages a **Modern Corporate** foundation—rooted in familiar mobile patterns—but enhances it with high-contrast elements and larger touch targets. It prioritizes clarity over ornamentation, ensuring that users feel confident and in control of their digital interactions. The "Assist Mode" features are integrated through bold, high-visibility cards and action-oriented components that reduce the "search and click" fatigue often found in dense messaging apps.

## Colors

This design system utilizes the iconic communication palette to maintain user familiarity while optimizing for legibility.

- **Primary & Secondary Greens:** Used for headers, top navigation bars, and primary brand actions.
- **Tertiary Green:** Reserved for active states, new message indicators, and primary call-to-action buttons.
- **Neutral Palette:** A warm grey/beige (`#ECE5DD`) is used for chat backgrounds to reduce screen glare, while pure white is used for cards and message bubbles to ensure maximum text contrast.
- **High Contrast:** Text strictly adheres to high-contrast ratios, primarily using pure black or deep grey against light backgrounds to accommodate visual impairments.

## Typography

The typography system uses **Plus Jakarta Sans** for its excellent legibility, open counters, and friendly character. 

To support the "Assist Mode" narrative, font sizes are significantly scaled up compared to standard mobile interfaces. The minimum body size is set to 18px to ensure readability without strain. Line heights are generous to prevent "crowding" of text lines, which is essential for users with declining vision. 

- **Headlines:** Bold and direct, used for screen titles and Assist Mode category cards.
- **Body Text:** Medium weight is preferred for standard messages to increase "ink density" on screen.
- **Labels:** Used for timestamps and metadata, kept clear and never smaller than 14px.

## Layout & Spacing

The layout follows a **fluid grid** model with exaggerated safe areas. 

- **Touch Targets:** Every interactive element (buttons, list items) has a minimum height of 56px (`3.5rem`) to accommodate users with reduced fine motor skills.
- **Vertical Rhythm:** A stack-based layout is used for Assist Mode features. Large action cards are separated by 24px gaps to prevent accidental taps.
- **Margins:** Standard side margins are increased to 20px to ensure the thumb naturally rests on the content without obscuring it.
- **Chat View:** Message bubbles utilize a maximum width of 85% of the screen to maintain a clear "gutter" between incoming and outgoing messages, making the conversation flow easier to track visually.

## Elevation & Depth

This system uses **Tonal Layers** rather than complex shadows to define hierarchy. 

- **Surface Levels:** The base layer is the warm neutral background. Interactive cards sit on a pure white surface with a subtle 1px border (`#D1D1D1`).
- **Assist Mode Priority:** Special assistive features (like "Call for Help" or "Voice to Text") use a slight ambient shadow (4px blur, 10% opacity) to "lift" them above the standard interface, signaling their importance.
- **Active States:** Instead of depth changes, active states are indicated by high-contrast color fills or thick borders (3px) to provide clear visual feedback.

## Shapes

The design system employs a **Rounded** shape language to feel approachable and safe. 

- **Message Bubbles:** Use the standard 0.5rem (8px) corner radius, but "Assist Mode" cards and large action buttons use `rounded-xl` (1.5rem/24px) to distinguish them from standard content.
- **Avatars:** Strictly circular to maintain the established mental model of "people."
- **Inputs:** Softly rounded (8px) to provide a clear container for text entry without feeling overly sharp or clinical.

## Components

### Buttons
- **Primary Action:** Large, full-width green buttons with white, bold 20px text.
- **Assistive Buttons:** High-contrast yellow or bright green circular buttons for critical actions like "Record Voice" or "Emergency Contact."

### Assist Mode Cards
- Large white containers with an icon on the left, a bold title, and a short description. These act as "shortcuts" to frequent actions (e.g., "Send Photo to Family").

### Input Fields
- The message input bar is taller than standard (64px) with a persistent, high-contrast "Send" button that does not disappear when empty, preventing confusion about how to submit text.

### List Items (Chats)
- Increased vertical padding. The contact name is bold and large, while the "last message" preview is limited to one line to keep the interface clean and uncluttered.

### Indicators
- Unread message badges use the Tertiary Green (`#25D366`) and are 30% larger than standard to ensure they are noticed immediately.