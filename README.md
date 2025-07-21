# elon-empire
Crypto blog and trading profile by Ike bathlomew
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Elon Empire | Welcome to Crypto</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #0d1117;
      color: #e6edf3;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #161b22;
      color: white;
      padding: 20px;
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      align-items: center;
    }
    .logo {
      max-width: 150px;
      margin-bottom: 10px;
    }
    .site-title {
      text-align: left;
      flex-grow: 1;
      padding-left: 20px;
    }
    nav {
      background-color: #010409;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: #58a6ff;
      text-decoration: none;
      margin: 0 10px;
      font-weight: bold;
      display: inline-block;
      padding: 8px 0;
    }
    main {
      padding: 20px;
      max-width: 900px;
      margin: auto;
    }
    h1, h2 {
      color: #58a6ff;
    }
    p, label {
      font-size: 1.1em;
      line-height: 1.6;
    }
    #prices, .blog-post, #trading-profile, #contact-form {
      background: #161b22;
      padding: 20px;
      margin-top: 30px;
      border: 1px solid #30363d;
      border-radius: 8px;
    }
    .crypto {
      font-size: 1.2em;
      margin: 10px 0;
    }
    .blog-post h3 {
      margin-top: 0;
    }
    .blog-post small {
      color: #8b949e;
    }
    input, textarea {
      width: 100%;
      padding: 10px;
      margin-top: 8px;
      background-color: #0d1117;
      border: 1px solid #30363d;
      border-radius: 4px;
      color: #c9d1d9;
    }
    button {
      margin-top: 15px;
      padding: 10px 20px;
      background-color: #238636;
      color: white;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
    footer {
      text-align: center;
      padding: 10px;
      background-color: #010409;
      color: #8b949e;
    }

    @media (max-width: 600px) {
      header {
        flex-direction: column;
        align-items: flex-start;
      }
      .site-title {
        padding-left: 0;
        margin-top: 10px;
      }
      nav a {
        display: block;
        margin: 5px 0;
      }
      main {
        padding: 15px;
      }
    }
  </style>
</head>
<body>
  <header>
    <img src="https://files.oaiusercontent.com/file-h0lE0zrbVfYOH0RZFxVxpaDA?se=2025-07-21T23%3A00%3A00Z&sp=r&sv=2021-08-06&sr=b&rscd=inline&rsct=image/png&sig=iBn8lR2Yv5eUYuAy5Z91U3IvBF6U6sYYcnUn9EjEXkU%3D" alt="Elon Empire Logo" class="logo">
    <div class="site-title">
      <h1>Elon Empire</h1>
      <p>Your gateway to understanding and trading crypto</p>
    </div>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#crypto-block">Crypto Block</a>
    <a href="#trading-profile">Trading Profile</a>
    <a href="#contact-form">Contact</a>
  </nav>

  <main>
    <h2>Welcome to the World of Crypto</h2>
    <p>
      Cryptocurrency is a new type of digital money that works on a technology called blockchain. Unlike traditional money, crypto is decentralized — meaning it's not controlled by any government or bank.
    </p>
    <p>
      At Elon Empire, we help beginners get comfortable with crypto by explaining things in a simple way. You'll learn about Bitcoin, Ethereum, and how to trade them to make profits. Whether you're just starting or already trading, you're in the right place.
    </p>
    <p>
      Ready to begin your journey to financial freedom? Explore our blog, check crypto prices, and build your trading profile with us.
    </p>

    <section id="prices">
      <h2>Live Crypto Prices</h2>
      <div class="crypto" id="btc">Bitcoin (BTC): Loading...</div>
      <div class="crypto" id="eth">Ethereum (ETH): Loading...</div>
    </section>

    <section id="crypto-block">
      <h2>Crypto Block - Latest Blog Posts</h2>
      <div class="blog-post">
        <h3>Getting Started with Crypto: What You Need to Know</h3>
        <small>Posted on July 21, 2025</small>
        <p>
          New to crypto? This post explains the basics in plain English. Learn what blockchain is, how wallets work, and the first steps to take before trading.
        </p>
      </div>
      <div class="blog-post">
        <h3>Bitcoin vs. Ethereum: What's the Difference?</h3>
        <small>Posted on July 19, 2025</small>
        <p>
          Two of the most popular cryptocurrencies are BTC and ETH — but they work very differently. This post breaks down the key features of each.
        </p>
      </div>
      <div class="blog-post">
        <h3>5 Crypto Trading Tips for Beginners</h3>
        <small>Posted on July 16, 2025</small>
        <p>
          Avoid beginner mistakes with these practical tips. From understanding charts to setting stop-losses, this guide gives you a strong foundation.
        </p>
      </div>
    </section>

    <section id="trading-profile">
      <h2>My Trading Profile</h2>
      <p>
        Hi, I'm Ike Bathlomew — a crypto enthusiast driven by the goal of financial freedom. My focus is on crypto trading, where I’m learning the skills to succeed in the market.
      </p>
      <p>
        I study market trends, trading signals, and tools like Binance and CoinMarketCap. This section will grow to include my portfolio, trades, and lessons learned.
      </p>
      <p>
        Tools I use:
        <ul>
          <li><a href="https://www.binance.com" target="_blank">Binance</a></li>
          <li><a href="https://www.coinmarketcap.com" target="_blank">CoinMarketCap</a></li>
        </ul>
      </p>
    </section>

    <section id="contact-form">
      <h2>Contact Me</h2>
      <p>Phone: 07033696465</p>
      <form>
        <label for="name">Your Name:</label>
        <input type="text" id="name" name="name" required />
        <label for="email">Your Email:</label>
        <input type="email" id="email" name="email" required />
        <label for="message">Message:</label>
        <textarea id="message" name="message" rows="5" required></textarea>
        <button type="submit">Send Message</button>
      </form>
    </section>
  </main>

  <footer>
    <p>Contact: 07033696465</p>
    <p>&copy; 2025 Elon Empire</p>
  </footer>

  <script>
    async function fetchPrices() {
      try {
        const res = await fetch('https://api.coingecko.com/api/v3/simple/price?ids=bitcoin,ethereum&vs_currencies=usd');
        const data = await res.json();
        document.getElementById('btc').innerText = `Bitcoin (BTC): $${data.bitcoin.usd}`;
        document.getElementById('eth').innerText = `Ethereum (ETH): $${data.ethereum.usd}`;
      } catch (error) {
        document.getElementById('btc').innerText = 'Bitcoin (BTC): Error loading';
        document.getElementById('eth').innerText = 'Ethereum (ETH): Error loading';
      }
    }
    fetchPrices();
    setInterval(fetchPrices, 10000);
  </script>
</body>
</html>
