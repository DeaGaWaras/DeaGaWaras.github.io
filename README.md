<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Atur bahasa ke Inggris -->
    <meta property="og:site_name" name="og:site_name" content="Calestial World">
    <meta property="og:title" name="og:title" content="Calestial Site">
    <meta property="og:description" name="og:description" content="Celestial is a team consisting of experts who have extraordinary skills.">
    <meta property="og:image" content="https://telegra.ph/file/70776cabe73e47260f47e.jpg">
    <!-- Tautkan file CSS eksternal -->
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.3.0/css/all.min.css"
  integrity="sha512-SzlrxWUlpfuzQ+pcUCosxcglQRNAq/DZjVsC0lE40xsADsfeQoEypE+enwcOiGjk/bSuGGKHEyjSoQ1zVisanQ=="
  crossorigin="anonymous" referrerpolicy="no-referrer" />
  
    <!-- Tambahkan favicon -->
    <link rel="shortcut icon" href="https://telegra.ph/file/70776cabe73e47260f47e.jpg">
    <title>Calestial.site</title>
</head>
<body>
    <!-- Latar belakang partikel -->
    <div id="particles-js"></div>
    
    <div class="center-content text-white">
        <img src="https://telegra.ph/file/989cd18fee21696db39fd.jpg" alt="Icon" class="img-fluid rounded-circle animated-icon" width="150">
        <h1 class="mt-3 animated-intro-text">Calestial Site</h1>
        <p class="mt-4 animated-intro-text">
            I'm Ward D Syah, owner of Calestial. We are committed to creating a unique and engaging web experience for you. Thank you for visiting!
        </p>
        <div style="display: flex; justify-content:center ; align-items: center;height: 100vh;">
  <div class="buttons">
    <button class="buttons__toggle"><i class="fa-solid fa-list"></i></button>
    <div class="allbtns">
      <a class="button" href="https://calestial.site"><i class="fa-brands fa-chrome"></i>Calestial World</a>
      <a class="button" href="https://chat.whatsapp.com/BC8LlVRpKUM8DRdKmVJ065"><i class="fa-solid fa-coffee"></i>Calestial Grup</a>
      <a class="button" href="https://wa.me/+62 831-1743-6733"><i class="fa-solid fa-link"></i>Owner</a>
      <a class="button" href="https://wa.me/+62 857-8524-3511"><i class="fa-solid fa-code"></i>Silver Wolf</a>
      <a class="button" href="https://instagram.com/ward_d_syah?igshid=NGVhN2U2NjQ0Yg=="><i class="fa-brands fa-instagram"></i>Instagram</a>
      <a class="button" href="https://saweria.co/calestial"><i class="fa-solid fa-credit-card"></i>Donate</a>
    </div>
  </div>
    </div>

    <!-- Tambahkan library particles.js dan script -->
   <script src="script.js"></script>
    <!-- Tambahkan library particles.js di sini -->
    <script src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
    <script>
    particlesJS("particles-js", {
        "particles": {
            "number": {
                "value": 90, // Mengubah jumlah partikel
                "density": {
                    "enable": true,
                    "value_area": 800
                }
            },
            "color": {
                "value": "#007bff" // Mengubah warna partikel menjadi biru (#007bff)
            },
            "shape": {
                "type": "circle", // Mengatur bentuk partikel menjadi bintang
                "stroke": {
                    "width": 0,
                    "color": "#ffffff"
                },
            },
            "opacity": {
                "value": 0.6, // Mengubah tingkat kejelasan partikel
                "random": true,
                "anim": {
                    "enable": true,
                    "speed": 0.5,
                    "opacity_min": 0.3,
                    "sync": false
                }
            },
            "size": {
                "value": 7, // Mengubah ukuran partikel
                "random": true,
                "anim": {
                    "enable": true,
                    "speed": 5,
                    "size_min": 0.1,
                    "sync": false
                }
            },
        },
        "interactivity": {
            "events": {
                "onhover": {
                    "enable": false, // Nonaktifkan efek saat mouse hover
                    "mode": "repulse"
                }
            },
        },
        "line_linked": {
            "enable": false // Nonaktifkan jaring-jaring
        },
    });
</script>

</body>
</html>
