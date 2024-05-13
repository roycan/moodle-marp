---
marp: true
theme: marp-w3
footer: ![w:150](img/footer.png) &copy; <span class="w3-center"> Canseco 2024 </span>

---

<!-- Add this anywhere in your Markdown file -->
<script src="https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.min.js"></script>
<script>
  mermaid.initialize({ startOnLoad: true });
</script>

<!-- _footer: - -->

![bg](img/cover.png)

---

<!-- _footer: - -->

![bg right:15%](img/bg.png)

<div style="height: 50vh">

# CS Teacher VPL Tricks

### *Half your time checking student programs while doubling student engagement with Moodle VPL*

<!-- sub sub title: Super Sulit Server Setup with Linode Akamai (and Nephila)   -->

</div>

<hr>
<p class="w3-text-deep-orange w3-bold"> Presented By:
</p>
Roy Vincent L. Canseco, MSEE, PhD Cand. CS <br>
Computer Science Unit /  MIS <br>
Philippine Science High School - Main Campus

<div class="w3-right">

![w:50 ](/img/pshs.png)

</div>

---



<div class="w3-row">
<div class="w3-col s8">

# Teacher and I.T. Practitioner 

<div class="w3-xlarge">
<p>I have had the privilege of teaching at various institutions, including the Institute of Electrical and Electronics Engineering (IEEE), the Department of Computer Science (DCS) and the Virata School of Business  at the University of the Philippines Diliman (UPD). During my time at UPD, I actively contributed to the development of UPD's Moodle-based UVLe LMS as a Project Development Associate.
</p>


Currently, I am teaching at Philippine Science High School - Main Campus, where I served as the head of the Information Technology Unit (MIS) during the deployment of our Moodle-based Learning Management System called KHub.
</div>

</div>
<div class="w3-col s4 w3-center">

![w:300](img/roynette.png)

<hr>

<div class="w3-right">
Roy Canseco 
<p class="w3-xlarge"> 
CS Teacher , MIS - PSHS-MC
</p>
</div>


</div>
</div>

---

![bg right:15%](img/bg.png)

# Talk Description

Join me as I share how our campus set up and leverages Moodle's Virtual Programming Laboratory (VPL), along with generative AI to heighten student engagement, while minimizing code checking time. 

Discover how we have implemented these technologies to enhance the learning experience, while keeping server costs cheap and maintenance easy. 



---

<!-- _footer: - -->
![bg right](img/robot_teacher.png)

<div class="w3-xxlarge w3-uppercase">

# CS Teacher VPL Tricks

</div>

### MoodleMoot 2024

#### May 2024

<br>

##### Roy Vincent L. Canseco



---

![bg right:15%](img/bg.png)

# Talk Outline


<div class="mermaid w3-center">
timeline
    Background : A key challenge to CS Teachers
    Big Idea : VPL 
    : AI chatbot (eg Copilot)
    Advantages : Auto Program checking 
    : Anti Plagiarism tools
    : Multi-language support
    Setup : Moodle VPL plugin
    : Execution Server
</div>




---

<!-- _footer: _ -->
<!-- paginate: true -->

![bg right:15%](img/bg.png)

According to a study funded by Google, under the direction of ACM, and in partnership with Microsoft:
<br>

<div class="w3-xxxlarge">

> "Computer science educators often struggle with limited access to **up-to-date materials**, **software**, and **hardware**"
> <span class="w3-right"> -University of Chicago Study </span>

</div>

<div class="w3-bottom w3-medium">
1) Century et al. 2013. Building an Operating System report. https://outlier.uchicago.edu/computerscience/OS4CS/challenges/. Accessed 2024
2) Doug Konopelko. 2024. Building an Operating System report. https://outlier.uchicago.edu/computerscience/OS4CS/challenges/. Accessed 2024
</div>

---

![bg right:15%](img/bg.png)

<div class="w3-container w3-black w3-center" style="position: absolute; top: 50; left: 50;">
  <p class="w3-text-white" style="font-size: 50px; font-family: 'Courier New', monospace;">01</p>
</div>


<div class="w3-display-middle w3-jumbo">
  VPL - Virtual Programming Laboratory
</div>


---

![bg opacity](img/kids.jpg)

<div class="w3-row"> 
  <div class="w3-col s5">

  # Virtual Programming Laboratory

  </div>
  <div class="w3-col s7">
  <div class="mermaid w3-center">
  graph LR
    MoodleVPL[Moodle VPL] --> InteractiveProgramming["Interactive      Programming      Assignments"]
    MoodleVPL --> WebBasedEnvironment["Web-Based Programming Environment"]
    MoodleVPL --> SecureSandbox["Secure Sandbox Environment"]
    MoodleVPL --> MultipleLanguages["Support for Multiple Programming Languages"]
    MoodleVPL --> AutomaticGrading["Automatic Grading and Feedback"]
    MoodleVPL --> PlagiarismChecker["
  Plagiarism Checker"]

  </div>
  </div>

</div>

---

<!-- _footer: - -->

![bg right:15%](img/bg.png)

<div class="w3-center w3-xxlarge w3-text-green">

 Interactive Secure Web-based Environment 
![](img/interactive.png)
</div>

---



![bg right:15%](img/bg.png)

<div class="w3-center w3-xxlarge w3-text-green">

 Automatic Code Similarity Checker 
![](img/similarity.png)
</div>

---



![bg right:15%](img/bg.png)

<div class="w3-center w3-xxlarge w3-text-green">

 Easy Code Comparison
![](img/comparison.png)
</div>

---

![bg right:15%](img/bg.png)

<div class="w3-rows">

<div class="w3-col s4">

# Lots of **Programming Languages** supported

\*\* there are more depending on the setup

</div>

<div class="w3-col s8 w3-center">

<div class="mermaid">
mindmap
  root(("Available <br> Languages"))
    **C**
    **C++**
    Java
    ::icon(fa-brands fa-java)
    Python
    ::icon(fab fa-python)
    PHP
    ::icon(fa-brands fa-php)
    Javascript
    ::icon(fa-brands fa-js)
    **Ruby**
    **Perl**
    Swift
    ::icon(fa-brands fa-swift)
    **Matlab**
    **R**
    **Shell**

</div>

</div>

---

<!-- _footer: - -->

![bg right:15%](img/bg.png)

<div class="w3-center w3-xxlarge w3-text-green">

Supported Programming Languages

![](img/languages.png)

</div>




---


![](img/becker2023-programming_is_hard.png)

---

![bg right:15%](img/bg.png)

<!-- _footer: Becker, B. A., Denny, P., Finnie-Ansley, J., Luxton-Reilly, A., Prather, J., & Santos, E. A. (2023). Programming Is Hard – Or at Least It Used to Be: Educational Opportunities and Challenges of AI Code Generation. In Proceedings of the 54th ACM Technical Symposium on Computer Science Education V. 1 (SIGCSE 2023), March 15–18, 2023, Toronto, ON, Canada. https://doi.org/10.1145/3545945.3569759 -->


<div class="w3-container w3-white w3-opacity w3-xxlarge">

  Becker et al, in 2023, discussed ways in which AI tools can  help students learn programming:

1. **AI-generated solutions** can provide students with model answers to programming exercises
2. AI can generate **explanations of complex code**
3. Educators can leave low-level code to A.I. then **shift the focus to algorithms** 
4. AI-generated starter code can help students **combat programmer's writer's block**

</div>




---


![](img/2023-ai_code_gen.png)

---

![bg right:15%](img/bg.png)

<!-- _footer: Kazemitabaar, M., Chow, J., Ma, C. K. T., Ericson, B. J., Weintrop, D., & Grossman, T. (2023). Studying the Effect of AI Code Generators on Supporting Novice Learners in Introductory Programming. In Proceedings of the 2023 CHI Conference on Human Factors in Computing Systems (CHI ’23), April 23–28, 2023, Hamburg, Germany.  https://doi.org/10.1145/3544548.3580919 -->


<div class="w3-container w3-white w3-opacity w3-xlarge">

  In a 2023 study that involved 69 novices aged 10-17, Kazemitabaar et al presented encouraging evidence that AI Coding Assistants can be integrated into programming education:

1. Students using AI code generators like Codex showed **completed tasks faster and with higher scores**,
2. Students with higher pre-test scores and access to Codex performed significantly **better in retention tests**
3. Students using AI code generators felt **less stressed and more eager** to continue learning programming 
4. Students used AI code generators to **break tasks into subgoals** and solve each subgoal step by step

</div>



---


![](img/fitria2021-ai_in_educ.png)

---

![bg right:15%](img/bg.png)

<!-- _footer: itria, T. N. (2021). Artificial intelligence (AI) in education: Using AI tools for teaching and learning process. Prosiding Seminar Nasional & Call for Paper STIE AAS, Surakarta, Jawa Tengah -->


<div class="w3-container w3-white w3-opacity w3-xxlarge">

  Fitria, in 2021, highlights the following aspects of A.I. for education:

1. Students can have a more **Personalized Learning** experience with AI
2. A.I. will be **Complementing Teachers**
3. AI Applications can serve as **Virtual mentors / tutors** 
4. A.I. carries potential technical issues like **cyberattacks and plagiarism.**

</div>




---




![bg left:25%](img/lightbulb-student.png)

# VPL Setup and Use

1. **_Install VPL plugin_** - Installing Moodle VPL is a straightforward process that involves uploading the plugin package and configuring the settings.

2. **_Setup VPL Jail Server_** - Involves setting up a dedicated server, installing the necessary packages, configuring the server, and testing the installation.

3. **_Create VPL Assignments_** - Creating VPL assignments involves careful planning, designing, and testing to ensure they align with learning objectives and effectively assess programming skills.

---

# Citations

* AI-gen picture: Leonardo AI. 2024. https://app.leonardo.ai/ai-generations
* AI-gen picture: Cici AI. 2024. https://www.ciciai.com/chat
* icons: Font Awesome. 2024. https://fontawesome.com/v6/

---

# Introduction

- Greeting and introduction
- Brief explanation of the Moodle VPL plugin
- Overview of the importance of programming education and the need for practical programming assignments

---

# Understanding the Moodle VPL Plugin

+ Explanation of what the Moodle VPL plugin is and its purpose
+_ Key features and benefits of using the Moodle VPL plugin
+ Supported programming languages and environments
+ Overview of the user roles and their responsibilities (instructors and students)

---

# Creating Programming Assignments with Moodle VPL

- Step-by-step guide on how to create programming assignments using the plugin
- Defining programming tasks, requirements, and constraints
- Setting up programming languages, libraries, and compiler options
- Configuring evaluation criteria and grading methods
- Demonstrating the use of test cases and expected outputs

---

# Student Experience with Moodle VPL

- Walkthrough of the student view and interface in the Moodle VPL activity
- Accessing and understanding the programming assignment
- Writing and submitting code within the web-based programming environment
- Running and testing code in the secure sandbox environment
- Receiving immediate feedback and evaluation results

---

# Best Practices and Tips for Using Moodle VPL

- Sharing effective strategies for designing and implementing programming assignments
- Providing tips for instructors to enhance student engagement and learning outcomes
- Addressing common challenges and how to overcome them
- Highlighting success stories and case studies from other institutions

---

# Q&A Session

- Allocating time for questions and answers
- Addressing any concerns or queries from the audience

---

# Conclusion

- Recap of the key points covered in the talk
- Encouraging further exploration and adoption of the Moodle VPL plugin
- Thanking the audience for their participation and attention
