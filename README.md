# A Framework

- In the same vein as Bootstrap and Foundation.
- Pure CSS.
- Based entirely on CSS variables.
- BEM class names.

## Features

- Responsive Grids and Containers
- Buttons
- SOON: Forms
- Trivial CSS for:
    - dark mode
    - narrower text containers for reading

## How to Use

In your `<head>`, in this order:

```
<link rel="stylesheet" href="a-framework/main.css">
<link rel="stylesheet" href="your-custom-settings.css">
```

## Things You Have to Do Yourself

Because we don't have the luxury of Sass.

```
/* Because can't use CSS variables in @media queries... */

@media (min-width: 576px) { /* ... */ } /* sm and up */
@media (min-width: 768px) { /* ... */ } /* md and up */
@media (min-width: 992px) { /* ... */ } /* lg and up */
@media (min-width: 1200px) { /* ... */ } /* xl and up */
@media (min-width: 1400px) { /* ... */ } /* xxl and up */

@media (max-width: 575.9375px) { /* ... */ } /* xs only */
@media (max-width: 767.9375px) { /* ... */ } /* sm and down */
@media (max-width: 991.9375px) { /* ... */ } /* md and down */
@media (max-width: 1199.9375px) { /* ... */ } /* lg and down */
@media (max-width: 1399.9375px) { /* ... */ } /* xl and down */
```
