# PORTFOLIO[index.html](https://github.com/user-attachments/files/25254575/index.html)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>John Rey Cañizar - Customer Success & Sales Specialist</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
  <style>
    /* Global Styles */
    body {
      margin: 0;
      font-family: 'Roboto', sans-serif;
      color: #333;
      background-color: #f9f9f9;
      line-height: 1.6;
      scroll-behavior: smooth;
    }
    a {
      color: #0077b6;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }
    h1, h2, h3 {
      margin-bottom: 20px;
    }
    .container {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }

    /* Header */
    header {
      background-color: #0077b6;
      color: white;
      text-align: center;
      padding: 80px 20px;
      position: relative;
      overflow: hidden;
    }
    header h1 {
      font-size: 2.8em;
      margin-bottom: 10px;
      animation: fadeInDown 1s ease forwards;
    }
    header h2 {
      font-weight: 400;
      font-size: 1.4em;
      animation: fadeInUp 1s ease forwards;
    }
    @keyframes fadeInDown {
      0% { opacity: 0; transform: translateY(-30px); }
      100% { opacity: 1; transform: translateY(0); }
    }
    @keyframes fadeInUp {
      0% { opacity: 0; transform: translateY(30px); }
      100% { opacity: 1; transform: translateY(0); }
    }

    /* About Section */
    #about {
      text-align: center;
    }
    #about p {
      font-size: 1.1em;
      max-width: 800px;
      margin: 20px auto;
    }
    .illustration {
      max-width: 300px;
      margin: 20px auto;
      display: block;
      transition: transform 0.5s ease;
    }
    .illustration:hover {
      transform: translateY(-10px);
    }

    /* Skills */
    #skills ul {
      list-style: none;
      padding: 0;
    }
    #skills li {
      background: #e0f0ff;
      padding: 12px 15px;
      margin-bottom: 12px;
      border-radius: 12px;
      transition: transform 0.3s ease, background 0.3s ease;
    }
    #skills li:hover {
      transform: translateX(5px);
      background: #cce7ff;
    }

    /* Work Experience */
    .job {
      margin-bottom: 40px;
      opacity: 0;
      transform: translateY(30px);
      animation: fadeInUpJob 1s forwards;
      animation-delay: 0.3s;
    }
    .job h3 {
      margin-bottom: 5px;
      color: #0077b6;
    }
    .job p {
      margin: 2px 0;
    }
    @keyframes fadeInUpJob {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    /* Contact */
    #contact {
      text-align: center;
    }
    #contact a {
      display: inline-block;
      margin: 5px 15px 5px 0;
      padding: 12px 20px;
      background-color: #0077b6;
      color: white;
      border-radius: 12px;
      transition: background 0.3s, transform 0.3s;
    }
    #contact a:hover {
      background-color: #005f8c;
      transform: scale(1.05);
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 20px;
      background-color: #f1f1f1;
      color: #555;
    }

    /* Responsive */
    @media(min-width: 768px){
      .container {
        justify-content: space-between;
      }
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <h1>John Rey Cañizar</h1>
    <h2>Customer Success & Sales Specialist</h2>
  </header>

  <!-- About -->
  <section id="about">
    <h2>About Me</h2>
    <!-- Modern Vector Illustration -->
    <img src="https://www.svgrepo.com/show/354095/customer-support.svg" alt="Customer Support Illustration" class="illustration">
    <p>I’ve always enjoyed connecting with people and helping solve problems. I’m passionate about communication and creating positive customer experiences. I’m also deeply interested in the digital world and how businesses grow through strong client relationships and smart systems.</p>
  </section>

  <!-- Skills -->
  <section id="skills">
    <h2>Skills</h2>
    <div class="container">
      <ul>
        <li>Provide professional customer support through calls, chats, and emails</li>
        <li>Qualify leads and schedule confirmed appointments accurately</li>
        <li>Maintain CRM records and follow up to ensure client satisfaction</li>
      </ul>
    </div>
  </section>

  <!-- Work Experience -->
  <section id="experience">
    <h2>Work Experience</h2>

    <div class="job">
      <h3>Client Relations Specialist - Local Igniter Inc.</h3>
      <p>A specialized digital marketing agency that focuses on helping HVAC and home appliance repair businesses generate and manage customer leads.</p>
    </div>

    <div class="job">
      <h3>Client Outreach Specialist - Virtual Buddy 24/7</h3>
      <p>Virtual Buddy 24/7 is a Philippine-based BPO serving international clients. MVA is a specialized service under VB, focusing on client outreach, lead qualification, and appointment scheduling.</p>
    </div>

    <div class="job">
      <h3>Medicare Sales Support Specialist - Virtual Buddy 24/7</h3>
      <p>VB’s Medicare Services division provides expert assistance for healthcare and insurance inquiries, guiding clients through the enrollment process while ensuring accurate information and a seamless experience.</p>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact">
    <h2>Contact Me</h2>
    <a href="https://facebook.com/johnrey13c" target="_blank">Facebook</a>
    <a href="https://instagram.com/johnreycsr" target="_blank">Instagram</a>
    <a href="https://linkedin.com/in/johnreycsr" target="_blank">LinkedIn</a>
    <a href="mailto:canizarjohnreys@gmail.com">Email</a>
  </section>

  <footer>
    &copy; 2026 John Rey Cañizar. All rights reserved.
  </footer>

</body>
</html>
