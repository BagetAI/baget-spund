---
version: alpha
colors:
  primary: "#1A1A1A"
  secondary: "#F5F0E6"
  accent: "#B8860B"
  neutral-dark: "#1A1A1A"
  neutral-light: "#F5F0E6"
typography:
  headings: "Söhne, sans-serif"
  body: "Inter, sans-serif"
spacing:
  xs: "0.25rem"
  sm: "0.5rem"
  md: "1rem"
  lg: "2rem"
  xl: "4rem"
rounded:
  sm: "2px"
  md: "4px"
  lg: "8px"
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.secondary}"
    padding: "{spacing.sm} {spacing.md}"
    rounded: "{rounded.sm}"
    border: "1px solid {colors.primary}"
  button-primary-hover:
    backgroundColor: "{colors.accent}"
    textColor: "{colors.primary}"
  button-secondary:
    backgroundColor: "transparent"
    textColor: "{colors.primary}"
    padding: "{spacing.sm} {spacing.md}"
    rounded: "{rounded.sm}"
    border: "1px solid {colors.primary}"
  card:
    backgroundColor: "{colors.secondary}"
    border: "1px solid {colors.primary}"
    padding: "{spacing.lg}"
    rounded: "{rounded.sm}"
---

# Spund Design Specification

The design system is engineered for Berlin's industrial-minimalist coffee culture. It bridges high-quality specialty craft with eco-conscious circular systems.

## Brand Mark Visual Rationale
- **The Tap & Oat**: Merging the technical precision of a gas/draft tap handle (Spund / Spundung) with a geometric, simplified oat kernel.
- **The Palette**: Contrast of warm oat cream (#F5F0E6) and heavy industrial charcoal (#1A1A1A) is highlighted by a rich, metallic brass accent (#B8860B) reminiscent of manual espresso group heads and custom draft columns.
