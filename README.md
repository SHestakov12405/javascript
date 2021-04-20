<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
    <script>
        $( document ).ready(function() {
        var ul = document.createElement('ul');
        ul.innerHTML = '<li>Hello, world!</li>';
        
        var ob = document.getElementById('obj');
        ob.appendChild(ul);
        });
        </script>
    
    <!-- <script src="script3.js"></script> -->
    <!-- <script src="script2.js"></script> -->
    <!-- <script src="script.js"></script> -->
</head>
<body>
    <button class="button"><script src="script5.js"></script> </button>
</body>
</html>
