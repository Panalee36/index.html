<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>การทดสอบ MoCA</title>
<style>

        body {

            font-family: Arial, sans-serif;

            margin: 20px;

            padding: 20px;

            background-color: #d4edda;

        }

        .container {

            max-width: 800px;

            background: #ffffff;

            padding: 20px;

            border-radius: 10px;

            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);

        }

        h1 {

            color: #155724;

        }

        .form-group {

            margin-bottom: 15px;

        }

        label {

            font-weight: bold;

        }

        input, select {

            width: 100%;

            padding: 8px;

            margin-top: 5px;

            border: 1px solid #ccc;

            border-radius: 5px;

        }

        button {

            background-color: #28a745;

            color: white;

            padding: 10px 15px;

            border: none;

            border-radius: 5px;

            cursor: pointer;

        }

        button:hover {

            background-color: #218838;

        }
</style>
</head>
<body>
<div class="container">
<h1>การทดสอบ MoCA (Montreal Cognitive Assessment)</h1>
<p>การทดสอบ MoCA เป็นแบบทดสอบที่ใช้ประเมินการทำงานของสมองและความจำ เหมาะสำหรับการคัดกรองภาวะสมองเสื่อมและความบกพร่องทางสติปัญญา</p>
<h2>วัตถุประสงค์ของการทดสอบ</h2>
<p>MoCA ใช้เพื่อประเมินความสามารถทางสติปัญญาด้านต่างๆ เช่น ความจำ การให้เหตุผล ความสนใจ และความสามารถในการแก้ปัญหา</p>
<h2>โครงสร้างของการทดสอบ</h2>
<ul>
<li>การจดจำคำ</li>
<li>การวาดภาพและการเชื่อมโยง</li>
<li>การจดจ่อและความสนใจ</li>
<li>ความเข้าใจด้านภาษา</li>
<li>การคิดและให้เหตุผล</li>
</ul>
<h2>การให้คะแนน</h2>
<p>คะแนนเต็มของ MoCA คือ 30 คะแนน โดยคะแนนที่ต่ำกว่า 26 อาจบ่งชี้ถึงความบกพร่องทางสติปัญญา</p>
<h2>ข้อมูลผู้ใช้งาน</h2>
<form action="moca_test_questions.html" method="GET">
<div class="form-group">
<label for="name">ชื่อ:</label>
<input type="text" id="name" name="name" required>
</div>
<div class="form-group">
<label for="gender">เพศ:</label>
<select id="gender" name="gender" required>
<option value="male">ชาย</option>
<option value="female">หญิง</option>
<option value="other">อื่นๆ</option>
</select>
</div>
<div class="form-group">
<label for="age">กรอกอายุ:</label>
<input type="number" id="age" name="age" min="1" max="120" required>
</div>
<a href="next.html">ถัดไป</a>
</form>
</div>
</body>
</html> 
