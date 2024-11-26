# Landing-Page
 
This is the HTML  Content for the Webpage

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page - Project Using Foundational HTML & CSS</title>
</head>

<body>
    <Header class="head">
        <!-- Navigation Menu  -->
        <nav class="nav_bar">
            <div class="logo">Header Logo</div>
            <div class="nav_item">Header Link 1</div>
            <div class="nav_item">Header Link 2</div>
            <div class="nav_item">Header Link 3</div>
        </nav>
        <!-- Navigation Content  -->
        <div class="container">
            <div class="contain_item1">
                <h2>This Website is awesome</h2>
                <p>This website has home subset that goes here the main title. its smaller font and the color is lower
                    contrast.</p>
                <button>Sign Up</button>
            </div>
            <div class="contain_item2">
                <img src="" alt="Header Example Image">
            </div>
        </div>
        <!-- Main Content  -->
        <main class="main">
            <h3 class="heading">Some random information.</h3>
            <div class="contain_2">
                <div class="items">
                    <div class="box"></div>
                    <p class="box_text">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Est!</p>
                </div>
                <div class="items">
                    <div class="box"></div>
                    <p class="box_text">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Est!</p>
                </div>
                <div class="items">
                    <div class="box"></div>
                    <p class="box_text">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Est!</p>
                </div>
                <div class="items">
                    <div class="box"></div>
                    <p class="box_text">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Est!</p>
                </div>
            </div>
        </main>
        <!-- Sub Section  -->
        <section class="section">
            <p class="quote">
                THis is an inspiring quote, or a testimonial from a customer, Maybe it's just filling up space, or maybe
                people will actually read it. Who knows? All I know is that it looks nice.
            </p>
            <div class="author_name">-Hadi, The Odinist</div>
        </section>
        <!-- Subcribtion Letter -->
         <div class="dialog">
            <div class="content_d">
               <p>Call to action! It's time!</p>
               <p>Sign up for our product by clinking the button right over there!</p>
                <button>Sign Up</button>
            </div>
         </div>
         <!-- Copyright  -->
          <div class="copy">
            Copyright &copy; The Hadi Project 2024
          </div>
    </Header>
</body>

</html>

This is the CSS Code for the Web Page 

@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');

*{
    margin: 0;
    padding: 0;
}

.head{
    background-color: #1F2937;
    height: 35vh;
    /* width: 100vw; */
    color: white; 
}


/* Navigation Menu  */
.nav_bar{
    display: flex;
    justify-content: space-between;
    padding: 12px 40px 29px 40px;
    align-items: center;
}

.logo{
    font-size: 20px;
    color: #F9FAF8;
}

.logo:hover{
    color: rgb(29, 239, 247);
    transition: 0.7s;
    cursor: pointer;
}

.side-by-side{
    display: flex;
    column-gap: 15px;
}

.side-by-side > div:hover{
    color: rgb(29, 239, 247);
    transition: 0.7s;
    cursor: pointer;
}

/* Navigation Content  */
.container{
    display: flex;
    padding: 12px 5vw;
    justify-content: space-between;

}

.contain_item1 > h2 {
    font-size: 38px;
    margin-bottom: 5px;
    font-family: "Roboto", sans-serif;
    font-weight: 900;
    font-style: normal;
}

.contain_item1 > p {
    margin-bottom: 5px;
}

.contain_item1{
    width: 300px;
}
.contain_item2 img{
    width: 370px;
    height: 180px;
}

.contain_item2{
    align-self: center;
    padding-left: 10px;
}

.contain_item1 button{
    background-color: #3882F6;
    border: none;
    color: #F9FAF8;
    padding: 7px 14px;
    cursor: pointer;
    margin: 2px 0;
    border-radius: 10%;
}

 /* Main Content  */

.main{
    margin-top: 5%;
    color: black;
}

.heading{
    text-align: center;
    font-size: 26px;
}

.box{
    width: 100px;
    height: 100px;
    border: 3px solid #3882F6;
    border-radius: 10px;
}

.contain_2{
    display: flex;
    justify-content: space-evenly;
    padding: 20px 40px;
}
.box_text{
    width: 106px;
    text-align: center;
}

/* Sub Section  */

.section{
    background-color: #e5e7eb;
    padding: 10px 0 0 0;
    color: black;
    display: flex;
    flex-direction: column;
    padding: 40px 200px;
}

.author_name{
    align-self: flex-end;
    padding: 10px;
    font-family: "Roboto", sans-serif;
    font-weight: 500;
    font-style: normal;
}

/* Subscribtion Letter  */

.dialog{
    background-color: #3882F6;
    margin: 20px;
    margin-bottom: 0;
    display: flex;
    height: 55px;
    border-radius: 10px;
    justify-content: center;
    align-items: center;
}

.dialog button{
    padding: 4px 12px;
    background-color: #3882F6;
    color: white;
    border: 2px solid white;
    border-radius: 6px;
    cursor: pointer;
    margin-left: 10px;
}

/* Copy right  */

.copy{
    background-color: #1F2937;
    height: 6vh;
    display: flex;
    justify-content: center;
    align-items: center;
}


