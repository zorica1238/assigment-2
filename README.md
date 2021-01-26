<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>Advanced CSS - Assignment 1</title>
    <style>

        a[href ^="https://www.google.com"] { 
	                    color: green; 
        }
        a[href ^="https://www.link-group.eu"]{
                        color: red;
        }

        p:nth-child(2n+2){
            color: red;
        }
        p:nth-child(2n+1){
            color: blue;
        }

        #first-div p::after{
            content: " - NEW";
            color: yellow;
        }
        #second-div p::after{
            content: none;
        }
        p:last-child:hover{
            font-style: italic;
            cursor: pointer;
        }
        #second-div p:last-child{
            font-style: normal;
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
