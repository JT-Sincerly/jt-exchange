<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Welcome Page</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Welcome to Jt Exchange</h1>
  </header>
  <main>
    <p>Kindly click the button below to proceed.</p>
    <button onclick="location.href='next-page.html'">Proceed</button>
  </main>
  <footer>
    <p></p>
  </footer>
  <script src="script.js"></script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Next Page</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1></h1>
  <form id="transaction-form">
    <label for="transaction-purpose">Transaction Purpose:</label>
    <select id="transaction-purpose" name="transaction-purpose">
      <option value="buying">Buying</option>
      <option value="selling">Selling</option>
      <option value="swapping">Swapping</option>
    </select>
    
    <label for="sending-currency">Sending:</label>
    <select id="sending-currency" name="sending-currency">
      <option value="local-currency">Local Currency (FIAT)</option>
      <option value="bitcoin">Bitcoin (BTC)</option>
      <option value="ethereum">Ethereum (ETH)</option>
      <option value="binance-coin">Binance Coin (BNB)</option>
      <option value="polygon">Polygon (POL)</option>
      <option value="cardano">Cardano (ADA)</option>
      <option value="ripple">Ripple (XRP)</option>
      <option value="solana">Solana (SOL)</option>
      <option value="polkadot">Polkadot (DOT)</option>
      <option value="bitcoin-cash">Bitcoin Cash (BCH)</option>
      <option value="atok">Atok</option>
      <option value="core">Core</option>
      <option value="shiba-inu">Shiba Inu (SHIB)</option>
      <option value="litecoin">Litecoin (LTC)</option>
      <option value="dogecoin">Dogecoin (DOGE)</option>
      <option value="rubi">Rubi (RBL)</option>
    </select>
    
    <label for="receiving-currency">Receiving:</label>
    <select id="receiving-currency" name="receiving-currency">
      <option value="local-currency">Local Currency (FIAT)</option>
      <option value="bitcoin">Bitcoin (BTC)</option>
      <option value="ethereum">Ethereum (ETH)</option>
      <option value="binance-coin">Binance Coin (BNB)</option>
      <option value="polygon">Polygon (POL)</option>
      <option value="cardano">Cardano (ADA)</option>
      <option value="ripple">Ripple (XRP)</option>
      <option value="solana">Solana (SOL)</option>
      <option value="polkadot">Polkadot (DOT)</option>
      <option value="bitcoin-cash">Bitcoin Cash (BCH)</option>
      <option value="atok">Atok</option>
      <option value="core">Core</option>
      <option value="shiba-inu">Shiba Inu (SHIB)</option>
      <option value="litecoin">Litecoin (LTC)</option>
      <option value="dogecoin">Dogecoin (DOGE)</option>
      <option value="rubi">Rubi (RBL)</option>
    </select>
    
    <label for="amount">Amount:</label>
    <input type="number" id="amount" name="amount">
    
    <label for="email">Email:</label>
    <input type="email" id="email" name="email">
    
    <button id="submit-button">Submit request</button>



<footer>
  <p>&copy;2025 Jt Exchange.</p>
  <button onclick="showTermsAndConditions()">Terms and Conditions</button>
  <div id="terms-and-conditions" style="display:none;">
    <h2>Terms and Conditions</h2>
    <p>Last updated: March 29, 2025</p>
    <p>Please read these Terms and Conditions carefully before using the Jt Exchange website.</p>
    <p>By accessing or using the website, you agree to be bound by these Terms and Conditions.</p>
  </div>
  <h2>Customer Support</h2>
  <p>Phone: +234 802 835 6771</p>
  <p>Whatsapp: +234 807 594 9900<p>
  <p>Email: <a href="mailto:enochakintayo62@gmail.com">enochakintayo662@gmail.com</a></p>
</footer>

<script>
  function showTermsAndConditions() {
    var termsAndConditionsDiv = document.getElementById("terms-and-conditions");
    if (termsAndConditionsDiv.style.display === "none") {
      termsAndConditionsDiv.style.display = "block";
    } else {
      termsAndConditionsDiv.style.display = "none";
    }
  }
</script>

