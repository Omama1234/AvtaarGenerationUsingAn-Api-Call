# AvtaarGenerationUsingAn-Api-Call
<!DOCTYPE html>
<html>
<head>
 <title></title>
 <link rel="stylesheet" type="text/css" href="Avtaar.css">
 <link href="https://fonts.googleapis.com/css?family=Luckiest+Guy" rel="stylesheet">
</head>
<body>

<section>
 <h1>WHAT DOES YOUR NAME SAY ABOUT YOUR PERSONALITY?</h1>
        
 <div class="centerDiv">
  <div class="details">
   <label>ENTER YOUR NAME</label><br>
   <input type="text" name="" id="nameid">
  </div>

  <div class="imgdiv">
   <img src="C:/Users/omama/OneDrive/Pictures/macbook_mouse.jpg" width="200" height="200" class="imgchange">
  </div>

  <button> Click Me</button>
  
 </div>
</section>


<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.4.0/jquery.min.js"></script>

<script>
 $(document).ready(function(){
  $('button').click(function(){
   const name = $('#nameid').val();
   alert(name);
   $('.imgchange').attr('src',`https://joeschmoe.io/api/v1/${name}`);
   const b = $('.imgchange');
   console.log(b);

  });
 });
</script>

</body>
</html>
