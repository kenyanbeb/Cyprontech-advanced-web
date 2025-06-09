<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>News Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>News Portal</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">World</a></li>
                <li><a href="#">Business</a></li>
                <li><a href="#">Politics</a></li>
                <li><a href="#">About</a></li>
            </ul>
        </nav>
    </header>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    background-color: #121212;
    color: #ffffff;
    margin: 0;
    padding: 0;
}

header {
    background-color: #1f1f1f;
    padding: 20px;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: #ffffff;
    text-decoration: none;
}

main {
    display: flex;
    padding: 20px;
}

.latest-news, .featured {
    flex: 2;
    margin-right: 20px;
}

.latest-news h2, .featured h2 {
    border-bottom: 2px solid #ffffff;
    padding-bottom: 10px;
}

article {
    background-color: #1f1f1f;
    padding: 15px;
    margin: 10px 0;
    border-radius: 5px;
}

aside {
    flex: 1;
    background-color: #1f1f1f;
    padding: 20px;
    border-radius: 5px;
}

footer {
    background-color: #1f1f1f;
    text-align: center;
    padding: 10px;
    margin-top: 20px;
}
