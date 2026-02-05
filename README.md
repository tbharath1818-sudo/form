# form
<!DOCTYPE html>
<html>
<head>
  <title>Student database</title>
  <link rel="stylesheet" href="student.css">
</head>
<body>
 
  <h2>Student database</h2>

  <form id="studentForm">
    <input type="text" id="name" placeholder="Name" required>
    <input type="email" id="email" placeholder="Email" required>
    <input type="text" id="mobile" placeholder="Mobile" required>
    <input type="text" id="course" placeholder="Course" required>
    <button type="submit">Add Student</button>
  </form>
	
	<div>
  <table>
    <thead>
      <tr>
        <th>Name</th>
        <th>Email</th>
        <th>Mobile</th>
        <th>Course</th>
        <th>Actions</th>
      </tr>
    </thead>
    <tbody id="studentTable"></tbody>
  </table>
</div>
  <script src="student.js"></script>
</body>
</html>
