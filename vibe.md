Vibe.md: Professional, Modern & Energetic

1. Core Vibe

The goal is to create a webpage that feels professional, modern, energetic, and trustworthy. The aesthetic is clean, sharp, and business-savvy, but also approachable and optimistic. It builds confidence through a clear, organized layout and drives action with strategic, high-contrast pops of color.

Keywords:

Professional

Modern

Energetic

Clean

Trustworthy

Organized

High-Contrast

Approachable

2. Color Palette (Updated from Style Kit)

The palette is based on the provided style kit. White space is the foundation, the "Grey" ramp provides hierarchy, and "Semantic-Yellow" injects the energy and directs the user's eye, maintaing the original "energetic" vibe.

Primary Background (--color-bg): #FFFFFF (White)

Secondary Background (--color-bg-alt): #F7F7F7 (Grey/200 from kit)

Primary Text (--color-text-primary): #1D2939 (Grey/900 from kit)

Secondary Text (--color-text-secondary): #475467 (Grey/700 from kit)

Primary Accent (--color-accent): #FDB022 (Semantic-Yellow/300 from kit. Used for all CTAs, highlights, and key data points.)

Borders & Dividers (--color-border): #D0D5DD (Grey/300 from kit)

Brand Primary (Alternate Accent): #444CE7 (Primary/800 from kit)

Semantic Green: #12B76A (Green/500 - for success states)

Semantic Red: #F04438 (Red/500 - for error states)

3. Typography (Updated from Style Kit)

Typography is based on the provided style kit.

Font Family (--font-family-sans): "Inter", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif

Font Weights: Regular (400), Medium (500), Semibold (600), Bold (700)

Code Font Family: "Source Code Pro", monospace

Font Sizing & Line Height:

H1: 80px / 120%

H2: 64px / 120%

H3: 48px / 120%

H4: 40px / 120%

H5: 32px / 120%

Title: 24px / 150%

Subtitle: 20px / 150%

Primary Text: 15px / 160%

Secondary Text: 13.5px / 150%

Small Text: 12px / 150%

Tiny Text: 10px / 150%

4. Layout & Spacing

The layout is structured, uncluttered, and grid-based. Generous white space is critical to the professional feel.

Grid: Use a 12-column grid with standard gutters.

Container: Main content should live within a max-width container (e.g., 1280px).

Spacing: Use a consistent spacing ramp (e.g., 4px, 8px, 16px, 24px, 32px, 64px) for all margins, padding, and gaps.

Border Radius (--border-radius): Apply a consistent, subtle border-radius (e.g., 8px or 12px) to all cards, buttons, and images to soften the look.

5. Component Styling (Updated)

Buttons (CTAs):

Primary: background-color: var(--color-accent); color: var(--color-text-primary); font-weight: bold; padding: 12px 24px; border-radius: var(--border-radius). No border.

Hover: Subtle brightness/transform shift (e.g., filter: brightness(0.95) or transform: scale(1.02)).

Cards:

Used to segment features or testimonials (matching style kit examples).

background-color: var(--color-bg).

border: 1px solid var(--color-border).

border-radius: var(--border-radius) (e.g., 12px).

padding: 24px.

box-shadow: 0 4px 12px rgba(0,0,0,0.05).

Links:

Standard text links should use var(--color-text-secondary) and add an underline on hover.

Call-to-action links (e.g., "Learn More >") can use var(--color-accent) with an arrow.

6. Core Element: The Customer Lifecycle Loop

This is the main challenge: integrating the loop diagram with this vibe. It must not look like a dry, academic chart. It must feel like an active, integrated part of the product's story.

Visual Style:

The loop itself should be large, clean, and prominent.

Use var(--color-border) for the loop's path.

The path should be thick enough to be a clear visual element.

Animation: Add a subtle, continuous animation. A small dot (using var(--color-accent)) should slowly trace the path of the loop to show it's an active, continuous cycle.

Stage Labels:

Label each stage (Discovery, Awareness, etc.) clearly.

Use var(--color-text-secondary) and a slightly bolder font weight.

"Enablers" (The Interactive Part):

Hotspots: Place small, clickable hotspots directly on the loop path at each stage.

Hotspot Style: These should be small circles (+ icons or pulsing dots) using var(--color-accent) to draw the eye. They should pulse gently to invite interaction.

Interaction: On hover or click, a popover/card appears next to the hotspot.

Popover/Card Style:

Must match the site's card styling (white, bordered, rounded corners, subtle shadow).

Content:

Title: The "Enabler" (Product Feature Name) in bold.

Description: A 1-2 line description of what it does.

Measurable Uptick: A clear, data-focused benefit. This is key. (e.g., "+15% Conversion Rate"). The metric itself should be highlighted in var(--color-accent).