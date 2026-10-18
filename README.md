# Sera Warm Gray Theme

A warm taupe theme with 14px text and subtle rounded corners; supports light and dark modes.

Install this directory or its release archive in OpenAgent Plugins, then select Sera Warm Gray Theme in General → Appearance. Light/dark and system appearance are supported. User appearance overrides apply last.

Requires the OpenAgent theme-fonts-v1 capability. This is a Svelte/Bits UI adaptation of the upstream visual grammar; React component libraries and icon libraries are not switched by a theme. Fonts and licenses are bundled in this plugin under fonts/ and work offline; CJK glyphs use system fallbacks.

recipe.json records the upstream mix options. The sidebar interaction colors are package-owned overrides of that recipe: hover and selection share a fill with OKLCH lightness 0.90 in light mode and 0.36 in dark mode, preserving the palette chroma and hue. `--sidebar-selected` and `--sidebar-selected-foreground` explicitly reference the hover pair, so both states remain the same color while allowing independent customization. provenance.json pins the MIT-licensed shadcn source. This package contains no scripts, remote fonts, or executable stylesheets.

Publish plugin.json, recipe.json, provenance.json, fonts/, LICENSE, and this README as a GitHub release archive; keep the manifest repository and version aligned with the release.
