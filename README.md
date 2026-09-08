<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Thirtyone Hats</title>

<script>
window.onload = function() {

    var userAgent = navigator.userAgent || navigator.vendor;

    if (/android/i.test(userAgent)) {
        window.location.replace("https://play.google.com/store/apps/details?id=com.io.hats_31");
    } 
    else if (/iPhone|iPad|iPod/i.test(userAgent)) {
        window.location.replace("https://apps.apple.com/us/app/thirtyone-hats/id6698876846");
    }

};
</script>

</head>

<body>
<h2>Thirtyone Hats</h2>
<p>Abriendo la aplicación...</p>
</body>
</html>
