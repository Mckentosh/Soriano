<!DOCTYPE html>
<html>
<head>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>

<script>
$(document).ready(function(){
  $("#hide").click(function(){	
    $("p").hide();
  });
  $("#show").click(function(){
    $("p").show();
  });
});
</script>

</head>
<body>

<p>If you click on the "Hide" button, I will disappear.</p>

<button id="hide">Hide</button>
<button id="show">Show</button>

</body>
</html>

<!DOCTYPE html>
<html>
<head>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
<script>
$(document).ready(function(){
  $("button").click(function(){
    $("#div1").fadeIn();
    $("#div2").fadeIn("slow");
    $("#div3").fadeIn(3000);
  });
});
</script>
</head>
<body>

<p>Demonstrate fadeIn() with different parameters.</p>

<button>Click to fade in boxes</button><br><br>

<div id="div1" style="width:80px;height:80px;display:none;background-color:red;"></div><br>
<div id="div2" style="width:80px;height:80px;display:none;background-color:green;"></div><br>
<div id="div3" style="width:80px;height:80px;display:none;background-color:blue;"></div>

</body>
</html>


<!DOCTYPE html>
<html>
<head>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
<script>
$(document).ready(function(){
  $("button").click(function(){
    $("#div1").fadeOut();
    $("#div2").fadeOut("slow");
    $("#div3").fadeOut(3000);
  });
});
</script>
</head>
<body>

<p>Demonstrate fadeOut() with different parameters.</p>

<button>Click to fade out boxes</button><br><br>

<div id="div1" style="width:80px;height:80px;background-color:red;"></div><br>
<div id="div2" style="width:80px;height:80px;background-color:green;"></div><br>
<div id="div3" style="width:80px;height:80px;background-color:blue;"></div>

</body>
</html>

<!DOCTYPE html>

<html>

<head>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>

<script>

$(document).ready(function(){

  $("button").click(function(){

    $("#div1").fadeOut();

    $("#div2").fadeOut("slow");

    $("#div3").fadeOut(3000);

    $("#div4").fadeOut(5000);

    $("#div5").fadeOut(7000);
  });

});
$(document).ready(function(){

  $("button").click(function(){

    $("#div1").fadeIn();

    $("#div2").fadeIn("Slow");

    $("#div3").fadeIn(3000);

  });

});

</script>

</head>

<body>


<p>Demonstrate fadeOut() with different parameters.</p>


<button>Click to fade out boxes</button><br><br>
<button>Click to fadein boxes</button><br><br

<div id="div1" style="border-radius: 50px; width:80px;margin-left:10%; height:80px;background-color:red;"></div><br>

<div id="div2" style="border-radius: 10px; width:80px;margin-left: 30%; height:80px;background-color:green;"></div><br>

<div id="div3" style="border-radius:  50px; margin-left: 50%; width:80px;height:80px;background-color:blue;"></div><br>

<div id="div4" style="border-radius: 10px;margin-left: 70%; width:80px;height:80px;background-color:violet;
transform: rotate( 50deg);"></div>

<div id="div5" style="border-radius: 10px;margin-top: -80px; margin-left: 70%; width:80px;height:80px;background-color:Black;"></div>


</body>

</html>