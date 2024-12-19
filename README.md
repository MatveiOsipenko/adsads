<h1>Description of My Online Store Built with Laravel</h1>
<h2>Hello! In this repository, I will share details about my project.</h2>
<h3>I utilized Laravel 11, PHP 8.3, MySQL 8.2, OSP, and Windows 11.</h3>

<h2>Controllers</h2>
<h3>Two controllers were created.</h3>
<h4>"CartController.php" manages the products in the cart and handles order processing.</h4>
<h4>"ProductController.php" displays the products. This is a simpler controller since most of the functionality is handled in "CartController.php".</h4>

<h2>Models</h2>
<h3>Three models were developed.</h3>
<h4>"Order.php" defines the properties of an order.</h4>
<h4>"Product.php" outlines the characteristics of a product.</h4>
<h4>"User .php" specifies the attributes of a user.</h4>

<h2>Database</h2>
<h3>Two migrations were created.</h3>
<h4>"create_products_table.php" for establishing the products table.</h4>
<h4>"create_orders_table.php" for setting up the orders table.</h4>
<h4>A database dump has been included.</h4>
<h3>One seeder was created.</h3>
<h4>"ProductSeeder.php" generates a list of products.</h4>

<h2>CSS</h2>
<h3>One CSS file was created in public/css/</h3>
<h4>"app.css" contains all the styles I used.</h4>

<h2>Resources/views</h2>
<h4>"index.blade.php" serves as the main page displaying the list of products.</h4>

<h2>Resources/views/</h2>
<h2>cart/</h2>
<h4>"checkout.blade.php" is used for processing orders.</h4>
<h4>"show.blade.php" describes the cart.</h4>

<h2>checkout/</h2>
<h4>"confirmation.blade.php" handles order confirmation.</h4>

<h2>layouts/</h2>
<h4>"app.blade.php" defines the header and footer.</h4>
<h4>"custom.blade.php" addresses pagination.</h4>

<h2>products/</h2>
<h4>"show.blade.php" is a dedicated page for each product.</h4>

<h2>Routes</h2>
<h4>"web.php" lists all the routes.</h4>

<h2>Main Functionality</h2>
<h4>Product details include name, price, and stock availability.</h4>
<h4>Each product opens on a new page.</h4>
<h4>On the product page, you can add the item to your cart.</h4>
<h4>From the cart, you can proceed to checkout.</h4>
<h4>On the checkout page, you will need to provide your details (name, email).</h4>
<h4>After completing your order, you will receive a confirmation.</h4>
<h4>All files contain comments for your convenience.</h4>
