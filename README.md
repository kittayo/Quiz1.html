<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Webpage Title</title>
    <style>
        body {
    margin: 0;
    padding: 0;
}
header {
    height: 50px;
    background-color: #bef107;
    color: #000;
    text-align: center;
    line-height: 50px;
}
main {
    min-height: 650px;
    width: 100%;
    display: flex;
}
.left-page {
    width: 15%;
    background-color: #ccecff;
}
.center-page {
    width: 70%;
    background-color: #FFFFCC;
    /* Add content for the center page here */
}
.right-page {
    width: 15%;
    background-color: #18cf18;
    /* Add content for the right page here */
}
footer {
    height: 50px;
    background-color: #0dc3ec;
    color: #000;
    text-align: center;
    line-height: 50px;
}
    </style>
</head>

<body>
    <header>
        Front End Quiz 1
    </header>
    <main>
        <div class="left-page">
            Left page
            <table border="1">
                <tr>
                    <td><a href="https://www.google.com/" target="_blank">Link 1</a></td>
                </tr>
                <tr>
                    <td><a href="https://www.google.com/" target="_blank">Link 2</a></td>
                </tr>
                <tr>
                    <td><a href="https://www.google.com/" target="_blank">Link 3</a></td>
                </tr>
                <tr>
                    <td><a href="https://www.google.com/" target="_blank">Link 4</a></td>
                </tr>
            </table>
        </div>
        <div class="center-page">
            Body page
            </div>
        <div class="right-page">
            Rigth page
            <img src="https://cdn-icons-png.flaticon.com/512/3135/3135715.png"width="200" height="200">
            </div>
    </main>
    <footer>
        Footer
    </footer>
</body>
</html>
