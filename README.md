# Fizz
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Fizz</title>
</head>
<body>
<h1>Expected Output</h1>
<div id="results"></div>

<script type = "text/javascript">
var div = document.getElementById('results');
    for (var i=1; i <= 100; i++)
    {
        if(i % 3 === 0){

            div.innerHTML = div.innerHTML   + "Fizz";
            div.innerHTML = div.innerHTML   + "<br/>";
        }else{

            div.innerHTML = div.innerHTML   + i;
            div.innerHTML = div.innerHTML   + "<br/>";
        }

    }
</script>
</body>
</html>
