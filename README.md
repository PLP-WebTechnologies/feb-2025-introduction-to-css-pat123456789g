# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Page</title>
    
    <style>
        /* General styles */
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f4;
            text-align: center;
            margin: 0;
            padding: 0;
        }

        /* Styling header using class selector */
        .title {
            color: #333;
            font-size: 28px;
            margin-top: 20px;
        }

        /* Styling paragraph using class selector */
        .description {
            color: #555;
            font-size: 18px;
            margin: 20px;
            padding: 10px;
        }

        /* Styling image */
        .styled-image {
            width: 300px;
            border: 5px solid #000;
            border-radius: 10px;
            margin: 20px;
            padding: 5px;
        }

        /* Styling footer using ID selector */
        #main-footer {
            background-color: #222;
            color: #fff;
            padding: 15px;
            margin-top: 30px;
        }
    </style>
</head>
<body>

    <header>
        <h1 class="title">Welcome to My Styled Page</h1>
    </header>

    <section>
        <p class="description">This page is styled using internal CSS. Enjoy the layout and typography!</p>
        <img src="https://via.placeholder.com/300" alt="Sample Image" class="styled-image">
    </section>

    <footer id="main-footer">
        <p>© 2025 My Website</p>
    </footer>

</body>
</html>
