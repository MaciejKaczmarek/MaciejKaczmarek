<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Twoje Logo</title>
    <style>
        /* Stylowanie dla animacji logo */
        #logo {
            width: 100px; /* Dopasuj wielkość */
            margin: auto;
            display: block;
            animation: fadeIn 1s ease-out;
        }

        /* Animacja fadeIn */
        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }
    </style>
</head>
<body>
    <!-- Logo lub animacja -->
    <img src="URL_DO_TWOJEGO_LOGO.gif" id="logo" alt="Twoje Logo">

    <script>
        // Automatyczne przekierowanie po 3 sekundach
        setTimeout(function() {
            window.location.href = "https://www.facebook.com/TwojaStrona";
        }, 3000); // 3000 ms = 3 sekundy
    </script>
</body>
</html>
