<template>
  <div class="container">
    <header>
      <div class="profile-pic">
        <img src="https://avatars.githubusercontent.com/u/41074356?v=4" alt="Your Name">
      </div>
      <div class="name">
        Raghunath Bhattacharjee 🚀<br>
        <label style="font-size: 18px;font-weight: 200;">Software Developmet Engineer</label>
      </div>
      
      <div class="contact">
        <i class="fas fa-envelope"></i> bhattacharjeer069@gmail.com <br>
        <i class="fas fa-phone-alt"></i> +91 8944036004
      </div>
    </header>

    <section>
      <h2><i class="fas fa-briefcase"></i>Objective</h2>
      <p style="margin-left: 25px;">
        Software Engineer with 4+ years of experience in the digital realm. Expertise in AWS, DevOps, Full-stack
        Development, and Data Analytics. 🌐 Passionate about transforming ideas into innovative solutions. 🚀 Let's
        harness the power of technology to make a difference. 🤝 Let's connect! 💡🌟
      </p>
    </section>

    <section>
      <h2><i class="fas fa-graduation-cap"></i>Education</h2>
      <ul>
        <li><strong>WBUT (MAKAUT, AICTE)</strong> 2015 - 2019, B-Tech (Computer Science & Engineering) - 8.34 GPA 🎓</li>
      </ul>
      <p style="margin-left: 25px;">
        Expertise lies in a range of subjects including Algorithm, Data Structure, Compiler Design, Programming, Automata,
        Pattern, Graphics Design, and Networking. With a solid foundation in these top subjects, possesses a deep
        understanding of complex problem-solving, efficient algorithm design, and data management.
      </p>
    </section>

    <section>
      <h2><i class="fas fa-building"></i>Experience</h2>
      <ul>
        <li>
          <strong>Present Company</strong>
          <br>Tata Consultancy Services (TCS), System Engineer - Sep 2019 🏢
        </li>
        <li>
          <strong>Previous Company</strong>
          <br>Adrobit Technologies, Fullstack Software Developmet Engineer - Sep 2018 to Aug 2021 👩‍💻
        </li>
      </ul>
    </section>

    <section>
      <h2><i class="fas fa-tools"></i>Skills</h2>
      <ul>
        <li>
          <b>
            Data & Analytics:
          </b>
          R Programming, Oracle SQL, PL/SQL, SQL Server, AWS, Google Analytics, UNICA
        </li>
        <li>
          <b>
            Web (Front-end):
          </b>
          HTML, CSS, JavaScript, Vue, React, Angular, Ionic, Typescript 🖥️
        </li>
        <li>
          <b>
            Web (Back-end):
          </b>
          Java, Spring, PHP, Laravel(5.8+) with MVC, Python, .Net (Basic)
        </li>
        <li>
          <b>
            Build & Deployment Tools:
          </b>
          Git, Webpack, CICD, Jenkins
        </li>
        <li>
          <b>
            Operating systems:
          </b>
          Windows, Linux -Ubuntu (16+), Unix, Dos
        </li>
        <li>
          <b>
            Cloud:
          </b>
          AWS (In-hand 2+ years), GCP (1+)
        </li>
        <li>
          <b>
            Code Deployment Tools:
          </b>
          Git, GitLab, Bitbucket & Jira
        </li>
      </ul>
    </section>

    <section>
      <h2><i class="fas fa-certificate"></i>Certification</h2>
      <ul>
        <li>
          Google Data Analytics Professional Certification (Google)
        </li>
        <li>
          Digital Technology Healthcare (IIT-KGP)
        </li>
        <li>
          Cloud Computing and Distributed Systems (NPTEL)
        </li>
        <li>
          Lam Stack Web development. (TechTree)
        </li>
        <li>
          Python Development (ISOEH)
        </li>
        <li>
          Complete Oracle SQL Certification Course (Udemy)
        </li>
      </ul>
    </section>

    <section>
      <h2><i class="fas fa-heart"></i>Interests</h2>
      <p style="margin-left: 25px;">
        I'm deeply passionate about the intersection of web technologies, data analytics, and cloud infrastructure 💻.
        With extensive experience in both front-end and back-end technologies ranging from Vue, React, and Angular 🌐 to
        Java, Python, and PHP 🛠, I believe in creating seamless and robust web applications. My grounding in data
        analytics with tools such as R Programming and Oracle SQL 📊 ensures that I leverage data to drive decisions and
        improve user experiences.
      </p>
      <p style="margin-left: 25px;">
          Beyond application development, I've honed my skills in cloud platforms like AWS and GCP ☁️. Having hands-on
          experience with deployment and integration tools like Git, Jenkins, and Webpack 🚀, I can manage applications from
          ideation to deployment. My familiarity with operating systems, including Linux (Ubuntu 16+), Windows, and Unix
          🖥️, further strengthens my ability to deploy, optimize, and troubleshoot applications in varied environments.
      </p>
      <p style="margin-left: 25px;">
          My journey in tech has been characterized by continuous learning and adaptation 📘. With each project, I seek to
          not just implement solutions but to elevate the entire ecosystem using best practices and forward-thinking
          strategies. Let's collaborate and push the boundaries of what's possible in the digital space! 🤝
      </p>
    </section>

    <div class="social-links" style="text-align: center;padding: inherit;">
      <!-- LinkedIn -->
      <a href="https://www.linkedin.com/in/raghunath-bhattacharjee/" target="_blank" rel="noopener noreferrer">
        <i class="fab fa-linkedin-in"></i>
      </a>
      <!-- GitHub -->
      <a href="https://github.com/raghunath-bhattacharjee" target="_blank" rel="noopener noreferrer">
        <i class="fab fa-github"></i>
      </a>

      <!-- Medium -->
      <a href="https://medium.com/@raghunathbhattacharjee21" target="_blank" rel="noopener noreferrer">
        <i class="fab fa-medium"></i>
      </a>
      <!-- Any other social links you'd like to add -->
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
body {
  font-family: 'Arial', sans-serif;
  background: linear-gradient(to right, #f4f4f4, #ffffff);
  margin: 0;
  overflow: hidden; /* This will prevent scrolling on the body */
}

.container {
  max-width: 800px;
  background-color: #ffffff;
  margin: 30px auto;
  padding: 20px;
  box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
  border-radius: 10px;
}

header {
  display: flex;
  align-items: center;
  border-bottom: 1px solid #e0e0e0;
  padding-bottom: 10px;
  margin-bottom: 20px;
}

@media screen and (max-width: 600px) {
  header {
    display: unset;
  }
}

header .profile-pic {
  width: 80px;
  height: 80px;
  border-radius: 50%;
  overflow: hidden;
  margin-right: 15px;
}

header .profile-pic img {
  width: 100%;
  height: auto;
}

header .name {
  font-size: 24px;
  font-weight: bold;
}

header .contact {
  margin-left: auto;
  font-size: 16px;
  color: #666;
}

section {
  margin-bottom: 20px;
}

h2 {
  border-bottom: 2px solid #0077cc;
  padding-bottom: 5px;
  margin-bottom: 15px;
  font-size: 20px;
  display: flex;
  align-items: center;
}

h2 i {
  margin-right: 10px;
}

p,
ul,
ol {
  font-size: 16px;
}

li {
  margin-bottom: 10px;
}

li:hover {
  font-weight: bold;
}

p:hover {
  font-weight: bold;
}


.social-links a {
  margin: 0 10px;
  font-size: 20px;
  color: #333;
  /* Change to any color you prefer */
  transition: color 0.3s;
}

.social-links a:hover {
  color: #0077b5;
  /* Color on hover - this is LinkedIn blue as an example */
  font-size: 30px;
}
</style>