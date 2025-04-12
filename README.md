# AD-Online-Shop
```html
<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AD Online Shop</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <div class="logo">
            <h1>AD Online Shop</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#home">হোম</a></li>
                <li><a href="#shop">শপ</a></li>
                <li><a href="#about">আমাদের সম্পর্কে</a></li>
                <li><a href="#contact">যোগাযোগ</a></li>
            </ul>
        </nav>
    </header>

    <!-- Banner Section -->
    <section id="home" class="banner">
        <h2>স্বাগতম AD Online Shop-এ</h2>
        <p>সর্বশেষ ফ্যাশন এবং আরামদায়ক পোশাকের জন্য আমাদের সাথে থাকুন।</p>
    </section>

    <!-- Product Categories Section -->
    <section id="shop" class="categories">
        <h3>পণ্য ক্যাটেগরি</h3>
        <div class="category">
            <h4>পুরুষ</h4>
            <ul>
<li><a href="#">টিশার্ট</a></li>
                <li><a href="#">হুডি</a></li>
                <li><a href="#">জিন্স</a></li>
            </ul>
        </div>
        <div class="category">
            <h4>মহিলা</h4>
            <ul>
                <li><a href="#">টপস</a></li>
                <li><a href="#">প্যান্ট</a></li>
                <li><a href="#">জাম্পসুট</a></li>
            </ul>
        </div>
        <div class="category">
            <h4>শিশু</h4>
            <ul>
                <li><a href="#">টিশার্ট</a></li>
                <li><a href="#">শর্টস</a></li>
                <li><a href="#">জাম্পসুট</a></li>
            </ul>
        </div>
    </section>

    <!-- About Us Section -->
    <section id="about" class="about-us">
        <h3>আমাদের সম্পর্কে</h3>
        <p>AD Online Shop বাংলাদেশের একটি দ্রুত বর্ধনশীল পোশাক ব্র্যান্ড, যেখানে আপনি পাবেন উচ্চমানের পোশাক যা আরামদায়ক এবং ফ্যাশনেবল।</p>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h3>যোগাযোগ</h3>
        <p>কোনো প্রশ্ন বা পরামর্শের জন্য আমাদের সাথে যোগাযোগ করুন:</p>
        <p>ফোন: +8801991652537</p>
    </section>
<!-- Footer Section -->
    <footer>
<p>&copy; ২০২৫ AD Online Shop. সর্বস্বত্ব সংরক্ষিত।</p>
    </footer>
</body>
</html>
```

*2. CSS (styles.css):*

```css
/* General Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

a {
    text-decoration: none;
    color: #333;
}

/* Header Styles */
header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 20px;
}

header .logo h1 {
    margin: 0;
}

header nav ul {
    list-style-type: none;
    display: flex;
    gap: 20px;
    margin: 0;
}

header nav ul li {
    margin: 0;
}

/* Banner Section */
.banner {
    background-color: #4CAF50;
    color: #fff;
    padding: 50px 20px;
    text-align: center;
}

.banner h2 {
    margin: 0;
    font-size: 2em;
}

.banner p {
    font-size: 1.2em;
}

/* Categories Section */
.categories {
    display: flex;
    justify-content: space-around;
    padding: 20px;
    background-color: #fff;
}

.category {
    width: 30%;
}

.category h4 {
    font-size: 1.5em;
    margin-bottom: 10px;
}

.category ul {
    list-style-type: none;
    padding: 0;
}

.category ul li {
    margin: 5px 0;
}

/* About Us Section */
.about-us {
    padding: 20px;
background-color: #fff;
    text-align: center;
}

.about-us h3 {
    font-size: 1.8em;
    margin-bottom: 10px;
}

.about-us p {
    font-size: 1.2em;
    color: #555;
}

/* Contact Section */
.contact {
    padding: 20px;
    background-color: #fff;
    text-align: center;
}

.contact h3 {
    font-size: 1.8em;
    margin-bottom: 10px;
}

.contact p {
    font-size: 1.2em;
    color: #555;
}

/* Footer Section */
footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}
```
