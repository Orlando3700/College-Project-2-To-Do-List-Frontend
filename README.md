<!DOCTYPE html>
<html>
  <head>
  	<meta charset="UTF-8">
    <meta http-equiv = "X-UA-Compatible" content="IE-edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">   
  </head>
  <body>
  	<div class="jumbotron">
  	<div class="container text-center">
    <div class="header">
      <h2 style="margin:5px">To Do List</h2>
      
      <select name="priority" id="priority">
  	  <option value="high-priority">High</option>
  	  <option value="medium-priority">Medium</option>
      <option value="low-priority">Low</option>
   </select>
      
      
      
      <input type="text" id = "myInput" placeholder = "New Task">
      <span onclick="newElement()" class="addBtn">Submit</span>
	</div>
</div>
</div>
    
    <ul id="myTasks"> 
</ul>
    
    <script src="JavaScript.js"></script>   
</body>
</html>
