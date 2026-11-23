# Design: firazoscar.com

Recorded 2026-11-23 from the built v1 (`index.html`, `assets/site.css`). Direction contract: `.impeccable/surfaces/index-html.md`.

## World
A messaging thread that answers a recruiter's questions in the order they ask them. Visitor questions are white bubbles on the right; Firaz's answers are saffron bubbles on the left; section headings are centred ink chips; the CV is a document bubble; screenshots are album bubbles; navigation is the quick-reply composer pinned to the bottom. Not any real chat app's look (no app green, no doodle wallpaper, no logos).

## Tokens (light / dark)
- ground `#e4e6ea` / `#101114`; panel `#f5f6f8` / `#17191d`; line `#d3d6dc` / `#2a2d33`
- ink `#15161a` / `#ecedef`; muted `#4d515b` / `#a6aab3`
- visitor bubble `#ffffff` / `#25282e`
- saffron `#ffc629` (both themes), edge `#f2b200`, ink on saffron `#1c1500`, muted on saffron `#5a4500`
- focus ring: ink (light), saffron (dark)
- Colour strategy: committed, saffron carries most of the thread.

## Type
Archivo variable (self-hosted, subset, 46 KB). Name: weight 850, width 122%, line-height 0.94, tracking -0.025em. Headings in bubbles: 800 at 108% width. Body 16px/1.5. Tabular lining figures everywhere.

## Shape and depth
Bubbles 18px radius with a 4px "tail" corner on the speaker's side; pills for chips and small controls; elevation is one soft shadow, never border plus shadow.

## Layout
Phone: sticky chat header, contact card, thread, fixed composer (quick replies + CV). Desktop >= 1024px: 400px sticky profile panel on the left (name, pitch, facts, availability, CV and links at the bottom), thread centred on the right.

## Motion
Only the jump-to-message flash: when a quick reply targets a section, its answer bubbles pulse once (CSS `:target`). Smooth scroll. Both off under reduced motion.
