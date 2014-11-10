# JQuery Time

>Time è un plug-in jquery per olorologio analogico live, l'orologio si ottiene senza l'uso di immagini, ma soltanto con i css.


###Come iniziare

>Codice HTML

    <div id="clock"></div>



>usare un div#clock, e inserire l'ultima versione di jquery , il plug-in jquery.time.js e clock.css.

    <link rel="stylesheet" href="css/clock.css">

    <script src="js/jquery-x.x.x.js" type="text/javascript"></script>
     
    <script src="js/jquery.clock.js" type="text/javascript"></script>
    
###Il Plug-in jquery.time.js     
>A questo punto per ottenere l'orologio live:

    <script type="text/javascript">
         $(document).ready(function(){
         $('#clock').time();
            });
    </script>
    
> Per cambiare il colore dell'orologio bisogna fare delle modifiche al foglio di stile clock.css, 'border-color' di #clock per il bordo dell'orologio, 'background' di #clock:after per il centro dell'orologio, 'background' di #secondi:after, #ore:after, #minuti:after per modificare rispettivamente il colore della lancetta dei secondi, ore e minuti.

###Demo

[demo.html](http://micheledefalco.altervista.org/github/time/demo.html)

