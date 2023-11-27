<h1 align="center">Zephyr 🎐</h1>

<p align="center">
  Minimal class-less css stylesheet to make boring sites look cool!
</p>



## Usage
Zephyr doesn't intends to become a complete css component kit, it's a *css stylesheet* to make default HTML sites better

Check out the [demo](https://itz-fork.github.io/Zephyr). If you're satisfied give it a try~


**In HTML**
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/Itz-fork/Zephyr-Css@latest/Zephyr/zephyr.all.css">

<!-- Or just use what you want -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/Itz-fork/Zephyr-Css@latest/Zephyr/styles/buttons.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/Itz-fork/Zephyr-Css@latest/Zephyr/styles/card.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/Itz-fork/Zephyr-Css@latest/Zephyr/styles/text.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/Itz-fork/Zephyr-Css@latest/Zephyr/styles/form.css">
```

**In Css**
```css
@import url("https://cdn.jsdelivr.net/gh/Itz-fork/Zephyr-Css@latest/Zephyr/zephyr.all.css");

/* Again, use what you want */
@import url("https://cdn.jsdelivr.net/gh/Itz-fork/Zephyr-Css@latest/Zephyr/styles/buttons.css");
@import url("https://cdn.jsdelivr.net/gh/Itz-fork/Zephyr-Css@latest/Zephyr/styles/card.css");
@import url("https://cdn.jsdelivr.net/gh/Itz-fork/Zephyr-Css@latest/Zephyr/styles/text.css");
@import url("https://cdn.jsdelivr.net/gh/Itz-fork/Zephyr-Css@latest/Zephyr/styles/form.css");
```

## z-* helpers
These are additional data classes to make sure you don't have to touch css, unless it's necessary

Syntax: `<element data-z-*></element>`

- Buttons
  - `data-z-red`
  - `data-z-green`
  - `data-z-white`
  - `data-z-yellow`
  - `data-z-purple`
  - `data-z-blue` (accent color)

- CSS cards
  - Create a container div with `data-z-card-container`
  - Add cards with `data-z-card`

- Code blocks
  - You can add code blocks with file names like this,
  ```html
  <pre>
  <code><span>file_name.js</span>
  console.log("My code")
  </code>
  </pre>
  ```

- Text formatting
  - Center text with `data-z-center`

## Examples 👷
Take a look at [Demo Html File](https://github.com/Itz-fork/Zephyr-Css/blob/main/index.html)
