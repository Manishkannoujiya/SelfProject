*{
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
    border: border-box;

}
/*-----------------------first panel------------------------*/
.navbar{
    height: 60px;
    background-color:#0f1111 ;
    color: white;
    display: flex;
    align-items: center;
    justify-content: space-evenly;
    position: fixed;
    width: 100%;
    top: 0;
    left: 0;
    z-index: 9999;

}
.nav-logo{ height: 50px;
    width: 100px;

}
.logo{
    background-image:url("Amazon-Logo-Black.jpg");
    background-size: cover;
    height: 50px;
    width: 100%;

}
.border{
    border: 1.5px solid transparent;
    border-radius: 3px;
}
.border:hover{
    border: 1.5px  solid white;
    cursor: pointer;

}
/** ------------------------box2---------------------**/
.add-first{
    color: #cccccc;
    font-size: .80rem;
    margin-left: 15px;
    margin-top: 4px;
   
}
body{
    padding-top:60px;
}
.add-sec{
    font-size: 1rem;
    margin-left: 3px;
}
.add-icon{
    display: flex;
    align-items: center;
} 
/**---------------------box3---------------------*/
.nav-search{
    display: flex;
    justify-content: space-evenly;
    width: 800px;
    height: 50px;
    border-radius:4px ;
    margin-left: 30px;
}
.nav-search:hover{
    border: 2px solid orange;
}
.search-select{
    background-color: #f3f3f3;
    padding: 5px;
    width: 50px;
    text-align: center;
    border-top-left-radius: 4px;
    border-bottom-left-radius: 4px;
    border: none;

}
.search-input{
    width: 800px;
    font-size: 1rem;
    border: none;
}
.search-icon{
  width: 80px;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 1.2rem;
  background-color: #febd68;
  border-top-right-radius: 4px;
  border-bottom-right-radius: 4px ;
  color: #0f1111;
}
/*-------------------- box4--------------------*/
span{
    font-size: 0.7rem;
    margin-left:20px;
    justify-content: space-evenly;
    align-items: center;
}
.nav-sec{
 font-size: 0.85rem;
 font-weight: 400;
 margin-left: 20px;
 justify-content: space-evenly;
 align-items: center;
}
.nav-return{
    margin-left: 20px;
}
/*box6*/
.nav-cart{
    margin-left: 20px ;
    font-size: 0.74rem;
    font-weight: 600 ;
    }
.nav-cart i{
    font-size: 30px;
}

/*--------------------second- panel--------------------*/
.panel{
    background-color:#222f3d ;
    height: 40px;
    display: flex;
    color: antiquewhite;
    justify-content: space-evenly;
    align-items: center;
}
.panel-apps p{
    display: inline;
    margin-left: 15px;

}
.panel-apps{
    width: 70%;
}
.panel-deals{
    font-size: 1.2rem;
    font-weight: 400;
}
.borders {
    border: 1.5px solid transparent;
}
.borders:hover{
 border: 1.5px solid white;
 border-radius: 2px;
 cursor: pointer;
}

/*-----------------------section 3------------------------*/

.section3{
    background-image: url(independenceday.jpg);
    background-size: contain;
    height: 200px;
  
}
.borderss{
    border: 1.5px solid transparent;
}
.borderss:hover{
    border: 1.5px solid black;
    border-radius: 2px;
}
.msg{
    background-color: rgb(241, 202, 129);
    height: 40px;
    display:flex;
    justify-content: center;
    align-items: center;
    text-decoration: double  ;
}
.msg p{
    text-decoration: line-through;
    display: inline;
}
.msg:hover{
 color: aliceblue;
 cursor: pointer;

}
.for-you{
    height: 160px;
   display: grid;
   gap: var(--size- -3);
   background-color:  white;
   grid-auto-flow: column;
   grid-auto-columns: 10%;
   overflow-x:scroll;
   overscroll-behavior-inline: contain;
}
.item2{
    padding: var(--size-3);
    background: var(--surface-2);
    border-radius: 5px;
    background-size: contain;
    background-repeat: no-repeat;
   margin-top: 20px;
   margin-left: 50px;
   margin-bottom: 8px;
   font-size: 0.8rem;
   cursor: pointer;
}
.item:hover{
    border: 1px groove white ;
    font-size: 1.1rem;
}



  
/*-------------------shop-section--------------------*/
.shop-section{
    margin-top: 20px;
    display: flex;
    justify-content: space-evenly;
    background-color: #dcd2c3;
}
.box{
    border: 2px solid transparent;
    height: 380px;
    width: 25%;
    margin: 12px;
    background-color: white;
    
}

.box1-img{
    background-image: url(oneplus.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    height: 250px;
    margin-top: 1rem;
    margin-bottom: 1rem;
    display: flex;
    justify-content: center;
  
    
}
.box1-content p{
    margin-left: 10px;
    margin-right: 10px;
    color: 
    rgb(174, 165, 250);

}
.box1-img:hover{
    border-color: aliceblue;
    cursor: pointer;
}
.box1-content h2:hover{
 color:rgb(3, 50, 29);
}
.box1-content p:hover{
 text-decoration: underline;
 cursor: pointer;
}
.shop-section:hover{
    border-radius: 1px;
    border-color: #cccccc;
}

.box2-img{
    background-image: url(home.png);
    background-size: contain;
    background-repeat: no-repeat;
    height: 250px;
    margin-top: 1rem;
    margin-bottom: 1rem;
    margin-left: 43px;
    display: flex;
    justify-content: center;
  
    
}
.box2-content p{
    margin-left: 10px;
    margin-right: 10px;
    color: 
    rgb(174, 165, 250);

}
.box2-img:hover{
    border-color: aliceblue;
    cursor: pointer;
}
.box2-content h2:hover{
 color:rgb(3, 50, 29);
}
.box2-content p:hover{
 text-decoration: underline;
 cursor: pointer;
}
.shop-section:hover{
    border-radius: 1px;
    border-color: #cccccc;
}

.box3-img{
    background-image: url(tv.png);
    background-size: contain;
    background-repeat: no-repeat;
    height: 250px;
    margin-top: 2.5rem;
    margin-bottom: 1rem;
    margin-left: 43px;
    display: flex;
    justify-content: center;
  
    
}
.box3-content p{
    margin-left: 10px;
    margin-right: 10px;
    color: 
    rgb(174, 165, 250);
    margin-top: 20px;

}
.box3-img:hover{
    border-color: aliceblue;
    cursor: pointer;
}
.box3-content h2:hover{
 color:rgb(3, 50, 29);
}
.box3-content p:hover{
 text-decoration: underline;
 cursor: pointer;
}
.shop-section:hover{
    border-radius: 1px;
    border-color: #cccccc;
}

.box4-img{
    background-image: url(kitchen.png);
    background-size: contain;
    background-repeat: no-repeat;
    height: 250px;
    margin-top: 1rem;
    margin-bottom: 1rem;
    margin-left: 43px;
    display: flex;
    justify-content: center;
  
    
}
.box4-content p{
    margin-left: 10px;
    margin-right: 10px;
    color: 
    rgb(174, 165, 250);

}
.box4-img:hover{
    border-color: aliceblue;
    cursor: pointer;
}
.box4-content h2:hover{
 color:rgb(3, 50, 29);
}
.box4-content p:hover{
 text-decoration: underline;
 cursor: pointer;
}
.shop-section:hover{
    border-radius: 1px;
    border-color: #cccccc;
}

.box5-img{
    background-image: url(adults.png);
    background-size: cover;
    background-repeat: no-repeat;
    height: 250px;
    margin-top: 1rem;
    margin-bottom: 1rem;
    display: flex;
    justify-content: center;
  
    
}
.box5-content p{
    margin-left: 10px;
    margin-right: 10px;
    color: 
    rgb(174, 165, 250);

}
.box5-img:hover{
    border-color: aliceblue;
    cursor: pointer;
}
.box5-content h2:hover{
 color:rgb(3, 50, 29);
}
.box5-content p:hover{
 text-decoration: underline;
 cursor: pointer;
}
.shop-section:hover{
    border-radius: 1px;
    border-color: #cccccc;
}

.box6-img{
    background-image: url(babyies.png);
    background-size: contain;
    background-repeat: no-repeat;
    height: 250px;
    margin-top: 1rem;
    margin-bottom: 1rem;
    margin-left: 43px;
    display: flex;
    justify-content: center;
  
    
}
.box6-content p{
    margin-left: 10px;
    margin-right: 10px;
    color: 
    rgb(174, 165, 250);

}
.box6-img:hover{
    border-color: aliceblue;
    cursor: pointer;
}
.box6-content h2:hover{
 color:rgb(3, 50, 29);
}
.box6-content p:hover{
 text-decoration: underline;
 cursor: pointer;
}
.shop-section:hover{
    border-radius: 1px;
    border-color: #cccccc;
}

.box7-img{
    background-image: url(women.png);
    background-size: contain;
    background-repeat: no-repeat;
    height: 250px;
    margin-top: 2.5rem;
    margin-bottom: 1rem;
    margin-left: 43px;
    display: flex;
    justify-content: center;
  
    
}
.box7-content p{
    margin-left: 10px;
    margin-right: 10px;
    color: 
    rgb(174, 165, 250);
    margin-top: 20px;

}
.box7-img:hover{
    border-color: aliceblue;
    cursor: pointer;
}
.box7-content h2:hover{
 color:rgb(3, 50, 29);
}
.box7-content p:hover{
 text-decoration: underline;
 cursor: pointer;
}
.shop-section:hover{
    border-radius: 1px;
    border-color: #cccccc;
}

.box8-img{
    background-image: url(company.png);
    background-size: contain;
    background-repeat: no-repeat;
    height: 250px;
    margin-top: 1rem;
    margin-bottom: 1rem;
    margin-left: 43px;
    display: flex;
    justify-content: center;
  
    
}
.box8-content p{
    margin-left: 10px;
    margin-right: 10px;
    color: 
    rgb(174, 165, 250);

}
.box8-img:hover{
    border-color: aliceblue;
    cursor: pointer;
}
.box8-content h2:hover{
 color:rgb(3, 50, 29);
}
.box8-content p:hover{
 text-decoration: underline;
 cursor: pointer;
}
.shop-section:hover{
    border-radius: 1px;
    border-color: #cccccc;
}

/*-----------scroll box 1st----*/
.wrapper{ 
    height: 250px;
   display: grid;
   gap: var(--size- -3);
   background-color:  #dcd2c3;
   grid-auto-flow: column;
   grid-auto-columns: 16.6%;
   overflow-x:scroll;
   overscroll-behavior-inline: contain;
}
.item{
    padding: var(--size-3);
    background: var(--surface-2);
    border-radius: 5px;
    background-size: contain;
    background-repeat: no-repeat;
   margin-top: 10px;
   margin-left: 50px;
   margin-bottom: 8px;
   cursor: pointer;
}
.block{
    margin-top: 10px;
    height: 35px;
    background-color: #dcd2c3;
    display:flex;
    border-radius: 0px;
    align-items: center;
}
.block p{
    color: rgb(119, 115, 246);
}
.block p:hover{
    text-decoration:none;
    cursor: pointer;
    color: #222f3d;
}

/*--------------3shop section------------*/
.box9-img{
    background-image: url(spe.png);
    background-size: cover;
    background-repeat: no-repeat;
    height: 250px;
    margin-top: 1rem;
    margin-bottom: 1rem;
    display: flex;
    justify-content: center;
  
    
}
.box9-content p{
    margin-left: 10px;
    margin-right: 10px;
    color: 
    rgb(174, 165, 250);

}
.box9-img:hover{
    border-color: aliceblue;
    cursor: pointer;
}
.box9-content h2:hover{
 color:rgb(3, 50, 29);
}
.box9-content p:hover{
 text-decoration: underline;
 cursor: pointer;
}
.shop-section:hover{
    border-radius: 1px;
    border-color: #cccccc;
}

.box10-img{
    background-image: url(just.png);
    background-size: contain;
    background-repeat: no-repeat;
    height: 250px;
    margin-top: 1rem;
    margin-bottom: 1rem;
    margin-left: 30px;
    display: flex;
    justify-content: center;
  
    
}
.box10-content p{
    margin-left: 10px;
    margin-right: 10px;
    color: 
    rgb(174, 165, 250);

}
.box10-img:hover{
    border-color: aliceblue;
    cursor: pointer;
}
.box10-content h2:hover{
 color:rgb(3, 50, 29);
}
.box10-content p:hover{
 text-decoration: underline;
 cursor: pointer;
}
.shop-section:hover{
    border-radius: 1px;
    border-color: #cccccc;
}

.box11-img{
    background-image: url(juste.png);
    background-size: contain;
    background-repeat: no-repeat;
    height: 250px;
    margin-top: .7rem;
    margin-bottom: 1rem;
    margin-left: 30px;
    display: flex;
    justify-content: center;
  
    
}
.box11-content p{
    margin-left: 10px;
    margin-right: 10px;
    color: 
    rgb(174, 165, 250);
    margin-top: 20px;

}
.box11-img:hover{
    border-color: aliceblue;
    cursor: pointer;
}
.box11-content h2:hover{
 color:rgb(3, 50, 29);
}
.box11-content p:hover{
 text-decoration: underline;
 cursor: pointer;
}
.shop-section:hover{
    border-radius: 1px;
    border-color: #cccccc;
}

.box12-img{
    background-image: url(head.png);
    background-size: contain;
    background-repeat: no-repeat;
    height: 250px;
    margin-top: 1rem;
    margin-bottom: 1rem;
    margin-left: 43px;
    display: flex;
    justify-content: center;
  
    
}
.box12-content p{
    margin-left: 10px;
    margin-right: 10px;
    color: 
    rgb(174, 165, 250);

}
.box12-img:hover{
    border-color: aliceblue;
    cursor: pointer;
}
.box12-content h2:hover{
 color:rgb(3, 50, 29);
}
.box12-content p:hover{
 text-decoration: underline;
 cursor: pointer;
}
.shop-section:hover{
    border-radius: 1px;
    border-color: #cccccc;
}

/*---------------add section 1st------------*/

.add{
    height: 400px;
    width: 100%;
    background-color: #dcd2c3 ;
    margin-top: 15px;
    background-image: url("Screenshot\ 2024-08-12\ 144903.png");
    padding: 20px 40px 20px 40px;
    background-size: contain;
    background-repeat: no-repeat;
    cursor: pointer;
}


/*-----------scroll bar 2-----------*/
.wrapper1{ 
    height: 250px;
   display: grid;
   gap: var(--size--3);
   background-color: white;
   grid-auto-flow: column;
   grid-auto-columns: 16.5%;
   overflow-x:scroll;
   overscroll-behavior-inline: contain;
   border: 5px solid #dcd2c3;
}


.block1{
    margin-top: 10px;
    height: 35px;
    background-color: #dcd2c3;
    display:flex;
    border-radius: 0px;
    align-items:end;
}
.block1 p{
    color: rgb(119, 115, 246);
    
}
.block1 p:hover{
    text-decoration:none;
    cursor: pointer;
    color: #222f3d;
}

/*-----------------scroll bar3----------------*/

.block2{
    margin-top: 10px;
    height: 35px;
    background-color: #dcd2c3;
    display:flex;
    border-radius: 0px;
    align-items:end;
}
.block2 p{
    color: rgb(119, 115, 246);
    
}
.block2 p:hover{
    text-decoration:none;
    cursor: pointer;
    color: #222f3d;
}
.man{
    padding-left: 60px;
}

/*---------------add section 2nd------------*/

.add1{
    height: 250px;
    width: 100%;
    background-color: #dcd2c3 ;
   
  
}
.image{
    height: 250px;
    width: 70%;
    background-image: url("shirt.png");
    background-size: contain;
    background-repeat: no-repeat;
    cursor: pointer;
    margin: 2% 20% 15% 17%;
}
.foot1{
    margin-top: 10px;
   height: 35px;
   width: 100%;
   background-color: #374758;
   display: flex;
   justify-content: center;
   align-items: center;
   color: #f3f3f3;
   font-size: 1.2rem;

}
.foot1:hover{
    cursor: pointer;
    text-decoration: underline;
}

.foot2{
 height: 380px;
 width: 100%;
 background-color: #222f3d;
 color: #dddddd;
display: flex;
justify-content: space-evenly;
border-bottom: 1px solid #f3f3f3;
}
ul p{
    padding-top: 50px;
    font-size: 1.25rem;
    font-weight: 100px;
}
ul a{
    padding-top: 6px;
    display: block;
    font-size: 0.9rem;
}
a:hover{
    cursor: pointer;
    text-decoration: underline;
}

.foot3{
    height: 120px;
    background-color: #222f3d;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}
.logo1{
    background-image:url("Amazon-Logo-Black.jpg");
    background-size: contain;
    height: 80px;
    width: 150px;
    background-color: #222f3d;

}
.logo1:hover{
    cursor: pointer;
    border: 1px solid white;
}
.foot4{
    height: 300px;
    width: 100%;
    background-color: #0f1111 ;
    color: #dddddd;
    display: flex;
    justify-content: space-evenly;
}
ul p{
 font-weight: 80;
 display: block;
}
.one:hover{
 cursor: pointer;
 text-decoration: underline;
}
.two:hover{
    cursor: pointer;
    text-decoration: underline;
   }
   .three:hover{
    cursor: pointer;
    text-decoration: underline;
   }
   .four:hover{
    cursor: pointer;
    text-decoration: underline;
   }
   .five:hover{
    cursor: pointer;
    text-decoration: underline;
   }
   .six:hover{
    cursor: pointer;
    text-decoration: underline;
   }
   .seven:hover{
    cursor: pointer;
    text-decoration: underline;
   }
   .eight:hover{
    cursor: pointer;
    text-decoration: underline;
   }
   
.foot5{
    height: 30px ;
    width: 100%;
    background-color: #0f1111;
    color: #dddddd;
    display: flex;
    justify-content:center;
    align-items: center;

}
.foot6{
    height: 30px ;
    width: 100%;
    background-color: #0f1111;
    color: #dddddd;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 0.8rem;
}
.first{
    cursor: pointer;
    text-decoration: none;
    font-size: 0.8rem;
    color: white;
}
.second{
    cursor: pointer;
    text-decoration: none;
    font-size: 0.8rem;
    color: white;
}
.third{
    cursor: pointer;
    text-decoration: none;
    font-size: 0.8rem;
    color: white;
}


