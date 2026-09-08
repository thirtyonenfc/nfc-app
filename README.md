<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thirtyone Hats</title>
</head>
<body>
    <p>Abriendo Thirtyone Hats...</p>

    <script>
        const android = "https://play.google.com/store/apps/details?id=com.io.hats_31";
        const iphone = "https://apps.apple.com/us/app/thirtyone-hats/id6698876846";

        const dispositivo = navigator.userAgent || navigator.vendor || window.opera;

        if (/android/i.test(dispositivo)) {
            window.location.href = android;
        } else if (/iPhone|iPad|iPod/i.test(dispositivo)) {
            window.location.href = iphone;
        } else {
            document.body.innerHTML = `
                <h2>Thirtyone Hats</h2>
                <p>Abre este enlace desde un teléfono Android o iPhone.</p>
            `;
        }
    </script>
</body>
</html>
