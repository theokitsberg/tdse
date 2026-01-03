# tdse Landing Page

A simple, elegant landing page for "the doing society of earth".

## Font Setup

This page uses **Tiempos Headline** font. Since this is a premium font from Commercial Type, you'll need to:

1. **Purchase a web license** from [Commercial Type](https://commercialtype.com/catalog/tiempos/tiempos_headline)
2. **Add the font files** to your project
3. **Update the CSS** to include the font files

### How to add Tiempos Headline font:

Once you have the font files, create a `fonts` folder and add this CSS at the top of your `<style>` section:

```css
@font-face {
    font-family: 'Tiempos Headline';
    src: url('fonts/TiemposHeadline-Regular.woff2') format('woff2'),
         url('fonts/TiemposHeadline-Regular.woff') format('woff');
    font-weight: normal;
    font-style: normal;
}

@font-face {
    font-family: 'Tiempos Headline';
    src: url('fonts/TiemposHeadline-RegularItalic.woff2') format('woff2'),
         url('fonts/TiemposHeadline-RegularItalic.woff') format('woff');
    font-weight: normal;
    font-style: italic;
}
```

### Fallback Font

The page currently uses Georgia as a fallback serif font until you add the Tiempos Headline files.

## Colors

- Background: `#F3DEBC` (RGB: 243, 222, 188)
- Header: `#445B32` (RGB: 68, 91, 50)
- Text: Black

## Viewing the Page

Simply open `index.html` in your web browser to view the landing page.

