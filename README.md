*{
    margin: 0;
    padding: 0;                      
}
.main{
    width: 100%;
    background: linear-gradient( to top, rgba(0,0,0,0.5)50%,rgba(0,0,0,0.5)50%),url(1.jpg);
    background-position: center;
    background-size: cover ;
    height: 109vh;
}
.navbar{
    width: 1200px;
    height: 75px;
    margin: auto;

}
.icon{
    width: 200px;
    float: left;
    height: 70px;
}
.logo{
    color: #ff7200;
    font-size: 35px;
    font-family: Arial;
    padding-left: 20px;
    float:left;
    padding-top: 10px;

}
.menu{
    width: 400px;
    float:left;
    height: 70px;

}
ul{
    float:left;
    display: flex;
    justify-content: center;
    align-items: center;
}
ul li {
    list-style: none;
    margin-left: 62px;
    margin-top: 27px;
    font-size: 14px;

}
ul li a{
    text-decoration: none;
    color: #fff;
    font-family: Arial;
    font-weight: bold;
    transition: 0.4s ease-in-out;

}
ul li a:hover{
    color:greenyellow
}
.search{
    width: 330px;
    float:left;
    margin-left:270px;

}
.srch{
    font-family: cursive;
    width: 200px ;
    height: 40px;
    background: transparent;
    border: 1px solid #a2f508;
    color: rgb(22, 21, 21);
    border-right:seagreen;
    font-size: 16px;
    float:left;
    padding: 1px;
    border-bottom-left-radius: 5px;
    border-top-left-radius: 5px;
}
.btn{
    width: 60px;
    height: 40px;
    background: peru;
    border: 20px solid #ec7011;
    margin-top: 13 px;
    color: #fff;
    font-size: 15px;
    border-bottom-right-radius: 5px;
    border-bottom-right-radius: 5px;

}
.btn:focus{
    outline:hotpink;
}
.srch:focus{
    outline: none;
}
.content{
    width: 1200px;
    height: auto;
    margin:auto;
    color: #fff;
    position: relative;
}
.content.par{
    padding-left: 20px;
    padding-bottom: 25px;
    font-family: arial;
    letter-spacing: 1.2px;
    line-height: 30px;
}
.content h1
{
    font-family:'Times New Roman';
    font-size: 50px;
    padding-left: 20px;
    margin-top: 9%;
    letter-spacing: 2px;

}
.content .cn{
    width: 160px;
    height: 40px;
    background: #ff7200;
    border: none;
    margin-bottom: 10px;
    margin-left: 20px;
    font-size: 18px;
    border-radius: 10px;
    cursor: pointer;
    transition: .4s ease;


}
.content .cn a{
    text-decoration:none;
    color:rgb(17, 16, 16);
    transition: .3s ease;

}
.cn:hover{
    background-color: rgb(231, 107, 18);
}
.content span{
    color: rgb(243, 237, 237);
    font-size: 40px;

}
.form{
    width: 250px;
    height: 380px;
    background: linear-gradient(to top, rgba(221, 11, 11, 0.8)50%rgba(228, 10, 10, 0.8)50%);
    position: absolute;
    top: -20px;
    left: 860px;
    border-radius: 10px;
    padding: 25px;
}
.form h2{
    width: 200px;
    font-family: sans-serif;
    text-align: center;
    color: rgb(19, 18, 17);
    font-size: 22px;
    background-color:#facf11;
    border-radius: 10px;
    margin: 2px;
    padding: 8px;

}
.form input{
    width: 240px;
    height: 45px;
    background: transparent;
    border-bottom: 1px solid #ff7200;
    border-top: none;
    border-right: none;
    border-left: none;
    color: rgba(235, 242, 243, 0.939);
    font-size: 20px;
    letter-spacing: 1px;
    margin-top: 30px;
    font-family: sans-serif;


}
.form input:focus{
    outline: none;
}
::placeholder{
    color: rgb(241, 239, 239);
    font-family: arial;
}
.btnn{
    width: 200px;
    height: 40px;
    background: #f0e9e3;
    border: none;
    margin-top: 30px;
    font-size: 18px;
    border-radius: 10px;
    cursor: pointer;
    color: white;
    transition: 1s ease ;
}
.btn:hover{
    background: rgb(231, 230, 226);
    color: darkorange;
}

.btn a{
    text-decoration: none;
    color: rgb(78, 13, 13);
    font-weight: bold;

}
.form.link{
    font-family: Arial;
    font-size: 17px;
    padding-top: 20px;
    text-align: center;
}
.form .link a{
    text-decoration: none;
    color: rgb(19, 18, 18);

}
.liw{
    padding-top: 20px;
    padding-bottom: 30px;
    text-align:center;
}
.icons ion-icon{
    color: rgb(190, 190, 10);
    font-size: 30px;
    padding-left: 14px;
    padding-top: 5px;
    transition: 0.3s ease ;

}
.icon ion-icon:hover{
    color: khaki;
}
