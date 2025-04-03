# unilag
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Unilag</title>
    <link rel="stylesheet" href="style.css">
</head>
<style>
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}

body{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    overflow-x: hidden;
}

#wrapper{
    width: 100%;
    background: rgb(131, 14, 14);
    color: white;
    box-sizing: border-box;
    overflow-x: hidden;
}

.container{
    width: 1500px;
    margin: 0 auto;
    box-sizing: border-box;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav ul li{
    list-style-type: none;
    display: inline-block;
    padding: 15px 2px;
}

#wrapper1{
    width: 97%;
    background: white;
    color: black;
    margin: 0 20px;
    position: fixed;
    z-index: 1px;
    top: 50px;

}

.container1{
    width: 100%;
    box-sizing: border-box;
    display: flex;
    /* justify-content:space-between; */
    align-items: center;
    
}

.logo{
    
    padding: 3px 50px;
    background: rgb(131, 14, 14);
}

.header2 nav ul li{
    display: inline-block;
    padding: 10px 10px;
    font-weight: 700;
}
.fixedheader{
    position: fixed;
    z-index: 10;
    width: 100%;
}
.drop li:hover{
    background: rgb(131, 14, 14);
    color: white;
    border-radius: 5px;
    transition: ease-in-out 1s;
}

.header2{
    margin-left: 30px;
}

.main-bg{
    background:linear-gradient(to top,rgba(0, 0, 1, 0.63),rgba(0, 0, 1, 0.877)),url(image/senate\ house.jfif)no-repeat;
    height: 850px;
    width: 1700px;
    background-size: 100%;
    background-position: center;
    background-attachment: fixed;
}

.display-1{
    font-size: 75px;
    color: rgb(255, 250, 250);
    line-height: 7rem;
    margin-top: -15px;
    font-weight: bolder;
}

.display-2{
    font-size: 25px;
    font-weight: lighter;
    line-height: 35px;
}

.mytextside p h4{
    color: rgb(253, 247, 247);
    font-size: 40px;
    margin-top: 20px;
}

.mytextside{
    margin-top: -650px;
    width: 100%;
    color: white;
    margin-left: 500px;
}

.deed{
    padding-left: 200px;
    padding-bottom: 50px;
    line-height: 20px;
    margin-top: 10px;
}

.star{
    padding-left: 230px;  
    margin-top: -30px;
    padding-bottom: 0px;
}

.dropdown{
    position: relative;
}

.dropdown-content{
    display: none;
    width: 1250px;
    background: rgba(0, 0, 0, 0.932);
    border: 1px solid #fff;
    position: absolute;
    z-index: 1;
    margin-left: -10px;
    margin-top: 8px;
    padding: 20px;
}
.col-md-3 ul li:hover{
    color: orange;
    background: none;
    transition: all 0.2s;
}

.dropdown:hover .dropdown-content{
    display: block;
}

.row{
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.schools ul li{
    display: block;
    padding: 5px 0;
    font-size: 13px;
}

.col-md-3{
    width: 25%;
}

.banks ul li{
    display: block;
    padding: 5px 0;
    font-size: 13px;
}

.hotels ul li{
    display: block;
    padding: 5px 0;
    font-size: 13px;
    font-weight: bold;
}

.acad{
    color: orange;
    font-size: 25px;
    line-height: 70px;
    font-weight: lighter;
}

.frames{
    width: 100%;
    display: flex;
    justify-content: space-between;
    height: 100%;
    margin-top: -250px;
}

.frame-left{
    margin-left: 200px;
}

.frame-right{
    margin-right: 200px;
}

.writeups{
    width: 100%;
    display: flex;
    justify-content: space-between;
    height: 100%;
    align-items: center;
}

.located{
    color: white;
    padding-top: 75px;
    font-size: 18px;
    margin-left: 200px;
    font-weight: bolder;
}

.pursuit{
    color: white;
    padding-top: 55px;
    font-size: 18px;
    margin-right: 200px;
    font-weight: bolder;
}

.dropdown-2{
    position: relative;
}

.dropdown-content-2{
    display: none;
    width: 1250px;
    height: 400px;
    background: rgba(0, 0, 0, 0.932);
    border: 1px solid #fff;
    position: absolute;
    z-index: 1;
    margin-left: -120px;
    margin-top: 8px;
    padding: 20px;
}
.col-md-6 ul li:hover{
    color: orange;
    background: none;
    transition: all 0.2s;
}

.dropdown-2:hover .dropdown-content-2{
    display: block;
}

.row-2{
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.col-md-6{
    width: 50%;
}

.phase-2{
    margin-top: 100px;
    width: 100%;
    height: 100%;
    background: black;
}

.container3{
    width: 1500px;
    margin: 0 auto;
    /* margin-left: px; */
    /* border: 1px solid #333; */
}

.row3{
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.col-md-60{
    width: 100%;
    height: 350px;
    margin: 20px;
    background: black;
    color: white;
    display: flex;  
    justify-content: space-between;
    align-items: center;
}

.text-side3{
    width: 50%;
    margin-left: 110px;
}

.rank{
    font-size: 35px;
    font-weight: bolder;
    line-height: 100px;
}

.accord{
    padding-top: 35px;
    font-size: 22px;
    font-weight: lighter;
}



.world{
    display: flex;
    justify-content: space-around;
    padding: 50px;
}

.first1 img{
    width: 150px;
}

.first2 img{
    margin-right: 400px;
}

.image-side3{
    display: flex;
    gap: 30px;
    margin-right: 100px;
}
.image-side3 img{
    width: 140px;
}

.phase-3{
    margin-bottom: 70px;
    width: 100%;
    height: 100%;
    background: white;
}

.wrapper4{
    width: 100%;
    box-sizing: border-box;
}

.container4{
    margin: 20px 250px;
    
}

.row4{
    display: flex;
    justify-content: space-between;
    align-items: center;
    /* margin-top: 40px; */
}

.col-md-70{
    width: 100%;
    height: 350px;
    background: white;
    color: black;
}

.text-side-4 h3{
    font-weight: bold;
    font-size: 33px;
    margin-top: 60px;
}
.bracket{
    margin-top: 50px;
}

.image-side-4{
    padding-top: 0;
}

.vision{
    margin-bottom: 50px;
}

hr{
    width: 100%;
}

.bold-tiny{
    font-size: 24px;
    line-height: 38px;
    font-weight: bold;
}

.prof{
    font-weight: bold;
    line-height: 50px;
    font-size: 20px;
}

.mbc{
    font-size: 18px;
    line-height: 40px;
}

.vc{
    font-size: 18px;
}

.btn-1{
    margin-top: 50px;
    width: 250px;
    height: 45px;
    font-size: 15px;
    font-weight: bolder;
    background: black;
    color: white;
    border: none;
    border-radius: 3px;
}

.phase-4{
    margin-top: 30px;
}

.wrapper5{
    width: 100%;
   
}

.container7{
    width: 100%;
   
}

.row5{
    width: 100%;
    justify-content: space-between;
    align-items: center;
    /* margin: 0 auto; */
    /* margin-top: 40px; */
}

.col-md-50{
    width: 70%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 50px auto;
}

/* .text-side-5 {
} */

.text-side-5 h4{
    /* margin-top: -20px; */
    font-size: 40px;
    line-height: 100px;
}

.text-side-5 p{
    color: rgba(0, 0, 0, 0.473);
    font-weight: 500;
    line-height: 25px;
}
.stn{
    display: block;  
}

.herf {
    margin-top: 50px;
}

.herf a{
    color: black;
    font-weight: bold;
    font-size: small;
}

.line{
    width: 70%;
    margin: 0 auto;
}
</style>
<body>
    <div class="fixedheader">
        <header>
            <div id="wrapper">
                <div class="container">
                    <div class="mail">
                        communicationunit@unilag.edu.ng
                    </div>
                    <div class="header1">
                        <nav>
                            <ul>
                                <li>Staff</li>
                                <li>|</li>
                                <li>Student</li>
                                <li>|</li>
                                <li>Alumni</li>
                                <li>|</li>
                                <li>Parents</li>
                                <li>|</li>
                                <li>Give to Unilag</li>
                            </ul>
                        </nav>
                    </div>
                </div>
            </div>
        </header>
    </div>


    <section class="main-bg">
        <div id="wrapper1">
            <div class="container1">
                <div class="logo">
                    <img src="image/Group-1.png" alt="">
                </div>
                <div class="header2">
                    <nav>
                        <ul class="drop">
                            <li class="dropdown">ACADEMICS
                                <div class="dropdown-content">
                                    <div class="row">
                                        <div class="col-md-3 cars">
                                            <ul>
                                                <div class="acad">
                                                    <h2>Academics</h2>
                                                </div>
                                                <p>Our academic programs are rigorous and carefully modelled to prepare
                                                    our
                                                    students to be ahead. Our nearly 60,000 students can choose from 80
                                                    undergraduate and 110 postgraduate degree programs plus research and
                                                    study opportunities across the world.That’s why University of Lagos
                                                    is
                                                    the university of first choice and the Nation's pride.
                                                </p>
                                            </ul>
                                        </div>
                                        <div class="col-md-3 hotels">
                                            <ul>
                                                <h3>Faculties</h3>
                                                <li>Faculty of Arts</li>
                                                <li>Faculty of Basic Medical Sciences</li>
                                                <li>Faculty of Management Sciences</li>
                                                <li>Faculty of Clinical Sciences</li>
                                                <li>Faculty of Dental Sciences</li>
                                                <li>Faculty of Education</li>
                                            </ul>
                                        </div>
                                        <div class="col-md-3 banks">
                                            <ul>
                                                <li>Faculty of Engineering</li>
                                                <li>Faculty of Environmental Sciences</li>
                                                <li>Faculty of Law</li>
                                                <li>Faculty of Pharmacy Sciences</li>
                                                <li>Faculty of Social Sciences</li>
                                                <li>Faculty of Sciences</li>
                                            </ul>
                                        </div>
                                        <div class="col-md-3 schools">
                                            <ul>
                                                <h3>Institutes & Colleges</h3>
                                                <li>College of Medicine</li>
                                                <li>Distance Learning Institute</li>
                                                <li>Institute of Continuing Education</li>
                                                <li>Confucius Institute</li>
                                                <li>Enterpreneurship and Skill Development Center (ESDC)</li>
                                                <li>Institute of Maritime Studies</li>
                                                <li>Institute of African & Diaspora Studies</li>
                                                <li>School of Post Graduates Studies</li>
                                                <li>School of Foundation Studies</li>
                                                <li>Library</li>
                                                <li>Unilag Business School (ULBS)</li>
                                                <li>International School (ISL)</li>
                                            </ul>
                                        </div>
                                    </div>
                                </div>
                            </li>
                            <li class="dropdown-2">ABOUT US
                                <div class="dropdown-content-2">
                                    <div class="row-2">
                                        <div class="col-md-6">
                                            <ul>
                                                <div class="about">
                                                    <h2>About Us</h2>
                                                </div>
                                                <p>
                                                    Founded in 1962, the University of Lagos has, for over 5 decades,
                                                    provided qualitative and research-oriented education to Nigerians
                                                    and all those who have entered its domain in search of knowledge.
                                                    The University has built a legacy of excellence and has been
                                                    instrumental in the production of top range graduates and academia
                                                    who have had tremendous impact, directly or indirectly, on growth
                                                    and development in Nigeria.
                                                </p>
                                            </ul>
                                        </div>
                                        <div class="col-md-6">
                                            <div class="history">
                                                <h3>About us</h3>
                                                <hr>
                                                <ul>
                                                    <li>History</li>
                                                    <li>Leadership and Organogram</li>
                                                    <li>vacancies</li>
                                                    <li>Our Awards</li>
                                                    <li>Vice Chancellor's Vision</li>
                                                </ul>
                                            </div>
                                        </div>
                                    </div>

                                </div>
                            </li>
                            <li>UNITS</li>
                            <li>RESERCH INNOVATION</li>
                            <li>RESOURCES</li>
                            <li>ADMISSIONS</li>
                            <li>ENTERPRISES</li>
                            <li>POLICIES</li>
                            <li>TETFUND</li>
                        </ul>
                    </nav>
                </div>
            </div>
        </div>
    </section>

    <section class="showcase">
        <div class="container5">
            <div class="mytextside">
                <div class="star">
                    <img src="image/star.png" alt="">
                </div>
                <div class="deed">
                    <p>
                    <h4>IN DEED AND IN TRUTH</h4>
                    </p>
                </div>
                <h1 class="display-1">The Nation's Pride </h1>
                <p>
                <p>
                <h4 class="display-2">A domain of knowlege and legacy of excellence, Instrumental in <br> the production
                    of academia with
                    tremendous impact in Nigeria.</h4>
                </p>
                </p>
            </div>
            <div class="frames">
                <div class="frame-left">
                    <img src="image/Frame-left.png" alt="">

                </div>
                <div class="frame-right">
                    <img src="image/frame-right.png" alt="">

                </div>
            </div>
        </div>
        <div class="writeups">
            <div class="located">
                <p>Located in Lagos Nigeria <br>Impacting accross the world</p>
            </div>

            <div class="pursuit">
                <p>In pursuit of service to humanity <br>60+ Years of Serving</p>
            </div>
        </div>
    </section>




    <section class="phase-2">
        <div id="wrapper3">
            <div class="container3">
                <div class="row3">
                    <div class="col-md-60">
                        <div class="text-side3">
                            <h2 class="rank">
                                <p>UNILAG Ranking</p>
                                <hr>
                            </h2>
                            <p class="accord">According to the 2023 Times Higher Education World University Ranking and
                                uniRank African University Ranking of the top recognized higher-education institutions
                            </p>
                            <div class="world">
                                <div class="first1">
                                    <img src="image/wordrank.png" alt="">
                                </div>
                                <div class="first2">
                                    <img src="image/unirank.png" alt="">
                                </div>
                            </div>
                        </div>
                        <div class="image-side3">
                            <img src="image/1st.png" alt="">
                            <img src="image/8th.png" alt="">
                            <img src="image/401-500.png" alt="">
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>


    <section class="phase-3">
        <div id="wrapper4">
            <div class="container4">
                <div class="text-side-4">
                    <h3 class="Vision">Vice Chancellor's Vision</h3><br>
                    <hr>
                    <p class="bracket"><img src="image/reverse-bracket.png" alt=""></p>
                </div>
                <div class="row4">
                    <div class="col-md-70">
                        <p class="bold-tiny">
                            To build the most innovative and entrepreneurial university <br> in Africa among the top 200
                            globally, yielding inquiring <br> minds as well as discoveries that are locally and globally
                            <br> impactful.”
                        </p>
                        <p class="prof">Professor Folasade T.Ogunsola</p>
                        <p class="mbc">MBChB, FMCPath, FWACP, FRCPath (UK) PhD (Cardiff) FNAMed, FAMedS, OON, FAS
                        </p>
                        <p class="vc">UNILAG VC</p>
                        <button class="btn-1">Read the entire VC agenda &#8594;</button>
                    </div>
                    <div class="image-side-4">
                        <img src="image/unilag-vc.png" alt="">
                    </div>
                </div>
            </div>
        </div>
    </section>


    <section class="phase-4">
        <div id="wrapper5">
            <div class="container7">
               <div class="row5">
                    <div class="col-md-50">
                        <div class="stn">
                            <div class="text-side-5">
                                <h4>UNILAG at a glance</h4>
                                <p>For over six decades, UNILAG has provided qualitative and research-oriented education to Nigerians and all those who have entered its domain in search of knowledge.</p>
                               
                            </div>
                            <div class="herf">
                                <a href="">Learn More About Our History</a>
                            </div>
                        </div>
                        <div class="image-side-5">
                            <img src="image/glance.png" alt="">
                        </div> 
                    </div>
                    <hr class="line">
               </div>
            </div>
        </div>
        
    </section>
</body>
</html>
