

<!DOCTYPE html>
<html>
    <head>
        
        <title>Rohit's Portfolio</title>
        <style>
            body{
                font-family:Arial,sans-serif;
                margin:0;
                padding:0;
                background-color:#f4f4f4;
                color:#333;
            }

            h1,h2{
                color:#2c3e50;
            }

            center{
                max-width:1200px;
                margin:0 auto;
                padding:20px;
            }

            p,h1,h2{
                margin:0;
                padding:0;
            }

            .section{
                margin:50px 0;
            }

            .tech-skills,.certifications{
                display:flex;
                flex-wrap:wrap;
                justify-content:center;
                gap:20px;
            }

            .overlay{
                position:absolute;
                top:0;
                left:0;
                right:0;
                bottom:0;
                background-color: rgba(0, 0, 0, 0.7);
                color: rgb(0, 0, 0);
                display: flex;
                justify-content: center;
                align-items: center;
                opacity: 0;
                transition: opacity 0.3s ease-in;
                font-size: 30px;
            }

            .tech-skills div,.certifications div{
                position: relative;
                background-color: white;
                border:5px solid #3498db;
                border-radius:10px;
                padding:20px;
                font-size:30px;
                width:300px;
                height:100px;
                display:flex;
                justify-content:center;
                align-items:center;
                transition: transform 0.3s, box-shadow 0.3s;
            }

            .certifications div{
                width:400px;
                height:200px;
            }

            .certifications div.wide{
                width:700px;
                height:150px;
            }

            .tech-skills div:hover,.certifications div:hover{
                transform:scale(1.05);
                box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
            }

            .certifications div:hover .overlay{
                opacity: 1;
            }

            .journey{
                text-align:left;
                margin: 0 20%;
            }

            .journey p{
                font-size: 30px;
                margin: 10px 0;
                padding: 10px;
                background-color: white;
                border-left: 5px solid #3498db;
                transition: background-color 0.3s;
            }

            .journey p:hover{
                background-color: #ecf0f1;
            }

                .pyramid-loader {
                    position: relative;
                    width: 300px;
                    height: 300px;
                    display: block;
                    transform-style: preserve-3d;
                    transform: rotateX(-20deg);
                    }

                    .wrapper {
                    position: relative;
                    width: 100%;
                    height: 100%;
                    transform-style: preserve-3d;
                    animation: spin 4s linear infinite;
                    }

                    @keyframes spin {
                    100% {
                        transform: rotateY(360deg);
                    }
                    }

                    .pyramid-loader .wrapper .side {
                    width: 200px;
                    height: 200px;
                    
                    position: absolute;
                    top: 0;
                    left: 0;
                    right: 0;
                    bottom: 0;
                    margin: auto;
                    transform-origin: center top;
                    clip-path: polygon(50% 0%, 0% 100%, 100% 100%);
                    }

                    .pyramid-loader .wrapper .side1 {
                    transform: rotateZ(-30deg) rotateY(90deg);
                    background: conic-gradient( #2BDEAC, #14a843, #D8CCE6, #2F2585);
                    }

                    .pyramid-loader .wrapper .side2 {
                    transform: rotateZ(30deg) rotateY(90deg);
                    background: conic-gradient( #2F2585, #D8CCE6, #F028FD, #2BDEAC);
                    }

                    .pyramid-loader .wrapper .side3 {
                    transform: rotateX(30deg);
                    background: conic-gradient( #2F2585, #D8CCE6, #F028FD, #2BDEAC);
                    }

                    .pyramid-loader .wrapper .side4 {
                    transform: rotateX(-30deg);
                    background: conic-gradient( #2BDEAC, #F028FD, #D8CCE6, #2F2585);
                    }

                    .pyramid-loader .wrapper .shadow {
                    width: 60px;
                    height: 60px;
                    background: #8B5AD5;
                    position: absolute;
                    top: 0;
                    left: 0;
                    right: 0;
                    bottom: 0;
                    margin: auto;
                    transform: rotateX(90deg) translateZ(-40px);
                    filter: blur(12px);
}



        </style>
    </head>
    <body>
        <center>
                    <div class="pyramid-loader">
                        <div class="wrapper">
                        <span class="side side1"></span>
                        <span class="side side2"></span>
                        <span class="side side3"></span>
                        <span class="side side4"></span>
                        <span class="shadow"></span>
                        </div>  
                    </div>

            <div class="section">
                <p style="font-size: 55px; margin-top: 0px;">Welcome to my page</p>
                <h1 style="font-size: 100px; margin-top: 20px;">Hi! I'm Rohit Mishra</h1>
                <p style="font-size: 40px; margin-top: 15px;">A Software Engineer</p>
                <p style="font-size: 40px; margin-top: 20px;">A Web Developer</p>
                <p style="font-size: 40px; margin-top: 20px;">A Video Editor</p>
                <p style="font-size: 40px; margin-top: 20px; margin-bottom:100px;">A Student</p>
            </div>

            <div class="section">
                <h2 style="font-size: 60px; margin-bottom: 30px;">Tech Skills I have</h2>
                <div class="tech-skills">
                    <div>C++</div>
                    <div>HTML</div>
                    <div>CSS</div>
                    <div>Cybersecurity</div>
                    <div>IT Automation</div>
                    <div>Adobe Premiere Pro</div>
                </div>
            </div>

            <div class="section">
                <h2 style="font-size: 60px; margin-bottom: 30px; margin-top: 150px;">Certifications I have</h2>
                <div class="certifications">
                    <div>
                        CPA: Programming Essentials in C++ 
                        <div class="overlay"> From Netacad </div>
                    </div>
                    <div>
                        Google IT Automation (4/6) 
                        <div class="overlay"> From Coursera </div>

                    </div>
                    <div>
                        PCAP: Programming Essentials in Python
                        <div class="overlay"> From Netacad </div>

                    </div>
                        <div class="wide">
                            Introductions to Cybersecurity & CyberSecurity Essentials
                            <div class="overlay"> From Netacad </div>

                        </div>
                </div>
            </div>

            <div class="section">
                <h2 style="font-size: 60px; margin-bottom: 10px;">Journey</h2>
                <div class="journey">
                    <p>2003 Born in Jamshedpur, Jharkhand</p>
                    <p>2007 Started my Education in Baridih High School</p>
                    <p>2014 Shifted to different school AIWC Acadey of Excellence</p>
                    <p>2019 Completed 10th Grade with an aggregate of 93%</p>
                    <p>2019 Completed 12th Grade from Valley View School with an aggregate of 81%</p>
                    <p>2021 Completed 12th Grade from Valley View School with an aggregate of 81%</p>
                    <p>2021 Started my Graduation degree in Bachelor in Technology in Computer Science and Engineering</p>
                </div>
            </div>
        </center>
    </body>
</html>
