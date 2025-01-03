<h1>Описание моего интернет-магазина на Laravel</h1>
<h2>Здравствуйте! В этом репозитории я расскажу вам о своем проекте.</h2>
<h3>Я использовал Laravel 11, PHP 8.3, MySQL 8.2, OSP и Windows 11.</h3>

<h2>Контроллеры</h2>
<h3>Было создано два контроллера.</h3>
<h4>"CartController.php" управляет товарами в корзине и обрабатывает оформление заказа.</h4>
<h4>"ProductController.php" отображает товары. Это более простой контроллер, так как большинство функционала реализовано в "CartController.php".</h4>

<h2>Модели</h2>
<h3>Было создано три модели.</h3>
<h4>"Order.php" определяет свойства заказа.</h4>
<h4>"Product.php" описывает характеристики товара.</h4>
<h4>"User .php" указывает атрибуты пользователя.</h4>

<h2>База данных</h2>
<h3>Было создано две миграции.</h3>
<h4>"create_products_table.php" для создания таблицы с продуктами.</h4>
<h4>"create_orders_table.php" для создания таблицы с заказами.</h4>
<h4>Дамп базы данных я приложил.</h4>
<h3>Был создан один сидер.</h3>
<h4>"ProductSeeder.php" генерирует список товаров.</h4>

<h2>CSS</h2>
<h3>Был создан один CSS файл в public/css/</h3>
<h4>"app.css" содержит все стили, которые я использовал.</h4>

<h2>Resources/views</h2>
<h4>"index.blade.php" служит главной страницей, отображающей список товаров.</h4>

<h2>Resources/views/</h2>
<h2>cart/</h2>
<h4>"checkout.blade.php" используется для оформления заказов.</h4>
<h4>"show.blade.php" описывает корзину.</h4>

<h2>checkout/</h2>
<h4>"confirmation.blade.php" обрабатывает подтверждение заказа.</h4>

<h2>layouts/</h2>
<h4>"app.blade.php" определяет заголовок и подвал.</h4>
<h4>"custom.blade.php" отвечает за пагинацию.</h4>

<h2>products/</h2>
<h4>"show.blade.php" является отдельной страницей для каждого товара.</h4>

<h2>Маршруты</h2>
<h4>"web.php" перечисляет все маршруты.</h4>

<h2>Основной функционал</h2>
<h4>Детали продукта включают название, цену и наличие на складе.</h4>
<h4>Каждый продукт открывается на новой странице.</h4>
<h4>На странице продукта можно добавить товар в корзину.</h4>
<h4>Из корзины можно перейти к оформлению заказа.</h4>
<h4>На странице оформления заказа необходимо указать свои данные (имя, email).</h4>
<h4>После завершения заказа вы получите подтверждение.</h4>
<h4>Во всех файлах содержатся комментарии для вашего удобства.</h4>
