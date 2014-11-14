# JQuery Time

>Time è un plug-in jquery per orologio analogico live, l'orologio si ottiene senza l'uso di immagini, ma soltanto con i css.


###How to get started

>HTML Code

    <div id="clock"></div>



>use a div # clock and put the latest version of jquery, the plug-in jquery.time.js and clock.css.

    <link rel="stylesheet" href="css/clock.css">

    <script src="js/jquery-x.x.x.js" type="text/javascript"></script>
     
    <script src="js/jquery.time.js" type="text/javascript"></script>
    
###jquery.time.js     
>At this point, to obtain the clock live:

    <script type="text/javascript">
         $(document).ready(function(){
         $('#clock').time();
            });
    </script>
    
>To change the color of the clock you have to make changes to the style sheet clock.css, 'border-color' of #clock to the edge of the clock, the 'background' of #clock: after the center of the clock, 'background 'of #secondi: after, #ore: after, #minuti: after, respectively, to change the color of the second hand, hour and minute.

###Demo

[demo.html](http://micheledefalco.altervista.org/github/time/demo.html)

