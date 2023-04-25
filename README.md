# phanbanhat.github.io
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Meow</title>
        <link rel="stylesheet" href="Style/CSS/style.css">
        <link rel="stylesheet" href="fontawesome-free-6.3.0-web/css/all.min.css">
    </head>
    <body>
        <!-- HEADER -->
        <header>
            <div class="nav container">
                <a href="https://www.facebook.com/hibari.sv" class="logo">
                    <i class=" fa-solid fa-paw"></i>
                    Meow
                </a>
                <!-- Cart-Icon -->
                <i class="fa-solid fa-bag-shopping" id="cart-icon"></i>
                <!-- Cart -->
                <div class="cart">
                    <h2 class="cart-title">Giỏ hàng</h2>
                    <!-- Content -->
                    <div class="cart-content">
                    </div>
                    <!-- Total -->
                    <div class="total">
                        <div class="total-title">Tổng tiền:</div>
                        <div class="total-price">0đ</div>
                    </div>
                    <!-- Buy Button -->
                    <button type="button" class="btn-buy">Mua ngay</button>
                    <!-- Cart Close -->
                    <i class="fa-solid fa-xmark" id="close-cart"></i>
                </div>
            </div>
        </header>
        <!-- Shop -->
        <div class="btn container">
            <h2 class="container__heading">
                <i class=" fa-solid fa-paw"></i>
                Menu
                <i class=" fa-solid fa-paw"></i>
            </h2>
            <div class="btn-menu">
                <div class="btn-menu__1">
                    <div class="btn-menu__1-1">
                        <a href="Index/menu1/menu__1.html" class="button">
                            Thức ăn
                        </a>
                    </div>
                    <div class="btn-menu__1-1">
                        <a href="Index/menu2/menu__1.html" class="button">
                            Bánh mì
                        </a>
                    </div>
                    <div class="btn-menu__1-1">
                        <a href="Index/menu3/menu__1.html" class="button">
                            Trái cây
                        </a>
                    </div>
                    <div class="btn-menu__1-1">
                        <a href="Index/menu4/menu__1.html" class="button">
                            Bánh ngọt
                        </a>
                    </div>
                </div>
                <div class="btn-menu__1">
                    <div class="btn-menu__1-1">
                        <a href="Index/menu5/menu__1.html" class="button">
                            Thức uống
                        </a>
                    </div>
                    <div class="btn-menu__1-1">
                        <a href="Index/menu6/menu__1.html" class="button">
                            Tráng miệng
                        </a>
                    </div>
                    <div class="btn-menu__1-1">
                        <a href="Index/menu7/menu__1.html" class="button">
                            Caffe & Trà
                        </a>
                    </div>
                    <div class="btn-menu__1-1">
                        <a href="Index/menu8/menu__1.html" class="button">
                            Trà sữa
                        </a>
                    </div>
                </div>
            </div>
        </div>

        <footer>
            <div class="footer container">
                <a href="https://www.facebook.com/hibari.sv">
                    <div class="footer-link__fb">
                        <i class="fa-brands fa-facebook"></i>
                        Facebook
                    </div>
                </a>
                <a href="https://www.facebook.com/hibari.sv">
                    <div class="footer-link__fb">
                        <i class="fa-brands fa-facebook-messenger"></i>
                        Messenger
                    </div>
                </a>
                <a href="https://www.instagram.com/duphanba/">
                    <div class="footer-link__fb">
                        <i class="fa-brands fa-instagram"></i>
                        Instagram
                    </div>
                </a>
            </div>
        </footer>

        <!-- Link To JS -->
        <script src="Style/JS/cart.js"></script>
    </body>
</html>
