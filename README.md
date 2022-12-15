# java-ascript
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Table Background</title>
    <style>
        #t1,#t2,#t3{
            border:2px solid black;
            padding:10px;
            margin:15px;
            font-size: 15px;
            font-weight: bold;
        }
        #t1{
            background-color: red;
        }
        #t2{
            background-color: blue;
        }
        #t3{
            background-color: green;
        }
    </style>
</head>
<body>
    <table id="t" onchange="clr()">
        <tr class="tr1">
            <td id="t1" onmouseover="document.body.style.backgroundColor='red';">Red</td>
            <td id="t2" onmouseover="document.body.style.backgroundColor='blue';">Blue</td>
            <td id="t3" onmouseover="document.body.style.backgroundColor='green';">Green</td>
        </tr>
    </table>
    
</body>
</html>
