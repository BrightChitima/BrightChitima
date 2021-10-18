<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

input[type=text], select,  textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 4px;
  resize: vertical;
}




input[type=submit] {
  background-color: #04AA6D;
  color: white;
  padding: 12px 20px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  float: center;
  width: 100%;
}

input[type=submit]:hover {
  background-color: #45a049;
}

.center {
  margin: auto;
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px;
  width: 50%;
 

}

.col-25 {
  float: left;
  width: 25%;
  margin-top: 6px;
}

.col-75 {
  float: left;
  width: 75%;
  margin-top: 6px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive layout - when the screen is less than 600px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .col-25, .col-75, input[type=submit] {
    width: 100%;
    margin-top: 0;
  }
}
</style>
</head>
<body>




<div class="center">
  <h2>Add students to a couse</h2>
  <form>
    <div class="row">
       <div class="col-75">
         <p>Select a Course</p>
        <select id="course" name="course">
          <option value="--select--">--select--</option >
          <option value="course 1">course 1</option >
          <option value="course 2">course 2</option>
          <option value="course 3">course 3</option>
        </select>
      </div>

    <div class="row">
       <div class="col-75">
         <p>Number of Students to enroll</p>
        <input type="text" id="Number of students" name="Number of students" placeholder="Number of Students">
      </div>
       <div class="row">
       <div class="col-75">
        
        <input type="submit" value="Enroll Students" >
      </div>
      <br><br>
      
    
  </form>
    </div>
</div>


  
    
  

</body>

</html>

