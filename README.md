<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>College Assignment Submission Tracker</title>

<style>

body{
    font-family:'Segoe UI',sans-serif;
    background:#f4f6f9;
    margin:0;
    padding:20px;
}

.container{
    max-width:1200px;
    margin:auto;
}

.header{
    background:#0d6efd;
    color:white;
    text-align:center;
    padding:20px;
    border-radius:10px;
    margin-bottom:25px;
}

.header h1{
    margin:0;
}

.header p{
    margin-top:10px;
}

.form-section{
    background:white;
    padding:20px;
    border-radius:10px;
    box-shadow:0 2px 8px rgba(0,0,0,0.1);
}

input,select{
    padding:10px;
    margin:5px;
    border:1px solid #ccc;
    border-radius:5px;
}

button{
    padding:10px 20px;
    background:#0d6efd;
    color:white;
    border:none;
    border-radius:5px;
    cursor:pointer;
}

button:hover{
    background:#084298;
}

.dashboard{
    display:flex;
    gap:20px;
    margin-top:25px;
    margin-bottom:25px;
    flex-wrap:wrap;
}

.card{
    flex:1;
    min-width:200px;
    background:white;
    border-left:5px solid #0d6efd;
    padding:20px;
    border-radius:10px;
    text-align:center;
    box-shadow:0 2px 8px rgba(0,0,0,0.1);
}

.card h3{
    color:#0d6efd;
    margin-bottom:10px;
}

.card p{
    font-size:28px;
    font-weight:bold;
}

.table-section{
    background:white;
    padding:20px;
    border-radius:10px;
    box-shadow:0 2px 8px rgba(0,0,0,0.1);
}

table{
    width:100%;
    border-collapse:collapse;
}

th{
    background:#0d6efd;
    color:white;
    padding:12px;
}

td{
    padding:12px;
    text-align:center;
    border-bottom:1px solid #ddd;
}

tr:hover{
    background:#f1f5ff;
}

.footer{
    text-align:center;
    margin-top:20px;
    color:#666;
}

</style>
</head>

<body>

<div class="container">

<div class="header">
    <h1>College Assignment Submission Tracker</h1>
    <p>Track and Manage Student Assignment Submissions Efficiently</p>
</div>

<div class="form-section">

    <h2>Add Assignment</h2>

    <input type="text" placeholder="Assignment Title">

    <input type="text" placeholder="Subject">

    <input type="date">

    <select>
        <option>Submitted</option>
        <option>Pending</option>
        <option>Late</option>
    </select>

    <button>Add Assignment</button>

</div>

<div class="dashboard">

    <div class="card">
        <h3>Total Assignments</h3>
        <p>25</p>
    </div>

    <div class="card">
        <h3>Submitted</h3>
        <p>15</p>
    </div>

    <div class="card">
        <h3>Pending</h3>
        <p>7</p>
    </div>

    <div class="card">
        <h3>Late</h3>
        <p>3</p>
    </div>

</div>

<div class="table-section">

    <h2>Assignment Records</h2>

    <table>

        <tr>
            <th>Assignment Title</th>
            <th>Subject</th>
            <th>Due Date</th>
            <th>Status</th>
        </tr>

        <tr>
            <td>Angular Mini Project</td>
            <td>Web Technology</td>
            <td>20-06-2026</td>
            <td>Submitted</td>
        </tr>

        <tr>
            <td>Database Report</td>
            <td>DBMS</td>
            <td>25-06-2026</td>
            <td>Pending</td>
        </tr>

        <tr>
            <td>Software Testing Assignment</td>
            <td>Testing</td>
            <td>28-06-2026</td>
            <td>Late</td>
        </tr>

    </table>

</div>

<div class="footer">
    © 2026 College Assignment Submission Tracker
</div>

</di
  v>
