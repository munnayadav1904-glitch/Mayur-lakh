<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Mayur-lakh | Study Stationery</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
    }

    body {
      background: #f5f3ee;
      color: #222;
    }

    header {
      background: #111;
      color: white;
      padding: 20px;
      text-align: center;
    }

    header h1 {
      font-size: 30px;
      letter-spacing: 2px;
    }

    header p {
      margin-top: 7px;
      color: #ddd;
    }

    .hero {
      text-align: center;
      padding: 55px 20px;
      background: linear-gradient(135deg, #fff, #eee8dc);
    }

    .hero h2 {
      font-size: 38px;
      margin-bottom: 15px;
    }

    .hero p {
      max-width: 650px;
      margin: auto;
      line-height: 1.6;
      font-size: 17px;
    }

    .join-box {
      max-width: 500px;
      margin: 35px auto;
      background: white;
      padding: 30px;
      border-radius: 18px;
      box-shadow: 0 5px 25px rgba(0,0,0,0.12);
    }

    .join-box h3 {
      text-align: center;
      font-size: 26px;
      margin-bottom: 10px;
    }

    .join-box p {
      text-align: center;
      color: #666;
      margin-bottom: 25px;
    }

    input, select {
      width: 100%;
      padding: 14px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 10px;
      font-size: 16px;
    }

    button {
      width: 100%;
      padding: 15px;
      border: none;
      border-radius: 10px;
      background: #111;
      color: white;
      font-size: 17px;
      cursor: pointer;
    }

    button:hover {
      background: #333;
    }

    #message {
      display: none;
      text-align: center;
      margin-top: 20px;
      color: green;
      font-weight: bold;
    }

    .products {
      padding: 40px 20px;
      text-align: center;
    }

    .products h2 {
      margin-bottom: 25px;
      font-size: 28px;
    }

    .cards {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 18px;
    }

    .card {
      background: white;
      width: 180px;
      padding: 25px 15px;
      border-radius: 15px;
      box-shadow: 0 3px 15px rgba(0,0,0,0.08);
    }

    .card .emoji {
      font-size: 45px;
      margin-bottom: 12px;
    }

    footer {
      background: #111;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 30px;
    }
  </style>
</head>

<body>

  <header>
    <h1>MAYUR-LAKH</h1>
    <p>Future Study Stationery Brand</p>
  </header>

  <section class="hero">
    <h2>Study Better. Create Better.</h2>

    <p>
      Mayur-lakh is a future study-stationery brand focused on
      creative, useful and attractive products for students.
      Join us and be among the first people to know about our
      upcoming stationery products.
    </p>
  </section>

  <section class="join-box">

    <h3>Join Mayur-lakh</h3>

    <p>
      Register your interest for our upcoming stationery products.
    </p>

    <form onsubmit="joinWebsite(event)">

      <input
        type="text"
        id="name"
        placeholder="Your Name"
        required
      >

      <select id="product" required>
        <option value="">What are you interested in?</option>
        <option value="Pens">Pens</option>
        <option value="Pencils">Pencils</option>
        <option value="Erasers">Erasers</option>
        <option value="Sharpeners">Sharpeners</option>
        <option value="Notebooks">Notebooks</option>
        <option value="All Stationery">All Stationery</option>
      </select>

      <button type="submit">
        JOIN NOW
      </button>

    </form>

    <div id="message">
      🎉 Thank you for joining Mayur-lakh!
    </div>

  </section>

  <section class="products">

    <h2>Coming Soon</h2>

    <div class="cards">

      <div class="card">
        <div class="emoji">🖊️</div>
        <h3>Pens</h3>
      </div>

      <div class="card">
        <div class="emoji">✏️</div>
        <h3>Pencils</h3>
      </div>

      <div class="card">
        <div class="emoji">📓</div>
        <h3>Notebooks</h3>
      </div>

      <div class="card">
        <div class="emoji">🧽</div>
        <h3>Erasers</h3>
      </div>

    </div>

  </section>

  <footer>
    <p>© 2026 Mayur-lakh | Study Stationery</p>
  </footer>

  <script>
    function joinWebsite(event) {
      event.preventDefault();

      document.getElementById("message").style.display = "block";

      document.getElementById("name").value = "";
      document.getElementById("product").value = "";
    }
  </script>

</body>
</html>
बिल्कुल 👍 अभी हम Mayur-lakh की Join Website का पहला पेज बना देते हैं। यह पूरा कोड index.html में पेस्ट करना है।
पूरा पुराना content हटाकर यह पूरा code paste करो:
HTML
⚠️ एक जरूरी बात
इस code से Join वाला सुंदर पेज और button बन जाएगा, लेकिन अभी लोगों की जानकारी GitHub में अपने-आप जमा नहीं होगी। असली Joiner List बनाने के लिए बाद में हम form को किसी सुरक्षित form/database से जोड़ेंगे।
अभी तुम्हारा काम सिर्फ:
index.html → code paste → Commit changes
करना है।
उसके बाद हम GitHub Pages पर इसे असली website की तरह खोलेंगे।
