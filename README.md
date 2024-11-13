# Lunch-box-
<!DOCTYPE html>
<html>

<head>
    <title>Order Your Lunch</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <h1>Order Your Lunch</h1>

    <form action="order_process.php" method="post"> <label for="name">Name:</label>
        <input type="text" id="name" name="name" required><br><br>

        <label for="phone">Phone Number:</label>
        <input type="tel" id="phone" name="phone" required><br><br>

        <label for="address">Delivery Address:</label>
        <textarea id="address" name="address" required></textarea><br><br>

        <h2>Choose Your Lunch</h2>

        <div class="lunch-option">
            <input type="radio" id="veg" name="lunch_type" value="veg">
            <label for="veg">Vegetarian</label>
            
        </div>

        <div class="lunch-option">
            <input type="radio" id="non-veg" name="lunch_type" value="non-veg">
            <label for="non-veg">Non-Vegetarian</label>
        </div>

        <br>

        <label for="quantity">Quantity:</label>
        <input type="number" id="quantity" name="quantity" min="1" required><br><br>

        <input type="submit" value="Order Now">
    </form>
</body>

</html>
