<!DOCTYPE html>
<html>
  <head>
    <title>Dhana Lakshmi Gajjala - Portfolio</title>
    <link rel="stylesheet" href="./style.css" />
    <script src="./script.js"></script>
  </head>
  <body>
    <!-- Navigation Bar -->
    <nav>
      <div id="home">
        <div class="profile_name">
          DHANALAKSHMI GAJJALA
          <div class="contact_info">
            <img
              src="html_finalprojimages/envelope.png"
              alt="https://icons8.com/icon/124377/circled-envelope"
            />
            danalakshmi443@gmail.com
          </div>
          <div style="clear: both"></div>
          <div class="contact_info">
            <img
              src="html_finalprojimages/phone.png"
              alt="https://icons8.com/icon/124377/circled-envelope"
            />
            +91 9390176575
          </div>
        </div>
        <div class="topdiv">
          <a class="topmenu" href="#about-me">About Me</a>
          <!-- Add the links for Skills, Projects and Recommendation here -->
          <a class="topmenu" href="#skills">Skills</a>
          <a class="topmenu" href="#projects">Projects</a>
          <a class="topmenu" href="#recommendations">Recommendation</a>
        </div>
      </div>
    </nav>

    <!-- About Me -->
    <section id="about-me" class="container">
      <div>
        <img
          src="html_finalprojimages/Coder.gif"
          class="profile_image"
          width="100px"
          height="100px"
          padding="50px"
        />
      </div>

      <div>
        <h1>
          Hi, I'm Dhana Lakshmi Gajjala!
          <span>👋</span>
        </h1>
        <p>
          Welcome 👋, My name is Dhana Lakshmi; I'm a Full Stack Web Developer based in
          Bengaluru, India. Passionate about delivering comprehensive and seamless web solutions, I thrive in a collaborative environment, utilizing a combination of technical expertise and creativity to build applications that meet both user needs and business objectives.
        </p>
      </div>
    </section>

    <!-- Skills -->
    <section id="skills">
      <h2>Skills</h2>
      <div style="clear: both"></div>

      <div class="all_skills">
        <div class="skill">
          <img src="html_finalprojimages/html5.png" />
          <h6>HTML</h6>
          <p>3 years experience</p>
        </div>

        <div class="skill">
          <img src="html_finalprojimages/CSS3.png" />
          <h6>CSS</h6>
          <p>3 years experience</p>
        </div>

        <div class="skill">
          <img src="html_finalprojimages/js.jpeg" />
          <h6>JavaScript</h6>
          <p>2+ years experience</p>
        </div>

        <div class="skill">
          <img src="html_finalprojimages/react.png" />
          <h6>React</h6>
          <p>2+ years experience</p>
        </div>

        <div class="skill">
          <img src="html_finalprojimages/java.png" />
          <h6>Java</h6>
          <p>4+ years experience</p>
        </div>

        <div class="skill">
          <img src="html_finalprojimages/node.png" />
          <h6>Node</h6>
          <p>2+ years experience</p>
        </div>

        <!-- Add more skills here -->
      </div>
    </section>

    <!-- Projects -->
    <section class="projects" id="projects">
      <h2>Projects</h2>
      <div style="clear: both"></div>

      <div id="projects-container" class="projects-container">
        <div class="project-card">
          <h3>Four-Wheel Steering System Using Arduino</h3>
          <ul>
            <li>
              Installed a four-wheel steering system for enhanced stability and maneuverability.
            </li>

            <li>
              Engineered electronic circuit to control rear wheel direction based on vehicle speed.
            </li>
            <li>
              Improved turning radius, lane-change capability, and terrain suitability.
            </li>
          </ul>
        </div>
        <!-- Add more projects here -->
      </div>
    </section>
    <div style="clear: both"></div>

    <!-- Recommendation Form -->
    <section id="contact">
      <div class="flex_center">
        <fieldset>
          <legend class="introduction">Leave a Recommendation</legend>
          <input type="text" placeholder="Name (Optional)" /> <br />
          <textarea
            id="new_recommendation"
            cols="500"
            rows="10"
            placeholder="Message"
          ></textarea>
          <div class="flex_center">
            
            <button  id="recommend_btn" onclick="addRecommendation()">
              Submit
            </button>
          </div>
        </fieldset>
      </div>
    </section>

    <div class="iconbutton">
      <a href="#home">
        <!--Add the code here for the logo to appear and the icon to be actionable-->
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="white" width="63px">
          <path stroke-linecap="round" stroke-linejoin="round" d="M15 11.25l-3-3m0 0l-3 3m3-3v7.5M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
        </svg>
      </a>
    </div>

    <div class="popup" id="popup" class="flex_center">
      <img src="html_finalprojimages/checkmark--outline.svg" />
      <h3>Thank you for your recommendation!</h3>
      <button onclick="showPopup(false)">Ok</button>
    </div>
  </body>
</html>
