---
version: alpha
colors:
  primary: "#1A1A1A"        # Deep Charcoal
  secondary: "#F5F0E6"      # Warm Cream
  accent: "#B8860B"         # Draft-tap Brass
  neutral-dark: "#1A1A1A"
  neutral-light: "#F5F0E6"
  neutral-muted: "#8A857B"
typography:
  headings: "Söhne, -apple-system, BlinkMacSystemFont, sans-serif"
  body: "Inter, -apple-system, BlinkMacSystemFont, sans-serif"
  size-base: "16px"
  size-lg: "20px"
  size-xl: "32px"
  size-xxl: "48px"
spacing:
  xs: "4px"
  sm: "8px"
  md: "16px"
  lg: "32px"
  xl: "64px"
rounded:
  sm: "2px"
  md: "4px"
  lg: "8px"
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.secondary}"
    border: "1px solid {colors.primary}"
    padding: "12px 24px"
    fontFamily: "{typography.body}"
    rounded: "{rounded.sm}"
  button-primary-hover:
    backgroundColor: "{colors.accent}"
    textColor: "{colors.primary}"
  button-secondary:
    backgroundColor: "transparent"
    textColor: "{colors.primary}"
    border: "1px solid {colors.primary}"
    padding: "12px 24px"
    fontFamily: "{typography.body}"
    rounded: "{rounded.sm}"
  button-secondary-hover:
    backgroundColor: "{colors.secondary}"
    textColor: "{colors.primary}"
  keg-badge:
    backgroundColor: "{colors.accent}"
    textColor: "{colors.primary}"
    padding: "6px 12px"
    rounded: "{rounded.lg}"
elevation:
  flat: "none"
  subtle: "0 2px 4px rgba(0,0,0,0.05)"
---

# Spund Brand Identity Spec

This document details the visual identity system for Spund, serving Berlin's premium specialty cafes.

## Logo System
The official Spund logo synthesizes Berlin's rugged, industrial-minimal aesthetic with the purity of high-end draft beverage systems.

- **Icon**: A unified glyph merging a draft tap head with a single, precise liquid droplet. 
- **Typography**: Wordmark set in a customized neo-grotesque sans-serif reflecting the architectural gravity of Berlin coffee culture.
- **Colorways**: Optimized for high-contrast presentation on stainless steel kegs, brass tap handles, and neutral porcelain.

## Visual Language Rules
1. **High Contrast**: Always set the warm cream (`#F5F0E6`) against the deep charcoal (`#1A1A1A`) to mimic industrial print and chalkboards.
2. **Metallic Accent**: Use the brass accent (`#B8860B`) strictly for functional focal points (draft taps, CTA highlights, active states).
3. **No Gradients**: All shapes, backgrounds, and icons must remain completely flat to uphold the raw, minimal warehouse aesthetic.
