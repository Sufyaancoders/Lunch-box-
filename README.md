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
             <select>
                <option value="Choose Dishes">Choose Dishes</option>
                <option value="Dal">Dal</option>
                <option value="Mater Paneer">Mater paneer</option>
                <option value="Chhole">Chhole</option>
                <option value="Palak">Palak</option>
                <option value="Soyachap">Soyachap</option>
                <option value="Curry">Curry</option>
                <option value="Bhaji">Bhaji</option>
                <option value="Sahi paneer">Sahi paneer></option>
            </select>
        </div><br>

        <div class="lunch-option">
            <input type="radio" id="non-veg" name="lunch_type" value="non-veg">
            <label for="non-veg">Non-Vegetarian</label>
            <select>
                <option value="Choose Dishes">Choose Dishes</option>
                <option value="Chicken">Chicken</option>
                <option value="Matan">Matan</option>
                <option value="Chiken Biryani">Chicken Biryani</option>
                <option value="Rosted chiken">Rosted chiken</option>
                <option value="Boil Chiken">Boil chiken</option>
            </select>
        </div>

        <br>

        <label for="quantity">Quantity:</label>
        <input type="number" id="quantity" name="quantity" min="1" required><br><br>

        <input type="submit" value="Order Now">
    </form>
</body>

</html>
