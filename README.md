<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>Advanced CSS - Assignment 1</title>
    <style>
        a[href^="https://www.google.com/"] {
            color: green;
        }

        a[target~="_blank"] {
            color: red;
        }

        #second-div p:nth-of-type(1) {
            color: red;
        }

        #second-div p:nth-of-type(2) {
            color: blue;
        }

        #second-div p:nth-of-type(3) {
            color: red;
        }

        #second-div p:nth-of-type(4) {
            color: blue;
        }

        #second-div p:nth-of-type(5) {
            color: red;
        }
        #first-div > p::after {
            content: "NEW";
            color: yellow;
        }
        body > p:last-of-type:hover {
            font-style: italic;
        }

       


    </style>
</head>

<body>
    <h1>Main Heading</h1>
    <p>Paragraph 1</p>
    <a href="https://www.google.com/">Google</a>
    <a href="https://www.google.com/doodles">Google Doodles</a>
    <a href="https://www.link-group.eu/" target="_blank">Goto Link Group</a>
    <div id="first-div">
        <h2>Subheading</h2>
        <p>Paragraph 2</p>
        <p>Paragraph 3</p>
        <div id="second-div">
            <h3>Sub subheading</h3>
            <p>Paragraph 4</p>
            <p>Paragraph 5</p>
            <p>Paragraph 6</p>
            <p>Paragraph 7</p>
            <p>Paragraph 8</p>
        </div>
    </div>
    <p>Paragraph 9</p>
    <p>Paragraph 10</p>
</body>

</html>
