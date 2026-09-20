# Fixed Rule: Mobile View Optimization & Desktop Preservation

## 1. Full Mobile Optimization
Every page and section across the website must be fully optimized for all standard mobile display sizes (e.g., 320px, 360px, 375px, 390px, 412px, 430px up to 768px tablet):
- No horizontal scrolling or content clipping (`overflow-x: hidden` clean layout).
- Proper line heights, font clamps, and padding on touch screens.
- All interactive elements, carousels, 3D books, grids, cards, lightboxes, and modals must scale and operate smoothly on mobile touchscreens.

## 2. Default Mobile Optimization for Future Work
From this point forward, every section added to the website or any code modification done must by default be fully optimized for mobile devices without requiring extra reminders.

## 3. Desktop View Preservation
Do NOT make breaking changes to any current feature, sizing, typography, or styling in the desktop view. All mobile enhancements must be implemented via scoped media queries (e.g., `@media (max-width: 768px)`, `@media (max-width: 600px)`, `@media (max-width: 480px)`) so that desktop remains 100% untouched.
