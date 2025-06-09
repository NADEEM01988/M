<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mohamed Nadeem - Resume</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f2f2f2;
    }
    header {
      background-color: #003366;
      color: white;
      padding: 40px;
      text-align: center;
    }
    nav {
      background-color: #005599;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }
    nav button {
      background: white;
      border: none;
      margin: 10px;
      padding: 10px 20px;
      cursor: pointer;
      font-weight: bold;
      border-radius: 5px;
      transition: background 0.3s;
    }
    nav button:hover {
      background: #e6e6e6;
    }
    section {
      display: none;
      padding: 20px;
      background: white;
      margin: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    section.active {
      display: block;
    }
    .title {
      font-size: 24px;
      margin-bottom: 10px;
      color: #003366;
    }
    .portfolio-gallery {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
      gap: 15px;
      margin-top: 20px;
    }
    .portfolio-gallery img {
      width: 100%;
      border-radius: 8px;
      box-shadow: 0 0 5px rgba(0,0,0,0.2);
      transition: transform 0.3s;
    }
    .portfolio-gallery img:hover {
      transform: scale(1.05);
    }
  </style>
<header>
  <h1>MOHAMED NADEEM</h1>
  <p>Customer Support Specialist | IT | Graphic Designer | Administrative Professional</p>
  <p>+971 56 140 1048 | mohamednadeem88@hotmail.com | Abu Dhabi, UAE</p>
</header>

<nav>
  <button onclick="showSection('about')">ABOUT</button>
  <button onclick="showSection('resume')">RESUME</button>
  <button onclick="showSection('education')">EDUCATION</button>
  <button onclick="showSection('certificates')">CERTIFICATES</button>
  <button onclick="showSection('experience')">EXPERIENCE</button>
  <button onclick="showSection('skills')">SKILLS</button>
  <button onclick="showSection('portfolio')">PORTFOLIO</button>
</nav>

<section id="about">
  <img src="images/myphoto.jpg.jpg" alt="Resume Photo" style="width: 200px; border-radius: 8px; margin-top: 10px;">
  <h2 class="title">Summary</h2>
  <p>
    Dynamic and results-oriented professional with 10 years of experience in graphic design, IT hardware support, customer care, and office administration. Proven track record in delivering high-quality visual solutions using Adobe Creative Suite and Canva, resolving complex issues, and streamlining administrative processes.
  </p>
</section>



<section id="certificates">

<p>
<img src="3/nad.jpg" alt="certificates" style="width: 300px; border-radius: 8px; margin-top: 10px;">
<img src="3/4.jpg" alt="certificates" style="width: 300px; border-radius: 8px; margin-top: 10px;">
 <p style="margin-top: 10px; font-size: 16px;">
    Awarded a professional certificate by the HSE Department for outstanding dedication to health, safety, and workplace excellence.
  </p>
<img src="3/nad1.jpg" alt="Resume Photo" style="width: 300px; border-radius: 8px; margin-top: 10px;">
<img src="3/CERTIFICATE.jpg" alt="Resume Photo" style="width: 300px; border-radius: 8px; margin-top: 10px;">
 <p style="margin-top: 10px; font-size: 16px;">
    Appreciation Award from Anas Ahmed Al Qubaisi, Senior Vice President, Shared Services, in recognition of exceptional dedication and performance.
  </p>
</section>

</section>
</p>
</section>

<section id="resume">
  <h2 class="title">Resume</h2>
  <p>
    Current Position: Printing Designer & IT Support Specialist at Emirates Post Group (2020–Present)<br>
    Previous: General Office Clerk at ADNOC (2013–2019), Document Controller at Al Madina (2010–2012)
  </p>
  <img src="RESUME/1.JPG" alt="Resume Photo" style="width: 300px; border-radius: 8px; margin-top: 10px;">
  <img src="RESUME/2.JPG" alt="Resume Photo" style="width: 300px; border-radius: 8px; margin-top: 10px;">	
</section>

<section id="education">
  <h2 class="title">Education</h2>
  <ul>
<img src="2/1.jpeg" alt="Education" style="width: 300px; border-radius: 8px; margin-top: 10px;">
<img src="2/2 copy.jpg" alt="Education" style="width: 300px; border-radius: 8px; margin-top: 10px;">
<img src="2/3 copy.jpg" alt="Education" style="width: 300px; border-radius: 8px; margin-top: 10px;">
    <li>Diploma of Higher Education in Computer Hardware – National Institute of Technology, Trichy, India (2006)</li>
    <li>Secondary School Level – Government of Tamil Nadu, India (2005)</li>
  </ul>
</section>

<section id="certificates">
  <h2 class="title">Certificates</h2>
  <ul>
    <li>Technical Support Fundamentals - Google</li>
    <li>Design Online Course Printables using Canva</li>
    <li>Diploma in Information Technology Management</li>
  </ul>
</section>

<section id="experience">
  <h2 class="title">Professional Experience</h2>

  <div class="job">
    <h3>Printing Designer & IT Support Specialist – Emirates Post Group</h3>
    <p><strong>Location:</strong> Abu Dhabi, UAE</p>
    <p><strong>Duration:</strong> 2017 – Present</p>
    <ul>
      <li>Designed high-quality marketing materials including flyers, brochures, and postal items using Adobe Photoshop and Illustrator.</li>
      <li>Provided IT hardware support and resolved user technical issues swiftly to minimize downtime.</li>
      <li>Maintained printers and handled all graphic design work for internal and client-based projects.</li>
    </ul>
  </div>

  <div class="job">
    <h3>General Office Clerk – ADNOC (Contract Role)</h3>
    <p><strong>Location:</strong> Abu Dhabi, UAE</p>
    <p><strong>Duration:</strong> 2015 – 2017</p>
    <ul>
      <li>Managed administrative tasks including data entry, correspondence handling, and file organization.</li>
      <li>Supported various departments in office coordination, meeting scheduling, and document preparation.</li>
    </ul>
  </div>

  <div class="job">
    <h3>Document Controller – Al Madina Agencies and Services</h3>
    <p><strong>Location:</strong> Abu Dhabi, UAE</p>
    <p><strong>Duration:</strong> 2009 – 2012</p>
    <ul>
      <li>Handled document control processes for contracts, drawings, and transmittals using DMS tools.</li>
      <li>Ensured version control and proper document archiving as per ISO standards.</li>
    </ul>
  </div>
</section>


<section id="skills">
  <h2 class="title">Key Skills</h2>
  <ul>
    <li>IT Helpdesk & User Support</li>
    <li>Hardware/Software Installation & Repair</li>
    <li>System Troubleshooting & Diagnostics</li>
    <li>Adobe Creative Suite (Photoshop, Illustrator, InDesign)</li>
    <li>Illustration & Print Layout</li>
    <li>Document Control (DMS)</li>
    <li>Customer Communication</li>
    <li>Office Administration</li>
  </ul>
</section>

<section id="portfolio">
  <h2 class="title">Portfolio - Calendar Design</h2>
 <div class="portfolio-gallery">
  <a href="1/Design1.jpg" target="_blank"><img src="1/Design1.jpg" alt="Design 1" /></a>
  <a href="1/Design2.jpg" target="_blank"><img src="1/Design2.jpg" alt="Design 2" /></a>
  <a href="1/Design3.jpg" target="_blank"><img src="1/Design3.jpg" alt="Design 3" /></a>
  <a href="1/Design4.jpg" target="_blank"><img src="1/Design4.jpg" alt="Design 4" /></a>
  <a href="1/Design5.jpg" target="_blank"><img src="1/Design5.jpg" alt="Design 5" /></a>
  <a href="1/Design6.MP4" target="_blank"><img src="1/Design6.MP4" alt="Design 6" /></a>	
  <!-- Video embedded -->
  <video width="300" controls>
    <source src="1/Design6.MP4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>
</div>
</section>

<script>
  function showSection(id) {
    document.querySelectorAll('section').forEach(sec => sec.classList.remove('active'));
    document.getElementById(id).classList.add('active');
  }
</script>

</body>
</html>
