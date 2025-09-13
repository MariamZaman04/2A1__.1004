# 2A1__.1004
Web Application Gradient project
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Welcome Page</title>
  <link rel="stylesheet" href="style.css" />

  <link href="https://fonts.googleapis.com/css2?family=Comic+Neue&display=swap" rel="stylesheet">
</head>
<body>

  <div class="container">
    <div class="text-section">
      <h1>Welcome<br>to<br>my<br>Website</h1>
      <div class="social-icons">
        <a href="https://instagram.com/" target="_blank">
          <img src="https://img.icons8.com/ios-glyphs/30/000000/instagram-new.png" alt="Instagram" />
        </a>
        <a href="https://facebook.com/" target="_blank">
          <img src="https://img.icons8.com/ios-filled/30/000000/facebook--v1.png" alt="Facebook" />
        </a>
      </div>
    </div>

    <div class="right-section">
      <div class="gradient-box">
        <button>Hello!!</button>
        <div class="circle purple"></div>
        <div class="circle green"></div>
        <div class="profile-img">
          <img src="https://www.pinterest.com/pin/1004232416920078902/" alt="Profile" />
        </div>
      </div>
    </div>
  </div>

  <div class="bottom-bar">Moriom Zaman Marzana</div>

</body>
</html>
body {
  margin: 0;
  font-family: 'Comic Neue', sans-serif;
  background: white;
}
.combo-regular {
  font-family: "Combo", system-ui;
  font-weight: 400;
  font-style: normal;
}


.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 40px;
  flex-wrap: wrap;
}

.text-section {
  flex: 1;
  padding: 20px;
}

.text-section h1 {
  font-size: 40px;
  line-height: 1.4;
  color: #668191;
  margin: 0;
}

.social-icons {
  margin-top: 20px;
}

.social-icons a {
  margin-right: 15px;
}

.social-icons img {
  width: 30px;
  height: 30px;
}

.right-section {
  flex: 1;
  display: flex;
  justify-content: center;
  align-items: center;
}

.gradient-box {
  position: relative;
  width: 300px;
  height: 300px;
  background: linear-gradient(to right, #d4f1f9, #8ee5ec);
  border-radius: 10px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.gradient-box button {
  position: absolute;
  top: 60px;
  left: 30px;
  padding: 10px 30px;
  background-color: #3fa3a5;
  color: white;
  border: none;
  border-radius: 5px;
  font-size: 18px;
  cursor: pointer;
}

.circle {
  position: absolute;
  border-radius: 50%;
}

.circle.purple {
  top: -20px;
  right: 20px;
  width: 60px;
  height: 60px;
  background-color: #561769;
}

.circle.green {
  top: 30px;
  right: 75px;
  width: 40px;
  height: 40px;
  background-color: #3c9416d3;
}

.profile-img {
  position: absolute;
  bottom: -60px;
  width: 160px;
  height: 160px;
  border: 10px solid #38afb1;
  border-radius: 50%;
  overflow: hidden;
}

.profile-img img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.bottom-bar {
  text-align: center;
  padding: 15px;
  font-size: 20px;
  background: linear-gradient(to right, #e3fce9, #a2dab7);
  font-weight: bold;
}
