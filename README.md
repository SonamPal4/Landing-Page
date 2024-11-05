<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="shortcut icon" href="images/tu.png" type="image/*">
    <script src="script.js"></script>
    <script src="typeWriter.js"></script>
    <title>Spread Linux | Use Linux | Love Linux 🐧</title>
</head>

<body onload="callFunctionsHere()">



    <div class="firstPage">

        <div id="navbardesktop">
            <div class="logo"><a target="__blank" href="https://www.linux.org/">Linux</a></div>
            <div class="navitems">
                <ul>
                    <li><a href="#home">HOME</a></li>
                    <li><a href="#why">WHY LINUX</a></li>
                    <li><a href="#contact">CONTACT</a></li>
                </ul>
            </div>
        </div>

        <div id="navbar">
            <div class="menus" id="close">
                <a href="#home">HOME</a>
                <a href="#why">WHY LINUX</a>
                <a href="#contact">CONTACT</a>
            </div>

            <div class="myHamburgerM">
                <img src="images/bars-solid.svg" onclick="myFunction()" onblur="myFunction()" id="myHamburgerMenu"
                    style="width:20px;padding:5px;" />
            </div>

        </div>
    </div>
    <div class="newpage1" id="home">

        <div class="centerdiv">

            <div class="fh">
                <h1> Linux is <span id="linuxSpan"></span></span></h1>
            </div>

            <div class="sh">
                <img src="images/tu.png" alt="tux penguin using computer">
            </div>

        </div>


        <div class="socialMedia">
            <label>Fun Facts about Linux</label>
            <p id="funfact"></p>
        </div>



    </div>
    </div>
    <div class="newpage2" id="why">
        <div class="whyCenter">
            <div class="mycard">
                <img src="images/icons8-protect-80.png" style="width: 60px;">
                <label>High Security</label>
                <p>Installing and using Linux on your system is the easiest way to avoid viruses and malware. The
                    security aspect was kept in mind when developing Linux and it is much less vulnerable to viruses
                    compared to Windows.</p>
            </div>
            <div class="mycard">
                <img src="images/icons8-gears-80.png" style="width: 60px;" alt="">
                <label>High Stability</label>
                <p>The Linux system is very stable and is not prone to crashes. The Linux OS runs exactly as fast as it
                    did when first installed, even after several years. Most of us must have experienced how a freshly
                    installed Windows system runs extremely fast and the same system becomes slow after around six
                    months to one year.</p>
            </div>
            <div class="mycard">
                <img src="images/icons8-hardware-64.png" style="width: 60px;">
                <label>Runs on any hardware</label>
                <p>Linux makes very efficient use of the system’s resources. Linux installation can be customised for
                    users and for specific hardware requirements. The installation procedure is very flexible, and
                    allows users to choose the modules they want to install. This allows them to install Linux even on
                    old hardware, thus helping in optimal use of all the hardware resources.</p>
            </div>
        </div>
    </div>
    <div class="newpage3" id="contact">

        <div class="addMessage">
            <div class="msg">
                <div class="content">
                    <h2>Send us a message</h2>
                    <p>If you have any queries of any type related to linux, you can send me message from here. It's our
                        pleasure to help you.</p>

                    <input type="text" placeholder="Enter your name" id="">
                    <input type="text" placeholder="Enter your email" id="">
                    <input type="text" placeholder="Enter your message" id="">
                    <button>Send Now</button>
                </div>

            </div>

            <div class="add">
                <div class="content">
                    <img src="images/icons8-address-48.png" alt="">
                    <h2>Address</h2>
                    <address>Kodoli,Kolhapur,Maharashtra</address>
                </div>
            </div>

        </div>

        <div class="socialMedia">
            <img src="images/github.svg" alt="">
            <img src="images/gmail.svg" alt="">
            <img src="images/telegram.svg" alt="">
            <img src="images/whatsapp.svg" alt="">
            <img src="images/phone.svg" alt="">
            <img src="images/instagram.svg" alt="">
        </div>
    </div>

</body>

</html>#  
