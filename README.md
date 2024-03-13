<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Website Projects To-Do List</title>
<style>
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
  }
  
  .container {
    max-width: 800px;
    margin: 20px auto;
    background-color: #fff;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  }
  
  h1 {
    text-align: center;
  }
  
  .task {
    margin-bottom: 10px;
    padding: 10px;
    background-color: #f9f9f9;
    border-radius: 5px;
    border-left: 4px solid transparent;
  }
  
  .task:hover {
    border-left-color: #007bff;
  }
  
  .priority-high {
    border-left-color: #dc3545; /* Red */
  }
  
  .priority-medium {
    border-left-color: #ffc107; /* Yellow */
  }
  
  .priority-low {
    border-left-color: #28a745; /* Green */
  }
  
  .label {
    font-size: 0.8em;
    background-color: #007bff;
    color: #fff;
    padding: 3px 8px;
    border-radius: 3px;
    margin-left: 5px;
  }
</style>
</head>
<body>

<div class="container">
  <h1>Website Projects To-Do List</h1>
  
  <div class="task priority-high">
    <span class="label">Urgent</span> Create wireframes for homepage
  </div>
  
  <div class="task priority-medium">
    <span class="label">Important</span> Write copy for product descriptions
  </div>
  
  <div class="task priority-low">
    <span class="label">Pending</span> Conduct keyword research for target audience
  </div>
  
  <!-- Add more tasks as needed -->
  
</div>

</body>
</html>
