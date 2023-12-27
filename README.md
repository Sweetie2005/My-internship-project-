<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Product Pricing</title>
</head>
<body>
    <style>
        body {
          font-family: 'Arial', sans-serif;
          margin: 0;
          padding: 0;
          background-color: #f4f4f4;
        }
    
        header {
          background-color: #333;
          color: #fff;
          text-align: center;
          padding: 10px 0;
        }
    
        nav {
          background-color: #444;
          padding: 10px 0;
          text-align: center;
        }
    
        nav a {
          color: #22b8c8;
          text-decoration: none;
          margin: 0 15px;
        }
    
    
        .pricing-container {
          max-width: 1200px;
          margin: 20px auto;
          display: flex;
          justify-content: space-around;
          flex-wrap: wrap;
        }
    
        .pricing-card {
          background-color: #fff;
          box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
          border-radius: 8px;
          padding: 20px;
          margin: 20px;
          flex: 1;
          text-align: center;
        }
    
        .pricing-card h2 {
          color: #333;
        }
    
        .pricing-card button {
          background-color: #4CAF50;
          color: #fff;
          padding: 10px 20px;
          border: none;
          border-radius: 5px;
          cursor: pointer;
        }
    
        .feature-list {
          list-style: none;
          padding: 0;
        }
    
        .feature-list li {
          margin: 10px 0;
        }
    
        footer {
            background-color: #333;
          color:rgb(137, 164, 95);
          text-align: center;
          padding: 10px 0;
          position: fixed;
          bottom: 0;
          width: 100%;
        }
      </style>

  <header>
    <h1>GUM </h1>
  </header>

  <nav>
    <a href="#"><button>Home</button></a>
    <a href="#"><button>Features</button></a>
    <a href="#"><button>Pricing</button></a>
    <a href="#"><button>About Us</button></a>
    <a href="#"><button>Contact</button></a>
  </nav>

  <div class="pricing-container">
    <div class="pricing-card">
      <h2>Basic</h2>
      <ul class="feature-list">
        <li>₹399/month</li>
        <li>single user</li>
        <li>HD(720p)</li>
      
        <select>
          <option>IND 399</option>
          <option>USD $5</option>
          <option>EURO 10</option>
          <option>DINAR 20</option>
        </select>
        </ul>
        <button>choose plan</button>
    </div>

    <div class="pricing-card">
      <h2>Standard</h2>
      <p>₹599/month</p>
      <ul class="feature-list">
        <li>HD(1080p)</li>
        <li>Dual users</li>
        <li>Unlimited content</li>
        <li>dual users</li>
        <select>
          <option>IND 599</option>
          <option>USD $8</option>
          <option>EURO 20</option>
          <option>DINAR 30</option>
          </select>
      </ul>
      <button>Choose Plan</button>
    </div>

    <div class="pricing-card">
      <h2>Premium</h2>
      <p>₹999/month</p>
      <ul class="feature-list">
        <li>HD+</li>
        <li>multi users</li>
        <li>5 user.</li>
        <li>Unlimited content.</li>
        <li>Premium content</li>
        <select>
          <option>IND 999</option>
          <option>USD 13</option>
          <option>EURO 29</option>
          <option>DINAR 60</option>
        </select>
      </ul>
      <button>Choose Plan</button>
    </div>
  </div>

  <footer>
    <p>&copy; 2023 Your Product Name. All rights reserved.</p>
  </footer>

</body>
</html>
