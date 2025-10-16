<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>গরু গবেষণা কেন্দ্র</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header>
    <h1>🐄 গরু গবেষণা কেন্দ্র</h1>
    <p>বাংলাদেশের একমাত্র গরু বিষয়ক উচ্চতর গবেষণা প্রতিষ্ঠান!</p>
  </header>

  <main>
    <section>
      <h2>আজকের গবেষণা প্রশ্ন:</h2>
      <p>গরু কেন চিপস খায় না?</p>
    </section>

    <section>
      <h2>গরুর অবদান:</h2>
      <ul>
        <li>দুধ দেয়</li>
        <li>ঘাস কমিয়ে পরিবেশ রক্ষা করে</li>
        <li>আমাদের দিকে তাকিয়ে চিন্তিত হয়ে পড়ে</li>
      </ul>
    </section>

    <section>
      <h2>গরু গান 🎵</h2>
      <audio controls>
        <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
        আপনার ব্রাউজার অডিও সাপোর্ট করে না।
      </audio>
    </section>

    <section>
      <h2>আপনি কি গরু ভালোবাসেন?</h2>
      <button onclick="alert('আপনি এখন গরুর ফ্যান ক্লাবে যোগ দিয়েছেন! 🎉')">হ্যাঁ, ভালোবাসি!</button>
    </section>
  </main>

  <footer>
    <p>&copy; ২০২৫ গরু গবেষণা কেন্দ্র | সব গরুর অধিকার সংরক্ষিত 🐮</p>
  </footer>

</body>
</html>
body {
  font-family: 'Comic Sans MS', cursive, sans-serif;
  background-color: #fffbea;
  color: #333;
  text-align: center;
  padding: 20px;
}

header {
  background-color: #ffefc1;
  padding: 20px;
  border-radius: 10px;
}

h1 {
  color: #964B00;
}

main {
  margin-top: 30px;
}

section {
  background-color: #fefefe;
  margin: 20px auto;
  padding: 15px;
  max-width: 600px;
  border: 2px dashed #ffcc00;
  border-radius: 10px;
}

button {
  padding: 10px 20px;
  font-size: 18px;
  background-color: #a3d977;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

button:hover {
  background-color: #8dc054;
}

footer {
  margin-top: 40px;
  font-size: 14px;
  color: #666;
}
<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cowzilla: দ্য মু র‍্যাপার 🐮🎤</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header>
    <h1>🐮 Cowzilla: দ্য মু র‍্যাপার 🎤</h1>
    <p>গরু শুধু ঘাস খায় না... র‍্যাপও করে!</p>
  </header>

  <main>
    <img src="https://i.imgur.com/1UeD7xC.png" alt="গরু র‍্যাপার" class="cow-img">

    <section class="rap-box">
      <h2>🎵 আজকের র‍্যাপ:</h2>
      <p>
        <strong>Cowzilla:</strong><br>
        Yo yo! আমার নাম গরু,<br>
        ঘাস খাই আর দিই গুরু!<br>
        শহরে আসি হেডফোন পরে,<br>
        মু মু করি বিটের তরে!
      </p>

      <audio controls>
        <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-2.mp3" type="audio/mpeg">
        আপনার ব্রাউজার অডিও প্লে সাপোর্ট করে না।
      </audio>
    </section>

    <section class="reaction-buttons">
      <h2>আপনার রিঅ্যাকশন কী?</h2>
      <button onclick="alert('🔥 আপনি হ্যাঁপ দিলেন Cowzilla কে!')">🔥 হ্যাঁপ দাও</button>
      <button onclick="alert('🐮 আপনি বললেন: মু~~~!')">🐮 মু বলো</button>
      <button onclick="alert('🤯 আপনি তো অবাক!')">🤯 অবাক!</button>
    </section>
  </main>

  <footer>
    <p>&copy; ২০২৫ Cowzilla Inc. | গরুর র‍্যাপ রেভ্যুলুশন 🐄🎶</p>
  </footer>

</body>
</html>

body {
  font-family: 'Comic Sans MS', cursive;
  background: #fef3ec;
  color: #333;
  text-align: center;
  padding: 20px;
}

header {
  background-color: #ffd6e0;
  padding: 20px;
  border-radius: 15px;
  box-shadow: 2px 2px 8px rgba(0,0,0,0.1);
}

h1 {
  color: #c0392b;
  font-size: 2.5em;
}

.cow-img {
  width: 250px;
  margin: 20px auto;
  display: block;
  border-radius: 10px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.2);
}

.rap-box {
  background-color: #fff;
  margin: 20px auto;
  padding: 20px;
  border: 3px dotted #ff5e5e;
  border-radius: 10px;
  max-width: 600px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

.reaction-buttons button {
  margin: 10px;
  padding: 15px 25px;
  font-size: 18px;
  border: none;
  border-radius: 10px;
  cursor: pointer;
  transition: 0.2s;
}

.reaction-buttons button:hover {
  transform: scale(1.05);
}

.reaction-buttons button:nth-child(1) {
  background-color: #ff7675;
  color: white;
}

.reaction-buttons button:nth-child(2) {
  background-color: #ffeaa7;
  color: #2d3436;
}

.reaction-buttons button:nth-child(3) {
  background-color: #74b9ff;
  color: white;
}

footer {
  margin-top: 40px;
  font-size: 14px;
  color: #555;
}
