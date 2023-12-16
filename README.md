


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio - ABC CONSULTANT</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
      color: #333;
    }

    header {
      background-color: hsl(217, 23%, 80%);
      color: #fff;
      text-align: left;
      padding: 1em;
    }

    nav {
      background-color: #333;
      color: #fff;
      text-align: center;
      padding: 1em;
    }

    nav a {
      text-decoration: none;
      color: #fff;
      margin: 0 15px;
      font-weight: bold;
      transition: color 0.3s ease-in-out;
    }

    nav a:hover {
      color: #4285f4;
      font-style: italic;
    }

    section {
      padding: 20px;
      margin: 20px;
      background-color: #fff;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }

    h1 {
      color: #4285f4;
    }

    img {
      border-radius: 50%;
      max-width: 100%;
      height: auto;
    }

    .skills {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      align-items: center;
    }

    .skills div {
      margin: 10px;
      text-align: center;
    }

    .projects, .recommendations {
      margin-top: 20px;
    }

    .recommendations blockquote {
      border-left: 3px solid #4285f4;
      padding-left: 10px;
    }

    .home-icon {
      font-size: 24px;
      cursor: pointer;
    }
  </style>
</head>
<body>

  <header>
    <h1>TANU PAL</h1>
  </header>

  <nav>
    <span class="home-icon">&#127968;</span>
    <a href="#about">About</a>
    <a href="#projects">Project details</a>
    <a href="#skills">Skills</a>
    <a href="#recommendations">Recommendations</a>
  </nav>

  <section id="about">
    <h2>About Me</h2>
    <img src="profile-image.jpg" alt="Profile Image"  height="100px" width="100x">
    <p> My name is Tanu Pal. I am very determined person and have a good command on Html, Css and Javascript.</p>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <div class="skills">
      <div>
        <img src="html-logo.png" alt="HTML Logo"  height="20px" width="20x">
        <p>HTML5</p>
      </div>
      <div>
        <img src="css-logo.png" alt="CSS Logo" height="80px" width="80x">
        <p>CSS3</p>
      </div>
      <div>
        <img src="js-logo.png" alt="JavaScript Logo" height="100px" width="100x">
        <p>JavaScript</p>
      </div>
    </div>
  </section>

  <section id="projects" class="projects">
    <h2>Projects</h2>
    <div>
      <h3>Project A</h3>
      <p>Created a portfolio for the resume and also made changes.</p>
    </div>
    <div>
      <h3>Project B</h3>
      <p>Cyber security project in which I made changes in the background colour and also added pictures related to crime and security.</p>
    </div>
    <div>
      <h3>Project C</h3>
      <p>Banking system.In this project, I made many changes in dialog box appearance and also added colours to the different process..</p>
    </div>
  </section>

  <section id="recommendations" class="recommendations">
    <h2>Recommendations</h2>
    <blockquote>
      <p>“Leadership offers an opportunity to make a difference in someone’s life, no matter what the project.”</p>
      <cite>Bill Owens</cite>
      <p> “Operations keep the lights on, strategy provides a light at the end of the tunnel, but project management is the train engine that moves the organization forward.” </p>
      <cite>Joy Gumz</cite>
      <p> “Being a Project Manager is like being an artist, you have the different colored process streams combining into a work of art”</p>
      <cite> Greg Cimmarrusti</cite>
      <p> “Effective leadership is not about making speeches or being liked; leadership is defined by results not attributes.” </p>
      <cite> Peter F. Drucker</cite>
    </blockquote>
  <button onclick="showConfirmationModal()">Submit Recommendation</button>
</section>

<div id="confirmationModal" class="modal">
  <p>Recommendation submitted!</p>
  <button onclick="hideConfirmationModal()">OK</button>
</div>

<script>
  // ... Existing JavaScript ...

  function showConfirmationModal() {
    document.getElementById('confirmationModal').style.display = 'block';
  }

  function hideConfirmationModal() {
    document.getElementById('confirmationModal').style.display = 'none';
  }
</script>
  <script>
    // JavaScript for the interactive parts...

    document.querySelector('.home-icon').addEventListener('click', () => {
      alert('Home icon clicked!');
    });
    document.querySelector('.recommendations').addEventListener('click', () => {
      alert('confirmed recommendatins!');
    });

    function submitRecommendation() {
      alert('Recommendation submitted!\nThank you for your feedback.');
    }
  </script>

</body>
</html>




