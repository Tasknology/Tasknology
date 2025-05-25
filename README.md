<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Tasknology - Your Business. Our Technology.</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', sans-serif;
    }
    body {
      background-color: #0B1F3A;
      color: #fff;
      line-height: 1.6;
    }
    header {
      text-align: center;
      padding: 4rem 1rem;
      background-color: #081526;
    }
    header img {
      max-width: 150px;
      margin-bottom: 1rem;
    }
    header h1 {
      font-size: 2.75rem;
      margin-bottom: 1rem;
    }
    header p {
      font-size: 1.25rem;
      color: #ccc;
    }
    .cta-buttons {
      margin-top: 2rem;
    }
    .cta-buttons a {
      display: inline-block;
      margin: 0 0.5rem;
      padding: 0.75rem 1.5rem;
      border-radius: 5px;
      text-decoration: none;
      font-weight: 600;
      transition: background 0.3s, color 0.3s;
    }
    .cta-primary {
      background: #00ffb7;
      color: #0B1F3A;
    }
    .cta-primary:hover {
      background: #00ddb7;
    }
    .cta-secondary {
      border: 2px solid #00ffb7;
      color: #00ffb7;
    }
    .cta-secondary:hover {
      background: #00ffb7;
      color: #0B1F3A;
    }
    section {
      padding: 3rem 1rem;
      text-align: center;
    }
    h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
    }
    .features, .industries, .plans {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 2rem;
      margin-top: 2rem;
    }
    .card {
      background: #1A2C4B;
      padding: 1.5rem;
      border-radius: 10px;
      width: 280px;
      color: #ccc;
      box-shadow: 0 4px 10px rgba(0, 255, 183, 0.1);
    }
    .testimonial {
      font-style: italic;
      margin-top: 2rem;
      color: #eee;
    }
    footer {
      text-align: center;
      padding: 2rem 1rem;
      background: #081526;
      color: #888;
      font-size: 0.9rem;
    }
    @media (max-width: 768px) {
      .features, .industries, .plans {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>
  <header>
    <img src="1000104981.png" alt="Tasknology Logo" />
    <h1>Let Tasknology Handle the Busywork.</h1>
    <p>Your AI-powered assistant for call answering, booking, and beyond — so you can focus on growing your business.</p>
    <div class="cta-buttons">
      <a href="#" class="cta-primary">Start Free Trial</a>
      <a href="#" class="cta-secondary">See How It Works</a>
    </div>
  </header>

  <section>
    <h2>How It Works</h2>
    <div class="features">
      <div class="card">
        <h3>Step 1</h3>
        <p>We answer your calls 24/7</p>
      </div>
      <div class="card">
        <h3>Step 2</h3>
        <p>We book appointments instantly</p>
      </div>
      <div class="card">
        <h3>Step 3</h3>
        <p>You focus on what matters most</p>
      </div>
    </div>
  </section>

  <section>
    <h2>What Tasknology Can Do for You</h2>
    <div class="features">
      <div class="card">AI Call Answering (Even After Hours)</div>
      <div class="card">Appointment Scheduling via Phone, SMS & Email</div>
      <div class="card">Booking Confirmations Sent Instantly</div>
      <div class="card">Tailored Workflows for Your Industry</div>
    </div>
  </section>

  <section>
    <h2>Built for Busy Small Businesses</h2>
    <div class="industries">
      <div class="card">Barbershops & Salons</div>
      <div class="card">Health & Wellness Clinics</div>
      <div class="card">Home Services & Trades</div>
      <div class="card">More Coming Soon</div>
    </div>
  </section>

  <section>
    <h2>Real Results</h2>
    <p class="testimonial">“Tasknology saved me hours a week. My calendar fills up while I focus on clients.”<br />– Jamal R., Barbershop Owner</p>
  </section>

  <section>
    <h2>Simple Plans That Grow With You</h2>
    <div class="plans">
      <div class="card"><strong>Starter</strong><br />$29/month<br />Basic Call Handling</div>
      <div class="card"><strong>Pro</strong><br />$59/month<br />Full Appointment Automation</div>
      <div class="card"><strong>Custom</strong><br />Let’s Talk</div>
    </div>
    <div class="cta-buttons">
      <a href="#" class="cta-secondary">Compare Plans</a>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Tasknology. All rights reserved. | Terms | Privacy</p>
  </footer>
</body>
</html>
