# Graits.  
<!DOCTYPE html>
<html lang="sk">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Graits</title>
  <script>
    // Skryje splash screen po 3 sekundách
    window.addEventListener('DOMContentLoaded', () => {
      setTimeout(() => {
        document.getElementById('splash').style.display = 'none';
        document.getElementById('mainApp').style.display = 'block';
      }, 3000);
    });
  </script>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-black text-white h-screen m-0 p-0">

  <!-- Úvodná obrazovka -->
  <div id="splash" class="flex flex-col items-center justify-center h-screen relative">
    <h1 class="text-9xl font-bold">#</h1>
    <p class="absolute bottom-4 right-4 text-xs text-gray-400 lowercase">
      vytvoril sun_admin123 a jeho spoločnosť sun_master_tm
    </p>
  </div>

  <!-- Hlavná aplikácia (zatiaľ prázdna) -->
  <div id="mainApp" class="hidden">
    <h2 class="text-center text-2xl mt-10">Vitaj v aplikácii Graits!</h2>
    <!-- Sem pôjdeme ďalej: feed, reels, videá, atď. -->
  </div>

</body>
</html>
