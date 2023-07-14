# NeonButton

HTML File:
1. `<!DOCTYPE html>`: Declares the document type as HTML.
2. `<html lang="en">`: Opens the HTML document and specifies the language as English.
3. `<head>`: Begins the head section of the document, containing metadata and external resources.
4. `<meta charset="UTF-8">`: Sets the character encoding to UTF-8.
5. `<meta http-equiv="X-UA-Compatible" content="IE=edge">`: Sets the compatibility mode for Internet Explorer.
6. `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Sets the viewport properties for responsive design.
7. `<title>Neon Button</title>`: Specifies the title of the web page shown in the browser tab.
8. `<link rel="stylesheet" href="styles.css">`: Links the external CSS file named "styles.css" to the HTML document.
9. `<link rel="preconnect" href="https://fonts.googleapis.com">`: Preconnects to the Google Fonts server.
10. `<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>`: Preconnects to the Google Fonts static content server.
11. `<link href="https://fonts.googleapis.com/css2?family=Balsamiq+Sans:wght@700&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">`: Links the Google Fonts stylesheet to import the specified font families.
12. `</head>`: Closes the head section of the document.
13. `<body>`: Begins the body section of the document.
14. `<a href="#" class="neon-button">Neon</a>`: Creates an anchor element with the class "neon-button" and the text "Neon". This represents the neon button in the HTML document.
15. `</body>`: Closes the body section of the document.
16. `</html>`: Closes the HTML document.


CSS File:
1. The `:root` selector defines CSS variables `--clr-neon` and `--clr-bg` to set the neon and background colors.
2. The universal selector `*`, along with `::before` and `::after` pseudo-elements, is set to `box-sizing: border-box` to include borders and padding in the element's total width and height calculations.
3. The `body` selector sets the styling for the entire document, including center alignment, background color, font family, text color, and right padding.
4. The `.neon-button` selector defines the styling for the neon button, including font size, display as inline-block, cursor as pointer, no text decoration, neon color for text, neon color border, padding, border radius, text shadow, and box shadow.
5. The `.neon-button::before` pseudo-element is positioned absolutely and styled with a neon color background, transformed perspective, and scaled to create a glow effect.
6. The `.neon-button::after` pseudo-element is positioned absolutely and styled with a box shadow in a neon color, adding a glowing border effect.
7. The `:hover` and `:focus` pseudo-classes define the button's appearance when hovered or focused, with a neon background color, background color for text, and removal of text shadow.
8. The `:hover::before` and `:focus::before` pseudo-elements become fully visible when the button is hovered or focused, with increased opacity.
9. The `:hover::after` and `:focus::after` pseudo-elements become fully visible when the button is hovered or focused, with increased opacity.

# Output:

Onhover:


<img width="455" alt="Screenshot 2023-07-14 162622" src="https://github.com/AmishaSharma12002/NeonButton/assets/92213190/f79230d8-ecbf-4ee0-bac1-78e24915047c">


