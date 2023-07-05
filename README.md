# Day_3_assignment_HTML_CODE
<!DOCTYPE html>
<html>
<head>
  <title>Responsive Card Layout</title>
  <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
  <div class="container">
    <div class="card">
      <h2 class="card-title">Today's Bootcamp</h2>
      <img src="https://media.letsupgrade.net/lms/program/EHTMLJUL123/image_1688551819117_HTML-_-CSS-3-Days.png" alt="Image 1" class="card-image">
      <p class="card-content">Enroll the bootcamp for free to visit our site</p>
    </div>
    <div class="card">
      <h2 class="card-title">Let's Do This</h2>
      <img src="https://lucdn.letsupgrade.net/assets/353041194_645133420967558_5205328418573096454_n_1353aac2b7.jpg" alt="Image 2" class="card-image">
      <p class="card-content">challenging the IITs in india TECH EDUCATION</p>
    </div>
    <div class="card">
      <h2 class="card-title">Upcoming bootcamp</h2>
      <img src="https://lucdn.letsupgrade.net/assets/python_ankit_png_9b91919108.webp" alt="Image 3" class="card-image">
      <p class="card-content">Learn python for free </p>
    </div>
  </div>
</body>
</html>





#CSS_CODE
.container {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}

.card {
  width: 300px;
  height: 300px;
  margin: 10px;
  padding: 10px;
  border: 1px solid #ddd;
  border-radius: 5px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

.card-title {
  font-size: 20px;
  margin: 0;
}

.card-image {
  width: 100%;
  height: auto;
  border-radius: 5px;
}

.card-content {
  margin-top: 10px;
}

