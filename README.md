<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <title>منصة الرحاب للقرآن الكريم</title>
  <style>
    body {
      font-family: 'Tahoma', sans-serif;
      background-color: #f7f7f7;
      margin: 0;
      padding: 0;
      text-align: center;
    }
    header {
      background-color: #2e8b57;
      color: white;
      padding: 30px 10px;
    }
    h1 {
      margin: 0;
    }
    .main-buttons {
      margin: 50px auto;
    }
    .main-buttons a {
      display: inline-block;
      background-color: #2e8b57;
      color: white;
      padding: 15px 30px;
      margin: 10px;
      text-decoration: none;
      border-radius: 8px;
      font-size: 18px;
    }
    footer {
      margin-top: 60px;
      padding: 20px;
      background-color: #eee;
      color: #333;
    }
  </style>
</head>
<body>

  <header>
    <h1>منصة الرحاب للقرآن الكريم</h1>
    <p>التسجيل عن بعد</p>
  </header>

  <div class="main-buttons">
    <a href="#">📋 تسجيل طالب جديد</a>
    <a href="#">🔐 دخول الإدارة</a>
  </div>

  <footer>
    <p>📞 للتواصل: 0501234567 | ✉️ info@rehab-quran.edu.sa</p>
  </footer>

</body>
</html>
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <title>تسجيل طالب جديد - منصة الرحاب</title>
  <style>
    body {
      font-family: 'Tahoma', sans-serif;
      background-color: #f0f0f0;
      padding: 20px;
      max-width: 600px;
      margin: auto;
    }
    h2 {
      text-align: center;
      color: #2e8b57;
    }
    form {
      background-color: #fff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    label {
      display: block;
      margin-top: 15px;
      font-weight: bold;
    }
    input, button {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      border-radius: 5px;
      border: 1px solid #ccc;
      font-size: 16px;
    }
    button {
      background-color: #2e8b57;
      color: white;
      border: none;
      margin-top: 20px;
      cursor: pointer;
    }
    button:hover {
      background-color: #276a48;
    }
  </style>
</head>
<body>

  <h2>تسجيل طالب جديد</h2>

  <form action="#" method="POST" enctype="multipart/form-data">
    <label for="studentName">الاسم الكامل للطالب</label>
    <input type="text" id="studentName" name="studentName" required>

    <label for="age">العمر</label>
    <input type="number" id="age" name="age" required>

    <label for="guardianName">اسم ولي الأمر</label>
    <input type="text" id="guardianName" name="guardianName" required>

    <label for="phone">رقم الهاتف</label>
    <input type="tel" id="phone" name="phone" required>

    <label for="email">البريد الإلكتروني</label>
    <input type="email" id="email" name="email" required>

    <label for="photo">صورة الطالب</label>
    <input type="file" id="photo" name="photo" accept="image/*" capture="user" required>

    <button type="submit">إرسال الطلب</button>
  </form>

</body>
</html>
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <title>تم إرسال الطلب</title>
  <style>
    body {
      font-family: 'Tahoma', sans-serif;
      background-color: #eafaf1;
      color: #2e8b57;
      text-align: center;
      padding: 50px;
    }
    h2 {
      font-size: 26px;
    }
    p {
      font-size: 18px;
      margin-top: 20px;
    }
    a {
      display: inline-block;
      margin-top: 30px;
      padding: 10px 20px;
      background-color: #2e8b57;
      color: white;
      text-decoration: none;
      border-radius: 8px;
      font-size: 16px;
    }
    a:hover {
      background-color: #276a48;
    }
  </style>
</head>
<body>

  <h2>🎉 تم إرسال الطلب بنجاح</h2>
  <p>شكرًا لك! تم استلام بيانات الطالب بنجاح، وسيتم التواصل معكم قريبًا من قبل إدارة مدرسة الرحاب.</p>
  <a href="index.html">🔙 الرجوع إلى الصفحة الرئيسية</a>

</body>
</html>
# alrehab<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <title>دخول الإدارة - منصة الرحاب</title>
  <style>
    body {
      font-family: 'Tahoma', sans-serif;
      background-color: #f4f4f4;
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
    }
    form {
      background-color: #fff;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      width: 300px;
    }
    h2 {
      color: #2e8b57;
      margin-bottom: 20px;
      text-align: center;
    }
    input {
      width: 100%;
      padding: 10px;
      margin-top: 10px;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
    button {
      width: 100%;
      padding: 10px;
      margin-top: 20px;
      background-color: #2e8b57;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background-color: #276a48;
    }
  </style>
</head>
<body>

  <form onsubmit="return login(event)">
    <h2>دخول الإدارة</h2>
    <input type="text" id="username" placeholder="اسم المستخدم" required>
    <input type="password" id="password" placeholder="كلمة المرور" required>
    <button type="submit">دخول</button>
  </form>

  <script>
    function login(e) {
      e.preventDefault();
      const user = document.getElementById('username').value;
      const pass = document.getElementById('password').value;

      // بيانات دخول افتراضية
      if (user === 'admin' && pass === '1234') {
        window.location.href = 'dashboard.html';
      } else {
        alert('بيانات الدخول غير صحيحة');
      }
    }
  </script>

</body>
</html>
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <title>لوحة التحكم - منصة الرحاب</title>
  <style>
    body {
      font-family: 'Tahoma', sans-serif;
      background-color: #f0f0f0;
      padding: 20px;
    }
    h2 {
      text-align: center;
      color: #2e8b57;
    }
    .request {
      background-color: white;
      padding: 15px;
      margin: 20px auto;
      border-radius: 10px;
      max-width: 600px;
      box-shadow: 0 0 8px rgba(0,0,0,0.1);
    }
    .request img {
      max-width: 100px;
      border-radius: 5px;
      margin-top: 10px;
    }
    .buttons {
      margin-top: 15px;
    }
    .buttons button {
      margin: 5px;
      padding: 8px 15px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      color: white;
    }
    .accept {
      background-color: #2e8b57;
    }
    .reject {
      background-color: #d9534f;
    }
  </style>
</head>
<body>

  <h2>طلبات تسجيل الطلاب</h2>

  <!-- مثال طلب -->
  <div class="request">
    <strong>الاسم:</strong> محمد أحمد<br>
    <strong>العمر:</strong> 9 سنوات<br>
    <strong>ولي الأمر:</strong> أحمد سعيد<br>
    <strong>الهاتف:</strong> 0501234567<br>
    <strong>البريد:</strong> ahmad@example.com<br>
    <strong>صورة:</strong><br>
    <img src="https://via.placeholder.com/100" alt="صورة الطالب"><br>

    <div class="buttons">
      <button class="accept">✔️ قبول</button>
      <button class="reject">❌ رفض</button>
    </div>
  </div>

</body>
</html>
