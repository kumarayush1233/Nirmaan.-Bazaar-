<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Nirmaan Bazaar</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; background-color: #f9f9f9; color: #333; }
    header { background: #0a3d62; color: white; padding: 20px; display: flex; justify-content: space-between; align-items: center; }
    header h1 { margin: 0; font-size: 28px; }
    nav a { color: white; margin-left: 15px; text-decoration: none; }
    .hero { background-color: #dff9fb; padding: 40px 20px; text-align: center; }
    .hero h2 { font-size: 28px; color: #130f40; }
    .hero p { font-size: 18px; }
    .cta-buttons button { padding: 10px 20px; margin: 10px; font-size: 16px; background: #27ae60; color: white; border: none; cursor: pointer; }
    .section { padding: 30px 20px; }
    .features, .metrics { display: flex; flex-wrap: wrap; gap: 20px; }
    .feature, .metric { flex: 1 1 200px; background: white; padding: 20px; border-radius: 8px; box-shadow: 0 0 10px rgba(0,0,0,0.1); }
    .form-section input, .form-section select { width: 100%; padding: 10px; margin: 10px 0; }
    .form-section button { padding: 10px 20px; background: #130f40; color: white; border: none; }
    footer { background: #222; color: white; padding: 20px; text-align: center; }
    footer a { color: #aaa; margin: 0 10px; text-decoration: none; }
  </style>
</head>
<body>

<header>
  <h1>Nirmaan Bazaar</h1>
  <nav>
    <a href="#">Home</a>
    <a href="#">FAQ</a>
    <a href="#">Contact</a>
    <a href="#"><img src="facebook-icon.png" alt="FB" width="20"></a>
    <a href="#"><img src="whatsapp-icon.png" alt="WA" width="20"></a>
  </nav>
</header>

<div class="hero">
  <h2>“ab thekedarr ke jhan jhat se hi azzad, Nirmaan Bazaar ke sath bano smart.”</h2>
  <p>All your construction needs at one place — from materials to manpower.</p>
  <div class="cta-buttons">
    <button>Book Now</button>
    <button>Get a Free Quote</button>
  </div>
</div>

<div class="section">
  <h3>Our Services</h3>
  <div class="features">
    <div class="feature">Cement, bricks, sand, steel, timber</div>
    <div class="feature">Skilled & unskilled labor (daily/hourly)</div>
    <div class="feature">Civil engineers & architects</div>
    <div class="feature">Land survey & estimation experts</div>
    <div class="feature">Photo/video-based site tracking</div>
  </div>
</div>

<div class="section form-section">
  <h3>Get a Free Quote</h3>
  <form>
    <input type="text" placeholder="Name" required />
    <input type="tel" placeholder="Phone Number" required />
    <input type="text" placeholder="Location" required />
    <select required>
      <option value="">Service Needed</option>
      <option value="material">Construction Material</option>
      <option value="labor">Labor</option>
      <option value="engineer">Engineer/Architect</option>
    </select>
    <button type="submit">Submit</button>
  </form>
</div>

<div class="section">
  <h3>Why Choose Us?</h3>
  <div class="features">
    <div class="feature">Nearest Vendor Delivery</div>
    <div class="feature">Transparent Pricing</div>
    <div class="feature">Customer & Labor Verification</div>
    <div class="feature">Full Support via WhatsApp</div>
  </div>
</div>

<div class="section">
  <h3>Key Metrics</h3>
  <div class="metrics">
    <div class="metric">170+ Customer Orders Received</div>
    <div class="metric">80+ Vendors Listed</div>
    <div class="metric">500+ Daily Website/App Visits</div>
  </div>
</div>

<div class="section">
  <h3>FAQ</h3>
  <p><strong>Q:</strong> Kya material aur manpower dono ek jagah se milega?<br />
  <strong>A:</strong> Haan, Nirmaan Bazaar pe aap dono ek hi jagah se book kar sakte hain.</p>
</div>

<footer>
  <p>Contact us: +91-87090XXXXX</p>
  <a href="#">Privacy Policy</a> | <a href="#">Terms and Conditions</a>
</footer>

</body>
</html>
