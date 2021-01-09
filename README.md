<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Mapl Training Videos </title>
    <link rel="icon" href="https://metalmanauto.com/admin/images/news/1456204098.jpg">
</head>
<body>
    <style>
        *{
            padding: 0;
            margin: 0;
            box-sizing: border-box;
        }
        .modal{
            position: fixed;  top: 0;  left: 0;
            width: 100%; height: 100%;
            background: rgb(0,0,0);
            background-color: rgba(0, 0, 0, 0.6);
            z-index: 1; display: none;
        }
        .modal-content{
            position: absolute;
            width: 80%; padding: 20px;
            height:  80%; top: 80px; left: 10%;
            padding: 34px; margin: auto;
            background-color:snow;
        }
        #close{
            position: absolute;  color: red;
            font-size: 30px; left: 98%; top: 0%; cursor: pointer;
        }
        #close:hover{
            color: rgb(75, 75, 75);
            font-weight: 900;   
        }
        .row{
            position: absolute;
          display:inline-block ;
        
          top: 6%; height: auto;
          padding: 15px;
        }
        @media only screen and (max-width:500px) {
           .slides{
               float: left;
               display: block;
           }
        }
        img:hover {
         transform: scale(1.1);
        }
        img{
            width: 100%; height: 100%;
            display: inline-block;
        }
    .slides {
        position: relative;
        display: inline-block;
        
        width:10%; height: 100px;
        padding: 12px;
    }
    #btn{
        top: 10%;
        background-image: url('/Capture1.JPG');
        background-repeat: no-repeat;
        background-size: cover;
        height: 13%; width: 10%;
        position: absolute; outline: none; border: none;
        left:12px;
        transition: all 1s;
        border-radius: 10%;
        box-shadow: 0px 10px 15px rgb(51, 51, 51);
    }
    #btn:hover{
        transform: scale(1.1);
    }
    .header{
        position: relative;
        width: 100%; 
        background-color: dodgerblue;
    }
    .secbtn{
        background-color: blue;
        background-image: url('/abc.JPG')
    }

    
/* second model */
    #secbtn{
        top: 10%;
        background-image: url('/Capture1.JPG');
        background-repeat: no-repeat;
        background-size: cover;
        height: 13%; width: 10%;
        position: absolute; outline: none; border: none;
        left:222px;
        transition: all 1s;
        border-radius: 10%;
        box-shadow: 0px 10px 15px rgb(51, 51, 51);
    }
.secmodal{
    position: fixed;  top: 0;  left: 0;
            width: 100%; height: 100%;
            background: rgb(0,0,0);
            background-color: rgba(0, 0, 0, 0.6);
            z-index: 1; display: none;
}
.secmodal-content{
    position: absolute;
            width: 80%; padding: 20px;
            height: 50%; top: 80px; left: 10%;
            padding: 34px; margin: auto;
            background-color:snow;
}
#secclose{
    position: absolute;  color: red;
            font-size: 30px; left: 98%; top: 0%; cursor: pointer;
}
#secclose:hover{
    color: rgb(75, 75, 75);
            font-weight: 900;   
}
#secbtn:hover{
    
        transform: scale(1.1);
    
}

.loader{
    position: fixed;
    top: 0;
    left: 0;
    z-index: 99;
    height: 100%;
    width: 100%;
    background-color: lightgrey;
    display: flex;
    justify-content: center;
    align-items: center;
}
.loaderimg{
position: fixed;
width: 20%;
height: 20%;
border-radius: 10px;
animation: rotate 6s forwards infinite;
}
@keyframes rotate{
    from {transform: rotateY(360deg);}
   
}
.ajaxloader{
    position: fixed;
    top: 61%;
    width: 20%;
    height: 4%;
}


.disappear{
    animation: vanish 4s forwards;
}
@keyframes vanish{
    100%{
        opacity: 0;

        visibility: hidden;
    }
    to{
        opacity: 1;
    }
}
    </style>
    <h1 class="header">Mapl</h1>

<div class='loader'>
  <img class="loaderimg" src="https://metalmanauto.com/admin/images/news/1456204098.jpg" alt="">
  <img class="ajaxloader" src="/Images/ajax-loader2.gif" alt="">
</div>


    <button id="btn">open</button>
<div id="myModel" class="modal">
    <div class="modal-content">      
            <span id="close" title="Close">&times;</span> 
        <div id="mymodel" class="row">
                <div class="slides">
                    <a href="https://media.geeksforgeeks.org/wp-content/uploads/20200513195558/Placement100-_-GeeksforGeeks-1.mp4">
                        <img src="/clud1.JPG" alt=""> 
                    </a>
                    <h3>Training1</h3>
                </div>
                <div class="slides">
                    <a href="https://media.geeksforgeeks.org/wp-content/uploads/20200513195558/Placement100-_-GeeksforGeeks-1.mp4">
                        <img src="/clud1.JPG" alt=""> 
                    </a>
                    <h3>Training2</h3>
                </div>
                <div class="slides">
                    <a href="https://media.geeksforgeeks.org/wp-content/uploads/20200513195558/Placement100-_-GeeksforGeeks-1.mp4">
                        <img src="/clud1.JPG" alt=""> 
                    </a>
                    <h3>Training3</h3>
                </div>
                <div class="slides">
                    <a href="https://media.geeksforgeeks.org/wp-content/uploads/20200513195558/Placement100-_-GeeksforGeeks-1.mp4">
                        <img src="/clud1.JPG" alt=""> 
                    </a>
                    <h3>Training4</h3>
                </div>
                <div class="slides">
                    <a href="https://media.geeksforgeeks.org/wp-content/uploads/20200513195558/Placement100-_-GeeksforGeeks-1.mp4">
                        <img src="/clud1.JPG" alt=""> 
                    </a>
                    <h3>Training5</h3>
                </div>
                <div class="slides">
                    <a href="https://media.geeksforgeeks.org/wp-content/uploads/20200513195558/Placement100-_-GeeksforGeeks-1.mp4">
                        <img src="/clud1.JPG" alt=""> 
                    </a>
                    <h3>Training6</h3>
                </div>
                <div class="slides">
                    <a href="https://media.geeksforgeeks.org/wp-content/uploads/20200513195558/Placement100-_-GeeksforGeeks-1.mp4">
                        <img src="/clud1.JPG" alt=""> 
                    </a>
                    <h3>Training7</h3>
                </div>
                <div class="slides">
                    <a href="https://media.geeksforgeeks.org/wp-content/uploads/20200513195558/Placement100-_-GeeksforGeeks-1.mp4">
                        <img src="/clud1.JPG" alt=""> 
                    </a>
                    <h3>Training8</h3>

                </div>
                <div class="slides">
                    <a href="https://media.geeksforgeeks.org/wp-content/uploads/20200513195558/Placement100-_-GeeksforGeeks-1.mp4">
                        <img src="/clud1.JPG" alt=""> 
                    </a>
                    <h3>Training9</h3>

                </div>
                <div class="slides">
                    <a href="https://media.geeksforgeeks.org/wp-content/uploads/20200513195558/Placement100-_-GeeksforGeeks-1.mp4">
                        <img src="/clud1.JPG" alt=""> 
                    </a>
                    <h3>Training10</h3>

                </div>
                <div class="slides">
                    <a href="https://media.geeksforgeeks.org/wp-content/uploads/20200513195558/Placement100-_-GeeksforGeeks-1.mp4">
                        <img src="/clud1.JPG" alt=""> 
                    </a>
                </div>
                <div class="slides">
                    <a href="https://media.geeksforgeeks.org/wp-content/uploads/20200513195558/Placement100-_-GeeksforGeeks-1.mp4">
                        <img src="/clud1.JPG" alt=""> 
                    </a>
                </div>
                <div class="slides">
                    <a href="https://media.geeksforgeeks.org/wp-content/uploads/20200513195558/Placement100-_-GeeksforGeeks-1.mp4">
                        <img src="/clud1.JPG" alt=""> 
                    </a>
                </div>
                <div class="slides">
                    <a href="https://media.geeksforgeeks.org/wp-content/uploads/20200513195558/Placement100-_-GeeksforGeeks-1.mp4">
                        <img src="/clud1.JPG" alt=""> 
                    </a>
                </div>
                <div class="slides">
                    <a href="https://media.geeksforgeeks.org/wp-content/uploads/20200513195558/Placement100-_-GeeksforGeeks-1.mp4">
                        <img src="/clud1.JPG" alt=""> 
                    </a>
                </div>
                <div class="slides">
                    <a href="https://media.geeksforgeeks.org/wp-content/uploads/20200513195558/Placement100-_-GeeksforGeeks-1.mp4">
                        <img src="/clud1.JPG" alt=""> 
                    </a>
                </div>
                <div class="slides">
                    <a href="https://media.geeksforgeeks.org/wp-content/uploads/20200513195558/Placement100-_-GeeksforGeeks-1.mp4">
                        <img src="/clud1.JPG" alt=""> 
                    </a>
                </div>
                <div class="slides">
                    <a href="https://media.geeksforgeeks.org/wp-content/uploads/20200513195558/Placement100-_-GeeksforGeeks-1.mp4">
                        <img src="/clud1.JPG" alt=""> 
                    </a>
                </div>
                <div class="slides">
                    <a href="https://media.geeksforgeeks.org/wp-content/uploads/20200513195558/Placement100-_-GeeksforGeeks-1.mp4">
                        <img src="/clud1.JPG" alt=""> 
                    </a>
                </div>
                <div class="slides">
                    <a href="https://media.geeksforgeeks.org/wp-content/uploads/20200513195558/Placement100-_-GeeksforGeeks-1.mp4">
                        <img src="/clud1.JPG" alt=""> 
                    </a>
                </div>
                <div class="slides">
                    <a href="https://media.geeksforgeeks.org/wp-content/uploads/20200513195558/Placement100-_-GeeksforGeeks-1.mp4">
                        <img src="/clud1.JPG" alt=""> 
                    </a>
                </div>
        </div>
    </div>      
</div>

 <!--2nd button Model -->
<button id="secbtn"></button>
<div id="mySecModel" class="secmodal">
    <div class="secmodal-content">      
            <span id="secclose" class="Close">&times;</span> 
            <div id="mymodel" class="row">
                <div class="slides">
                    <a href="https://media.geeksforgeeks.org/wp-content/uploads/20200513195558/Placement100-_-GeeksforGeeks-1.mp4">
                        <img src="/clud1.JPG" alt=""> 
                    </a>
                </div>
                <div class="slides">
                    <a href="https://media.geeksforgeeks.org/wp-content/uploads/20200513195558/Placement100-_-GeeksforGeeks-1.mp4">
                        <img src="/clud1.JPG" alt=""> 
                    </a>
                </div>
                <div class="slides">
                    <a href="https://media.geeksforgeeks.org/wp-content/uploads/20200513195558/Placement100-_-GeeksforGeeks-1.mp4">
                        <img src="/clud1.JPG" alt=""> 
                    </a>
                </div>
                <div class="slides">
                    <a href="https://media.geeksforgeeks.org/wp-content/uploads/20200513195558/Placement100-_-GeeksforGeeks-1.mp4">
                        <img src="/clud1.JPG" alt=""> 
                    </a>
                </div>
                <div class="slides">
                    <a href="https://media.geeksforgeeks.org/wp-content/uploads/20200513195558/Placement100-_-GeeksforGeeks-1.mp4">
                        <img src="/clud1.JPG" alt=""> 
                    </a>
                </div>

                
            </div>
    </div>      
</div>



    <script>
        // 1st Model
        var model = document.getElementById('myModel');
        var btn = document.getElementById('btn');
        var span = document.getElementById('close');

        btn.onclick = function(){
            model.style.display = 'block';
        }

        span.onclick = function(){
            model.style.display = 'none';
        }

        window.onclick = function(event){
            if(event.target == model){
                model.style.display = 'none';
            }
        }
    </script>

    <script>
    var secmodel = document.getElementById('mySecModel');
        var secbtn = document.getElementById('secbtn');
        var secspan = document.getElementById('secclose');

        secbtn.onclick = function(){
            secmodel.style.display = 'block';
        }

        secspan.onclick = function(){
            secmodel.style.display = 'none';
        }

        window.onclick = function(ev){
            if(ev.target == secmodel){
                secmodel.style.display = 'none';
            }
        }

    </script>

<script>
    var loader = document.querySelector('.loader');
    window.addEventListener('load', vanish);

    function vanish(){
        loader.classList.add('disappear')
    }
</script>
  
</body>
</html>
