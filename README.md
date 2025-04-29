<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        #box {
            width: 150px;
            height: 150px;
            background: lightblue;
            transition: 0.5s;
        }
    </style>
</head>
<body>

<div id="box"></div>

<script>
    let rotated = false;
    document.getElementById("box").onclick = function() {
        rotated = !rotated;
        this.style.transform = rotated ? "rotate(180deg)" : "rotate(0deg)";
    };
</script>

</body>
</html>
