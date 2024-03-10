<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Random Joke generator</title>
    <link rel="stylesheet" href="style.css">
    <script src="dynamic.js"></script>
</head>
<body>
    <div class="container">
       <div class="box">
          <div class="emoji">
            😂
          </div>
          <div class="para">
            <p id="para1">
             Hello World !! <br><br>
             This is random joke generator program 
               😁
            </p>
          </div>
          <div class="bt">
          <button onclick="generateJoke()">
            Random Joke
          </button>
          </div>
    
       </div>
       <div class="yt">
           <a href="https://youtube.com/shorts/A5Bg40TjhdI?si=JEj8RJqUJl-Agulz">You Tube</a>
       </div>
       
    </div>

    <script>
        
        function generateJoke(){
            let randomJoke = Math.random()*16;
            if(randomJoke>0 && randomJoke<=1){
            document.getElementById("para1").innerHTML = "Why do programmers prefer dark mode? </br> </br>Because light attracts bugs !";
            
            
           }
           else if(randomJoke>1 && randomJoke<=2){
            document.getElementById("para1").innerHTML = "A guy walks into a bar and asks for 1.4 root beers. The bartender says</br> “I’ll have to charge you extra, that’s a root beer float”. </br>The guy says “In that case, better make it a double.";
          

           }
           else if(randomJoke>2 && randomJoke<=3){
            document.getElementById("para1").innerHTML = "A programmer puts two glasses on his bedside table before going to sleep.</br> A full one, in case he gets thirsty, and an empty one, in case he doesn’t";
          

           }
           else if(randomJoke>3 && randomJoke<=4){
            document.getElementById("para1").innerHTML = `A ham sandwich walks into a bar and orders a beer,</br></br> <i>bartender says "sorry , we don't serve food here."</i>`;

           }
           else if(randomJoke>4 && randomJoke<=5){
            document.getElementById("para1").innerHTML = `The programmer's wife sent him to the grocery store. </br> Her instructions were : </br> <b>"Buy butter. See if they have eggs. If they do, by 10"</b> </br> So he bought 10. </br>
            <i>Returning with 10 butters, the programmer says, “They had eggs.”</i>`;

           }
           else if(randomJoke>5 && randomJoke<=6){
            document.getElementById("para1").innerHTML = `My mind is like an internet browser, 19 tabs open, 3 of them are frozen, ads popping up everywhere, I have no idea where the music is coming from`;

           }
           else if(randomJoke>6 && randomJoke<=7){
            document.getElementById("para1").innerHTML = `Q : Why did two Java methods get a divorce? ,</br> </br> A : Because they had constant arguments.`;

           }
           else if(randomJoke>7 && randomJoke<=8){
            document.getElementById("para1").innerHTML = `Q : Why did the edge server go bankrupt? </br> </br> A : Because it ran out of cache.`;

           }
           else if(randomJoke>8 && randomJoke<=9){
            document.getElementById("para1").innerHTML = `How many developers does it take to screw in a lightbulb? </br> </br> None. It’s a hardware problem.`;

           }
           else if(randomJoke>9 && randomJoke<=10){
            document.getElementById("para1").innerHTML = `Q : Why did the private classes break up? </br></br> A : Because they never saw each other.`;

           }
           else if(randomJoke>10 && randomJoke<=11){
            document.getElementById("para1").innerHTML = `Why did the Java developer teach his young kids about single quotes? </br></br> <i>Because they build character.</i>`;

           }
           else if(randomJoke>11 && randomJoke<=12){
            document.getElementById("para1").innerHTML = `Q : Why did the JavaScript developer go broke?
            </br></br>A : Because he used typeof on a penny and got a "string" instead of a "number."`;

           }
           else if(randomJoke>12 && randomJoke<=13){
            document.getElementById("para1").innerHTML = `A programmer started to cuss</br>
            Because getting to sleep was a fuss</br>
            As she lay there in bed</br>
            Looping ’round in her head</br>
            was: while(!asleep()) sheep++`;  

           }
           else if(randomJoke>13 && randomJoke<=14){
            document.getElementById("para1").innerHTML = "Q : Why do Java programmers have to wear glasses? </br> </br> A : Because they don't C#(see sharp) ";

           }
          
           else if(randomJoke>14 && randomJoke<=15){
            document.getElementById("para1").innerHTML = `Two bytes meet. The first byte asks, “Are you ill?” </br></br>
            The second byte replies,<i> “No, just feeling a bit off.”</i>`;

           }
          
           
           else {
            document.getElementById("para1").innerHTML = "I love you JAANU 💕";
           }
        }
    </script>
</body>
</html>
