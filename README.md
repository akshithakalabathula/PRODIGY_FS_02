!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Employee CRUD App</title>
    <link rel="stylesheet" href="task2.css">
</head>
<body>

    <div class="container">
        <h1>Employee Management System</h1>

        <form id="employeeForm">
            <input type="hidden" id="employeeId">
            <input type="text" id="name" placeholder="Employee Name" required>
            <input type="text" id="position" placeholder="Position" required>
            <input type="text" id="salary" placeholder="Salary" required>
            <button type="submit">Save Employee</button>
        </form>

        <table>
            <thead>
                <tr>
                    <th>Name</th>
                    <th>Position</th>
                    <th>Salary</th>
                    <th>Actions</th>
                </tr>
            </thead>
            <tbody id="employeeTableBody"></tbody>
        </table>
    </div>

    <script src="task2.js"></script>

</body>
</html>

