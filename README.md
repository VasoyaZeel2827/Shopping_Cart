
<html>
<head>
    <title>Shopping Cart</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 50%;
            margin: 50px auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            text-align: left;
        }
        h2 {
            text-align: center;
        }
        .book {
            border-bottom: 1px solid #ddd;
            padding: 15px 0;
            display: flex;
            align-items: center;
        }
        .book img {
            margin-right: 20px;
            border-radius: 5px;
        }
        .book-info {
            flex: 1;
        }
        label {
            font-weight: bold;
        }
        input[type="number"] {
            width: 50px;
            padding: 5px;
            margin-left: 10px;
        }
        .checkout-btn {
            background-color: #05A8AA;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            display: block;
            margin: 20px auto;
            border-radius: 5px;
        }
        .checkout-btn:hover {
            background-color: #048b8d;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Shopping Cart</h2>
        
        <div class="book">
            <img src="/Image/81OrquAzkJL._AC_UF1000-1000_QL80_.jpg" alt="Book 1" width="100">
            <div class="book-info">
                <p><strong>Title:</strong> The Great Adventure</p>
                <p><strong>Author:</strong> John Smith</p>
                <p><strong>Price:</strong> $15.99</p>
                <label for="quantity1">Quantity:</label>
                <input type="number" id="quantity1" name="quantity1" value="1" min="1">
            </div>
        </div>
        
        <div class="book">
            <img src="/Image/automic habits.webp" alt="Book 2" width="100">
            <div class="book-info">
                <p><strong>Title:</strong> Science Wonders</p>
                <p><strong>Author:</strong> Jane Doe</p>
                <p><strong>Price:</strong> $12.99</p>
                <label for="quantity2">Quantity:</label>
                <input type="number" id="quantity2" name="quantity2" value="1" min="1">
            </div>
        </div>
        
        <div class="book">
            <img src="/Image/book-img2.jpg" alt="Book 3" width="100">
            <div class="book-info">
                <p><strong>Title:</strong> History Unveiled</p>
                <p><strong>Author:</strong> Robert Brown</p>
                <p><strong>Price:</strong> $18.99</p>
                <label for="quantity3">Quantity:</label>
                <input type="number" id="quantity3" name="quantity3" value="1" min="1">
            </div>
        </div>
        
        <button class="checkout-btn" type="submit">Proceed to Checkout</button>
    </div>
</body>
</html>
