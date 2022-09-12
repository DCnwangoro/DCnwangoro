<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <!-- <link rel="stylesheet" href="./Home.css" /> -->
    <script
      src="https://kit.fontawesome.com/ea0631fe92.js"
      crossorigin="anonymous"
    ></script>
    <style>
        *{
    margin: 0;
    box-sizing: border-box;
    padding: 0;

}
body{
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    
}
.hr1{
    height: 3px;
    padding: none;
    border: none;
    background-color: rgb(94, 94, 94);
    margin: 0 10px;
}
hr{
    height: 3px;
    padding: none;
    border: none;
    background-color: rgb(94, 94, 94);
}
@media (max-width:570px) {
    .sec1{
        background-color: #15171d;
    }
    /* first div styling with red color */
    .first-div{
        background-color: rgb(204, 7, 7);
        display: flex;
        padding: 7px;
        justify-content: space-evenly;
    }
    .first-div p{
        color: white;
        font-size: 23px;
        position: relative;
        right: 10vw;
    }
    .first-div .fa-arrow-left,.fa-home{
        color: white;
        font-size: 27px;
    }
    .fa-home{
        position: relative;
        left: 7vw;
    }
    .fa-arrow-left{
        position: relative;
        right: 7vw;
    }
/* second div styling */
    .second-div{
        display: flex;
        justify-content: space-between;
        padding: 10px;
    }
    .sec-div-inner1 small{
        color: rgb(124, 124, 124);
        font-size: 16px;
    }
    .sec-div-inner1 p{
        font-size: 20px;
        color: rgb(231, 231, 231);
    }
    .sec-div-inner2 .won{
        display: flex;
    }
    .sec-div-inner2 .won p{
        position: relative;
        left: 9px;
        font-size: 20px;
        color:#1BB64E;
    }
    .sec-div-inner2 .fa-trophy{
        color:#1BB64E;
    }
    .sec-div-inner2 small{
        color: rgb(124, 124, 124);
        font-size: 16px;
    }
    .sec-div-inner2 h4{
        color:#1BB64E;
        font-size: 21px;

    }
    /* third div styling */
    .third-div{
        display: flex;
        justify-content: space-between;
        padding: 10px;
    }
    .fourth-div{
        display: flex;
        padding: 10px;
        background-image: url("./newpurple77.jpg");
        height: 80px;
        justify-content: space-between;
    }
    .fourth-div img{
        width: 60px;
        position: relative;
        bottom: 10px;

    }
    .fourth-div strong{
        color: rgb(221, 221, 221);
        font-size: 20px;
    }
    .fourth-div button{
        padding: 15px;
        border: none;
        background-color: orange;
        color: black;
        border-radius: 3px;
        font-weight: 700;
    }
/* next section div showing results styling */
.papa{
    padding: 10px;
    display: flex;
    padding: 10px;
    justify-content: space-between;
}
.gamesright{
    position: relative;
    /* right:25%; */
}
.papa .thicker .fa-check-circle{
    position: relative;
    top: 45%;
    color:#1BB64E;
}
.papa small{
    color: rgb(131, 131, 131);
}
.papa .fixture{
    color: black;
}
.papa .tracker{
    display: flex;
    color:#1BB64E;

}
.papa .fa-chart-line{
    margin-right: 5px;
    color:#1BB64E;

}
.papa .fa-check{
    color:#1BB64E;
}
.papa .tracker p{
    font-size: 13px;
}
.papa span{
    color: black;
}
.papa .downdiv{
    background-color: rgb(219, 219, 219);
    border-radius: 3px;
    padding: 7px;
    width: 250px;
}
/* footer section */
.footer{
    padding: 10px;
    justify-content: space-between;
    display: flex;
}
.hrft{
    background-color: rgb(221, 221, 221);
}
.bet-details{
    color:#1BB64E;
}
}






@media (min-width:571px) {
    .sec1{
        background-color: #15171d;
    }
    /* first div styling with red color */
    .first-div{
        background-color: rgb(204, 7, 7);
        display: flex;
        padding: 7px;
        justify-content: space-evenly;
    }
    .first-div p{
        color: white;
        font-size: 23px;
        position: relative;
        right: 10vw;
    }
    .first-div .fa-arrow-left,.fa-home{
        color: white;
        font-size: 27px;
    }
    .fa-home{
        position: relative;
        left: 7vw;
    }
    .fa-arrow-left{
        position: relative;
        right: 7vw;
    }
    /* second div styling */
    .second-div{
        display: flex;
        justify-content: space-between;
        padding: 10px;
    }
    .sec-div-inner1 small{
        color: rgb(124, 124, 124);
        font-size: 16px;
    }
    .sec-div-inner1 p{
        font-size: 20px;
        color: rgb(231, 231, 231);
    }
    .sec-div-inner2 .won{
        display: flex;
    }
    .sec-div-inner2 .won p{
        position: relative;
        left: 9px;
        font-size: 20px;
        color:#1BB64E;
    }
    .sec-div-inner2 .fa-trophy{
        color:#1BB64E;
    }
    .sec-div-inner2 small{
        color: rgb(124, 124, 124);
        font-size: 16px;
    }
    .sec-div-inner2 h4{
        color:#1BB64E;
        font-size: 21px;
    
    }
    /* third div styling */
    .third-div{
        display: flex;
        justify-content: space-between;
        padding: 10px;
    }
    .fourth-div{
        display: flex;
        padding: 10px;
        background-image: url("./newpurple77.jpg");
        height: 80px;
        justify-content: space-between;
    }
    .fourth-div img{
        width: 100px;
        height: 100px;
        position: relative;
        bottom: 30px;
    
    }
    .fourth-div strong{
        color: rgb(221, 221, 221);
        font-size: 20px;
    }
    .fourth-div button{
        padding: 15px;
        border: none;
        background-color: orange;
        color: black;
        border-radius: 3px;
        font-weight: 700;
    }
    /* next section div showing results styling */
    .papa{
    padding: 10px;
    display: flex;
    padding: 10px;
    justify-content: space-between;
    }
    .gamesright{
    position: relative;
    right:25%;
    }
    .papa .thicker .fa-check-circle{
    position: relative;
    top: 45%;
    color:#1BB64E;
    font-size: 30px;
    }
    .papa small{
    color: rgb(131, 131, 131);
    }
    .papa .fixture{
    color: black;
    }
    .papa .tracker{
    display: flex;
    color:#1BB64E;
    
    }
    .papa .fa-chart-line{
    margin-right: 5px;
    color:#1BB64E;
    
    }
    .papa .fa-check{
    color:#1BB64E;
    }
    .papa .tracker p{
    font-size: 13px;
    }
    .papa span{
    color: black;
    }
    .papa .downdiv{
    background-color: rgb(219, 219, 219);
    border-radius: 3px;
    padding: 7px;
    width: 500px;
    }
    /* footer section */
    .footer{
    padding: 10px;
    justify-content: space-between;
    display: flex;
    }
    .hrft{
    background-color: rgb(221, 221, 221);
    }
    .bet-details{
    color:#1BB64E;
    }
    
}
    </style>
  </head>
  <body>
    <section class="sec1">
      <!-- first div -->
      <div class="first-div">
        <i class="fas fa-arrow-left"></i>
        <p>Ticket Details</p>
        <i class="fas fa-home"></i>
      </div>
      <!-- second div -->
      <div class="second-div">
        <div class="sec-div-inner1">
          <small>Ticket ID:765400</small>
          <br />
          <br />
          <p>Multiple</p>
          <br />
          <small>Total Return</small>
        </div>
        <div class="sec-div-inner2">
          <small>12|9|2022|16:35</small>
          <br />
          <br />
          <div class="won">
            <i class="fas fa-trophy"></i>
            <p>Won</p>
          </div>
          <br />
          <h4>918,750.00</h4>
        </div>
      </div>
      <hr class="hr1" />
      <!-- third div -->
      <div class="third-div">
        <div class="sec-div-inner1">
          <small>Total Stake</small>
          <br />
          <br />
          <small>Total Odd</small>
        </div>
        <div class="sec-div-inner2">
          <small>10,000.00</small>
          <br />
          <br />
          <small>91.87</small>
        </div>
      </div>
      <hr class="hr2" />
      <!-- fourth div -->
      <div class="fourth-div">
        <img
          src="./869c607551f2f89cc65bce46cc67d08c-removebg-preview.png"
          alt="trophy"
        />
        <strong>Congratulations!<br />You are Amazing!</strong>
        <div>
            <button>Show off</button>

        </div>
      </div>
    </section>
    <section>
        <div class="papa">
            <div class="thicker">
                <i class="fas fa-check-circle"></i>
            </div>
            <div class="gamesright">
                <div class="updiv">
                    <small>
                        Game ID:14085 |12:9:2022
                    </small>
                    <br>
                    <small class="fixture">Besiktas Istanbul v Istanbul BB</small>
                    <div class="tracker">
                        <i class="fas fa-chart-line"></i>
                        <p>Match Tracker</p>
                    </div>
                    <small>FullTime Score:<span>0:1</span></small>
                </div>
                <div class="downdiv">
                    <small>
                        Pick:<span>0:1 @ 10.50</span><i class="fas fa-check"></i>
                    </small>
                    <br>
                    <small>
                        Market:<span>Correct Score</span>
                    </small>
                    <br>
                    <small>
                        outcome:<span>0:1</span>
                    </small>
                </div>
            </div>
           
        </div>
        <div class="papa">
            <div class="thicker">
                <i class="fas fa-check-circle"></i>
            </div>
            <div class="gamesright">
                <div class="updiv">
                    <small>
                        Game ID:19102 |12:9:2022
                    </small>
                    <br>
                    <small class="fixture"> Olympiakos Nicosia v AEL Limassol</small>
                    <div class="tracker">
                        <i class="fas fa-chart-line"></i>
                        <p>Match Tracker</p>
                    </div>
                    <small>FullTime Score:<span>0:0</span></small>
                </div>
                <div class="downdiv">
                    <small>
                        Pick:<span>0:0 @ 8.75</span><i class="fas fa-check"></i>
                    </small>
                    <br>
                    <small>
                        Market:<span>Correct Score</span>
                    </small>
                    <br>
                    <small>
                        outcome:<span>0:0</span>
                    </small>
                </div>
            </div>
           
        </div>
    </section>
    <br>
   
   
    <hr class="hrft">
    <section>
        <div class="footer">
            <p>Number of Bets:1</p>
            <p class="bet-details">Bet Details</p>
        </div>
    </section>
  </body>
</html>





