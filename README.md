<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Navigation</title>
    <style>
        .navbar {
            background-color: rgb(0, 0, 0);
            border-radius: 4px;
        }

        .navbar ul {
            overflow: auto;
        }

        .navbar li {
            float: left;
            list-style: none;
            margin: 13px 20px;
        }

        .navbar li a {
            padding: 3px 3px;
            text-decoration: none;
            color: white;
        }

        .navbar li a:hover {
            color: cornflowerblue;
        }

        .search {
            float: left;
            color: white;
            padding: 12px 75px;
        }

        .navbar input {
            border: 2px solid black;
            border-radius: 8px;
            padding: 6px 243px;
        }
    </style>
</head>

<body>
    <header>
        <nav class="navbar">
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Shopping</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Contact Us</a> </li>
                <div>
                    <input type="text" name="search" id="search" placeholder="search this website">
                </div>
            </ul>
        </nav>
    </header>
  <h1>myShopppingCart</h1>
  <p>This is a website based on cart view just like amazon and flipkart. The technologies used are Mongodb as a database, Express and Nodejs.
The second project is based on python where we srcape the data and we can query using the natural languge(ENGLISH) to the data base</p>
</body>

</html>
