
    <header class="header">
        <a style="text-decoration: none;" href="#" class="logo">Anuj.</a>

        <i class='bx bx-menu' id="menu-icon"></i>

        <nav class="navbar">
            <a href="#home" class="active">Home</a>
            <a href="#about">About</a>
            <a href="#services">Interests</a>
            <a href="#portfolio">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- <div class="loader"></div> -->

    <section class="home" id="home">
        <svg class="svg1" preserveAspectRatio="xMidYMid slice" viewBox="10 10 80 80">
            <defs>
                <style>
                    @keyframes rotate {
                        0% {
                            transform: rotate(0deg);
                        }

                        100% {
                            transform: rotate(360deg);
                        }
                    }

                    .out-top {
                        animation: rotate 20s linear infinite;
                        transform-origin: 13px 25px;
                    }

                    .in-top {
                        animation: rotate 10s linear infinite;
                        transform-origin: 13px 25px;
                    }

                    .out-bottom {
                        animation: rotate 25s linear infinite;
                        transform-origin: 84px 93px;
                    }

                    .in-bottom {
                        animation: rotate 15s linear infinite;
                        transform-origin: 84px 93px;
                    }
                </style>
            </defs>
            <!-- <path fill="#00bbf9" class="out-top"
                d="M37-5C25.1-14.7,5.7-19.1-9.2-10-28.5,1.8-32.7,31.1-19.8,49c15.5,21.5,52.6,22,67.2,2.3C59.4,35,53.7,8.5,37-5Z" /> -->
            <path fill="#29ffe2" class="in-top"
                d="M20.6,4.1C11.6,1.5-1.9,2.5-8,11.2-16.3,23.1-8.2,45.6,7.4,50S42.1,38.9,41,24.5C40.2,14.1,29.4,6.6,20.6,4.1Z" />
            <!-- <path fill="#00bbf9" class="out-bottom"
                d="M105.9,48.6c-12.4-8.2-29.3-4.8-39.4.8-23.4,12.8-37.7,51.9-19.1,74.1s63.9,15.3,76-5.6c7.6-13.3,1.8-31.1-2.3-43.8C117.6,63.3,114.7,54.3,105.9,48.6Z" /> -->
            <path fill="#00f5d4" class="in-bottom"
                d="M102,67.1c-9.6-6.1-22-3.1-29.5,2-15.4,10.7-19.6,37.5-7.6,47.8s35.9,3.9,44.5-12.5C115.5,92.6,113.9,74.6,102,67.1Z" />
        </svg>
        <div style="z-index: 1;" class="home-content">
            <h3>Hello, It's Me</h3>
            <h1>Anuj Pandey</h1>
            <h3 class="andI">And I'm a <span id="job-title">Frontend Developer</span></h3>
            <p style="text-align: justify;">Ambitious and versatile technology enthusiast with a passion for exploring
                new tech stacks. Skilled in web development, with a focus on
                problem-solving and a desire to innovate.</p>
            <div class="social-media">
                <a href="https://www.instagram.com/not_ur_anuj/" target="_blank"><i
                        class='bx bxl-instagram-alt'></i></a>
                <a href="https://github.com/codermal7" target="_blank"><i class='bx bxl-github'></i></a>
                <a href="https://www.linkedin.com/in/anuj-kumar-pandey-6151a81b5/" target="_blank"><i
                        class='bx bxl-linkedin'></i></a>
                <a href="https://leetcode.com/codermal7/" target="_blank"><i class='bx bx-code'></i></a>
            </div>
            <!-- <a href="https://drive.google.com/uc?export=download&id=1laaNkSdXJ1FSGDsqiNI9kciVR8fgf9ie" class="btn" id="trthis">Try
                this <i class='bx bx-terminal' id="termm"></i></a> -->

            <a href="terminal.html" class="btn" id="trthis">Try
                this <i class='bx bx-terminal' id="termm"></i></a>
        </div>
        <div class="home-img">
            <!-- <img src="images/desk4__1_-removebg-preview (1).png" alt=""> -->
            <img src="images/Young_business_man.png" alt="">
        </div>
    </section>


    <!-- about section design -->
    <section class="about area" id="about">
        <ul class="circles">
            <li></li>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
        </ul>
        <div style="z-index: 1;" class="about-img">
            <img src="images/home.png" alt="">
        </div>
        <div style="z-index: 1;" class="about-content">
            <h2 class="heading">About <span>Me</span></h2>
            <h3>Frontend Developer!</h3>
            <p>I am a highly ambitious and versatile technology enthusiast, always eager to explore the latest tech
                stacks. With a solid foundation in web development, my expertise lies in problem-solving and a
                deep-rooted passion for innovation. <br><br>
                Currently, I am actively engaged in expanding my knowledge of machine learning while simultaneously
                working on a diverse range of projects. My goal is to make a meaningful impact by leveraging
                cutting-edge technologies and staying ahead of the curve in the ever-evolving tech industry.</p>
            <!-- <a href="#" class="btn">Read More</a> -->
        </div>
    </section>


    <!-- services section design -->
    <section class="services" id="services">
        
        <h2 class="heading">My <span>Domains</span></h2>
        <div class="services-container">
            <div class="services-box">
                <i class='bx bx-code-alt'></i>
                <h3>Web Development</h3>
                <p>I possess a strong skill set in frontend web development and have been actively expanding my
                    knowledge in backend development. Over the years, I have successfully completed numerous projects in
                    web development and have garnered recognition for my achievements by working on different projects
                    and winning several hackathons in this field.</p>
                <a href="https://github.com/codermal7" target="_blank" class="btn">Know More<i
                        class='bx bx-link'></i></a>
            </div>


            <div class="services-box">
                <i class='bx bxs-paint'></i>
                <h3>Machine Learning</h3>
                <p>I am actively exploring the field of ML, expanding my knowledge and practical skills. Through
                    hands-on experience, I have completed multiple mini projects, implementing various machine learning
                    models.By working on these projects, I have honed my ability to identify appropriate machine
                    learning algorithms and apply them effectively to real-world datasets.
                </p>
                <a href="https://github.com/codermal7/Countless-Days-Of-ML" target="_blank"
                    class="service_btn btn">Current Repo<i class='bx bx-link'></i></a>
            </div>


            <div class="services-box">
                <i class='bx bx-bar-chart-alt'></i>
                <h3>DSA</h3>
                <p>As an individual who is deeply enthusiastic about DSA, I maintain an active presence on renowned
                    platforms such as LeetCode and GeeksforGeeks to further develop my proficiency in this area. With a
                    track record of solving over 150 questions on LeetCode, I am dedicated to honing my DSA skills and
                    staying at the forefront of algorithmic problem-solving.</p>
                <a href="https://leetcode.com/codermal7/" target="_blank" class="btn">Leetcode<i
                        class='bx bx-link'></i></a>
            </div>
        </div>
    </section>



    <!-- services section design -->


    <section class="portfolio" id="portfolio">
        <!-- <ul class="circles">
            <li></li>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
        </ul> -->
        <h2 style class="heading">Latest <span>Projects</span></h2>
        <div style="z-index: 1;"  class="portfolio-container">
            <div class="portfolio-box">
                <img src="images/proj1weatherlged.jpg" alt="">
                <div class="portfolio-layer">
                    <h4>Weather App</h4>
                    <p>This impressive weather application has been developed using HTML, CSS, and JavaScript by using
                        the Open Weather Map API. Notable features of this weather application include the provision of
                        weather updates for the user's respective city and an aesthetically pleasing CSS design.</p>
                    <a href="https://codermal7.github.io/Weather-App-Project/" target="_blank"><i
                            class='bx bx-link-external'></i></a>
                </div>
            </div>

            <div class="portfolio-box">
                <!-- <img src="images/proj2dappfundeditm.jpg" alt=""> -->
                <!-- <img src="images/proj2dappfund_500x300.png" alt=""> -->
                <!-- <img src="images/proj2dappfund (1).png" alt=""> -->
                <img src="images/proj2dappfund_new.png" alt="">
                <div class="portfolio-layer">
                    <h4>Web Design</h4>
                    <p>Web3 based Secure Crowdfunding Website for Startups.

                        dAppFund(Decentralized Application Fund) is a decentralized crowdfunding website that utilizes
                        Web 3 technology and smart contracts to provide a secure and transparent platform for
                        fundraising.</p>
                    <a href="https://codermal7.github.io/dAppFund/" target="_blank"><i
                            class='bx bx-link-external'></i></a>
                </div>
            </div>

            <div class="portfolio-box">
                <img src="images/calcpiced.jpg" alt="">
                <div class="portfolio-layer">
                    <h4>Awesome Calculator</h4>
                    <p>This remarkable calculator boasts a visually stunning and captivating design crafted exclusively
                        with the utilization of HTML and CSS.</p>
                    <a href="https://codermal7.github.io/Awesome-Calculator/" target="_blank"><i
                            class='bx bx-link-external'></i></a>
                </div>
            </div>

            <div class="portfolio-box">
                <img src="images/dogvscat.jpg" alt="">
                <div class="portfolio-layer">
                    <h4>Dog vs Cat Classifier</h4>
                    <p>Developed a Deep Learning Project "Dog vs. Cat Classifier," utilizing Kaggle's Dog vs. Cat
                        dataset. To enhance the performance and accuracy of the classifier, I leveraged the pre-trained
                        MobileNet V2 model from TensorFlow Hub.</p>
                    <a href="https://colab.research.google.com/drive/1yS6Og8WXHFYwne49wvAP_7UKV53NYj4e?usp=sharing"
                        target="_blank"><i class='bx bx-link-external'></i></a>
                </div>
            </div>
        </div>
    </section>




    <!-- contacts section design -->

    <section class="contact" id="contact">
        <form onsubmit="sendEmail(); reset(); return false;" action="#">
            <h2 class="heading">Contact <span>Me!</span></h2>
            <div class="input-box">
                <input type="text" id="name" placeholder="Full Name">
                <input type="email" id="email" placeholder="Email Address">
            </div>
            <div class="input-box">
                <input type="number" id="phone" placeholder="Mobile Number">
                <input type="text" id="subject" placeholder="Email Subject">
            </div>
            <textarea name="" id="message" cols="30" rows="10" placeholder="Your Message"></textarea>
            <button type="submit" class="btn">Send Message</button>
            <!-- <input type="submit" value="Send Message" class="btn"> -->
        </form>
        <div class="image-container">
            <!-- <img class="cont-img" src="images/desk3 (1).jpg" alt=""> -->
            <!-- <img class="cont-img" src="images/AdobeStock-WozOXajSq3-removebg-preview.png" alt=""> -->
            <img class="cont-img" src="images/contactmewebp.webp" alt="">
        </div>
    </section>



    <!-- footer design -->

    <footer class="site-footer">
        <!-- <ul style="width: inherit;" class="circles">
            <li></li>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
        </ul> -->
        <div class="container">
            <div class="row">
                <div class="col-sm-12 col-md-6">
                    <h2>Message</h2>
                    <p class="text-justify">Didn't like the way it looks 😔? Let me know your views through the contact
                        form or drop me a message on my socials mentioned below.
                    <p style="color: rgb(210, 205, 205);">As I beleive in the saying, "In the realm of self-improvement,
                        constructive criticism is the compass guiding me towards the shores of wisdom"</p>
                    </p>
                </div>
                <div class="col-6 col-md-3">
                    <h2>Interests</h2>
                    <ul class="footer-links ">
                        <li><a href="#site-footer">Web Development</a></li>
                        <li><a href="#site-footer">Web Design</a></li>
                        <li><a href="#site-footer">Machine Learning</a></li>
                        <li><a href="#site-footer">DSA</a></li>
                    </ul>
                </div>
                <div class="col-6 col-md-3">
                    <h2>Quick Links</h2>
                    <ul class="footer-links">
                        <li><a href="#home">Home</a></li>
                        <li><a href="#about">About</a></li>
                        <li><a href="#services">Interests</a></li>
                        <li><a href="#portfolio">Projects</a></li>
                        <li><a href="#contact">Contact</a></li>
                    </ul>
                </div>
            </div>
            <hr class="small">
        </div>
        <div class="container">
            <div class="row">
                <div class="col-md-8 col-sm-6 col-12">
                    <p>Copyright &copy; 2023 by Anuj Kumar Pandey | All Rights Reserved.</p>
                </div>
                <div class="col-md-4 col-sm-6 col-12">
                    <ul class="social-icons">
                        <li><a href="https://www.instagram.com/not_ur_anuj/" target="_blank"><i
                                    class='bx bxl-instagram-alt'></i></a></li>
                        <li><a href="https://twitter.com/not_ur_anuj" target="_blank"><i class='bx bxl-twitter'></i></a>
                        </li>
                        <li><a href="https://www.linkedin.com/in/anuj-kumar-pandey-6151a81b5/" target="_blank"><i
                                    class='bx bxl-linkedin'></i></a></li>
                        <li><a href="https://web.snapchat.com/not_uranuj" target="_blank" class="leet"><i
                                    class='bx bxl-snapchat'></i></a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
        <!-- <div class="footer-iconTop">
            <a href="#home"><i class='bx bx-up-arrow-alt'></i></a>
        </div> -->
    </footer>

    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>

    <!-- custom js -->
    <script src="js/script.js"></script>
    <script src="https://smtpjs.com/v3/smtp.js"></script>
    <script>
        document.addEventListener("contextmenu", (event) => {
            event.preventDefault();
        });
        function sendEmail() {
            var name = document.getElementById("name").value;
            var email = document.getElementById("email").value;
            var subject = document.getElementById("subject").value;
            var phone = document.getElementById("phone").value;
            var message = document.getElementById("message").value;

            if (name === "" || email === "" || subject === "" || phone === "" || message === "") {
                var alertBox = document.createElement("div");
                alertBox.id = "alert";
                alertBox.innerHTML = "Some of the fields are empty 😔 <br> Please fill them first";
                document.body.appendChild(alertBox);

                setTimeout(function () {
                    alertBox.style.opacity = 1;
                }, 10);

                setTimeout(function () {
                    alertBox.style.opacity = 0;
                    setTimeout(function () {
                        alertBox.parentNode.removeChild(alertBox);
                    }, 1000);
                }, 1400);
                return;
            }
            Email.send({
                SecureToken: "1107fb88-13a2-4c24-9466-24e97e2b3418",
                To: 'anuj18.work@gmail.com',
                From: 'anuj18.work@gmail.com',
                Subject: document.getElementById("subject").value,
                Body: "Name: " + document.getElementById("name").value +
                    "<br> Email: " + document.getElementById("email").value +
                    "<br> Phone no: " + document.getElementById("phone").value +
                    "<br> Message: " + document.getElementById("message").value
            }).then(
                message => {
                    var alertBox = document.createElement("div");
                    alertBox.id = "alert";
                    alertBox.innerHTML = "I will read your message shortly <br> Thanks for reaching out ♡";
                    document.body.appendChild(alertBox);

                    setTimeout(function () {
                        alertBox.style.opacity = 1;
                    }, 10);

                    setTimeout(function () {
                        alertBox.style.opacity = 0;
                        setTimeout(function () {
                            alertBox.parentNode.removeChild(alertBox);
                        }, 1000);
                    }, 1400);
                }
            );
        }
    </script>
</body>

</html>
