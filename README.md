# readme03

# WHAT IS HTML Layout

Page layout is the part of graphic design that deals with the arrangement of visual elements on a page. Page layout is used to make the web pages look better. It establishes the overall appearance, relative importance, and relationships between the graphic elements to achieve a smooth flow of information and eye movement for maximum effectiveness or impact
HTML Layout Elements
•  header> - Defines a header for a document or a section 
•  <nav> - Defines a set of navigation links 
•  <section> - Defines a section in a document 
•  <article> - Defines an independent, self-contained content 
•  <aside> - Defines content aside from the content (like a sidebar) 
•  <footer> - Defines a footer for a document or a section 
•  <details> - Defines additional details that the user can open and close on demand 
•  <summary> - Defines a heading for the <details> element
 
 ![alt text](https://media.geeksforgeeks.org/wp-content/uploads/layout.png)
  
  
Page Layout Information:
•	Header: The part of a front end which is used at the top of the page. <header> tag is used to add header section in web pages.
•	Navigation bar: The navigation bar is same as menu list. It is used to display the content information using hyperlink.
•	Index / Sidebar: It holds additional information or advertisements and is not always necessary to be added into the page.
•	Content Section: The content section is the main part where content is displayed.
•	Footer: The footer section contains the contact information and other query related to web pages. The footer section always put on the bottom of the web pages. The <footer> tag is used to set the footer in web pages.
Example:
<!DOCTYPE html>
<html>
<head>
    <title>Page Layout</title>
    <style>
        .head1 {
            font-size:40px;
            color:#009900;
            font-weight:bold;
        }
        .head2 {
            font-size:17px;
            margin-left:10px;
            margin-bottom:15px;
        }
        body {
            margin: 0 auto;
            background-position:center;
            background-size: contain;
        }
      
        .menu {   
            position: sticky;
            top: 0;
            background-color: #009900;
            padding:10px 0px 10px 0px;
            color:white;
            margin: 0 auto;
            overflow: hidden;
        }
        .menu a {
            float: left;
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
            font-size: 20px;
        }
        .menu-log {
            right: auto;
            float: right;
        }
        footer {
            width: 100%;
            bottom: 0px;
            background-color: #000;
            color: #fff;
            position: absolute;
            padding-top:20px;
            padding-bottom:50px;
            text-align:center;
            font-size:30px;
            font-weight:bold;
        }
        .body_sec {
            margin-left:20px;
        }
    </style>
</head>
  
<body>
      
    <!-- Header Section -->
    <header>
        <div class="head1">GeeksforGeeks</div>
        <div class="head2">A computer science portal for geeks</div>
    </header>
      
    <!-- Menu Navigation Bar -->
    <div class="menu">
        <a href="#home">HOME</a>
        <a href="#news">NEWS</a>
        <a href="#notification">NOTIFICATIONS</a>
        <div class="menu-log">
            <a href="#login">LOGIN</a>
        </div>
    </div>
      
    <!-- Body section -->
    <div class = "body_sec">
        <section id="Content">
            <h3>Content section</h3>
        </section>
    </div>
      
    <!-- Footer Section -->
    <footer>Footer Section</footer>
</body>
</html>                    
