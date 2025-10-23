<!DOCTYPE html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Jess' Profile Page</title>

 
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js"></script>


  <link rel="stylesheet" href="css/mycss_web.css" media="screen and (min-width: 769px)">
  <link rel="stylesheet" href="css/mycss_tablet.css" media="screen and (max-width: 768px)">

  <style>
    h1 {
      font-family: 'Georgia', serif;
      text-align: center;
      color: rgba(237, 137, 179, 0.8);
    }
  </style>
</head>
<body>

  
  <nav class="navbar navbar-expand-lg navbar-light bg-light shadow-sm">
    <a class="navbar-brand" href="#">Jess' Profile</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ml-auto">
        <li class="nav-item"><a class="nav-link" href="#profile">Profile</a></li>
        <li class="nav-item"><a class="nav-link" href="#education">Education</a></li>
        <li class="nav-item"><a class="nav-link" href="#experience">Work Experience</a></li>
        <li class="nav-item"><a class="nav-link" href="#skills">Programming Skills</a></li>
        <li class="nav-item"><a class="nav-link" href="#interests">Interests</a></li>
        <li class="nav-item"><a class="nav-link" href="#favorites">Favorites</a></li>
        <li class="nav-item"><a class="nav-link" href="#websites">Websites</a></li>
        <li class="nav-item"><a class="nav-link" href="#projects">Projects</a></li>
        <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
      </ul>
    </div>
  </nav>

 
  <div id="profile" class="container my-5">
    <h1>Profile</h1>
    <div class="row">
      <div class="col-md-6">
        <p><strong>Name:</strong> Jessica Koo</p>
        <p><strong>Major:</strong> Computer Science | <strong>Minor:</strong> Data Science</p>
      </div>
      <div class="col-md-6 text-center">
        <img src="IMG_0583.JPG" class="img-fluid rounded shadow-sm mb-3" width="200">
        <video class="w-100 shadow-sm" controls>
          <source src="vid.mp4" type="video/mp4">
          Your browser does not support the video tag.
        </video>
      </div>
    </div>
  </div>


  <div id="education" class="container my-5">
    <h1>Education</h1>
    <p>I am currently pursuing a B.S. in Computer Science.</p>
    <table class="table table-striped table-bordered shadow-sm">
      <thead class="thead-dark">
        <tr>
          <th>Year</th>
          <th>Institution</th>
          <th>Degree</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>2024–Present</td>
          <td>St. Johns university</td>
          <td>B.S. Computer Science</td>
        </tr>
      </tbody>
    </table>
  </div>


  <div id="experience" class="container my-5">
    <h1>Work Experience</h1>
    <div class="card-deck">
      <div class="card shadow-sm">
        <div class="card-body">
          <h5 class="card-title">Digital Marketing & UX Designer</h5>
          <p class="card-text">Plastic Surgery Office</p>
        </div>
      </div>
      <div class="card shadow-sm">
        <div class="card-body">
          <h5 class="card-title">Research Assistant</h5>
          <p class="card-text">CS Department</p>
        </div>
      </div>
      <div class="card shadow-sm">
        <div class="card-body">
          <h5 class="card-title">Course Projects</h5>
          <p class="card-text">Java OOP, React website</p>
        </div>
      </div>
    </div>
  </div>

  <!-- Skills -->
  <div id="skills" class="container my-5">
    <h1>Programming Skills</h1>
    <ul class="list-group shadow-sm">
      <li class="list-group-item">Java — Intermediate</li>
      <li class="list-group-item">Python — Intermediate</li>
      <li class="list-group-item">HTML/CSS/JS — Beginner</li>
    </ul>
  </div>


  <div id="interests" class="container my-5">
    <h1>Interests</h1>
    <p class="lead">I love UI/UX design, music, reading, and Korean culture.</p>
  </div>


  <div id="favorites" class="container my-5">
    <h1>Favorites</h1>
    <p>My favorite song, movie, and TV show:</p>
    <a href="https://www.youtube.com/watch?v=OTPsMjsY8is&list=RDOTPsMjsY8is&start_radio=1" target="_blank" class="btn btn-outline-primary btn-sm mb-2">Favorite Song</a><br>
    <a href="https://www.youtube.com/watch?v=dPb717U_hf0" target="_blank" class="btn btn-outline-success btn-sm mb-2">Favorite Movie Trailer</a><br>
    <a href="https://www.youtube.com/watch?v=F_PhJG4hf1s" target="_blank" class="btn btn-outline-danger btn-sm">Favorite TV Show Clip</a>
  </div>


  <div id="websites" class="container my-5">
    <h1>Favorite Websites</h1>
    <ul class="list-group shadow-sm">
      <li class="list-group-item"><a href="https://us.brandymelville.com/">Brandy Melville</a></li>
      <li class="list-group-item"><a href="https://tracker.gg/valorant">Valorant Tracker</a></li>
    </ul>
  </div>


  <div id="projects" class="container my-5">
    <h1>Projects</h1>
    <div class="card shadow-sm">
      <div class="card-body">
        <p class="card-text">Calculator app and Snake game</p>
      </div>
    </div>
  </div>


  <div id="contact" class="container my-5">
    <h1>Contact Me</h1>
    <form class="shadow-sm p-4 bg-light rounded">
      <div class="form-group">
        <label for="name">Name:</label>
        <input type="text" class="form-control" id="name" name="name">
      </div>
      <div class="form-group">
        <label for="message">Message:</label>
        <textarea class="form-control" id="message" name="message" rows="3"></textarea>
      </div>
      <button type="submit" class="btn btn-primary">Send</button>
    </form>
  </div>
</body>
</html>
