# grid-magazine

Hosted link: https://rajkumarrj.github.io/grid-magazine/

![image](https://github.com/RajkumarRj/grid-magazine/assets/142428565/975969dc-2ed6-4ecc-9e75-dcce3b2a3efa)




The provided HTML code appears to be the structure of a web page for a magazine article. Let's break down the key components and elements of this HTML code:

1. Document Type Declaration (`<!DOCTYPE html>`): This line defines the document type and version of HTML being used, which is HTML5 in this case.

2. `<html>` Element: The root element of the HTML document, with the `lang` attribute set to "en" to indicate that the page is in English.

3. `<head>` Section: This section contains meta-information about the page that is not visible to the user. It includes:
   - Character set declaration (`<meta charset="UTF-8" />`): Specifies the character encoding used for the page.
   - Viewport meta tag (`<meta name="viewport" content="width=device-width, initial-scale=1.0" />`): Configures the viewport settings for responsive web design.
   - Page title (`<title>Magazine</title>`): Sets the title of the web page, which is displayed in the browser's title bar or tab.
   - External CSS and font resources: Links to external CSS stylesheets and fonts from Google Fonts and Font Awesome.
   - `<link rel="stylesheet" href="styles.css" />`: Links to an external CSS file named "styles.css."

4. `<body>` Element: The main content of the web page is contained within the `<body>` element. It includes:
   - `<main>` Element: Represents the main content of the page.
   - Two `<section>` elements, one with the class "heading" and the other with the class "text," to structure the content.
   - Inside the "heading" section, there's a header with a title, subtitle, and an image.
   - Information about the author and the publication date.
   - Social media icons linked to various social media profiles.

5. Content Sections: The "text" section contains the main content of the article, consisting of paragraphs and a blockquote.
6.  The paragraphs provide information about changes in the curriculum, and the blockquote emphasizes a key point.

7. "text-with-images" Section: Another section within the "main" element contains an article and an aside.
8. The article provides a brief history of the curriculum with a list of versions and descriptions. The aside includes images related to the article and a blockquote.

9. `<ul>` (Unordered List) and `<li>` (List Item) Elements: Used to create a list of versions in the article's history.

10. `<img>` Elements: Used to display images within the content.
11.  Each `<img>` element includes attributes like "src" (source URL), "alt" (alternative text), and dimensions (width and height).

This HTML code represents the structure of a magazine-style web page with headings, text content, images, and lists.
The page is styled using external CSS and uses various web fonts and icons from external sources to enhance its visual appearance and functionality.




The provided CSS code is a stylesheet that defines the styling and layout rules for the HTML content you provided earlier. Let's break down the key CSS rules and their purposes:

1. Universal Reset (`*`, `::before`, `::after`):
   - Removes padding and margin for all elements.
   - Sets the box-sizing property to "border-box" for all elements, ensuring that padding and border are included in the element's total width and height.

2. `html`:
   - Sets the base font size to 62.5% of the default font size. This is often done to make it easier to calculate font sizes using rems.

3. `body`:
   - Sets the font family to 'Baskervville', a serif font.
   - Sets the text color to "linen."
   - Sets the background color to an RGB value (dark blue).

4. Headings (`h1`, `h2`, `h3`, `h4`, `h5`, `h6`):
   - Specifies different font families for various heading levels.
   
5. Links (`a`):
   - Removes text decoration (underlines) from links.
   - Sets the link text color to "linen."

6. `main`:
   - Configures a grid layout for the main content section, with three columns: a narrow left column, a central content column, and a narrow right column.
   - Defines a row gap of 3rem between grid items.

7. Images (`img`):
   - Makes images responsive by setting their width to 100% and using "object-fit: cover" to maintain their aspect ratio.

8. Horizontal Rule (`hr`):
   - Sets margins and defines a light gray border for horizontal rules.

9. `.heading`:
   - Applies a grid layout to the "heading" section, with two equally sized columns and a row gap.
   
10. `.text`:
    - Styles the main text content within the "text" section.
    - Sets the font size, letter spacing, and column width.
    - Justifies the text.

11. `.hero`:
    - Styles the "hero" section, which contains a large image and a title.
    - Spans across the entire grid by using "grid-column: 1 / -1."

12. `.hero-title` and `.hero-subtitle`:
    - Style the title and subtitle within the "hero" section with specific font sizes and colors.

13. `.author`:
    - Styles the author information with a specific font size and font family ("Raleway").

14. `.author-name a:hover`:
    - Applies a background color change on hover for the author's name link.

15. `.publish-date`:
    - Sets a color with transparency for the publication date.

16. `.social-icons`:
    - Styles the social media icons.
    - Configures a grid layout with five columns for the icons.

17. `.first-paragraph::first-letter`:
    - Styles the first letter of the first paragraph with a larger font size, color, and float.

18. `.quote`:
    - Styles blockquotes with a specific color, font size, and font family.
    - Adds opening and closing quotation marks using `::before` and `::after` pseudo-elements.

19. `.text-with-images`:
    - Defines a grid layout for sections with text and images.
    - Uses a two-column layout with a gap between them.

20. `.lists` and `.lists li`:
    - Styles unordered lists and list items, removing default list styles and setting margins.

21. `.list-title` and `.list-subtitle`:
    - Styles list titles and subtitles with a specific color.

22. `.image-wrapper`:
    - Defines a grid layout for the image section.
    - Uses two columns and three rows, with a gap between them.
    - Centers items within the grid.

23. Media Queries:
   - Apply responsive styles based on the screen width.
   - Adjust font sizes, grid layouts, and other styles for different screen sizes.

Overall, this CSS code provides comprehensive styling for the HTML content, making it visually appealing and responsive to various screen sizes. 
It also uses custom fonts and colors to create a unique design for the web page.







