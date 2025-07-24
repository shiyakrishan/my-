<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Student Attendance Record</title>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: #f0f4f8;
      margin: 0;
      padding: 20px;
    }

    .container {
      max-width: 900px;
      margin: auto;
      background: white;
      border-radius: 16px;
      padding: 30px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }

    h1 {
      text-align: center;
      color: #2c3e50;
      margin-bottom: 30px;
    }

    form {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 20px;
      margin-bottom: 30px;
    }

    input, select, button {
      padding: 12px;
      border: 1px solid #ccc;
      border-radius: 8px;
      font-size: 16px;
    }

    button {
      grid-column: span 2;
      background: #2ecc71;
      color: white;
      border: none;
      cursor: pointer;
      transition: background 0.3s ease;
    }

    button:hover {
      background: #27ae60;
    }

    .download-btn {
      margin-top: -20px;
      margin-bottom: 30px;
      text-align: right;
    }

    .download-btn button {
      background: #3498db;
    }

    .download-btn button:hover {
      background: #2980b9;
    }

    table {
      width: 100%;
      border-collapse: collapse;
    }

    th, td {
      padding: 12px;
      text-align: center;
      border-bottom: 1px solid #ddd;
    }

    th {
      background: #2980b9;
      color: white;
    }

    tr:hover {
      background-color: #f1f1f1;
    }

    @media (max-width: 600px) {
      form {
        grid-template-columns: 1fr;
      }

      button {
        grid-column: span 1;
      }

      .download-btn {
        text-align: center;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Student Attendance</h1>

    <form id="attendanceForm">
      <input type="text" id="name" placeholder="Student Name" required />
      <input type="date" id="date" required />
      <input type="time" id="inTime" required />
      <input type="time" id="outTime" required />
      <select id="year" required>
        <option value="">Select Year</option>
        <option value="1st Year">1st Year</option>
        <option value="2nd Year">2nd Year</option>
        <option value="3rd Year">3rd Year</option>
        <option value="4th Year">4th Year</option>
      </select>
      <select id="semester" required>
        <option value="">Select Semester</option>
        <option value="Semester 1">Semester 1</option>
        <option value="Semester 2">Semester 2</option>
        <option value="Semester 3">Semester 3</option>
        <option value="Semester 4">Semester 4</option>
        <option value="Semester 5">Semester 5</option>
        <option value="Semester 6">Semester 6</option>
        <option value="Semester 7">Semester 7</option>
        <option value="Semester 8">Semester 8</option>
      </select>
      <button type="submit">Mark Attendance</button>
    </form>

    <div class="download-btn">
      <button onclick="downloadPDF()">Download PDF</button>
    </div>

    <table id="attendanceTable">
      <thead>
        <tr>
          <th>Name</th>
          <th>Year</th>
          <th>Semester</th>
          <th>Date</th>
          <th>In Time</th>
          <th>Out Time</th>
        </tr>
      </thead>
      <tbody></tbody>
    </table>
  </div>

  <script>
    const form = document.getElementById('attendanceForm');
    const tableBody = document.querySelector('#attendanceTable tbody');

    form.addEventListener('submit', function (e) {
      e.preventDefault();

      const name = document.getElementById('name').value;
      const date = document.getElementById('date').value;
      const inTime = document.getElementById('inTime').value;
      const outTime = document.getElementById('outTime').value;
      const year = document.getElementById('year').value;
      const semester = document.getElementById('semester').value;

      const row = document.createElement('tr');
      row.innerHTML = `
        <td>${name}</td>
        <td>${year}</td>
        <td>${semester}</td>
        <td>${date}</td>
        <td>${inTime}</td>
        <td>${outTime}</td>
      `;

      tableBody.appendChild(row);
      form.reset();
    });

    function downloadPDF() {
      const { jsPDF } = window.jspdf;
      const doc = new jsPDF();
      doc.text("Student Attendance Record", 20, 10);

      const table = document.getElementById('attendanceTable');
      let rows = [];
      const headers = [...table.querySelectorAll('th')].map(th => th.innerText);
      const dataRows = table.querySelectorAll('tbody tr');

      dataRows.forEach(tr => {
        const row = [...tr.querySelectorAll('td')].map(td => td.innerText);
        rows.push(row);
      });

      doc.autoTable({
        head: [headers],
        body: rows,
        startY: 20,
        theme: 'grid'
      });

      doc.save('Attendance_Record.pdf');
    }
  </script>

  <!-- jsPDF AutoTable Plugin -->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf-autotable/3.5.25/jspdf.plugin.autotable.min.js"></script>
</body>
</html>
