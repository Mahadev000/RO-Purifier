<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Aaro Purifier Machine - Clean Air, Healthier Life">
    <title>Aaro Purifier Machine</title>
     <style>
        /* Cart Styles */
        .cart-container {
            display: none;
            padding: 40px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        .cart-item {
            display: flex;
            justify-content: space-between;
            margin-bottom: 20px;
        }

        .cart-item h4 {
            margin: 0;
        }

        .cart-total {
            text-align: right;
            margin-top: 20px;
        }

        .cart-form {
            margin-top: 30px;
        }

        .cart-form input {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
        }

        .place-order-button {
            background-color: #2a9d8f;
            color: white;
            padding: 10px 20px;
            cursor: pointer;
            border-radius: 5px;
            font-size: 18px;
        }

        .place-order-button:hover {
            background-color: #219a7a;
        }

        .ro-item {
            padding: 10px;
            margin-bottom: 10px;
            background-color: #f9f9f9;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .button-container button {
            background-color: #2a9d8f;
            color: white;
            padding: 8px 15px;
            cursor: pointer;
            margin: 5px;
            border-radius: 5px;
        }

        .button-container button:hover {
            background-color: #219a7a;
        }
        /* Global Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #2a9d8f;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        section {
            padding: 40px 20px;
            text-align: center;
        }

        section h2 {
            color: #2a9d8f;
        }

        section img {
            width: 100%;
            max-width: 500px;
            height: auto;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        ul li {
            font-size: 18px;
            margin: 10px 0;
        }

        table {
            margin: 0 auto;
            width: 80%;
            border-collapse: collapse;
            margin-top: 20px;
        }

        table td {
            padding: 10px;
            border: 1px solid #ddd;
        }

        table td:nth-child(odd) {
            font-weight: bold;
        }

        #pricing p {
            font-size: 24px;
            color: #333;
        }

        #pricing button {
            padding: 10px 20px;
            background-color: #2a9d8f;
            color: white;
            border: none;
            font-size: 18px;
            cursor: pointer;
            border-radius: 5px;
        }

        #pricing button:hover {
            background-color: #219a7a;
        }

        form {
            text-align: left;
            max-width: 500px;
            margin: 0 auto;
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        form input[type="text"],
        form input[type="email"],
        form input[type="submit"] {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            font-size: 16px;
            border-radius: 5px;
            border: 1px solid #ddd;
        }

        form input[type="submit"] {
            background-color: #2a9d8f;
            color: white;
            cursor: pointer;
        }

        form input[type="submit"]:hover {
            background-color: #219a7a;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        /* RO Purifier List */
        .ro-list {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
            margin-top: 20px;
        }

        .ro-item {
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        .ro-item h3 {
            color: #2a9d8f;
        }

        .ro-item p {
            font-size: 16px;
        }

        .ro-item button {
            background-color: #2a9d8f;
            color: white;
            border: none;
            padding: 10px;
            cursor: pointer;
            border-radius: 5px;
            margin-right: 10px;
        }

        .ro-item button:hover {
            background-color: #219a7a;
        }

        .ro-item .button-container {
            display: flex;
            justify-content: space-between;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            nav ul li {
                display: block;
                margin: 10px 0;
            }

            section img {
                max-width: 100%;
            }

            .ro-list {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Aaro Purifier Machine</h1>
        <p>Breath Fresh, Clean Air Every Day</p>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#features">Features</a></li>
                <li><a href="#specifications">Specifications</a></li>
                <li><a href="#pricing">Pricing</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Home Section -->
    <section id="home">
        <h2>Welcome to Aaro Purifier</h2>
        <p>The future of air purification is here! Aaro Purifier Machine is designed to improve your air quality and make your living spaces healthier.</p>
        <!-- Adding an image to the home section -->
        <img src="C:/Users/sgupta24/Desktop/html/RO purifire.jpg" alt="RO purifire" width="500">
    </section>
      <!-- Cart Section -->
    <section id="cart" class="cart-container">
        <h2>Your Cart</h2>
        <div id="cart-items"></div>
        <div class="cart-total">
            <strong>Total: $<span id="total-price">0</span></strong>
        </div>

        <div class="cart-form">
            <label for="address">Address:</label>
            <input type="text" id="address" placeholder="Enter your address" required />
            <button id="update-address-btn">Change Address</button>
        </div>

        <button class="place-order-button" id="place-order-btn">Place Order</button>
    </section>
    <!-- Features Section -->
    <section id="features">
        <h2>Key Features</h2>
        <ul>
            <li>Advanced Filtration System</li>
            <li>Energy-Efficient</li>
            <li>Smart Air Quality Detection</li>
            <li>Low Noise Operation</li>
        </ul>
    </section>

    <!-- Specifications Section -->
    <section id="specifications">
        <h2>Specifications</h2>
        <table>
            <tr>
                <td>Model:</td>
                <td>Aaro Purifier X100</td>
            </tr>
            <tr>
                <td>Power Consumption:</td>
                <td>30W</td>
            </tr>
            <tr>
                <td>Weight:</td>
                <td>5.5 kg</td>
            </tr>
            <tr>
                <td>Noise Level:</td>
                <td>35 dB</td>
            </tr>
        </table>
    </section>

    <!-- Pricing Section -->
    <section id="pricing">
        <h2>Pricing</h2>
        <p>Get the Aaro Purifier Machine for just <strong>$299</strong></p>
        <button id="buy-now-btn">Buy Now</button>
        <div id="ro-purifier-list" style="display: none;">
            <h3>Choose Your RO Purifier</h3>
            <div class="ro-list" id="ro-list-container"></div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Us</h2>
        <p>If you have any questions, feel free to contact us!</p>
        <!-- Update the action URL with your Formspree endpoint -->
        <form action="https://formspree.io/f/xkgodrqn" method="POST">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required><br>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required><br>
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea><br>
            <input type="submit" value="Submit">
        </form>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2025 Aaro Purifier Machine. All rights reserved.</p>
    </footer>

<script>
        // RO purifier data (for demonstration purposes)
        const roPurifiers = Array.from({ length: 50 }, (_, i) => ({
            name: `RO Purifier ${i + 1}`,
            rate: `$${(100 + i * 5).toFixed(2)}`,
            capacity: `${(i % 5) + 10}L`,
            load: `${(i % 3) + 1} kW`
        }));

        // Store the cart items and address
        let cart = [];
        let totalPrice = 0;
        let address = "";

        // Display the RO purifiers when "Buy Now" is clicked
        document.getElementById("buy-now-btn").addEventListener("click", function() {
            const roListContainer = document.getElementById("ro-list-container");
            roListContainer.innerHTML = ''; // Clear previous content
            roPurifiers.forEach(purifier => {
                const roItem = document.createElement('div');
                roItem.classList.add('ro-item');
                roItem.innerHTML = `
                    <h3>${purifier.name}</h3>
                    <p>Rate: ${purifier.rate}</p>
                    <p>Capacity: ${purifier.capacity}</p>
                    <p>Load: ${purifier.load}</p>
                    <div class="button-container">
                        <button onclick="addToCart('${purifier.name}', ${purifier.rate.slice(1)})">Add to Cart</button>
                        <button onclick="window.location.href='checkout.html'">Buy Now</button>
                    </div>
                `;
                roListContainer.appendChild(roItem);
            });
            document.getElementById("ro-purifier-list").style.display = 'block';
        });

        // Add item to the cart and update the cart UI
        function addToCart(name, rate) {
            cart.push({ name, rate });
            totalPrice += rate;

            // Show the cart
            showCart();
        }

        // Show the cart with the items
        function showCart() {
            const cartItemsContainer = document.getElementById("cart-items");
            cartItemsContainer.innerHTML = '';

            cart.forEach(item => {
                const itemElement = document.createElement('div');
                itemElement.classList.add('cart-item');
                itemElement.innerHTML = `
                    <h4>${item.name}</h4>
                    <p>$${item.rate}</p>
                `;
                cartItemsContainer.appendChild(itemElement);
            });

            document.getElementById("total-price").textContent = totalPrice.toFixed(2);
            document.getElementById("cart").style.display = 'block';
        }

        // Handle the address change
        document.getElementById("update-address-btn").addEventListener("click", function() {
            address = document.getElementById("address").value;
            if (address) {
                alert("Address updated successfully!");
            } else {
                alert("Please enter a valid address.");
            }
        });

        // Handle the place order action
        document.getElementById("place-order-btn").addEventListener("click", function() {
            if (cart.length === 0) {
                alert("Your cart is empty. Please add items before placing an order.");
                return;
            }

            if (!address) {
                alert("Please provide your address before placing the order.");
                return;
            }

            alert(`Order placed successfully! Your total is $${totalPrice.toFixed(2)}. Address: ${address}`);
            // Reset cart and address after placing the order
            cart = [];
            totalPrice = 0;
            document.getElementById("total-price").textContent = '0';
            document.getElementById("cart").style.display = 'none';
        });
    </script>
</body>
</html>
