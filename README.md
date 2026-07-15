# Font-Awesome-Pro-Free

![thumbnail](<./Font Awesome Pro Free Thumbnail.png>)

Automatically obtain the latest Pro CDN of Font Awesome icons for free (for educational purpose and personal testing only)

## Author's Note

This small automated project was created for educational purposes only. This was created to practice and play with GitHub Actions. This repository was publicized as a demonstration and example of GitHub Actions's automation for you to peek at the code, as well as previewing the icons before buying Pro.

Only use this for personal testing or previewing the way your websites look with the icons before paying the premium ("free trial"). Do support Font Awesome and buy their Pro plan here if you can afford it!  
<https://fontawesome.com/plans>

## Usage

Latest release: v7.3.1

```html
    <link rel="stylesheet" href="https://site-assets.fontawesome.com/releases/v7.3.1/css/all.css">
```

Some icon families may not work with the `all.css`, try using the specific family (scroll down)

To obtain an individual icon's svg directly:

```
https://site-assets.fontawesome.com/releases/v7.3.1/svgs-full/{icon-family}-{style}/{icon-name}.svg
```

```
https://site-assets.fontawesome.com/releases/v7.0.1/svgs/{icon-family}-{style}/{icon-name}.svg
```

Note:

* List of available icon families and their styles: <https://docs.fontawesome.com/web/dig-deeper/styles>
* Replace `{icon-family}` with the `kebab-case` form of an icon family, in lowercase
  * Exception: Classic: `classic-` is omitted
    * e.g Classic, Solid, globe-stand: `https://site-assets.fontawesome.com/releases/v7.0.1/svgs-full/solid/globe-stand.svg`
* Replace `{style}` with a family's style, in lowercase
  * Exception: Duotone Solid: `-solid` is omitted
    * e.g Duotone, Solid, globe-stand: `https://site-assets.fontawesome.com/releases/v7.0.1/svgs-full/duotone/globe-stand.svg`
* Replace `{icon-name}` with the icon name found in FA's website
* Example: Sharp Duotone, Light, global-stand: `https://site-assets.fontawesome.com/releases/v7.0.1/svgs/sharp-duotone-light/globe-stand.svg`

<details>
<summary>Classic</summary>

```html
    <link rel="stylesheet" href="https://site-assets.fontawesome.com/releases/v7.3.1/css/solid.css">
    <link rel="stylesheet" href="https://site-assets.fontawesome.com/releases/v7.3.1/css/regular.css">
    <link rel="stylesheet" href="https://site-assets.fontawesome.com/releases/v7.3.1/css/light.css">
    <link rel="stylesheet" href="https://site-assets.fontawesome.com/releases/v7.3.1/css/thin.css">
```

</details>

<details>
<summary>Duotone</summary>

```html
    <link rel="stylesheet" href="https://site-assets.fontawesome.com/releases/v7.3.1/css/duotone.css">
    <link rel="stylesheet" href="https://site-assets.fontawesome.com/releases/v7.3.1/css/duotone-regular.css">
    <link rel="stylesheet" href="https://site-assets.fontawesome.com/releases/v7.3.1/css/duotone-light.css">
    <link rel="stylesheet" href="https://site-assets.fontawesome.com/releases/v7.3.1/css/duotone-thin.css">
```

</details>

<details>
<summary>Sharp</summary>

```html
    <link rel="stylesheet" href="https://site-assets.fontawesome.com/releases/v7.3.1/css/sharp-solid.css">
    <link rel="stylesheet" href="https://site-assets.fontawesome.com/releases/v7.3.1/css/sharp-regular.css">
    <link rel="stylesheet" href="https://site-assets.fontawesome.com/releases/v7.3.1/css/sharp-light.css">
    <link rel="stylesheet" href="https://site-assets.fontawesome.com/releases/v7.3.1/css/sharp-thin.css">
```

</details>

<details>
<summary>Sharp Duotone</summary>

```html
    <link rel="stylesheet" href="https://site-assets.fontawesome.com/releases/v7.3.1/css/sharp-duotone-solid.css">
    <link rel="stylesheet" href="https://site-assets.fontawesome.com/releases/v7.3.1/css/sharp-duotone-regular.css">
    <link rel="stylesheet" href="https://site-assets.fontawesome.com/releases/v7.3.1/css/sharp-duotone-light.css">
    <link rel="stylesheet" href="https://site-assets.fontawesome.com/releases/v7.3.1/css/sharp-duotone-thin.css">
```

</details>

<details>
<summary>Brands</summary>

```html
    <link rel="stylesheet" href="https://site-assets.fontawesome.com/releases/v7.3.1/css/brands.css">
```

</details>

<details>
<summary>Chisel</summary>

```html
    <link rel="stylesheet" href="https://site-assets.fontawesome.com/releases/v7.3.1/css/chisel-regular.css">
```

</details>

<details>
<summary>Etch</summary>

```html
    <link rel="stylesheet" href="https://site-assets.fontawesome.com/releases/v7.3.1/css/etch-solid.css">
```

</details>

<details>
<summary>Jelly</summary>

```html
    <link rel="stylesheet" href="https://site-assets.fontawesome.com/releases/v7.3.1/css/jelly-regular.css">
    <link rel="stylesheet" href="https://site-assets.fontawesome.com/releases/v7.3.1/css/jelly-duo-regular.css">
    <link rel="stylesheet" href="https://site-assets.fontawesome.com/releases/v7.3.1/css/jelly-fill-regular.css">
```

</details>

<details>
<summary>Notdog</summary>

```html
    <link rel="stylesheet" href="https://site-assets.fontawesome.com/releases/v7.3.1/css/notdog-solid.css">
    <link rel="stylesheet" href="https://site-assets.fontawesome.com/releases/v7.3.1/css/notdog-duo-solid.css">
```

</details>

<details>
<summary>Slab</summary>

```html
    <link rel="stylesheet" href="https://site-assets.fontawesome.com/releases/v7.3.1/css/slab-regular.css">
    <link rel="stylesheet" href="https://site-assets.fontawesome.com/releases/v7.3.1/css/slab-press-regular.css">
```

</details>

<details>
<summary>Thumprint</summary>

```html
    <link rel="stylesheet" href="https://site-assets.fontawesome.com/releases/v7.3.1/css/thumbprint-light.css">
```

</details>

<details>
<summary>Whiteboard</summary>

```html
    <link rel="stylesheet" href="https://site-assets.fontawesome.com/releases/v7.3.1/css/whiteboard-semibold.css">
```

</details>
