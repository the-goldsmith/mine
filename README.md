php

<!DOCTYPE html>
This line declares that the document is an HTML5 document.

php

<html>
<head>
  <title>Trust Me</title>
This opens the HTML document and the head section, which contains information about the document, such as the title of the page.

php

  <script type="text/javascript">
    function navigate() {
      document.getElementById("firstPage").style.display = "none";
      document.getElementById("secondPage").style.display = "flex";
    }
  </script>
This section includes the JavaScript code for the page. The code defines a function called navigate that sets the display property of two elements with the id's "firstPage" and "secondPage" to "none" and "flex", respectively. This causes the first page to be hidden and the second page to be displayed.

php

  <style>
    body {
      background-image: url(https://i.pinimg.com/originals/df/52/db/df52db29c82e823e2aaca009881c18bb.jpg);
      background-size: contain;
    }
    #firstPage {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    #secondPage {
      display: none;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    button {
      background-color: transparent;
      border: none;
      font-size: 70px;
      color: red;
      cursor: pointer;
  </style>
This section contains the CSS code for the page. It sets the body's background to a purple heart pattern and sets the properties of the elements with the id's "firstPage" and "secondPage". For the first page, it sets the display to "flex", the content to be centered both horizontally and vertically, and the height to the full viewport height. For the second page, it sets the display to "none", the content to be centered both horizontally and vertically, and the height to the full viewport height. It also sets the properties of the button element, including the background color, border, font size, color, and cursor.

php

</head>
<body>
  <div id="firstPage">
    <button onclick="navigate()">Trust Me💜</button>
  </div>
This opens the body of the HTML document and creates a div element with the id "firstPage". It contains a button that has the text "Trust Me💜" and triggers the navigate function when it is clicked.

php

  <div id="secondPage">
    <p style="color: Black: font-size: 56px"> I Just Realise. I am slowly falling in love With You💜 <br> and suddenly every love songs were about You🎶<br>love you PREETY CHEEKS😊
     </p>
  </div>
This creates another div element with the id "secondPage" that contains a paragraph of text. The text is displayed in a large font with a black color.
