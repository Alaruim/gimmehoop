<!DOCTYPE html>
<html lang="en">

<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>GIMMEHOOP</title>
	<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css" />
	<link rel="stylesheet" href="product.css">
	<!-- Подключаем шрифт Inter -->
	<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;700;900&display=swap" rel="stylesheet">
</head>

<body>
	<!-- header -->
	<header>
		<!-- Полоска с промокодом -->
		<div class="promo-bar">
			<div>
				BUY 2 GET 1 FREE <span class="code"> сode: </span> B2G1
			</div>
		</div>

		<!-- Основной хедер -->
		<nav class="navbar">
			<div class="content">
				<div class="header-container">
					
					<div class="burger-menu desktop-hidden">
						<div class="burger-icon" onclick="toggleMenu()">
						  <div class="bar"></div>
						  <div class="bar"></div>
						  <div class="bar"></div>
						</div>
						<div class="dropdown-menu mobile-hidden">
						  <a href="#">Home</a>
						  <a href="#">Shop</a>
						  <a href="#">About Us</a>
						</div>
					</div>

					<div class="logo">
						<img src="images/logo.png" alt="Logo">
					</div>
					<a class="mobile-hidden" href="#">Home</a>
					<div class="dropdown-shop mobile-hidden">
						<div class="a-shop">
							<a href="#">
								<span>Shop</span>
								<img src="images/shop-vector.svg" alt="Logo">
							</a>
							<div class="dropdown-menu-shop">
								<a href="#">Framed Canvas Collection</a>
								<a href="#">Basketball Art Framed Hoops</a>
								<a href="#">Surfboards</a>
								<a href="#">Arts</a>
							</div>
						</div>
					</div>
					<a  class="mobile-hidden" href="#">About Us</a>
					<div class="nav-icons ">
						<button class="search-btn mobile-hidden">
							<img src="images/search.svg" alt="Logo">
						</button>
						<button class="cart-btn">
							<div class="cart-and-circle">
								<img src="images/cart.svg" alt="Logo">
								<div>0</div>
							</div>
							<span class="mobile-hidden">$0.00</span>
						</button>
					</div>
				</div>
			</div>
		</nav>
	</header>
	<!-- 1 блок -->
	<div class="block-product">
		<div class="content block-product-container">
			<div class="block-product-description">
				<h2>Description</h2>
				<h3>Italian Framed Hoop</h3>
				<div class="desc-image-sh">
					<img src="images/block-product-desc-image.png" alt="">
					<img src="images/product-shadow.png" alt="">
				</div>

				<span>About the product</span>
				<p> Show off your ultimate fandom with this collection of framed basketball hoops. Each unique piece is
					framed in an oversized Baroque style frame with a leather backing, giving the ultimate sport the
					royal treatment. This collection is sure to be a conversation starter among guests. </p>
				<div class="block-product-tags">
					<div>Hanging hardware included</div>
					<div>Frame included</div>
					<div>Worldwide Shipping</div>
				</div>

			</div>
			<div class="block-product-image">
				<img src="images/block-product-main-image.png" class="background-img" id="hero-image">
				<button class="overlay-img mobile-hidden"><img src="images/block-product-main-image-up.png"></button>
			</div>
			<div class="slider-block-horizontal desktop-hidden">
				<div class="swiper-container">
					<div class="swiper-wrapper">
						<div class="swiper-slide"><img class="slider-horiz-img" src="images/horiont-slider-2.png" alt="Image 1"></div>
						<div class="swiper-slide"><img class="slider-horiz-img" src="images/block-product-main-image.png" alt="Image 1"></div>
						<div class="swiper-slide"><img class="slider-horiz-img" src="https://i.natgeofe.com/n/548467d8-c5f1-4551-9f58-6817a8d2c45e/NationalGeographic_2572187_3x2.jpg" alt="Image 1"></div>
						<div class="swiper-slide"><img class="slider-horiz-img" src="images/block-product-main-image.png" alt="Image 1"></div>
						<div class="swiper-slide"><img class="slider-horiz-img" src="images/block-product-main-image.png" alt="Image 1"></div>
					</div>
				</div>
			</div>
			<div id="overlay" class="overlay"></div>
			<div class="block-product-selling">
				<h1>Italian Framed Hoop</h1>
				<div class="bar-rating">
					<div class="bar-stars">
						<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
							<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
						</svg>
						<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
							<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
						</svg>
						<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
							<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
						</svg>
						<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
							<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
						</svg>
						<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
							<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
						</svg>
					</div>
					<div class="bar-rating-score">(3.9)</div>
					<div class="bar-rating-count">3182 Reviews</div>
				</div>
				<div class="dropdown-container">
					<span>Size:</span>

					<div class="custom-select">
						<div class="selected">
							<span>20*16 inches (50*40cm)</span>
							<img src="images/arrow.svg" alt="">
						</div>
						<div class="dropdown">
							<div class="option">20*16 inches (50*40cm)</div>
							<div class="option">30*26 inches (75*65cm)</div>
							<div class="option">40*32 inches (100*80cm)</div>
							<div class="option">64*48 inches (162*123cm)</div>
						</div>
						<!-- Скрытый селект -->
						<select class="hidden-select">
							<option value="20*16 inches (50*40cm)">20*16 inches (50*40cm)</option>
							<option value="30*26 inches (75*65cm)">30*26 inches (75*65cm)</option>
							<option value="40*32 inches (100*80cm)">40*32 inches (100*80cm)</option>
							<option value="64*48 inches (162*123cm)">64*48 inches (162*123cm)</option>
						</select>
					</div>
					<div class="container-button desktop-hidden">
						<button class="minus-button">-</button>
						<input type="number" id="quantity" value="0">
						<button class="plus-button">+</button>
					</div>

				</div>
				<div class="price-bar">
					<div class="act-price">$379.90</div> <span>$499.90</span>
				</div>
				<div class="bar-progress mobile-hidden">
					<progress value="3" max="50"></progress>
					<span>Only 3 left in stock</span>
				</div>
				<div class="add-to-cart">
					<button class="add-button">ADD TO CART</button>
				</div>
				<img class="img-card mobile-hidden" src="images/card.png" alt="">
				<div class="delivery">
					Expected Delivery Date to Russian Federation 
					<span>янв. 17 - янв. 19</span>
				</div>
				<div class="bar-progress desktop-hidden">
					<progress value="3" max="50"></progress>
					<span>Only 3 left in stock</span>
				</div>
				<div class="easy-returns mobile-hidden">
					<span>EASY RETURNS / EXCHANGES</span>
					<div class="p-ret">Customer satisfaction is our number one priority. If for any reason you are dissatisfied, we will gladly issue a&nbsp;full refund, exchange, or GIMMEHOOP store credit for items returned.</div>
				</div>

			</div>
		</div>
	</div>
	<!-- 2 блок -->
	<div class="slider-block-horizontal mobile-hidden">
		<div class="swiper-container">
			<div class="swiper-wrapper">
				<div class="swiper-slide"><img class="slider-horiz-img" src="images/block-product-main-image.png" alt="Image 1"></div>
				<div class="swiper-slide"><img class="slider-horiz-img" src="https://i.natgeofe.com/n/548467d8-c5f1-4551-9f58-6817a8d2c45e/NationalGeographic_2572187_3x2.jpg" alt="Image 1"></div>
				<div class="swiper-slide"><img class="slider-horiz-img" src="images/horiont-slider-1.png" alt="Image 1"></div>
				<div class="swiper-slide"><img class="slider-horiz-img" src="images/horiont-slider-2.png" alt="Image 1"></div>
				<div class="swiper-slide"><img class="slider-horiz-img" src="images/horiont-slider-1.png" alt="Image 1"></div>
				<div class="swiper-slide"><img class="slider-horiz-img" src="images/horiont-slider-2.png" alt="Image 1"></div>
				<div class="swiper-slide"><img class="slider-horiz-img" src="images/horiont-slider-1.png" alt="Image 1"></div>
				<div class="swiper-slide"><img class="slider-horiz-img" src="images/horiont-slider-2.png" alt="Image 1"></div>
				<div class="swiper-slide"><img class="slider-horiz-img" src="images/horiont-slider-1.png" alt="Image 1"></div>
				<div class="swiper-slide"><img class="slider-horiz-img" src="images/horiont-slider-2.png" alt="Image 1"></div>
				<div class="swiper-slide"><img class="slider-horiz-img" src="images/horiont-slider-1.png" alt="Image 1"></div>
				<div class="swiper-slide"><img class="slider-horiz-img" src="images/horiont-slider-2.png" alt="Image 1"></div>
				<div class="swiper-slide"><img class="slider-horiz-img" src="images/horiont-slider-1.png" alt="Image 1"></div>
				<div class="swiper-slide"><img class="slider-horiz-img" src="images/horiont-slider-2.png" alt="Image 1"></div>
				<div class="swiper-slide"><img class="slider-horiz-img" src="images/horiont-slider-1.png" alt="Image 1"></div>
				<div class="swiper-slide"><img class="slider-horiz-img" src="images/horiont-slider-2.png" alt="Image 1"></div>
				<div class="swiper-slide"><img class="slider-horiz-img" src="images/horiont-slider-1.png" alt="Image 1"></div>
				<div class="swiper-slide"><img class="slider-horiz-img" src="images/horiont-slider-2.png" alt="Image 1"></div>
				<div class="swiper-slide"><img class="slider-horiz-img" src="images/horiont-slider-1.png" alt="Image 1"></div>
				<div class="swiper-slide"><img class="slider-horiz-img" src="images/horiont-slider-2.png" alt="Image 1"></div>
			</div>
			<div class="swiper-button-prev"></div>
			<div class="swiper-button-next"></div>
		</div>
	</div>
	<!-- 3 блок -->
	<div class="block-line-shadow block-line-shadow-border">
		<div class="content">
			<div class="block-slider-chosen1">
				
				<h3 class="desktop-hidden">Choose Your Size</h3>
				<div class="slider-cart">
					<div class="swiper mySwiper">
						<div class="swiper-pagination"></div>
						<div class="swiper-wrapper">
							<div class="swiper-slide"><img src="images/choose-slze.png" alt=""></div>
							<div class="swiper-slide"><img src="images/choose-slze.png" alt=""></div>
							<div class="swiper-slide"><img src="images/choose-slze.png" alt=""></div>
						</div>
						<div class="swiper-button-prev"></div>
						<div class="swiper-button-next"></div>
					</div>
				</div>
				<div class="chosen-desc">
					
					<div class="chosen-desc-block">
						<h3 class="mobile-hidden">Choose Your Size</h3>
						<p>Get your own framed hoop for fun and games at your home or office. Imagine how much of a conversation starter this would be in your home.</p>
						<ul class="mobile-hidden">
							<li>A conversation starter</li>
							<li>Shows off your impeccable taste</li>
							<li>Increases the amount of gold in your house</li>
							<li>Dunk on your friends. (It’s functional, but we recommend lay ups, as we wouldn’t want you to damage it!)</li>
						</ul>
						
					</div>
					
				</div>
			</div>

		</div>
	</div>
	<div class="block-line-shadow">
		<div class="content">
			<div class="block-slider-chosen2">
				
				<div class="chosen-desc">
					<h3>We are being chosen</h3>
					<p class="mobile-hidden">Get your own framed hoop for fun and games at your home or office. Imagine how much of a
						conversation starter this would be in your home. Get your own framed hoop for fun and games at
						your home or office.</p>
				</div>
				<div class="slider-cart">
					<div class="swiper mySwiper">
						<div class="swiper-pagination"></div>
						<div class="swiper-wrapper">
							<div class="swiper-slide"><img src="images/card-slider-1-1.png" alt=""></div>
							<div class="swiper-slide"><img src="images/card-slider-1-1.png" alt=""></div>
							<div class="swiper-slide"><img src="images/card-slider-1-1.png" alt=""></div>
						</div>
						<div class="swiper-button-prev"></div>
						<div class="swiper-button-next"></div>
					</div>
				</div>
				<p class="desktop-hidden">Get your own framed hoop for fun and games at your home or office. Imagine how much of a
					conversation starter this would be in your home. Get your own framed hoop for fun and games at
					your home or office.</p>
			</div>
		</div>
	</div>

	<!-- 4 блок -->
	<div class="image-line">
		<div class="content content-image-line">
			<span class="mobile-hidden">
				<img src="images/line-image-1.png" alt="">
				FAST WORLDWIDE DELIVERY
			</span>
			<span class="mobile-hidden">
				<img src="images/line-image-2.png" alt="">
				100% SAFE & SECURE CHECKOUT
			</span>
			<span class="desktop-hidden">
				<img class="img1" src="images/line-image-1.png" alt="">
				FAST DELIVERY AND 100% SAFETY
			</span>
			<span>
				<img class="img2" src="images/line-image-3.png" alt="">
				HIGH QUALITY PRODUCT
			</span>
		</div>
	</div>
	<!-- 5 блок -->
	<div class="content mobile-hidden">
		<div class="block-reviews">
			<div class="cust-rev-dropdown-cont mobile-hidden">
				<div class="customer-reviews">
					<div class="cust-rev-text">CUSTOMER REVIEWS</div>
					<div class="rait">
						<div class="bar-stars">
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
						</div>
						<div class="numb-rait">4.9 out of 5.0</div>
					</div>
					<div class="count-rev">3182 Reviews</div>
					<div class="rait-progress-bar">
						<div class="rait-num">5</div>
						<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
							<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
						</svg>
						<progress value="90" max="100"></progress>
					</div>
					<div class="rait-progress-bar">
						<div class="rait-num">4</div>
						<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
							<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
						</svg>
						<progress value="7" max="100"></progress>
					</div>
					<div class="rait-progress-bar">
						<div class="rait-num">3</div>
						<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
							<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
						</svg>
						<progress value="3" max="100"></progress>
					</div>
					<div class="rait-progress-bar">
						<div class="rait-num">2</div>
						<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
							<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
						</svg>
						<progress value="0" max="100"></progress>
					</div>
					<div class="rait-progress-bar">
						<div class="rait-num">1</div>
						<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
							<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
						</svg>
						<progress value="0" max="100"></progress>
					</div>
	
	
	
				</div>
				<div class="dropdown-container">
					<div class="custom-select">
						<div class="selected">
							<span style="font-weight: 700;">Top reviews</span>
							<img src="images/arrow.svg" alt="">
						</div>
						<div class="dropdown">
							<div class="option">All reviews</div>
							<div class="option">New reviews</div>
							<div class="option">Top reviews</div>
						</div>
						<!-- Скрытый селект -->
						<select class="hidden-select">
							<option value="All reviews">All reviews</option>
							<option value=">New reviews">>New reviews</option>
							<option value="Top reviews">Top reviews</option>
						</select>
					</div>
	
				</div>
			</div>


			<div class="customer-say">
				<div class="cust-say-head">Customers say</div>
				<div class="cust-say-text">Customers find the board game enjoyable and creative. They appreciate its
					artistic design and easy learning process. The game pieces are well-made and of good quality. Many
					consider it a great value for money, though some are disappointed with the kickstarter exclusivity.
				</div>
				<div class="cust-say-ai">AI-generated from the text of customer reviews</div>
				<div class="rev-images-block">
					<div class="rev-images-text">Reviews with images</div>
					<button class="see-all-photo">
						<span>See all photo</span>
						<img src="images/arrow2.svg" alt="">
					</button>
					<div class="pop-cont">
						<div class="photo-popup">
							<div class="popup-content">
								<div class="close-popup">
									<img src="images/closed.png" alt=""> 
								</div>
								<div class="scroll-popup">
									<div class="photo-popup-content">
										<div><img src="images/see-all-photo.png" alt=""></div>
										<div><img src="https://i.natgeofe.com/n/548467d8-c5f1-4551-9f58-6817a8d2c45e/NationalGeographic_2572187_3x2.jpg" alt=""></div>
										<div><img src="images/see-all-photo.png" alt=""></div>
										<div><img src="images/see-all-photo.png" alt=""></div>
										<div><img src="images/see-all-photo.png" alt=""></div>
										<div><img src="images/see-all-photo.png" alt=""></div>
										<div><img src="images/see-all-photo.png" alt=""></div>
										<div><img src="images/see-all-photo.png" alt=""></div>
										<div><img src="images/see-all-photo.png" alt=""></div>
										<div><img src="images/see-all-photo.png" alt=""></div>
										<div><img src="images/see-all-photo.png" alt=""></div>
										<div><img src="images/see-all-photo.png" alt=""></div>
										<div><img src="images/see-all-photo.png" alt=""></div>
										<div><img src="images/see-all-photo.png" alt=""></div>
									</div>
								</div>
							</div>
						</div>
					
					</div>
				</div>
				<div class="slider-rev">
					<div class="swiper-father">
						<div class="swiper mySwiper3">
							<div class="swiper-wrapper">
								<div class="swiper-slide">
									<img src="images/also-like.png" alt="">
								</div>
								<div class="swiper-slide">
									<img src="images/also-like.png" alt="">
								</div>
								<div class="swiper-slide">
									<img src="images/also-like.png" alt="">
								</div>
								<div class="swiper-slide">
									<img src="images/also-like.png" alt="">
								</div>
								<div class="swiper-slide">
									<img src="images/also-like.png" alt="">
								</div>
								<div class="swiper-slide">
									<img src="images/also-like.png" alt="">
								</div>
							</div>
						</div>
						<div class="arrow-but">
							<button id="arrow-prev">
								<svg width="5" height="13" viewBox="0 0 5 13" fill="none" xmlns="http://www.w3.org/2000/svg">
									<path d="M0 6.5L4.5 0.870834L4.5 12.1292L0 6.5Z" fill="currentColor"/>
								</svg>									
							</button>
							<button id="arrow-next">
								<svg width="5" height="13" viewBox="0 0 5 13" fill="none" xmlns="http://www.w3.org/2000/svg">
									<path d="M0 6.5L4.5 0.870834L4.5 12.1292L0 6.5Z" fill="currentColor"/>
								</svg>									
							</button>
						</div>
					</div>

					
				</div>
			</div>
		</div>
	</div>
		<!-- 6 блок -->
		 <div class="block-rev-mob desktop-hidden">
			<h3>Customer reviews</h3>
			<div class="block-rev-mob-flex">
				<span>
					<span style="font-weight: 700;">4.9</span>
					out of 5.0
				</span>
				<div class="bar-stars">
					<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
						<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
					</svg>
					<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
						<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
					</svg>
					<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
						<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
					</svg>
					<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
						<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
					</svg>
					<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
						<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
					</svg>
				</div>
				<span>3182 Reviews</span>
			</div>
		 </div>
		<div class="content">
			<div class="block-top-reviews">
				<div class="top-rev-header">
					<div class="top-rew-1">Top reviews</div>
					<div class="dropdown-container desktop-hidden">
						<div class="custom-select">
							<div class="selected">
								<span>Top reviews</span>
								<img src="images/arrow.svg" alt="">
							</div>
							<div class="dropdown">
								<div class="option">All reviews</div>
								<div class="option">New reviews</div>
								<div class="option">Top reviews</div>
							</div>
							<!-- Скрытый селект -->
							<select class="hidden-select">
								<option value="All reviews">All reviews</option>
								<option value=">New reviews">>New reviews</option>
								<option value="Top reviews">Top reviews</option>
							</select>
						</div>
		
					</div>

				</div>
				<div class="rewiew">
					<img src="images/rewiew1.png" alt="">
					<div class="rewiew-block">
						<div class="name-block">
							<div class="name">JASON</div>
							<svg width="15" height="15" viewBox="0 0 15 15" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path d="M15 7.5C15 9.48912 14.2098 11.3968 12.8033 12.8033C11.3968 14.2098 9.48912 15 7.5 15C5.51088 15 3.60322 14.2098 2.1967 12.8033C0.790176 11.3968 0 9.48912 0 7.5C0 5.51088 0.790176 3.60322 2.1967 2.1967C3.60322 0.790176 5.51088 0 7.5 0C9.48912 0 11.3968 0.790176 12.8033 2.1967C14.2098 3.60322 15 5.51088 15 7.5ZM11.2781 4.65937C11.2112 4.59264 11.1314 4.5401 11.0437 4.50489C10.9559 4.46968 10.862 4.45252 10.7675 4.45445C10.673 4.45637 10.5798 4.47734 10.4936 4.5161C10.4073 4.55485 10.3298 4.6106 10.2656 4.68L7.00969 8.82844L5.0475 6.86531C4.91421 6.74111 4.73792 6.6735 4.55576 6.67671C4.3736 6.67992 4.1998 6.75372 4.07098 6.88254C3.94215 7.01137 3.86836 7.18517 3.86515 7.36732C3.86193 7.54948 3.92955 7.72577 4.05375 7.85906L6.53437 10.3406C6.6012 10.4073 6.68078 10.4599 6.76836 10.4952C6.85594 10.5305 6.94973 10.5477 7.04414 10.546C7.13854 10.5442 7.23163 10.5235 7.31784 10.485C7.40405 10.4465 7.48163 10.391 7.54594 10.3219L11.2884 5.64375C11.416 5.51109 11.4865 5.3337 11.4848 5.14965C11.483 4.9656 11.4092 4.78958 11.2791 4.65937H11.2781Z" fill="#5538C9"/>
							</svg>
							<span>Verified</span>
						</div>
						<div class="date">10.02.2025</div>

						<div class="bar-stars">
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
						</div>
						<div class="rewiew-text">Exquisite art object! The unique combination of contemporary art and
							baroque frame makes it a true masterpiece. Simply delighted! The fur combs easily in any
							direction, allowing you to style it as you wish. I created a fluffy, voluminous look!</div>
					</div>
				</div>
				<div class="rewiew">
					<img src="images/rewiew1.png" alt="">
					<div class="rewiew-block">
						<div class="name-block">
							<div class="name">JASON</div>
							<svg width="15" height="15" viewBox="0 0 15 15" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path d="M15 7.5C15 9.48912 14.2098 11.3968 12.8033 12.8033C11.3968 14.2098 9.48912 15 7.5 15C5.51088 15 3.60322 14.2098 2.1967 12.8033C0.790176 11.3968 0 9.48912 0 7.5C0 5.51088 0.790176 3.60322 2.1967 2.1967C3.60322 0.790176 5.51088 0 7.5 0C9.48912 0 11.3968 0.790176 12.8033 2.1967C14.2098 3.60322 15 5.51088 15 7.5ZM11.2781 4.65937C11.2112 4.59264 11.1314 4.5401 11.0437 4.50489C10.9559 4.46968 10.862 4.45252 10.7675 4.45445C10.673 4.45637 10.5798 4.47734 10.4936 4.5161C10.4073 4.55485 10.3298 4.6106 10.2656 4.68L7.00969 8.82844L5.0475 6.86531C4.91421 6.74111 4.73792 6.6735 4.55576 6.67671C4.3736 6.67992 4.1998 6.75372 4.07098 6.88254C3.94215 7.01137 3.86836 7.18517 3.86515 7.36732C3.86193 7.54948 3.92955 7.72577 4.05375 7.85906L6.53437 10.3406C6.6012 10.4073 6.68078 10.4599 6.76836 10.4952C6.85594 10.5305 6.94973 10.5477 7.04414 10.546C7.13854 10.5442 7.23163 10.5235 7.31784 10.485C7.40405 10.4465 7.48163 10.391 7.54594 10.3219L11.2884 5.64375C11.416 5.51109 11.4865 5.3337 11.4848 5.14965C11.483 4.9656 11.4092 4.78958 11.2791 4.65937H11.2781Z" fill="#5538C9"/>
							</svg>
							<span>Verified</span>
						</div>
						<div class="date">10.02.2025</div>

						<div class="bar-stars">
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
						</div>
						<div class="rewiew-text">Exquisite art object! The unique combination of contemporary art and
							baroque frame makes it a true masterpiece. Simply delighted! The fur combs easily in any
							direction, allowing you to style it as you wish. I created a fluffy, voluminous look!</div>
					</div>
				</div>
				<div class="rewiew">
					<img src="images/rewiew1.png" alt="">
					<div class="rewiew-block">
						<div class="name-block">
							<div class="name">JASON</div>
							<svg width="15" height="15" viewBox="0 0 15 15" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path d="M15 7.5C15 9.48912 14.2098 11.3968 12.8033 12.8033C11.3968 14.2098 9.48912 15 7.5 15C5.51088 15 3.60322 14.2098 2.1967 12.8033C0.790176 11.3968 0 9.48912 0 7.5C0 5.51088 0.790176 3.60322 2.1967 2.1967C3.60322 0.790176 5.51088 0 7.5 0C9.48912 0 11.3968 0.790176 12.8033 2.1967C14.2098 3.60322 15 5.51088 15 7.5ZM11.2781 4.65937C11.2112 4.59264 11.1314 4.5401 11.0437 4.50489C10.9559 4.46968 10.862 4.45252 10.7675 4.45445C10.673 4.45637 10.5798 4.47734 10.4936 4.5161C10.4073 4.55485 10.3298 4.6106 10.2656 4.68L7.00969 8.82844L5.0475 6.86531C4.91421 6.74111 4.73792 6.6735 4.55576 6.67671C4.3736 6.67992 4.1998 6.75372 4.07098 6.88254C3.94215 7.01137 3.86836 7.18517 3.86515 7.36732C3.86193 7.54948 3.92955 7.72577 4.05375 7.85906L6.53437 10.3406C6.6012 10.4073 6.68078 10.4599 6.76836 10.4952C6.85594 10.5305 6.94973 10.5477 7.04414 10.546C7.13854 10.5442 7.23163 10.5235 7.31784 10.485C7.40405 10.4465 7.48163 10.391 7.54594 10.3219L11.2884 5.64375C11.416 5.51109 11.4865 5.3337 11.4848 5.14965C11.483 4.9656 11.4092 4.78958 11.2791 4.65937H11.2781Z" fill="#5538C9"/>
							</svg>
							<span>Verified</span>
						</div>
						<div class="date">10.02.2025</div>

						<div class="bar-stars">
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
						</div>
						<div class="rewiew-text">Exquisite art object! The unique combination of contemporary art and
							baroque frame makes it a true masterpiece. Simply delighted! The fur combs easily in any
							direction, allowing you to style it as you wish. I created a fluffy, voluminous look!</div>
					</div>
				</div>
				<div class="rewiew">
					<img src="images/rewiew1.png" alt="">
					<div class="rewiew-block">
						<div class="name-block">
							<div class="name">JASON</div>
							<svg width="15" height="15" viewBox="0 0 15 15" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path d="M15 7.5C15 9.48912 14.2098 11.3968 12.8033 12.8033C11.3968 14.2098 9.48912 15 7.5 15C5.51088 15 3.60322 14.2098 2.1967 12.8033C0.790176 11.3968 0 9.48912 0 7.5C0 5.51088 0.790176 3.60322 2.1967 2.1967C3.60322 0.790176 5.51088 0 7.5 0C9.48912 0 11.3968 0.790176 12.8033 2.1967C14.2098 3.60322 15 5.51088 15 7.5ZM11.2781 4.65937C11.2112 4.59264 11.1314 4.5401 11.0437 4.50489C10.9559 4.46968 10.862 4.45252 10.7675 4.45445C10.673 4.45637 10.5798 4.47734 10.4936 4.5161C10.4073 4.55485 10.3298 4.6106 10.2656 4.68L7.00969 8.82844L5.0475 6.86531C4.91421 6.74111 4.73792 6.6735 4.55576 6.67671C4.3736 6.67992 4.1998 6.75372 4.07098 6.88254C3.94215 7.01137 3.86836 7.18517 3.86515 7.36732C3.86193 7.54948 3.92955 7.72577 4.05375 7.85906L6.53437 10.3406C6.6012 10.4073 6.68078 10.4599 6.76836 10.4952C6.85594 10.5305 6.94973 10.5477 7.04414 10.546C7.13854 10.5442 7.23163 10.5235 7.31784 10.485C7.40405 10.4465 7.48163 10.391 7.54594 10.3219L11.2884 5.64375C11.416 5.51109 11.4865 5.3337 11.4848 5.14965C11.483 4.9656 11.4092 4.78958 11.2791 4.65937H11.2781Z" fill="#5538C9"/>
							</svg>
							<span>Verified</span>
						</div>
						<div class="date">10.02.2025</div>

						<div class="bar-stars">
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
						</div>
						<div class="rewiew-text">Exquisite art object! The unique combination of contemporary art and
							baroque frame makes it a true masterpiece. Simply delighted! The fur combs easily in any
							direction, allowing you to style it as you wish. I created a fluffy, voluminous look!</div>
					</div>
				</div>
				<div class="rewiew">
					<img src="images/rewiew1.png" alt="">
					<div class="rewiew-block">
						<div class="name-block">
							<div class="name">JASON</div>
							<svg width="15" height="15" viewBox="0 0 15 15" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path d="M15 7.5C15 9.48912 14.2098 11.3968 12.8033 12.8033C11.3968 14.2098 9.48912 15 7.5 15C5.51088 15 3.60322 14.2098 2.1967 12.8033C0.790176 11.3968 0 9.48912 0 7.5C0 5.51088 0.790176 3.60322 2.1967 2.1967C3.60322 0.790176 5.51088 0 7.5 0C9.48912 0 11.3968 0.790176 12.8033 2.1967C14.2098 3.60322 15 5.51088 15 7.5ZM11.2781 4.65937C11.2112 4.59264 11.1314 4.5401 11.0437 4.50489C10.9559 4.46968 10.862 4.45252 10.7675 4.45445C10.673 4.45637 10.5798 4.47734 10.4936 4.5161C10.4073 4.55485 10.3298 4.6106 10.2656 4.68L7.00969 8.82844L5.0475 6.86531C4.91421 6.74111 4.73792 6.6735 4.55576 6.67671C4.3736 6.67992 4.1998 6.75372 4.07098 6.88254C3.94215 7.01137 3.86836 7.18517 3.86515 7.36732C3.86193 7.54948 3.92955 7.72577 4.05375 7.85906L6.53437 10.3406C6.6012 10.4073 6.68078 10.4599 6.76836 10.4952C6.85594 10.5305 6.94973 10.5477 7.04414 10.546C7.13854 10.5442 7.23163 10.5235 7.31784 10.485C7.40405 10.4465 7.48163 10.391 7.54594 10.3219L11.2884 5.64375C11.416 5.51109 11.4865 5.3337 11.4848 5.14965C11.483 4.9656 11.4092 4.78958 11.2791 4.65937H11.2781Z" fill="#5538C9"/>
							</svg>
							<span>Verified</span>
						</div>
						<div class="date">10.02.2025</div>

						<div class="bar-stars">
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
						</div>
						<div class="rewiew-text">Exquisite art object! The unique combination of contemporary art and
							baroque frame makes it a true masterpiece. Simply delighted! The fur combs easily in any
							direction, allowing you to style it as you wish. I created a fluffy, voluminous look!</div>
					</div>
				</div>
				<div class="rewiew">
					<img src="images/rewiew1.png" alt="">
					<div class="rewiew-block">
						<div class="name-block">
							<div class="name">JASON</div>
							<svg width="15" height="15" viewBox="0 0 15 15" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path d="M15 7.5C15 9.48912 14.2098 11.3968 12.8033 12.8033C11.3968 14.2098 9.48912 15 7.5 15C5.51088 15 3.60322 14.2098 2.1967 12.8033C0.790176 11.3968 0 9.48912 0 7.5C0 5.51088 0.790176 3.60322 2.1967 2.1967C3.60322 0.790176 5.51088 0 7.5 0C9.48912 0 11.3968 0.790176 12.8033 2.1967C14.2098 3.60322 15 5.51088 15 7.5ZM11.2781 4.65937C11.2112 4.59264 11.1314 4.5401 11.0437 4.50489C10.9559 4.46968 10.862 4.45252 10.7675 4.45445C10.673 4.45637 10.5798 4.47734 10.4936 4.5161C10.4073 4.55485 10.3298 4.6106 10.2656 4.68L7.00969 8.82844L5.0475 6.86531C4.91421 6.74111 4.73792 6.6735 4.55576 6.67671C4.3736 6.67992 4.1998 6.75372 4.07098 6.88254C3.94215 7.01137 3.86836 7.18517 3.86515 7.36732C3.86193 7.54948 3.92955 7.72577 4.05375 7.85906L6.53437 10.3406C6.6012 10.4073 6.68078 10.4599 6.76836 10.4952C6.85594 10.5305 6.94973 10.5477 7.04414 10.546C7.13854 10.5442 7.23163 10.5235 7.31784 10.485C7.40405 10.4465 7.48163 10.391 7.54594 10.3219L11.2884 5.64375C11.416 5.51109 11.4865 5.3337 11.4848 5.14965C11.483 4.9656 11.4092 4.78958 11.2791 4.65937H11.2781Z" fill="#5538C9"/>
							</svg>
							<span>Verified</span>
						</div>
						<div class="date">10.02.2025</div>

						<div class="bar-stars">
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
						</div>
						<div class="rewiew-text">Exquisite art object! The unique combination of contemporary art and
							baroque frame makes it a true masterpiece. Simply delighted! The fur combs easily in any
							direction, allowing you to style it as you wish. I created a fluffy, voluminous look!</div>
					</div>
				</div>
				<div class="rewiew">
					<img src="images/rewiew1.png" alt="">
					<div class="rewiew-block">
						<div class="name-block">
							<div class="name">JASON</div>
							<svg width="15" height="15" viewBox="0 0 15 15" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path d="M15 7.5C15 9.48912 14.2098 11.3968 12.8033 12.8033C11.3968 14.2098 9.48912 15 7.5 15C5.51088 15 3.60322 14.2098 2.1967 12.8033C0.790176 11.3968 0 9.48912 0 7.5C0 5.51088 0.790176 3.60322 2.1967 2.1967C3.60322 0.790176 5.51088 0 7.5 0C9.48912 0 11.3968 0.790176 12.8033 2.1967C14.2098 3.60322 15 5.51088 15 7.5ZM11.2781 4.65937C11.2112 4.59264 11.1314 4.5401 11.0437 4.50489C10.9559 4.46968 10.862 4.45252 10.7675 4.45445C10.673 4.45637 10.5798 4.47734 10.4936 4.5161C10.4073 4.55485 10.3298 4.6106 10.2656 4.68L7.00969 8.82844L5.0475 6.86531C4.91421 6.74111 4.73792 6.6735 4.55576 6.67671C4.3736 6.67992 4.1998 6.75372 4.07098 6.88254C3.94215 7.01137 3.86836 7.18517 3.86515 7.36732C3.86193 7.54948 3.92955 7.72577 4.05375 7.85906L6.53437 10.3406C6.6012 10.4073 6.68078 10.4599 6.76836 10.4952C6.85594 10.5305 6.94973 10.5477 7.04414 10.546C7.13854 10.5442 7.23163 10.5235 7.31784 10.485C7.40405 10.4465 7.48163 10.391 7.54594 10.3219L11.2884 5.64375C11.416 5.51109 11.4865 5.3337 11.4848 5.14965C11.483 4.9656 11.4092 4.78958 11.2791 4.65937H11.2781Z" fill="#5538C9"/>
							</svg>
							<span>Verified</span>
						</div>
						<div class="date">10.02.2025</div>

						<div class="bar-stars">
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
						</div>
						<div class="rewiew-text">Exquisite art object! The unique combination of contemporary art and
							baroque frame makes it a true masterpiece. Simply delighted! The fur combs easily in any
							direction, allowing you to style it as you wish. I created a fluffy, voluminous look!</div>
					</div>
				</div>
				<div class="rewiew">
					<img src="images/rewiew1.png" alt="">
					<div class="rewiew-block">
						<div class="name-block">
							<div class="name">JASON</div>
							<svg width="15" height="15" viewBox="0 0 15 15" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path d="M15 7.5C15 9.48912 14.2098 11.3968 12.8033 12.8033C11.3968 14.2098 9.48912 15 7.5 15C5.51088 15 3.60322 14.2098 2.1967 12.8033C0.790176 11.3968 0 9.48912 0 7.5C0 5.51088 0.790176 3.60322 2.1967 2.1967C3.60322 0.790176 5.51088 0 7.5 0C9.48912 0 11.3968 0.790176 12.8033 2.1967C14.2098 3.60322 15 5.51088 15 7.5ZM11.2781 4.65937C11.2112 4.59264 11.1314 4.5401 11.0437 4.50489C10.9559 4.46968 10.862 4.45252 10.7675 4.45445C10.673 4.45637 10.5798 4.47734 10.4936 4.5161C10.4073 4.55485 10.3298 4.6106 10.2656 4.68L7.00969 8.82844L5.0475 6.86531C4.91421 6.74111 4.73792 6.6735 4.55576 6.67671C4.3736 6.67992 4.1998 6.75372 4.07098 6.88254C3.94215 7.01137 3.86836 7.18517 3.86515 7.36732C3.86193 7.54948 3.92955 7.72577 4.05375 7.85906L6.53437 10.3406C6.6012 10.4073 6.68078 10.4599 6.76836 10.4952C6.85594 10.5305 6.94973 10.5477 7.04414 10.546C7.13854 10.5442 7.23163 10.5235 7.31784 10.485C7.40405 10.4465 7.48163 10.391 7.54594 10.3219L11.2884 5.64375C11.416 5.51109 11.4865 5.3337 11.4848 5.14965C11.483 4.9656 11.4092 4.78958 11.2791 4.65937H11.2781Z" fill="#5538C9"/>
							</svg>
							<span>Verified</span>
						</div>
						<div class="date">10.02.2025</div>

						<div class="bar-stars">
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
						</div>
						<div class="rewiew-text">Exquisite art object! The unique combination of contemporary art and
							baroque frame makes it a true masterpiece. Simply delighted! The fur combs easily in any
							direction, allowing you to style it as you wish. I created a fluffy, voluminous look!</div>
					</div>
				</div>
				<div class="rewiew">
					<img src="images/rewiew1.png" alt="">
					<div class="rewiew-block">
						<div class="name-block">
							<div class="name">JASON</div>
							<svg width="15" height="15" viewBox="0 0 15 15" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path d="M15 7.5C15 9.48912 14.2098 11.3968 12.8033 12.8033C11.3968 14.2098 9.48912 15 7.5 15C5.51088 15 3.60322 14.2098 2.1967 12.8033C0.790176 11.3968 0 9.48912 0 7.5C0 5.51088 0.790176 3.60322 2.1967 2.1967C3.60322 0.790176 5.51088 0 7.5 0C9.48912 0 11.3968 0.790176 12.8033 2.1967C14.2098 3.60322 15 5.51088 15 7.5ZM11.2781 4.65937C11.2112 4.59264 11.1314 4.5401 11.0437 4.50489C10.9559 4.46968 10.862 4.45252 10.7675 4.45445C10.673 4.45637 10.5798 4.47734 10.4936 4.5161C10.4073 4.55485 10.3298 4.6106 10.2656 4.68L7.00969 8.82844L5.0475 6.86531C4.91421 6.74111 4.73792 6.6735 4.55576 6.67671C4.3736 6.67992 4.1998 6.75372 4.07098 6.88254C3.94215 7.01137 3.86836 7.18517 3.86515 7.36732C3.86193 7.54948 3.92955 7.72577 4.05375 7.85906L6.53437 10.3406C6.6012 10.4073 6.68078 10.4599 6.76836 10.4952C6.85594 10.5305 6.94973 10.5477 7.04414 10.546C7.13854 10.5442 7.23163 10.5235 7.31784 10.485C7.40405 10.4465 7.48163 10.391 7.54594 10.3219L11.2884 5.64375C11.416 5.51109 11.4865 5.3337 11.4848 5.14965C11.483 4.9656 11.4092 4.78958 11.2791 4.65937H11.2781Z" fill="#5538C9"/>
							</svg>
							<span>Verified</span>
						</div>
						<div class="date">10.02.2025</div>

						<div class="bar-stars">
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
							<svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
								<path fill-rule="evenodd" clip-rule="evenodd" d="M0 0H16V16H0V0ZM8 2L9.364 6.197H13.777L10.206 8.791L11.57 12.988L8 10.394L4.429 12.988L5.793 8.791L2.222 6.197H6.636L8 2Z" fill="#00B67A"/>
							</svg>
						</div>
						<div class="rewiew-text">Exquisite art object! The unique combination of contemporary art and
							baroque frame makes it a true masterpiece. Simply delighted! The fur combs easily in any
							direction, allowing you to style it as you wish. I created a fluffy, voluminous look!</div>
					</div>
				</div>
				<div class="button-prev-next">
					<button>PREVIOUS</button>
					<button>NEXT</button>
				</div>
			</div>
		</div>
		<!-- 7 блок -->
		<div class="block-also-like">
			<div class="also-like-text">YOU MAY ALSO LIKE</div>
			<div class="swiper mySwiper2">
				<div class="swiper-wrapper">
					<div class="swiper-slide">
						<img src="images/also-like.png" alt="">
						<span>GOOD VIBES FRAMED HOOP</span>
						<div class="price-bar1">
							<div class="act-price">$379.90</div>
							<div class="old-price">$499.90</div>
						</div>
						<button>ADD TO CART</button>
					</div>
					<div class="swiper-slide">
						<img src="images/also-like.png" alt="">
						<span>GOOD VIBES FRAMED HOOP</span>
						<div class="price-bar1">
							<div class="act-price">$379.90</div>
							<div class="old-price">$499.90</div>
						</div>
						<button>ADD TO CART</button>
					</div>
					<div class="swiper-slide">
						<img src="images/also-like.png" alt="">
						<span>GOOD VIBES FRAMED HOOP</span>
						<div class="price-bar1">
							<div class="act-price">$379.90</div>
							<div class="old-price">$499.90</div>
						</div>
						<button>ADD TO CART</button>
					</div>
					<div class="swiper-slide">
						<img src="images/also-like.png" alt="">
						<span>GOOD VIBES FRAMED HOOP</span>
						<div class="price-bar1">
							<div class="act-price">$379.90</div>
							<div class="old-price">$499.90</div>
						</div>
						<button>ADD TO CART</button>
					</div>
					<div class="swiper-slide">
						<img src="images/also-like.png" alt="">
						<span>GOOD VIBES FRAMED HOOP</span>
						<div class="price-bar1">
							<div class="act-price">$379.90</div>
							<div class="old-price">$499.90</div>
						</div>
						<button>ADD TO CART</button>
					</div>
					<div class="swiper-slide">
						<img src="images/also-like.png" alt="">
						<span>GOOD VIBES FRAMED HOOP</span>
						<div class="price-bar1">
							<div class="act-price">$379.90</div>
							<div class="old-price">$499.90</div>
						</div>
						<button>ADD TO CART</button>
					</div>
					<div class="swiper-slide">
						<img src="images/also-like.png" alt="">
						<span>GOOD VIBES FRAMED HOOP</span>
						<div class="price-bar1">
							<div class="act-price">$379.90</div>
							<div class="old-price">$499.90</div>
						</div>
						<button>ADD TO CART</button>
					</div>
					<div class="swiper-slide">
						<img src="images/also-like.png" alt="">
						<span>GOOD VIBES FRAMED HOOP</span>
						<div class="price-bar1">
							<div class="act-price">$379.90</div>
							<div class="old-price">$499.90</div>
						</div>
						<button>ADD TO CART</button>
					</div>
					<div class="swiper-slide">
						<img src="images/also-like.png" alt="">
						<span>GOOD VIBES FRAMED HOOP</span>
						<div class="price-bar1">
							<div class="act-price">$379.90</div>
							<div class="old-price">$499.90</div>
						</div>
						<button>ADD TO CART</button>
					</div>
				</div>
				<div class="swiper-button-prev mobile-hidden"></div>
				<div class="swiper-button-next mobile-hidden"></div>
				<div class="swiper-pagination mobile-hidden"></div>
			</div>
		</div>
		<!-- 8 блок -->
		<div class="content">
			<div class="faq-center">
				<div class="mini-faq">
					<div class="mini-faq-text faq1">
						<span>CUSTOMER SUPPORT</span>
						<p>Any questions you may have, we're here waiting and ready to answer them. Speak to a rep today, <br> 9am - 6pm PST.</p>
					</div>
					<div class="mini-faq-text faq2">
						<span>WE ARE PRODUCERS</span>
						<p>We produce Baroque framed Hoops / Arts, that is why our prices are so low. Major brands markup
							their products 8-10x the actual cost. We do things differently. To make our prices accessible,
							we sell directly to you from our production but without the traditional markups.</p>
					</div>
					<div class="mini-faq-text faq3">
						<span>EASY RETURNS / EXCHANGES</span>
						<p>Customer satisfaction is our number one priority. If for any reason you are dissatisfied, we will
							gladly issue a full refund, exchange, or GIMMEHOOP store credit for items returned.</p>
					</div>
				</div>
			</div>
		</div>
		<!-- footer -->
		<div class="footer mobile-hidden">
			<div class="content footer-content">
				<div class="footer-menu">
					<h3>MENU</h3>
					<a href="">Home</a>
					<a href="">Shop</a>
					<a href="">
						<li>Framed Canvas Collection </li>
					</a>
					<a href="">
						<li>Basketball Art Framed Hoops </li>
					</a>
					<a href="">
						<li> Surfboards</li>
					</a>
					<a href="">
						<li>Arts</li>
					</a>
					<a href="">About Us</a>
				</div>
				<div class="footer-center">
					<div class="contacts">
						<span>GIMMEHOOP</span>
						<a href="">support@gimmehoop.com</a>
						<div class="contacts-img">
							<a href=""><img src="images/facebook.svg" alt=""></a>
							<a href=""><img src="images/inst.svg" alt=""></a>
							<a href=""><img src="images/tt.svg" alt=""></a>
						</div>
					</div>
					<div class="cart-copyright">
						<img src="images/card.png" alt="">
						<p>Copyright © 2023 GimmeHoop LLC, All Rights Reserved</p>
					</div>
				</div>
				<div class="footer-policy">
					<h3>POLICY</h3>
					<a href="">Refund Policy</a>
					<a href="">Privacy Policy</a>
					<a href="">Terms of Service</a>
					<a href="">Shipping Policy</a>
				</div>
			</div>
		</div>
		<div class="footer desktop-hidden">
			<div class="content footer-content">
				<div class="contacts">
					<span>GIMMEHOOP</span>
					<a href="">support@gimmehoop.com</a>
					<div class="contacts-img">
						<a href=""><img src="images/facebook.svg" alt=""></a>
						<a href=""><img src="images/inst.svg" alt=""></a>
						<a href=""><img src="images/tt.svg" alt=""></a>
					</div>
				</div>
				<div class="footer-center1">
					<div class="footer-menu">
						<h3>MENU</h3>
						<a href="">Home</a>
						<a href="">Shop</a>
						<a href="">
							<li>Framed Canvas Collection </li>
						</a>
						<a href="">
							<li>Basketball Art Framed Hoops </li>
						</a>
						<a href="">
							<li> Surfboards</li>
						</a>
						<a href="">
							<li>Arts</li>
						</a>
						<a href="">About Us</a>
					</div>
					<div class="footer-policy">
						<h3>POLICY</h3>
						<a href="">Refund Policy</a>
						<a href="">Privacy Policy</a>
						<a href="">Terms of Service</a>
						<a href="">Shipping Policy</a>
					</div>
				</div>
				
				<div class="cart-copyright">
					<img src="images/card.png" alt="">
					<p>Copyright © 2023 GimmeHoop LLC, All Rights Reserved</p>
				</div>
			</div>
		</div>
		<script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>
		<script src="main.js"></script>
</body>

</html>
