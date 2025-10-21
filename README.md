
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Profile Card</title>
<style>
  /* ====== Root Colors & Config ====== */
  :root {
    --bg-color: #0a0f1a;
    --card-bg: #000000;
    --primary: #4a4949;
    --secondary: #9a9a9a;
    --text: #fff;
    --radius: 20px;
    --transition: 0.4s ease;
  }

  body {
    margin: 0;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    background: radial-gradient(circle at top, #121a2c, #000000 80%);
    font-family: "Poppins", sans-serif;
    color: var(--text);
    background: url("https://i.pinimg.com/736x/9b/f2/52/9bf2529f6c9dd705c7bc7d1761a5d0f5.jpg") no-repeat center center/cover;
  }

  /* ====== Profile Card Container ====== */
  .profile-card {
    position: relative;
    background: var(--card-bg);
    width: 320px;
    border-radius: var(--radius);
    overflow: hidden;
    box-shadow: 0 0 30px rgba(0,0,0,0.6);
    text-align: center;
    transition: transform var(--transition), box-shadow var(--transition);
  }

  .profile-card:hover {
    transform: translateY(-10px) scale(1.03);
    box-shadow: 0 0 25px var(--primary), 0 0 50px var(--secondary);
  }

  /* ====== Banner & Avatar ====== */
  .banner {
    width: 100%;
    height: 100px;
    background: linear-gradient(135deg, var(--secondary), var(--primary));

  }

  .avatar {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    border: 4px solid var(--bg-color);
    background: url("https://files.kick.com/images/user/16649165/profile_image/conversion/8c09c6e1-39d3-4401-a8fc-7c4ea9445613-fullsize.webp") no-repeat center/cover;
    position: relative;
    top: -50px;
    margin: 0 auto;
    box-shadow: 0 0 15px var(--primary);
  }

  /* ====== Content ====== */
  .content {
    padding: 0 20px 30px;
    position: relative;
    top: -40px;
  }

  .name {
    font-size: 1.4em;
    font-weight: 700;
    letter-spacing: 0.5px;
    margin: 10px 0 5px;
  }

  .role {
    font-size: 0.9em;
    color: rgba(255,255,255,0.7);
    margin-bottom: 20px;
  }

  .bio {
    font-size: 0.85em;
    color: rgba(255,255,255,0.6);
    line-height: 1.5;
    margin-bottom: 20px;
  }

  /* ====== Social Icons ====== */
  .social {
    display: flex;
    justify-content: center;
    gap: 15px;
  }

  .social a {
    width: 38px;
    height: 38px;
    display: grid;
    place-items: center;
    background: linear-gradient(135deg, var(--primary), var(--secondary));
    border-radius: 50%;
    color: white;
    text-decoration: none;
    font-size: 18px;
    transition: 0.3s;
  }

  .social a:hover {
    transform: scale(1.15) rotate(5deg);
    box-shadow: 0 0 20px var(--primary);
  }

  /* ====== Neon Border Effect ====== */
  .profile-card::before {
    content: "";
    position: absolute;
    inset: 0;
    border-radius: var(--radius);
    padding: 2px;
    background: linear-gradient(135deg, var(--secondary), var(--primary));
    mask: linear-gradient(#fff 0 0) content-box, linear-gradient(#fff 0 0);
    mask-composite: exclude;
    -webkit-mask-composite: destination-out;
    pointer-events: none;
  }
</style>
<!-- Use Remix Icons or Font Awesome -->
<link href="https://cdn.jsdelivr.net/npm/remixicon@4.3.0/fonts/remixicon.css" rel="stylesheet">
</head>
<body>

  <div class="profile-card">
    <div class="banner"></div>
    <div class="avatar"></div>
    <div class="content">
      <h2 class="name">AguerroX9</h2>
      <p class="role">Web Developer by Virus</p>
      <p class="bio">AguerroX9 wld drif makidirch dssarat wld sskhirat 3Ndo t-roc hwa biha sskhirat kamlha ou kib9A DRI ZWIN❤️.</p>
      <div class="social">
<a  href="https://discord.gg/VJmeDUpP" target="_blank">
  <i class="ri-discord-fill"></i>
</a>


    <a href="https://www.instagram.com/agueerrox9/" target="_blank">
  <i class="ri-instagram-fill"></i>
</a>

<a href="https://kick.com/aguerrox9" target="_blank">
  <i class="ri-kick-fill"></i>
</a> 
<a href="https://www.youtube.com/@FDI-TEAM" target="_blank">
  <i class="ri-youtube-fill"></i>
</a>
      </div>
    </div>
  </div>

</body>
</html>


