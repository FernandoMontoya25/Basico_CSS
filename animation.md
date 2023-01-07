```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="./css/style.css">
</head>
<body>
    <div class="wrapper">
        <p>Coding is</p>
        <div class="words">
            <span>increible</span>
            <span>intresting</span>
            <span>stunning</span>
            <span>fantastic</span>
        </div>
    </div>
</body>
</html>
```
````css
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-size: 30px;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}
body{
    height: 100vh;
    margin: 0px;
    padding: 0px;
    background-color: #7369f5;
    display: flex;
    justify-content: center;
    align-items: center;
}
.wrapper{
    box-sizing: content-box;
    padding: 50px 30px;
    border-radius: 17px;
    display: flex;
    background: #968ff7;
    box-shadow: 0px 12px 27px #000;
}
.words{
    overflow: hidden;
    height: 50px;
}
span{
    display: flex;
    height: 100%;
    padding-left: 7px;
    animation: spin 6s infinite;
}
@keyframes spin {
    10%{transform: translateY(-112%);}
    25%{transform: translateY(-100%);}
    35%{transform: translateY(-212%);}
    50%{transform: translateY(-200%);}
    60%{transform: translateY(-312%);}
    75%{transform: translateY(-300%);}
    85%{transform: translateY(-412%);}
    100%{transform: translateY(-400%);}
}
```
