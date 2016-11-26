# PAGINA-INICIO

<div id="date">
<script type="text/javascript">
//<![CDATA[
function makeArray() {
for (i = 0; i<makeArray.arguments.length; i++)
this[i + 1] = makeArray.arguments[i];
}
var months = new makeArray('Enero','Febrero','Marzo','Abril','Mayo',
'Junio','Julio','Augosto','Septiembre','Octubre','Noviembre','Diciembre');
var date = new Date();
var day = date.getDate();
var month = date.getMonth() + 1;
var yy = date.getYear();
var year = (yy < 1000) ? yy + 1900 : yy;
document.write(day + " " + months[month] + " " + year);
//]]>
</script>
</div>
<div id="credit">
<a href="javascript:document.getElementById('hola').style.display='block';void 0">¿Qué es esto?</a>
</div>
<div id="hola" style="display:none;color:#333333;margin:12px 0 12px 16px;text-shadow:0;">
Hola, esta es mi página de inicio de internet.<br>
Es la que uso cuando me conecto a internet desde un sitio público.<br>
En ella tengo enlaces a los sitios que más visito y un cuadro para buscar en la red con DuckDuckGo.<br>
Puedes usarla si así te parece, para eso guárdala en tus favoritos usando las teclas ContrOl + D.<br>
Puedes probar <a href="http://norfipc.com/internet/inicio-2.html">otra similar</a> u <a href="http://norfipc.com/internet/los-enlaces-mas-importantes-internet.php">otra con bastantes enlaces</a>, además lee <a href="http://norfipc.com/internet/crear-mi-pagina-inicio-para-navegar-internet.php">como crear</a> la tuya propia.<br>
<a href="javascript:document.getElementById('hola').style.display='none';void 0">OCULTAR</a>
</div>

<script type="text/javascript">    
    $(window).load(function() {
        $('#slider').nivoSlider({ borderRadius: 5 });
    });   
</script>
<script type="text/javascript">
$('body').hide();
$('body').fadeIn(2000);
</script>
<script type="text/javascript">
	if(showDate) {
		// Add empty '#clock' div
		$('body').append('<div id="date"></div>');

	  // Update clock
   	setInterval('makeArray()',);
	}
</script>
<div id="foot"></div>
<script src="../js/foot-1.js"></script>
<script type="text/javascript">
  var _gaq = _gaq || [];
  _gaq.push(['_setAccount', 'UA-17996196-1']);
  _gaq.push(['_trackPageview']);

  (function() {
    var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;
    ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js';
    var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
  })();
</script>
</body>
</html>
