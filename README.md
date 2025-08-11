

<!DOCTYPE html>
<html>
<head>
  <title>
    form
  </title>
  
</head>
<body>
  <form method="get" autocomplete="on">
    <fieldset>
      <legend>Persona:</legend>
    <label for="fname">First name</label>
    <input type="text" id="fname" name="fname"placeholder="josh"><br>
    <h4><b>Select your favorite hobbies</b></h4>
    <input type="checkbox" id="hob" name="hobbies"value="Singing">
    <label for="hob">Singing</label><br>
    <input type="checkbox" id="hob" name="hobbies"value="playing">
    <label for="hob">Volleyball</label><br><br>
    <label for="cars"> <b>Select fav cars</\b></label><br>
    <select id="cars" name="favoritecars">Fav cars
        <option value="lambo">lambo</option>
        <option value="audi">audi</option>
    </select><br><br>
    
    
    
    <label for="Self"><b>Tell about yourself</b></label><br><br>
    <textarea name="tell about yourself" rows="10" cols="20">Write</textarea>
    <input type="submit" value="submit">
    </fieldset>
  </form>
  <style>
  input[type=text],select,textarea{
    border: 2px solid grey;
    border-radius:4px;
    width:100%;
    padding:
  }
  .grad{
    background-color: linear-gradient(red,yellow,green);
  }
  input[type=submit]{
    width:100%;
    background-color:tint;
    border:2px solid black;
    border-radius:16px;
  }
  
  
    
  
  </style>
</body></html>
