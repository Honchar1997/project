<!DOCTYPE html>
<html lang="he">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>LifePilot - מצפן לחיים</title>
  <link href="https://fonts.googleapis.com/css2?family=Assistant:wght@400;600;700&display=swap" rel="stylesheet">
  <script src="https://kit.fontawesome.com/a2e00b8a07.js" crossorigin="anonymous"></script>
  <style>
    body {
      margin: 0;
      font-family: 'Assistant', sans-serif;
      background: linear-gradient(135deg, #e0f7fa, #ffffff);
      color: #004d40;
      direction: rtl;
    }

    header {
      background-color: #00acc1;
      padding: 20px;
      text-align: center;
      color: white;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.2);
    }

    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }

    .tagline {
      font-size: 1.2rem;
      margin-top: 5px;
    }

    .video-section {
      text-align: center;
      margin: 40px 20px;
    }

    .video-section iframe {
      width: 100%;
      max-width: 800px;
      height: 450px;
      border-radius: 12px;
      box-shadow: 0 4px 16px rgba(0, 0, 0, 0.2);
    }

    .features {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 40px;
      margin: 40px 20px;
    }

    .feature {
      background-color: #ffffff;
      border-radius: 12px;
      padding: 30px;
      width: 300px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      text-align: center;
      transition: transform 0.3s ease;
    }

    .feature:hover {
      transform: translateY(-5px);
    }

    .feature i {
      font-size: 3rem;
      color: #00838f;
      margin-bottom: 10px;
    }

    .feature h3 {
      margin-bottom: 10px;
      color: #00796b;
    }

    footer {
      background-color: #004d40;
      color: white;
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
      margin-top: 60px;
    }

    .cta-section {
      background-color: #b2ebf2;
      padding: 40px 20px;
      text-align: center;
    }

    .cta-section h2 {
      color: #006064;
      margin-bottom: 20px;
    }

    .cta-section form {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 15px;
      max-width: 400px;
      margin: 0 auto;
    }

    .cta-section input[type="email"] {
      padding: 12px;
      width: 100%;
      border-radius: 8px;
      border: 1px solid #80deea;
      font-size: 1rem;
    }

    .cta-section button {
      padding: 12px 24px;
      background-color: #00acc1;
      color: white;
      border: none;
      border-radius: 8px;
      font-size: 1rem;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    .cta-section button:hover {
      background-color: #00838f;
    }
  </style>
</head>

<body>
  <header>
    <h1>LifePilot</h1>
    <p class="tagline">האפליקציה שתכוון אותך בחיים</p>
  </header>

  <section class="video-section">
    <iframe src="https://www.youtube.com/embed/2unBxh6LZsA" frameborder="0" allowfullscreen></iframe>
  </section>

  <section class="features">
    <div class="feature">
      <i class="fas fa-bullseye"></i>
      <h3>הצבת מטרות</h3>
      <p>קבע מטרות אישיות ועסקיות ותעקוב אחר ההתקדמות שלך בזמן אמת.</p>
    </div>
    <div class="feature">
      <i class="fas fa-calendar-check"></i>
      <h3>ניהול זמן</h3>
      <p>נהל את סדר היום שלך בקלות עם כלים חכמים להתייעלות.</p>
    </div>
    <div class="feature">
      <i class="fas fa-heart"></i>
      <h3>איזון חיים</h3>
      <p>שמור על איזון בין קריירה, משפחה ופנאי עם תמיכה מותאמת אישית.</p>
    </div>
  </section>

  <section class="cta-section">
    <h2>הצטרפו עכשיו וקבלו גישה מוקדמת לאפליקציה!</h2>
    <form>
      <input type="email" placeholder="הכניסו את כתובת המייל שלכם" required>
      <button type="submit">הרשמה</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 LifePilot. כל הזכויות שמורות.</p>
  </footer>
</body>

</html>
