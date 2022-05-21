# Skyline
Séléctionnez un membre et une année : <select name="Membre">
<option value="SuperAtraction">SuperAtraction</option>
<option value="Jeanne123456789">Jeanne123456789</option>
  <option value="CaptainPierre">CaptainPierre</option>
</select><select name="Annee">
<option value="1">2021</option>
</select>
<script type="text/javascript" src="https://code.jquery.com/jquery-3.6.0.min.js"></script><br>
<div id="Iframe"></div>
<script type="text/javascript">
  var Nom =document.getElementById("Membre").selectedIndex;
  var Annee =document.getElementById("Membre").selectedIndex;
  
  $("#Iframe").html("<iframe src=\"https://skylines.github.com/"+Nom+"/"+Annee);
                             </script>
