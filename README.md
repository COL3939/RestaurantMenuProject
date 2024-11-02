/* Reset default margin and padding */
* { margin: 0; padding: 0; box-sizing: border-box; }

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f9;
}

header {
    text-align: center;
    padding: 1em;
    background-color: #4CAF50;
    color: white;
}

.menu {
    list-style-type: none;
    display: flex;
    justify-content: center;
    background-color: #333;
}

.menu li {
    margin: 0 1em;
}

.menu li a {
    display: block;
    padding: 1em;
    color: white;
    text-decoration: none;
}

.menu li a:hover {
    background-color: #4CAF50;
}

main {
    text-align: center;
    padding: 2em;
}
