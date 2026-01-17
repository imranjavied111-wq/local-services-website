# Local Services Website (Ready to Use)

Below is a **complete professional HTML website** for local services.

---

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Local Services | Electrician, Plumber, RO Repair</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; background: #f5f5f5; }
    header { background: #0d6efd; color: white; padding: 20px; text-align: center; }
    header a { color: white; text-decoration: none; font-weight: bold; }
    .container { padding: 20px; }
    .services { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 15px; }
    .card { background: white; padding: 20px; border-radius: 10px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); text-align: center; }
    .card h3 { margin-top: 0; }
    .btn { background: #0d6efd; color: white; padding: 10px 15px; border-radius: 5px; text-decoration: none; display: inline-block; margin-top: 10px; }
    .contact { background: white; padding: 20px; border-radius: 10px; margin-top: 30px; }
    input, select { width: 100%; padding: 10px; margin: 10px 0; }
    button { width: 100%; background: #25D366; color: white; padding: 12px; border: none; border-radius: 5px; font-size: 16px; }
    footer { background: #222; color: white; text-align: center; padding: 15px; margin-top: 30px; }
    .whatsapp { position: fixed; bottom: 20px; right: 20px; background: #25D366; color: white; padding: 15px; border-radius: 50%; font-size: 20px; text-decoration: none; }
  </style>
</head>
<body>

<header>
  <h1>Local Home Services</h1>
  <p>Electrician | Plumber | RO Repair</p>
  <a href="tel:9999999999">📞 Call Now</a>
</header>

<div class="container">
  <h2>Our Services</h2>
  <div class="services">
    <div class="card">
      <h3>Electrician</h3>
      <p>Wiring, Fan, Light, Switch Repair</p>
      <a class="btn" href="#contact">Book Now</a>
    </div>
    <div class="card">
      <h3>Plumber</h3>
      <p>Leakage, Bathroom, Pipeline Repair</p>
      <a class="btn" href="#contact">Book Now</a>
    </div>
    <div class="card">
      <h3>RO Repair</h3>
      <p>RO Service, Filter Change</p>
      <a class="btn" href="#contact">Book Now</a>
    </div>
  </div>

  <div class="contact" id="contact">
    <h2>Book a Service</h2>
    <form onsubmit="sendWhatsApp(); return false;">
      <input type="text" id="name" placeholder="Your Name" required />
      <input type="tel" id="phone" placeholder="Mobile Number" required />
      <select id="service">
        <option>Electrician</option>
        <option>Plumber</option>
        <option>RO Repair</option>
      </select>
      <button type="submit">Send on WhatsApp</button>
    </form>
  </div>
</div>

<a class="whatsapp" href="https://wa.me/919999999999" target="_blank">💬</a>

<footer>
  <p>© 2026 Local Services. All Rights Reserved.</p>
</footer>

<script>
function sendWhatsApp() {
  var name = document.getElementById('name').value;
  var phone = document.getElementById('phone').value;
  var service = document.getElementById('service').value;
  var msg = `Name: ${name}%0APhone: ${phone}%0AService: ${service}`;
  window.open(`https://wa.me/919999999999?text=${msg}`, '_blank');
}
</script>

</body>
</html>
```

---

### 🔧 IMPORTANT
- Replace **9149589051** with your real mobile number
- Replace **919149589051** with WhatsApp number
- Save file as **index.html** in GitHub

Netlify will auto-update your website 🚀
