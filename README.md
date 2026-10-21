## Sold Out

### 1. Uncomment the line for the sold-out coffee

```css
/* ¥400 */
/* #coffee-400-1 { --sold-out: block; } */
/* #coffee-400-2 { --sold-out: block; } */

/* ¥300 */
/* #coffee-300-1 { --sold-out: block; } */
/* #coffee-300-2 { --sold-out: block; } */

/* ¥200 */
/* #coffee-200-1 { --sold-out: block; } */
/* #coffee-200-2 { --sold-out: block; } */
```

### 2. Change the CSS URL to bypass the browser cache

```html
<link rel="stylesheet" href="./css/sold-out.css?v=1">
```

Increase the version number each time:

`?v=1`, `?v=2`, `?v=3`, and so on and so forth
