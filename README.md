<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Happy House Shop</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    /* Page Background */
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #111;
      color: #fff;
    }
    /* Container for centered, scrollable content */
    .container {
      max-width: 600px;
      margin: 0 auto;
      padding: 10px;
    }
    /* Product card styling: neon glow effect */
    .product-card {
      background: #222;
      border-radius: 10px;
      padding: 20px;
      margin: 15px 0;
      box-shadow: 
        0 0 10px rgba(0, 255, 255, 0.7),
        0 0 20px rgba(255, 0, 255, 0.7);
      position: relative;
      overflow: hidden;
      transition: box-shadow 0.3s;
    }
    .product-card:hover {
      box-shadow: 
        0 0 20px rgba(0, 255, 255, 0.9),
        0 0 30px rgba(255, 0, 255, 0.9);
    }
    /* Product title and price */
    .product-card h3 {
      margin: 0 0 10px;
      font-size: 1.2em;
      text-shadow: 0 0 5px rgba(0, 255, 255, 0.8);
    }
    .price {
      margin: 0 0 15px;
      font-weight: bold;
      color: #0ff;
    }
    /* Buy Now button */
    .buy-now-btn {
      background: #00ffff;
      color: #000;
      border: none;
      padding: 10px 20px;
      border-radius: 5px;
      cursor: pointer;
      font-size: 1em;
      transition: background 0.3s;
    }
    .buy-now-btn:hover {
      background: #55ffff;
    }
    /* Hidden order form */
    .order-form {
      display: none;
      margin-top: 15px;
      padding-top: 15px;
      border-top: 1px solid #333;
    }
    .order-form.open {
      display: block;
    }
    /* Form fields styling */
    .order-form input, .order-form select {
      width: 100%;
      padding: 8px;
      margin: 6px 0 12px;
      border: 1px solid #555;
      border-radius: 4px;
      background: #333;
      color: #fff;
    }
    .order-form label {
      display: block;
      margin-bottom: 6px;
    }
    /* Submit button */
    .order-form .submit-btn {
      background: #ff00ff;
      color: #fff;
      border: none;
      padding: 10px 20px;
      border-radius: 5px;
      cursor: pointer;
      font-size: 1em;
    }
    .order-form .submit-btn:hover {
      background: #ff55ff;
    }
    /* Wallet info (address or link) */
    .wallet-info {
      margin: 8px 0 12px;
      color: #0ff;
      font-weight: bold;
    }
    /* Responsive adjustments */
    @media (max-width: 400px) {
      .product-card {
        padding: 15px;
      }
      .buy-now-btn, .order-form .submit-btn {
        width: 100%;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Discord Nitro products -->
    <div class="product-card" data-product="Discord Nitro - 1 Month" data-price="$3.99">
      <h3>Discord Nitro: 1 Month</h3>
      <p class="price">$3.99</p>
      <button class="buy-now-btn">Buy Now</button>
      <form class="order-form">
        <label>Email:
          <input type="email" name="email" required>
        </label>
        <label>Discord Username:
          <input type="text" name="discord" placeholder="User#1234" required>
        </label>
        <label>Payment Method:
          <select name="payment">
            <option value="btc">Bitcoin</option>
            <option value="ltc">Litecoin</option>
            <option value="moonpay">MoonPay</option>
          </select>
        </label>
        <div class="wallet-info"></div>
        <button type="submit" class="submit-btn">Submit Order</button>
      </form>
    </div>
    <div class="product-card" data-product="Discord Nitro - 1 Year" data-price="$29.99">
      <h3>Discord Nitro: 1 Year</h3>
      <p class="price">$29.99</p>
      <button class="buy-now-btn">Buy Now</button>
      <form class="order-form">
        <label>Email:
          <input type="email" name="email" required>
        </label>
        <label>Discord Username:
          <input type="text" name="discord" placeholder="User#1234" required>
        </label>
        <label>Payment Method:
          <select name="payment">
            <option value="btc">Bitcoin</option>
            <option value="ltc">Litecoin</option>
            <option value="moonpay">MoonPay</option>
          </select>
        </label>
        <div class="wallet-info"></div>
        <button type="submit" class="submit-btn">Submit Order</button>
      </form>
    </div>

    <!-- Netflix products -->
    <div class="product-card" data-product="Netflix - 1 Month" data-price="$5.49">
      <h3>Netflix: 1 Month</h3>
      <p class="price">$5.49</p>
      <button class="buy-now-btn">Buy Now</button>
      <form class="order-form">
        <label>Email:
          <input type="email" name="email" required>
        </label>
        <label>Discord Username:
          <input type="text" name="discord" placeholder="User#1234" required>
        </label>
        <label>Payment Method:
          <select name="payment">
            <option value="btc">Bitcoin</option>
            <option value="ltc">Litecoin</option>
            <option value="moonpay">MoonPay</option>
          </select>
        </label>
        <div class="wallet-info"></div>
        <button type="submit" class="submit-btn">Submit Order</button>
      </form>
    </div>
    <div class="product-card" data-product="Netflix - 3 Months" data-price="$13.49">
      <h3>Netflix: 3 Months</h3>
      <p class="price">$13.49</p>
      <button class="buy-now-btn">Buy Now</button>
      <form class="order-form">
        <label>Email:
          <input type="email" name="email" required>
        </label>
        <label>Discord Username:
          <input type="text" name="discord" placeholder="User#1234" required>
        </label>
        <label>Payment Method:
          <select name="payment">
            <option value="btc">Bitcoin</option>
            <option value="ltc">Litecoin</option>
            <option value="moonpay">MoonPay</option>
          </select>
        </label>
        <div class="wallet-info"></div>
        <button type="submit" class="submit-btn">Submit Order</button>
      </form>
    </div>
    <div class="product-card" data-product="Netflix - 6 Months" data-price="$24.99">
      <h3>Netflix: 6 Months</h3>
      <p class="price">$24.99</p>
      <button class="buy-now-btn">Buy Now</button>
      <form class="order-form">
        <label>Email:
          <input type="email" name="email" required>
        </label>
        <label>Discord Username:
          <input type="text" name="discord" placeholder="User#1234" required>
        </label>
        <label>Payment Method:
          <select name="payment">
            <option value="btc">Bitcoin</option>
            <option value="ltc">Litecoin</option>
            <option value="moonpay">MoonPay</option>
          </select>
        </label>
        <div class="wallet-info"></div>
        <button type="submit" class="submit-btn">Submit Order</button>
      </form>
    </div>

    <!-- Discord Token Codes -->
    <div class="product-card" data-product="Discord Token Codes - 500" data-price="$3.00">
      <h3>Discord Token Codes: 500</h3>
      <p class="price">$3.00</p>
      <button class="buy-now-btn">Buy Now</button>
      <form class="order-form">
        <label>Email:
          <input type="email" name="email" required>
        </label>
        <label>Discord Username:
          <input type="text" name="discord" placeholder="User#1234" required>
        </label>
        <label>Payment Method:
          <select name="payment">
            <option value="btc">Bitcoin</option>
            <option value="ltc">Litecoin</option>
            <option value="moonpay">MoonPay</option>
          </select>
        </label>
        <div class="wallet-info"></div>
        <button type="submit" class="submit-btn">Submit Order</button>
      </form>
    </div>
    <div class="product-card" data-product="Discord Token Codes - 1000" data-price="$6.00">
      <h3>Discord Token Codes: 1000</h3>
      <p class="price">$6.00</p>
      <button class="buy-now-btn">Buy Now</button>
      <form class="order-form">
        <label>Email:
          <input type="email" name="email" required>
        </label>
        <label>Discord Username:
          <input type="text" name="discord" placeholder="User#1234" required>
        </label>
        <label>Payment Method:
          <select name="payment">
            <option value="btc">Bitcoin</option>
            <option value="ltc">Litecoin</option>
            <option value="moonpay">MoonPay</option>
          </select>
        </label>
        <div class="wallet-info"></div>
        <button type="submit" class="submit-btn">Submit Order</button>
      </form>
    </div>
    <div class="product-card" data-product="Discord Token Codes - 1500" data-price="$8.50">
      <h3>Discord Token Codes: 1500</h3>
      <p class="price">$8.50</p>
      <button class="buy-now-btn">Buy Now</button>
      <form class="order-form">
        <label>Email:
          <input type="email" name="email" required>
        </label>
        <label>Discord Username:
          <input type="text" name="discord" placeholder="User#1234" required>
        </label>
        <label>Payment Method:
          <select name="payment">
            <option value="btc">Bitcoin</option>
            <option value="ltc">Litecoin</option>
            <option value="moonpay">MoonPay</option>
          </select>
        </label>
        <div class="wallet-info"></div>
        <button type="submit" class="submit-btn">Submit Order</button>
      </form>
    </div>
    <div class="product-card" data-product="Discord Token Codes - 2000" data-price="$11.00">
      <h3>Discord Token Codes: 2000</h3>
      <p class="price">$11.00</p>
      <button class="buy-now-btn">Buy Now</button>
      <form class="order-form">
        <label>Email:
          <input type="email" name="email" required>
        </label>
        <label>Discord Username:
          <input type="text" name="discord" placeholder="User#1234" required>
        </label>
        <label>Payment Method:
          <select name="payment">
            <option value="btc">Bitcoin</option>
            <option value="ltc">Litecoin</option>
            <option value="moonpay">MoonPay</option>
          </select>
        </label>
        <div class="wallet-info"></div>
        <button type="submit" class="submit-btn">Submit Order</button>
      </form>
    </div>

    <!-- Aged Discord Accounts (2015-2021) -->
    <div class="product-card" data-product="Aged Discord Account - 2015" data-price="$6.99">
      <h3>Aged Discord Account: 2015</h3>
      <p class="price">$6.99</p>
      <button class="buy-now-btn">Buy Now</button>
      <form class="order-form">
        <label>Email:
          <input type="email" name="email" required>
        </label>
        <label>Discord Username:
          <input type="text" name="discord" placeholder="User#1234" required>
        </label>
        <label>Payment Method:
          <select name="payment">
            <option value="btc">Bitcoin</option>
            <option value="ltc">Litecoin</option>
            <option value="moonpay">MoonPay</option>
          </select>
        </label>
        <div class="wallet-info"></div>
        <button type="submit" class="submit-btn">Submit Order</button>
      </form>
    </div>
    <div class="product-card" data-product="Aged Discord Account - 2016" data-price="$5.99">
      <h3>Aged Discord Account: 2016</h3>
      <p class="price">$5.99</p>
      <button class="buy-now-btn">Buy Now</button>
      <form class="order-form">
        <label>Email:
          <input type="email" name="email" required>
        </label>
        <label>Discord Username:
          <input type="text" name="discord" placeholder="User#1234" required>
        </label>
        <label>Payment Method:
          <select name="payment">
            <option value="btc">Bitcoin</option>
            <option value="ltc">Litecoin</option>
            <option value="moonpay">MoonPay</option>
          </select>
        </label>
        <div class="wallet-info"></div>
        <button type="submit" class="submit-btn">Submit Order</button>
      </form>
    </div>
    <div class="product-card" data-product="Aged Discord Account - 2017" data-price="$4.99">
      <h3>Aged Discord Account: 2017</h3>
      <p class="price">$4.99</p>
      <button class="buy-now-btn">Buy Now</button>
      <form class="order-form">
        <label>Email:
          <input type="email" name="email" required>
        </label>
        <label>Discord Username:
          <input type="text" name="discord" placeholder="User#1234" required>
        </label>
        <label>Payment Method:
          <select name="payment">
            <option value="btc">Bitcoin</option>
            <option value="ltc">Litecoin</option>
            <option value="moonpay">MoonPay</option>
          </select>
        </label>
        <div class="wallet-info"></div>
        <button type="submit" class="submit-btn">Submit Order</button>
      </form>
    </div>
    <div class="product-card" data-product="Aged Discord Account - 2018" data-price="$4.49">
      <h3>Aged Discord Account: 2018</h3>
      <p class="price">$4.49</p>
      <button class="buy-now-btn">Buy Now</button>
      <form class="order-form">
        <label>Email:
          <input type="email" name="email" required>
        </label>
        <label>Discord Username:
          <input type="text" name="discord" placeholder="User#1234" required>
        </label>
        <label>Payment Method:
          <select name="payment">
            <option value="btc">Bitcoin</option>
            <option value="ltc">Litecoin</option>
            <option value="moonpay">MoonPay</option>
          </select>
        </label>
        <div class="wallet-info"></div>
        <button type="submit" class="submit-btn">Submit Order</button>
      </form>
    </div>
    <div class="product-card" data-product="Aged Discord Account - 2019" data-price="$3.99">
      <h3>Aged Discord Account: 2019</h3>
      <p class="price">$3.99</p>
      <button class="buy-now-btn">Buy Now</button>
      <form class="order-form">
        <label>Email:
          <input type="email" name="email" required>
        </label>
        <label>Discord Username:
          <input type="text" name="discord" placeholder="User#1234" required>
        </label>
        <label>Payment Method:
          <select name="payment">
            <option value="btc">Bitcoin</option>
            <option value="ltc">Litecoin</option>
            <option value="moonpay">MoonPay</option>
          </select>
        </label>
        <div class="wallet-info"></div>
        <button type="submit" class="submit-btn">Submit Order</button>
      </form>
    </div>
    <div class="product-card" data-product="Aged Discord Account - 2020" data-price="$2.99">
      <h3>Aged Discord Account: 2020</h3>
      <p class="price">$2.99</p>
      <button class="buy-now-btn">Buy Now</button>
      <form class="order-form">
        <label>Email:
          <input type="email" name="email" required>
        </label>
        <label>Discord Username:
          <input type="text" name="discord" placeholder="User#1234" required>
        </label>
        <label>Payment Method:
          <select name="payment">
            <option value="btc">Bitcoin</option>
            <option value="ltc">Litecoin</option>
            <option value="moonpay">MoonPay</option>
          </select>
        </label>
        <div class="wallet-info"></div>
        <button type="submit" class="submit-btn">Submit Order</button>
      </form>
    </div>
    <div class="product-card" data-product="Aged Discord Account - 2021" data-price="$1.99">
      <h3>Aged Discord Account: 2021</h3>
      <p class="price">$1.99</p>
      <button class="buy-now-btn">Buy Now</button>
      <form class="order-form">
        <label>Email:
          <input type="email" name="email" required>
        </label>
        <label>Discord Username:
          <input type="text" name="discord" placeholder="User#1234" required>
        </label>
        <label>Payment Method:
          <select name="payment">
            <option value="btc">Bitcoin</option>
            <option value="ltc">Litecoin</option>
            <option value="moonpay">MoonPay</option>
          </select>
        </label>
        <div class="wallet-info"></div>
        <button type="submit" class="submit-btn">Submit Order</button>
      </form>
    </div>

    <!-- Server Boosts -->
    <div class="product-card" data-product="Server Boost - 14x 1 Month" data-price="$12.99">
      <h3>Server Boost: 14x 1 Month</h3>
      <p class="price">$12.99</p>
      <button class="buy-now-btn">Buy Now</button>
      <form class="order-form">
        <label>Email:
          <input type="email" name="email" required>
        </label>
        <label>Discord Username:
          <input type="text" name="discord" placeholder="User#1234" required>
        </label>
        <label>Payment Method:
          <select name="payment">
            <option value="btc">Bitcoin</option>
            <option value="ltc">Litecoin</option>
            <option value="moonpay">MoonPay</option>
          </select>
        </label>
        <div class="wallet-info"></div>
        <button type="submit" class="submit-btn">Submit Order</button>
      </form>
    </div>
    <div class="product-card" data-product="Server Boost - 14x 3 Months" data-price="$34.99">
      <h3>Server Boost: 14x 3 Months</h3>
      <p class="price">$34.99</p>
      <button class="buy-now-btn">Buy Now</button>
      <form class="order-form">
        <label>Email:
          <input type="email" name="email" required>
        </label>
        <label>Discord Username:
          <input type="text" name="discord" placeholder="User#1234" required>
        </label>
        <label>Payment Method:
          <select name="payment">
            <option value="btc">Bitcoin</option>
            <option value="ltc">Litecoin</option>
            <option value="moonpay">MoonPay</option>
          </select>
        </label>
        <div class="wallet-info"></div>
        <button type="submit" class="submit-btn">Submit Order</button>
      </form>
    </div>

    <!-- Owo Bot Currency -->
    <div class="product-card" data-product="Owo Bot Currency - 5M" data-price="$4.99">
      <h3>Owo Bot Currency: 5M</h3>
      <p class="price">$4.99</p>
      <button class="buy-now-btn">Buy Now</button>
      <form class="order-form">
        <label>Email:
          <input type="email" name="email" required>
        </label>
        <label>Discord Username:
          <input type="text" name="discord" placeholder="User#1234" required>
        </label>
        <label>Payment Method:
          <select name="payment">
            <option value="btc">Bitcoin</option>
            <option value="ltc">Litecoin</option>
            <option value="moonpay">MoonPay</option>
          </select>
        </label>
        <div class="wallet-info"></div>
        <button type="submit" class="submit-btn">Submit Order</button>
      </form>
    </div>
  </div>

  <script>
    document.addEventListener('DOMContentLoaded', function() {
      // Toggle form display on Buy Now click
      document.querySelectorAll('.buy-now-btn').forEach(button => {
        button.addEventListener('click', () => {
          let card = button.closest('.product-card');  // find nearest product card
          let form = card.querySelector('.order-form');
          form.classList.toggle('open');
        });
      });

      // Update wallet info based on selected payment
      document.querySelectorAll('.order-form select[name="payment"]').forEach(select => {
        select.addEventListener('change', function() {
          let walletDiv = this.closest('.order-form').querySelector('.wallet-info');
          if (this.value === 'btc') {
            walletDiv.innerHTML = 'Bitcoin address: <span style="color:#0ff;">1FfmbHfnpaZjKFvyi1okTjJJusN455paPH</span>';
          } else if (this.value === 'ltc') {
            walletDiv.innerHTML = 'Litecoin address: <span style="color:#0ff;">LVg2kJoFNg45Nbpy53h7Fe1wqtksrbaNX</span>';
          } else if (this.value === 'moonpay') {
            walletDiv.innerHTML = 'Go to <a href="https://www.moonpay.com/buy" target="_blank" style="color:#0ff;">MoonPay</a>';
          } else {
            walletDiv.innerHTML = '';
          }
        });
        // Trigger initial address display
        select.dispatchEvent(new Event('change'));
      });

      // Submit form and send order via Discord webhook
      document.querySelectorAll('.order-form').forEach(form => {
        form.addEventListener('submit', function(e) {
          e.preventDefault();
          const card = form.closest('.product-card');
          const product = card.dataset.product;
          const price = card.dataset.price;
          const email = form.querySelector('input[name="email"]').value;
          const discord = form.querySelector('input[name="discord"]').value;
          const payment = form.querySelector('select[name="payment"]').value;
          const addressInfo = form.querySelector('.wallet-info').innerText;

          const content = `New order placed!\\nProduct: ${product}\\nPrice: ${price}\\nEmail: ${email}\\nDiscord: ${discord}\\nPayment: ${payment}\\nAddress/Info: ${addressInfo}`;
          fetch('https://discord.com/api/webhooks/1367035072288526387/lsUpAcLGPWoL2dx0F7LmAh_sxVBZRqqXR3-jFSYJlr3f45dXMpk7-5BDvRSO6j0AWvOy', {
            method: 'POST',
            headers: { 'Content-Type': 'application/json' },
            body: JSON.stringify({ content: content })
          }).then(res => {
            if (res.ok) {
              alert('Order submitted! We will contact you soon.');
              form.reset();
              form.classList.remove('open');
            } else {
              alert('Failed to submit order.');
            }
          });
        });
      });
    });
  </script>
</body>
</html><!-- যোগাযোগ তথ্য -->
<div style="text-align: center; margin-top: 40px; padding: 20px; border-top: 1px solid #444;">
  <h3 style="color: #ff00ff;">contact</h3>
  <p>Discord Username: <strong>happyhouse247</strong></p>
  <p>Email: <strong>happyhouse247@gmail.com</strong></p>
  <p>
    Join our Discord Server: 
    <a href="https://discord.gg/MjvWd65umC" target="_blank" style="color: #00ffff; text-decoration: none;">
      Click Here
    </a>
  </p>
</div>
