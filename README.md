<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <title>نموذج طلب توظيف PikHire</title>
  <link href="https://fonts.googleapis.com/css2?family=Cairo&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Cairo', sans-serif;
      background: #f5f5f5;
      margin: 0;
      padding: 20px;
    }
    .container {
      max-width: 720px;
      margin: auto;
      background: #fff;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 6px 20px rgba(0,0,0,0.08);
    }
    h1 {
      text-align: center;
      margin-bottom: 20px;
      font-size: 24px;
    }
    label {
      display: block;
      margin-top: 14px;
      font-weight: bold;
    }
    input, textarea {
      width: 100%;
      padding: 10px;
      margin-top: 6px;
      border: 1px solid #ccc;
      border-radius: 8px;
    }
    textarea {
      min-height: 100px;
    }
    button {
      margin-top: 20px;
      background: #28a745;
      color: #fff;
      border: none;
      padding: 12px;
      border-radius: 8px;
      cursor: pointer;
      width: 100%;
      font-size: 16px;
    }
    button:hover {
      background: #218838;
    }
    .note {
      font-size: 14px;
      color: #555;
      text-align: center;
      margin-top: 20px;
    }
    .logo {
      display: block;
      margin: 0 auto 20px;
      max-width: 180px;
    }
  </style>
</head>
<body>
  <div class="container">
    <img src="logo.png" alt="شعار PikHire" class="logo">
    <h1>نموذج طلب توظيف PikHire</h1>
    <form action="#" method="POST" enctype="multipart/form-data">
      <label>الاسم</label>
      <input type="text" name="first_name" required>

      <label>الكنية</label>
      <input type="text" name="last_name" required>

      <label>اسم الأب</label>
      <input type="text" name="father_name">

      <label>اسم الأم</label>
      <input type="text" name="mother_name">

      <label>محل الولادة</label>
      <input type="text" name="birth_place">

      <label>تاريخ الولادة</label>
      <input type="date" name="birth_date">

      <label>مكان الإقامة الحالي</label>
      <input type="text" name="current_residence">

      <label>رقم الهاتف</label>
      <input type="tel" name="phone" placeholder="+963..." required>

      <label>المؤهلات العلمية</label>
      <textarea name="qualifications"></textarea>

      <label>الشهادات الدراسية</label>
      <textarea name="certificates"></textarea>

      <label>نبذة عنك</label>
      <textarea name="about"></textarea>

      <label>البريد الإلكتروني</label>
      <input type="email" name="email" required>

      <label>السيرة الذاتية (PDF)</label>
      <input type="file" name="cv" accept=".pdf">

      <button type="submit">إرسال الطلب</button>
    </form>
    <p class="note">
      PikHire هي شركة توظيف خاصة وغير ربحية. التسجيل مجاني ومتاح للجميع، والمنصة مستقلة وغير تابعة لأي جهة.
    </p>
  </div>
</body>
</html>
