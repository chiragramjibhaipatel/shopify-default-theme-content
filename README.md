# Shopify Default Theme Content

Shopify's **Edit default theme content** screen lists hundreds of checkout texts with no picture of where each one appears. This page shows a real-looking Shopify checkout instead: tap any text and see the exact field behind it, what it says now, and what to search for in the language editor.

**Live:** https://shopify-default-theme-content.com/

## What it covers

- One-page and three-page checkout layouts
- Regular cart and a cart with a subscription item
- Checkout and Thank you pages
- Fields used in several places, sentences built from several fields, and text that's edited somewhere else (shipping rate names, product titles, payment provider names)

## How to use

1. Tap any text on the checkout.
2. Press **Copy key** (for example `shopify.checkout.order_summary.discount_placeholder`).
3. In Shopify admin, open **Online Store › Themes › ⋯ › Edit default theme content** and paste the key into the search box. It jumps straight to that one field.

You can type your own wording in the panel to preview it on the checkout first. The **Edits** tab collects every change, with its key, as a checklist.

## Notes

- Layout and default texts were captured from a Shopify development store with the default English (Dawn) theme content, on 30 Sep 2026.
- Fields are matched to the checkout by their text. Where several fields share the same text, the field key panel says so, and a few uncertain matches are marked **Best guess**.
- Single static page, no build step: open `index.html` in a browser.

Not affiliated with or endorsed by Shopify.
