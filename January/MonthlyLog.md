# January 2026

## News & fixes for the website

### Pull #326 https://github.com/ruyisdk/ruyisdk-website/pull/326
- Fix layout issues when news pictures have different height/width ratios.
- Adjust article and skeleton layouts so text and thumbnails stretch consistently across aspect ratios.
- Add a `check-news-images` validation script for news image existence and basic size/aspect constraints.
- Wire the image validation script into package.json for optional strict checking.
- (Merged 2026-01-08)

### Pull #329 https://github.com/ruyisdk/ruyisdk-website/pull/329
- Optimize the mobile news page: refine typography, title/date/summary layout for better small-screen readability.
- Ensure article images render as block elements while keeping existing hover scaling behavior.
- Improve responsive behavior of news cards to reduce layout shifts on narrow viewports.

### Pull #330 https://github.com/ruyisdk/ruyisdk-website/pull/330
- Improve the subscribe form and button with consistent, responsive layout and localized copy.
- Add internationalization support for labels, placeholders, and status messages.
- Refresh visual design (gradients, shadows, focus/hover states) and replace inline styles with CSS module classes for maintainability and consistent layout across viewports.

### Pull #331 https://github.com/ruyisdk/ruyisdk-website/pull/331
- CI behaviour fix for contributor JSON file: add a CI step to detect changes to the generated contributors JSON and only run the diff check when that file changed.
- Prevent unnecessary CI failures by skipping the generated_contributors.json diff check when no relevant generation changes exist.
