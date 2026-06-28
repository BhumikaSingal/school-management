Stack & Structure: Use semantic HTML5 + custom CSS (no frameworks). Follow BEM naming and W3C validation.
Accessibility: WCAG 2.2 AA compliant, ARIA roles for sliders, skip-to-content, keyboard + screen reader support.
Responsiveness: It should be properly responsive to all the browsers and devices
Cross-browser: Ensure compatibility with Chrome, Firefox, Safari, Edge (latest 2 versions) + iOS/Android browsers.
Hero Section: Dual-axis slider (horizontal & vertical), auto-play, swipe, pause on hover, and accessible controls.
Participating School Logos: Continuous sling animation with alternating left–right and right–left flow; pause on hover/focus.
Choose the School: Four cards on desktop; convert to mobile slider with swipe + pagination dots.
Exhibition Section: Entire section as a slider with 3–6 highlight cards; accessible, consistent height, auto-play optional.
QA Criteria: Validate HTML/CSS, accessibility via axe, test on key devices, animations honor prefers-reduced-motion.
accessible, consistent height, auto-play optional.
QA Criteria: Validate HTML/CSS, accessibility via axe, test on key devices, animations honor prefers-reduced-motion.

 
 
Here's what's built into every section:
Hero — Dual-Axis Slider

4 slides arranged in a 2×2 grid (2 rows × 2 columns). The horizontal track slides left/right; the vertical track moves up/down independently. Auto-plays every 5 seconds with a gold progress bar, pauses on hover/focus, and has dedicated H/V arrow controls, dot indicators, a pause/play toggle, and full swipe + keyboard support.
Participating School Logos

Two rows with alternating directions — row 1 scrolls left-to-right, row 2 right-to-left — at slightly different speeds for a natural sling feel. Both rows pause when hovered or keyboard-focused. Cloned items create a seamless infinite loop.
Choose the School

4-card grid on desktop (1280px), 2-col at tablet, and converts to a swipeable single-card mobile slider with pagination dots at ≤768px.
Exhibition Slider

6 highlight cards with consistent heights, auto-play (pauses on hover/focus), prev/next arrows, dot indicators, swipe support, and responsive visible-count (3 → 2 → 1 per viewport).
Accessibility (WCAG 2.2 AA)

Skip-to-content link
All sliders use role="region" / aria-roledescription="carousel" / role="tab" dots
aria-selected, aria-pressed, aria-label on every interactive control
Keyboard navigation (Arrow keys, Tab, Enter/Space)
prefers-reduced-motion disables all auto-play and animations
