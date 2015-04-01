# simple-to-do-lists
task for rubygarage
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>my task</title>
	<link rel="stylesheet" href="1.css">
</head>
<body>
	<div class="container">
      <p>
        <label for="new-task">Add Item</label><input id="new-task" type="text"><button>Add</button>
      </p>
      
      <h3>Todo</h3>
      <ul id="incomplete-tasks">
        <li><input type="checkbox"><label>Buy a milk</label><input type="text"><button class="edit">Edit</button><button class="delete">Delete</button></li>
        
        <li class="editMode"><input type="checkbox"><label>Call Mam</label><input type="text" value="Call Mam"><button class="edit">Edit</button><button class="delete">Delete</button></li>
        
      </ul>
      
      <h3>Completed</h3>
      <ul id="completed-tasks">
        <li><input type="checkbox" checked><label>Clean the room</label><input type="text"><button class="edit">Edit</button><button class="delete">Delete</button></li>
      </ul>
</div>
<script src="1.js"></script>
</body>
</html>
