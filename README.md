# greatest-number-checker
<html lang="en">
<head>
    <title>Demo5</title>
    <script>
        function findGreatest() {
            let num1 = parseInt(document.getElementById("num1").value);
            let num2 = parseInt(document.getElementById("num2").value);
            let num3 = parseInt(document.getElementById("num3").value);
            
            let max = num1;

            if (max < num2) {
                max = num2;
            }

            if (max < num3) {
                max = num3;
            }
            
            document.getElementById("result").innerHTML = max + " is Greater";
        }
    </script>
</head>

<body>
    <h1 id="header1">Welcome to JavaScript</h1>

    Enter Number-1: <input type="text" id="num1" /> <br />
    Enter Number-2: <input type="text" id="num2" /> <br />
    Enter Number-3: <input type="text" id="num3" /> <br />
    <button onclick="findGreatest()">Find Greatest</button> <br />

    <h1 id="result"></h1>
</body>

</html>
