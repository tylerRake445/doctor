<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Patient Information Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 700px;
            margin: 0 auto;
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            text-align: center;
            color: #333;
        }
        .form-group {
            margin-bottom: 15px;
        }
        label {
            font-weight: bold;
            display: block;
            margin-bottom: 5px;
        }
        input[type="text"], input[type="number"], input[type="date"], select, textarea {
            width: 100%;
            padding: 10px;
            border-radius: 4px;
            border: 1px solid #ccc;
            font-size: 16px;
        }
        textarea {
            resize: vertical;
            height: 100px;
        }
        input[type="submit"] {
            background-color: #4CAF50;
            color: white;
            cursor: pointer;
            border: none;
            padding: 12px 20px;
            font-size: 16px;
            border-radius: 4px;
        }
        input[type="submit"]:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

    <div class="container">
        <h2>Patient Information Form</h2>
        <form action="#" method="POST">
            <div class="form-group">
                <label for="patientName">Patient's Name:</label>
                <input type="text" id="patientName" name="patientName" required>
            </div>
            <div class="form-group">
                <label for="doctorName">Consulting Doctor's Name:</label>
                <input type="text" id="doctorName" name="doctorName" required>
            </div>
            <div class="form-group">
                <label for="age">Age:</label>
                <input type="number" id="age" name="age" required min="1">
            </div>
            <div class="form-group">
                <label for="admissionDate">Date of Admission:</label>
                <input type="date" id="admissionDate" name="admissionDate" required>
            </div>
            <div class="form-group">
                <label for="disease">Disease:</label>
                <textarea id="disease" name="disease" required></textarea>
            </div>
            <div class="form-group">
                <input type="submit" value="Submit">
            </div>
        </form>
    </div>

</body>
</html>
