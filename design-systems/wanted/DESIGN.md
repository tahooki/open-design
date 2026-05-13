# Wanted

> Category: Internal
> Wanted Lab Design System for Web. Clean career-product UI with precise blue actions, cool-neutral surfaces, Pretendard typography, soft translucent controls, and dense but readable content patterns.

## 1. Visual Theme & Atmosphere

Wanted is a modern career and work-product design system: crisp, trustworthy, service-oriented, and optimized for Korean, English, and Japanese text. It should feel like a polished production web and mobile product, not a decorative marketing page.

The visual tone is clean and slightly rounded. Use white and cool-neutral backgrounds, subtle borders, soft fills, and a clear blue primary action. Surfaces should feel light, calm, and structured. Use translucency and blur only for controls that need a soft floating feel, such as assistive buttons, text fields, search fields, and iOS-like navigation.

Prefer practical product layouts: job lists, profile cards, company cards, filters, tables, forms, dashboards, onboarding steps, modals, bottom sheets, and navigation bars. The system should be content-first with a strong scan hierarchy.

Key characteristics:
- Primary blue action color `#0066FF`.
- Cool-neutral text and line system built from `#171719`, `#70737C`, `#C2C4C8`, `#F4F4F5`, `#F7F7F8`, and white.
- Rounded controls with 8px, 10px, and 12px radii.
- Pretendard-based typography with compact Korean-friendly line heights.
- Mobile and desktop product patterns with responsive breakpoints.
- Functional components over ornamental graphics.

## 2. Color Palette & Roles

Use these tokens as the authoritative palette. Do not invent random colors when one of these fits.

### Core Brand

- **Primary Brand / Blue 50:** `#0066FF` - primary CTAs, selected states, focused borders, links, progress, active steps.
- **Primary Strong / Blue 45:** `#005EEB` - stronger blue state.
- **Primary Heavy / Blue 40:** `#0054D1` - pressed or highest-emphasis blue in light mode.
- **Inverse Primary / Blue 60:** `#3385FF` - primary action on dark or inverse surfaces.
- **Primary Soft / Blue 95:** `#EAF2FE` - pale blue backgrounds and calm highlights.
- **Primary Pale / Blue 99:** `#F7FBFF` - very light brand-tinted surface.

### Static

- **Static White:** `#FFFFFF`
- **Static Black:** `#000000`

### Light Theme Semantics

- **Page Background:** `#FFFFFF`
- **Foreground:** `#171719`
- **Alternative Background:** `#F7F7F8`
- **Elevated Background:** `#FFFFFF`
- **Elevated Alternative:** `#F7F7F8`
- **Text Normal:** `#171719`
- **Text Strong:** `#000000`
- **Text Neutral:** `#2E2F33` at 88% opacity.
- **Text Alternative:** `#37383C` at 61% opacity.
- **Text Assistive:** `#37383C` at 28% opacity.
- **Text Disabled:** `#37383C` at 16% opacity.
- **Line Normal:** `#70737C` at 22% opacity.
- **Line Neutral:** `#70737C` at 16% opacity.
- **Line Alternative:** `#70737C` at 8% opacity.
- **Solid Line Normal:** `#E1E2E4`
- **Solid Line Neutral:** `#EAEBEC`
- **Solid Line Alternative:** `#F4F4F5`
- **Border Neutral:** `#E1E2E4`
- **Fill Normal:** `#70737C` at 8% opacity.
- **Fill Strong:** `#70737C` at 16% opacity.
- **Fill Alternative:** `#70737C` at 5% opacity.
- **Interaction Inactive:** `#989BA2`
- **Interaction Disabled:** `#F4F4F5`
- **Dimmer:** `#171719` at 52% opacity.

### Dark Theme Semantics

- **Dark Page Background:** `#1B1C1E`
- **Dark Alternative Background:** `#0F0F10`
- **Dark Elevated Background:** `#212225`
- **Dark Elevated Alternative:** `#141415`
- **Dark Text Normal:** `#F7F7F8`
- **Dark Text Strong:** `#FFFFFF`
- **Dark Text Neutral:** `#C2C4C8` at 88% opacity.
- **Dark Text Alternative:** `#AEB0B6` at 61% opacity.
- **Dark Line Normal:** `#70737C` at 32% opacity.
- **Dark Solid Line Normal:** `#37383C`
- **Dark Fill Normal:** `#70737C` at 22% opacity.

### Status

- **Positive:** `#00BF40` in light mode, `#1ED45A` in dark mode.
- **Cautionary:** `#FF9200` in light mode, `#FFA938` in dark mode.
- **Negative:** `#FF4242` in light mode, `#FF6363` in dark mode.

### Accent Palette

Use accents for badges, category markers, charts, or small supporting signals. The main product should still be neutral plus primary blue.

- **Signal Red Orange:** `#FF5E00`
- **Signal Lime:** `#58CF04`
- **Signal Cyan:** `#00BDDE`
- **Signal Light Blue:** `#00AEFF`
- **Signal Violet:** `#6541F2`
- **Signal Purple:** `#CB59FF`
- **Signal Pink:** `#F553DA`
- **Signal Red Text:** `#E52222`
- **Signal Green Text:** `#009632`
- **Signal Orange Text:** `#D17600`
- **Signal Blue Text:** `#005EEB`

### Color Use Rules

- Primary blue is for user action, current state, and focus. Use it sparingly and confidently.
- Keep most UI neutral: white, cool-neutral 99/98/97 surfaces, and low-opacity line tokens.
- Use pale fills instead of heavy borders when grouping related controls.
- Use red only for destructive or error states.
- Avoid purple-blue gradients, brand mashups, decorative color clouds, and saturated multi-color backgrounds.

## 3. Typography Rules

Use Wanted Sans / Pretendard-style typography. If the exact font is unavailable, use this fallback stack:

`"Wanted Sans Variable", "Wanted Sans", "Pretendard JP", "Pretendard", -apple-system, BlinkMacSystemFont, system-ui, "Segoe UI", "Apple SD Gothic Neo", "Noto Sans KR", "Malgun Gothic", sans-serif`

Typography must support Korean, English, and Japanese. Keep Korean text readable and let it wrap naturally by syllable where appropriate.

### Type Scale

| Token | Size | Line Height | Letter Spacing | Use |
|---|---:|---:|---:|---|
| `display1` | 56px | 72px | -0.0319em | Rare hero display only |
| `display2` | 40px | 52px | -0.0282em | Large campaign title |
| `display3` | 36px | 48px | -0.027em | Large page title |
| `title1` | 32px | 44px | -0.0253em | Page title |
| `title2` | 28px | 38px | -0.0236em | Section title |
| `title3` | 24px | 32px | -0.023em | Section title / card title |
| `heading1` | 22px | 30px | -0.0194em | Panel heading |
| `heading2` | 20px | 28px | -0.012em | Subsection heading |
| `headline1` | 18px | 26px | -0.002em | Emphasized row title |
| `headline2` | 17px | 24px | 0 | Compact heading |
| `body1` | 16px | 24px | 0.0057em | Default body and form text |
| `body1-reading` | 16px | 26px | 0.0057em | Long-form readable copy |
| `body2` | 15px | 22px | 0.0096em | Secondary body |
| `body2-reading` | 15px | 24px | 0.0096em | Dense paragraphs |
| `label1` | 14px | 20px | 0.0145em | Labels, chips, metadata |
| `label1-reading` | 14px | 22px | 0.0145em | Small readable text |
| `label2` | 13px | 18px | 0.0194em | Badges, compact labels |
| `caption1` | 12px | 16px | 0.0252em | Captions |
| `caption2` | 11px | 14px | 0.0311em | Micro captions |

### Weights

- **Regular:** 400
- **Medium:** 500
- **Bold:** 700 for display/title sizes, 600 for smaller UI text.
- Primary buttons generally use bold text.
- Assistive buttons generally use medium text.

### Typography Principles

- Use `title1` or `title2` for page-level headings, not oversized hero text unless the artifact is explicitly a landing page.
- Use `body1` for form fields and primary copy.
- Use `body2`, `label1`, and `label2` for dense product metadata.
- Keep hierarchy subtle: size, weight, and color should work together.
- Do not overuse uppercase. This system is sentence-case and product-native.

## 4. Spacing, Grid & Layout

### Spacing Scale

Use the WDS spacing scale:

`0`, `0.5`, `1`, `2`, `4`, `6`, `8`, `10`, `12`, `14`, `16`, `20`, `24`, `32`, `40`, `48`, `56`, `64`, `72`, `80`.

Default rhythm:
- 4px for tiny internal offsets.
- 6px to 8px for compact inline gaps.
- 10px to 12px for control padding.
- 16px to 20px for card internals and list rows.
- 24px to 32px for panel gaps.
- 40px to 64px for major page sections.

### Breakpoints

- **xs:** `0px`
- **sm:** `768px`
- **md:** `992px`
- **lg:** `1200px`
- **xl:** `1600px`

### Layout Patterns

- Desktop product pages should use a centered content width with clear sections and predictable side navigation when needed.
- Documentation or admin surfaces can use a top global navigation plus left local navigation.
- Mobile flows should prioritize top navigation, bottom navigation, bottom sheets, full-width action areas, and single-column cards.
- Use content cards and list rows for repeated items. Avoid nested cards.
- Prefer `FlexBox` and `Grid` style layouts with fixed gaps from the spacing scale.
- Keep tables dense but readable; align numbers and statuses for scanning.

### Container Rules

- Default page canvas is white or `#F7F7F8`.
- Cards and elevated panels are white in light mode and cool-neutral elevated surfaces in dark mode.
- Use 1px cool-neutral lines or low-opacity fills to separate groups.
- Do not rely on decorative backgrounds to create hierarchy.

## 5. Component Stylings

### Buttons

Use two variants: `solid` and `outlined`. Use two colors: `primary` and `assistive`.

Large button:
- Radius: 12px
- Padding: 12px 28px
- Gap: 6px
- Text: `body1`, bold for primary, medium for assistive.
- Icon: 20px; icon-only: 24px with 12px padding.

Medium button:
- Radius: 10px
- Padding: 9px 20px
- Gap: 5px
- Text: `body2`, bold for primary, medium for assistive.
- Icon: 18px; icon-only: 20px with 10px padding.

Small button:
- Radius: 8px
- Padding: 7px 14px
- Gap: 4px
- Text: `label2`, bold for primary, medium for assistive.
- Icon: 16px; icon-only: 18px with 7px padding.

Color behavior:
- Solid primary: blue fill `#0066FF`, white text.
- Solid assistive: neutral low-opacity fill, neutral text, optional 32px blur.
- Outlined primary: transparent background, blue text, 1px neutral line.
- Disabled: disabled text and disabled fill; no pointer interaction.

### Text Buttons

Use text buttons for low-friction actions inside navigation, cards, section headers, and menus. Primary text buttons use blue. Assistive text buttons use neutral text. Keep them compact and aligned to surrounding labels.

### Icon Buttons

Use icon buttons for close, search, menu, bookmark, notification, reset, navigation, and overflow actions. Prefer WDS icon shapes when representing product actions. Keep icon-only controls square, optically centered, and accessible.

### Chips

Use chips for filters, selectable tags, and compact categories.

- xsmall: 6px radius, 4px 7px padding, caption1 medium.
- small: 8px radius, 6px 8px padding, label1 medium.
- medium: 8px radius, 7px 11px padding, body2 medium.
- large: 10px radius, 9px 12px padding, body2 medium.
- Solid inactive chips use alternative fill and normal label text.
- Active chips invert to dark inverse background and inverse label.
- Outlined active chips use a pale primary-blue background and a blue 43% border.

### Content Badges

Use badges for status, metadata, counts, and content labels.

- medium: 8px radius, 7px 8px padding, label2 medium.
- small: 6px radius, 4px 6px padding, caption1 medium.
- xsmall: 6px radius, 3px 6px padding, caption2 medium.
- Neutral badges use neutral fill and neutral text.
- Accent badges use the accent foreground color with an 8% tint background and a 43% border when outlined.

### Cards

Use cards for job, company, profile, article, media, or task items.

Desktop card:
- Gap: 8px
- Thumbnail ratio: 3:2
- Thumbnail content padding: 14px
- Content padding: 0 6px
- Title: body1 bold
- Caption: label2 medium

Mobile card:
- Gap: 6px
- Thumbnail ratio: 4:3
- Thumbnail content padding: 10px
- Content padding: 0 2px
- Title: body2 bold
- Caption: label2 medium

Card hover can scale thumbnail images to 1.025 with a 0.2s ease transition. Use this only for media/listing cards, not form panels.

### Thumbnails

Use thumbnail ratios deliberately:

`1:1`, `5:4`, `4:3`, `3:2`, `16:10`, `1.618:1`, `16:9`, `2:1`, `21:9`.

Default rounded thumbnail radius is 12px. Optional thumbnail border uses the neutral line token. Images should be object-fit cover.

### Text Fields

Text fields are soft, rounded, and functional.

- Radius: 12px
- Padding: 12px
- Background: transparent white in light mode or elevated transparent surface.
- Border: inset 1px neutral line.
- Focus: inset 2px primary blue at 43% opacity.
- Invalid: inset 1px negative at 28%; focus invalid uses 2px negative at 43%.
- Text: body1 regular.
- Placeholder: body1 regular, assistive label color.
- Caret: primary blue.
- Disabled: alternative fill, alternative line, disabled placeholder.

### Search Fields

Search fields use a neutral fill and 12px radius.

- Small: 8px padding.
- Medium: 12px padding.
- Text: body1 regular.
- Search icon starts assistive, becomes alternative when focused or filled.
- Reset action appears only while focused with a value.

### Selection & Input

Use checkbox, radio, round checkbox, switch, slider, segmented control, select, date picker, time picker, text area, and filter button patterns from WDS. Selection states should use primary blue. Disabled states use cool-neutral disabled tokens.

### Navigation

Use top navigation for page title, search, back, close, confirm, or contextual actions. Use bottom navigation for mobile app-level sections. Use tabs for peer views and segmented control for mode switches. Use progress indicators or progress trackers for onboarding, multi-step application, checkout, or form completion flows.

### Feedback & Presentation

Use alert, section message, fallback view, push badge, snackbar, toast, tooltip, popover, popup, menu, modal, and bottom sheet patterns. Prefer concise copy and one clear action. Dimmed overlays use the material dimmer token.

### Tables

Tables should be dense and product-focused. Use neutral lines, body2 or label text, clear row hover, status badges, and right-aligned numeric columns. Avoid heavy table borders.

## 6. Depth, Elevation & Materials

Use subtle elevation. Do not create dramatic shadows.

Light theme elevation:
- xsmall: `0px 1px 2px -1px` with black at 10%.
- small: `0px 2px 4px -2px` and `0px 4px 6px -1px` with black at 6%.
- medium: `0px 4px 6px -2px` and `0px 10px 15px -3px` with black at 7%.
- large: `0px 6px 10px -4px` and `0px 16px 24px -6px` with black at 8%.
- xlarge: `0px 10px 15px -5px` with black at 10% plus `0px 24px 38px -10px` with black at 12%.

Use shadows for popovers, menus, modals, floating controls, and elevated overlays. Most cards should use a border or neutral fill rather than a shadow.

Translucent material:
- Use 32px blur on assistive controls, text-field wrappers, and iOS-like navigation when it improves layering.
- Do not turn whole pages into glassmorphism.

## 7. Motion & Interaction

Interaction should be subtle and quick.

- Button loading indicator is centered and inherits current color.
- Disabled controls remove pointer interaction.
- Text-field focus transitions use 0.2s ease.
- Chip color, background, and shadow transitions use 0.3s ease.
- Card thumbnail hover uses transform scale 1.025 over 0.2s ease.
- Avoid playful bounce, oversized spring motion, or continuous animation except loading/skeleton states.

Focus states must be visible. Use primary blue at partial opacity for focus rings or inset outlines.

## 8. Do

- Use the folder/system identity as `wanted`.
- Use `#0066FF` for primary actions and focused states.
- Use Pretendard / Wanted Sans fallback stack for all UI.
- Use semantic tokens: primary, label, background, line, fill, status, accent, inverse, material, elevation.
- Use compact product components: buttons, chips, badges, cards, lists, forms, tables, nav bars, bottom sheets, modals.
- Use 8px-centered spacing with the WDS scale.
- Use 12px radius for thumbnails and form fields, 8px to 10px for compact controls.
- Keep content dense but calm, with clear labels and metadata.
- Support both mobile-first and desktop product layouts.
- Use neutral fill and line tokens before introducing new surface colors.

## 9. Don't

- Do not invent colors outside the palette.
- Do not make the UI dominated by gradients, decorative blobs, or illustrative hero art.
- Do not use random purple/blue gradients as a brand substitute.
- Do not make marketing-style landing pages when the request is for a product tool.
- Do not over-round every component into pill shapes; reserve pill radii for badges and compact tags.
- Do not use heavy shadows on basic cards or form fields.
- Do not use pure black page backgrounds unless explicitly generating dark mode.
- Do not use tiny low-contrast text for important job, profile, price, status, or form information.
- Do not nest cards inside cards.
- Do not use playful consumer styling when the brief calls for recruitment, professional profile, enterprise, or admin workflows.

## Agent Prompt Guide

When generating with this design system, translate the source tokens into the artifact's own CSS variables before layout:

```css
:root {
  --wanted-primary: #0066ff;
  --wanted-primary-strong: #005eeb;
  --wanted-bg: #ffffff;
  --wanted-bg-alt: #f7f7f8;
  --wanted-surface: #ffffff;
  --wanted-text: #171719;
  --wanted-text-muted: rgba(55, 56, 60, 0.61);
  --wanted-text-assistive: rgba(55, 56, 60, 0.28);
  --wanted-line: rgba(112, 115, 124, 0.22);
  --wanted-line-neutral: rgba(112, 115, 124, 0.16);
  --wanted-fill: rgba(112, 115, 124, 0.08);
  --wanted-fill-alt: rgba(112, 115, 124, 0.05);
  --wanted-disabled: #f4f4f5;
  --wanted-positive: #00bf40;
  --wanted-warning: #ff9200;
  --wanted-negative: #ff4242;
  --wanted-font: "Wanted Sans Variable", "Wanted Sans", "Pretendard JP", "Pretendard", -apple-system, BlinkMacSystemFont, system-ui, "Segoe UI", "Apple SD Gothic Neo", "Noto Sans KR", "Malgun Gothic", sans-serif;
}
```

Build screens like a real Wanted product surface: clear navigation, tight content hierarchy, blue primary actions, neutral list/card systems, compact filters, and professional Korean-friendly typography.
