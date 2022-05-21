# Skyline
Séléctionnez un membre et une année : <select id="Membre">
<option value="SuperAtraction">superatraction</option>
<option value="Jeanne123456789">jeanne123456789</option>
  <option value="CaptainPierre">captainpierre</option>
</select><select id="Annee">
<option>2021</option>
</select><input type="button" onclick="ChargerIframe()">
<script type="text/javascript" src="https://code.jquery.com/jquery-3.6.0.min.js"></script><br>
<div id="Iframe"></div><div id="link"></div>
<script type="text/javascript">
  function ChargerIframe(){
  var Nom = $("#Membre").children("option:selected").val();
  var Annee = $("#Annee").children("option:selected").val();;
  
  $("#Iframe").html("<iframe src=\"https://skyline.github.com/"+Nom+"/"+Annee+"\" width=\"500\" height=\"500\"></iframe>");
  $("#link").html("<a href=\"https://skyline.github.com/"+Nom+"/"+Annee+"\">https://skylines.github.com/"+Nom+"/"+Annee+"</a>");
                             }
                             </script>
