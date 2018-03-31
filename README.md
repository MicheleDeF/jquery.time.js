# JQuery Time


>Time is a jQuery plug-in for  digital clock live.

###How to get started

>HTML Code

    <div class="watch"></div>



>use a div with a class whatever (in this case I chose watch), and include the latest version of jquery and the plug-in jquery.time.js.

    <script src="jquery-1.9.1.js" type="text/javascript"></script>     
    <script src="jquery.time.js" type="text/javascript"></script>
     
###jquery.time.js     
>At this point, to obtain the clock live:

    <script type="text/javascript">
         $(document).ready(function(){
         $('.watch').time({font_size:18 , color:'green'}
              );
            });
    </script>
    

<p data-height="268" data-theme-id="0" data-slug-hash="azVEBx" data-default-tab="result" data-user="MicheleDeF" class='codepen'>See the Pen <a href='http://codepen.io/MicheleDeF/pen/azVEBx/'>azVEBx</a> by michele de falco (<a href='http://codepen.io/MicheleDeF'>@MicheleDeF</a>) on <a href='http://codepen.io'>CodePen</a>.</p>

