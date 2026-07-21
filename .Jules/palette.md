## 2025-05-14 - [Making hover-activated menus keyboard accessible]
**Learning:** Menus or tooltips that only appear on hover (using `group-hover`) are inaccessible to keyboard users. Using `group-focus-within` allows these elements to become visible when any child element receives focus, ensuring accessibility.
**Action:** Always pair `group-hover` with `group-focus-within` for interactive menus and popovers.
