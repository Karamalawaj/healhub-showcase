# Contributing to the HealHub showcase

This repository is the public, sanitized portfolio showcase for HealHub. The private application source, credentials, Firebase rules, and production configuration are intentionally not published.

## Useful contribution areas

Contributions are welcome when they improve the public showcase without exposing private implementation details. The most useful areas are:

- accessibility and keyboard navigation
- Arabic/RTL presentation quality
- responsive layout fixes
- descriptive image alternative text
- reduced-motion support
- semantic HTML and screen-reader clarity
- broken links or deployment issues
- documentation clarity

## Current collaboration task

The live showcase needs an accessibility + Arabic RTL review. A useful contribution can include one or more of the following:

1. Add clearly visible `:focus-visible` states for interactive elements.
2. Respect `prefers-reduced-motion` for smooth scrolling and decorative motion.
3. Improve screenshot `alt` text so each image describes its purpose rather than repeating a generic label.
4. Review heading, landmark, and navigation semantics with a screen reader.
5. Add an Arabic/RTL presentation path or document the minimum RTL changes required for the public page.
6. Verify mobile layout at narrow widths and keyboard-only navigation.

## How to contribute

1. Open or claim an issue before starting a larger change.
2. Keep the change focused and explain the user-facing benefit.
3. Do not add secrets, credentials, patient data, private Firebase configuration, or proprietary application source.
4. Test the public page locally and include the viewport/browser used when reporting visual fixes.
5. If two people genuinely work on the same change, preserve accurate co-author attribution in the commit rather than adding artificial attribution.

## Definition of done

A contribution should leave the showcase easier to use, easier to evaluate, or more accessible, while keeping the repository portfolio-safe.