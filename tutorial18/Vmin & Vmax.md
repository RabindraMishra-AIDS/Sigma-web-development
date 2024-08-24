Vmin and Vmax are the concepts that depending on desktop size.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Em sizing</title>
    <style>
        .box{
            width: 100Vmin;                              /*100vh*/
        }
        .container{
            margin: 20px;
            margin:23px  auto;
            background-color: beige;
            border: 2px solid black ;
            font-size: 20px;
            width: 100vw;
            height: 20vh;
        }
        .container p{
            font-size: 1.5em;
            color: brown;
        }
    </style>
</head>
<body>
    <div class="box">
        This is a box
    </div>
    <div class="container">
        <p>Hello em sizing.</p>
        Rabindra Mishra ipsum dolor sit amet consectetur adipisicing elit. Ducimus at repellat sequi eligendi neque!.
    </div>
</body>
</html>

