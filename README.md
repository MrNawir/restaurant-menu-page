# Sushi Menu (Practice Project)

Small, hand-written looking sushi menu page used to practice basic CSS selectors.

## What this shows
- **Element selectors** like `body`, `h1`, `ul`
- **Class selectors** like `.menu-card`, `.item`
- **ID selectors** like `#nigiri`, `#maki`
- **Attribute selector** using `.unit[data-size]`
- **Pseudo-classes** like `:nth-child(even)`
- **Universal selector** `*` for box-sizing

## Tech notes
- Background is `skyblue` and cards are `aliceblue` (as requested).
- Prices are placeholder values in **KES** for now.
- Custom font included:
  ```css
  @font-face {
    font-family: 'DaddyTimeMono Nerd Font';
    src: url('DaddyTimeMonoNF.woff2') format('woff2'),
         url('DaddyTimeMonoNF.woff') format('woff');
    font-weight: normal;
    font-style: normal;
    font-display: swap;
  }
  ```

## How to run
Just open `index.html` in a browser.

## Notes
- No hover effects or “spicy/special” highlights (kept it simple on purpose).
- Layout is straightforward: stacked cards, flex used to separate names and prices.
- Swap in real prices later by editing the numbers in `index.html`.
