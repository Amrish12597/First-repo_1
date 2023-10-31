# First-repo_1
<br />
This is my first repository.
<br>
Registration form code
<br />
<br />

<!DOCTYPE html>
<html lang="en">
  <head>  
    <tittle> my first page</tittle> 
  </head>
  <h2 Registration form</h2>
  <body>
    
    <form action="/action.php">
      <input type="text"placeholder="Enter your name ">
      <br />
      <br />
      <input type="password"placeholder="Enter your password ">
      <br />
      <h4>select your class</h4>
      <label for="101">
        <input type="radio"value="class X"name="class"id="101">class X
      </label>
      <br />
      <label for="102"> 
        <input type="radio"value="class XII"name="class"id="102">class XII
      </label>
      <h4><i>select your gender</i></h4>
      <label for="106">
        <input type="radio"value="Male"name="gender"id="106">Male
      </label>
      <br />
      <label for="105">
        <input type="radio"value="female"  name="gender" id="105">female
      
      </label>
      <h4><i>select your fav. subject</i></h4>
      <label for ="math">
        <input type="checkbox"value="math"name="subject"id="101">math
      </label>
      <br />
      <label for ="physiscs">
        <input type="checkbox"value="physics"name="subject"id="107">physics
      </label>
      <br />
      <label for ="english">
        <input type="checkbox"value="english"name="subject"id="104">english
      </label>
      <br />
      <label for ="chemistry">
        <input type="checkbox"value="chemistry"name="subject"id="112">chemistry
      </label>
      <br />
      <label for ="computer science">
        <input type="checkbox"value="computer science"name="subject"id="113">computer science
      </label>
      <br />
      <h4><i>Select your state</i></h4>
      <select name="state">
        <option value="Andhra pradesh">Andhra pradesh</option>
        <option value="madhya pradesh">madhya pradesh</option>
        <option value="himanchal pradesh">himanchal pradesh</option>
        <option value="bihar">bihar</option>
        <option value="uttar pradesh">uttar pradesh</option>
        <option value="chattisgadh">chattisgadh</option>
        <option value="kerla">kerla</option>
      </select>  
        <br / >
        <br />
      <select name="District">
        <option value=" Satna"> satna</option>
        <option value=" Shahdol"> shahdol</option>
        <option value=" Sihor"> sihor</option>
        <option value="Rewa">Rewa </option>
        <option value="Sidhi"> Sidhi</option>
        <option value=" Majholi">Majholi </option>
      </select>  
      <br />
      <br />
      <textarea name="feedback" id="114" paceholder="please give your feedback" rows=10>feedback</textarea>
      <br />
      <input type="submit" value="submit">   
  </body>  
</html>
  