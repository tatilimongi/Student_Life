# CSS Experiment: Font Variation and Animation

This repository contains an HTML file (`index.html`) along with its associated CSS file (`style.css`) that demonstrates the use of font variation and animation effects using CSS.

## Font Usage

The experiment utilizes the **Inconsolata** font, loaded via `@font-face` from an external source. 

```css
@font-face {
  font-family: "Inconsolata";
  src: url("https://ggayane.github.io/css-experiments/Inconsolata-VF.ttf");
  font-weight: 275 900;
  font-stretch: 50% 200%;
}
```
## CSS Styles

- **Body**: The body element is styled to have a full viewport height and width, with a dark background color (`#000119`). Text is displayed in white, with a large font size of `8em`, utilizing the Inconsolata font.

- **Main**: The `main` element is centered horizontally on the page and contains two `div` elements.

- **Static Text**: The `.static` class is applied to the static text "(im)BALANCE", which has a smaller font size (`30px`) and bold weight.

- **Variable Text**: The `.variable` class applies variable font settings for weight and width, with animation (`swapthings`) to transition between font styles.

- **Work, Life, Study**: Each of these classes applies a different color and background effect to the text. They also utilize the `swapthings2` animation for transitioning font styles.

- **Life Text**: The `.life` class applies a gradient background effect to the text, creating a colorful appearance.

- **Root Variables**: CSS custom properties (`--color-background`, `--stroke-width`, `--font-size`, `--font-weight`, `--letter-spacing`) are defined for use throughout the stylesheet.

- **Keyframe Animations**: Two keyframe animations (`swapthings` and `swapthings2`) are defined to animate font variation settings.

## HTML Structure

The HTML file (`index.html`) contains a simple structure with a `main` element containing two `div` elements. The first `div` contains text with the `.variable` class, showcasing the font variation and animation effects. The second `div` contains static text with the `.static` class.

## Usage

To view the demonstration, you have two options:

1. Open `index.html` in a web browser.
2. Alternatively, you can view the experiment hosted online by visiting [https://work-life-study.netlify.app](https://work-life-study.netlify.app). 

Feel free to experiment with the CSS styles in `style.css` to further customize the appearance and animations.
