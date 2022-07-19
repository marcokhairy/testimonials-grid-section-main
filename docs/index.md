<!DOCTYPE html>
<html>
<head>
<style>
    .box{border-radius: 10px;border: 10px solid transparent;}
    body{background-color:#b6bbc0; ;}
    .main{width: 1440px;
     height: 800px;
    display: grid;
    background-color:#b6bbc0;
    gap: 1%;
    grid-template-columns: 24% 24% 24% 24%;
grid-template-rows: 49% 49%;
resize: both;
overflow: auto;
grid-template-areas: 
"Daniel Daniel Jonathan Kira"
"Jeanette Patrick Patrick Kira"}
    .one{grid-area: Daniel;}
    .two{grid-area: Jonathan;}
    .three{grid-area:Jeanette;}
    .four{grid-area:Patrick}
    .five{grid-area:Kira;color : black}
</style>
</head>

<body>
<div class="main">
    <div class="box one" style="background-color:  hsl(263, 55%, 52%);;display:grid;grid-template-rows:30% 30% 40%;border: 20px solid transparent;">
        <div style="font-size:14pt;
        color:white;
        display: flex;
        flex-direction: row;">
        <img src="image-daniel.jpg"style="
            border-radius:50px
            ;display: block;
            width:50px;height:50px;
            position: relative;top:25px;">
        <div style="position: relative;left: 25px;top:20px;line-height: 1px;"><p>Daniel Clifford</p>
         <p style="color:white;opacity: 50%;line-height: .5px;-webkit-text-stroke: .2px  black;">Verified Graduate</p></div>
         </div>
        <div style="font-size: 20pt;color: white;"><strong>
            I received a job offer mid-course, and the subjects I learned were current, if not more so, 
            in the company I joined. I honestly feel I got every penny’s worth.</strong></div>
        <div style="font-size:14pt ;color: white;opacity: 75%;"><strong>  “ I was an EMT for many years before I joined the bootcamp. I’ve been looking to make a 
            transition and have heard some people who had an amazing experience here. I signed up 
            for the free intro course and found it incredibly fun! I enrolled shortly thereafter. 
            The next 12 weeks was the best - and most grueling - time of my life. Since completing 
            the course, I’ve successfully switched careers, working as a Software Engineer at a VR startup. ”          
              </strong>
            </div>
        </div>
<div class="box two" style="background-color: hsl(217, 19%, 35%);display:grid;grid-template-rows:30% 30% 40%;border: 20px solid transparent;">
    <div style="font-size:14pt;
    color:white;
    display: flex;
    flex-direction: row;">
    <img src="image-jonathan.jpg"style="
        border-radius:50px
        ;display: block;
        width:50px;height:50px;
        position: relative;top:25px;">
    <div style="position: relative;left: 25px;top:20px;line-height: 1px;"><p> Jonathan Walters</p>
     <p style="color:white;opacity: 50%;line-height: .5px;-webkit-text-stroke: .2px  black;">Verified Graduate</p></div>
     </div>
    <div style="font-size: 20pt;color: white;"><strong>
         The team was very supportive and kept me motivated.</strong></div>
    <div style="font-size:14pt ;color: white;opacity: 75%;"><strong> 
        “ I started as a total newbie with virtually no coding skills. I now work as a mobile engineer 
        for a big company. This was one of the best investments I’ve made in myself. ”
          </strong>
        </div>
</div>
 <div class="box three"style="background-color:white;
          display:grid;grid-template-rows:30% 30% 40%">   
          <div style="font-size:17pt;color:black;display: flex;flex-direction: row;"><img src="image-jeanette.jpg"style="border-radius:50px
          ;display: block;
          width:50px;height:50px;
          position: relative;top:25px;">
              <div style="position: relative;left: 25px;top:20px;line-height: 1px;"><p> Jeanette Harmon</p>
              <p style="color:black;opacity: 50%;line-height: .5px;-webkit-text-stroke: .2px  black;">Verified Graduate</p></div>
            </div>
          <div style="font-size: 20pt;color: black;"><strong>An overall wonderful and rewarding experience</strong></div>
          <div style="font-size:14pt ;color: black;opacity: 75%;"><strong> “ Thank you for the wonderful experience! I now have a job I really enjoy, and make a good living 
            while doing something I love. ”</strong></div>
</div>
<div class="box four" style="background-color:  hsl(219, 29%, 14%);display:grid;grid-template-rows:30% 30% 40%;border: 20px solid transparent;">
<div style="font-size:14pt;
color:white;
display: flex;
flex-direction: row;">
<img src="image-patrick.jpg"style="
    border-radius:50px
    ;display: block;
    width:50px;height:50px;
    position: relative;top:25px;">
<div style="position: relative;left: 25px;top:20px;line-height: 1px;"><p>Patrick Abrams</p>
 <p style="color:white;opacity: 50%;line-height: .5px;-webkit-text-stroke: .2px  black;">Verified Graduate</p></div>
 </div>
<div style="font-size: 20pt;color: white;"><strong>
        Awesome teaching support from TAs who did the bootcamp themselves. Getting guidance from them and 
        learning from their experiences was easy.</strong></div>
<div style="font-size:14pt ;color: white;opacity: 75%;"><strong> “ The staff seem genuinely concerned about my progress which I find really refreshing. The program 
        gave me the confidence necessary to be able to go out in the world and present myself as a capable 
        junior developer. The standard is above the rest. You will get the personal attention you need from 
        an incredible community of smart and amazing people. ”
      </strong>
    </div>
</div>
<div class="box five"style="background-color:white;
display:grid;grid-template-rows:15% 20% 65%">   
<div style="font-size:17pt;color:black;display: flex;flex-direction: row;"><img src="image-kira.jpg"style="border-radius:50px
;display: block;
width:50px;height:50px;
position: relative;top:25px;">
    <div style="position: relative;left: 25px;top:20px;line-height: 1px;"><p>Kira Whittle</p>
    <p style="color:black;opacity: 50%;line-height: .5px;-webkit-text-stroke: .2px  black;">Verified Graduate</p></div>
  </div>
<div style="font-size: 20pt;color: #7b7e86;"><strong>Such a life-changing experience. Highly recommended!</strong></div>
<div style="font-size:14pt ;color: black;opacity: 75%;"><strong>“ Before joining the bootcamp, I’ve never written a line of code. I needed some structure from 
    professionals who can help me learn programming step by step. I was encouraged to enroll by a former 
    student of theirs who can only say wonderful things about the program. The entire curriculum and staff 
    did not disappoint. They were very hands-on and I never had to wait long for assistance. The agile team 
    project, in particular, was outstanding. It took my learning to the next level in a way that no tutorial 
    could ever have. In fact, I’ve often referred to it during interviews as an example of my developent 
    experience. It certainly helped me land a job as a full-stack developer after receiving multiple offers. 
    100% recommend! ”</strong></div>
</div>
</div>
</body>
</html>
