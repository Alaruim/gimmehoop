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
					<div>Returns in 30 days</div>
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
				<h2 class="mobile-hidden">Basketball Art</h2>
				<h1>Italian Framed Hoop</h1>
				<div class="bar-rating">
					<div class="bar-stars">
						<svg class="filled" width="15" height="15" viewBox="0 0 15 15" fill="none"
							xmlns="http://www.w3.org/2000/svg">
							<path
								d="M7.5 0L9.18386 5.52786H14.6329L10.2245 8.94427L11.9084 14.4721L7.5 11.0557L3.09161 14.4721L4.77547 8.94427L0.367076 5.52786H5.81614L7.5 0Z"
								fill="currentColor" />
						</svg>
						<svg class="filled" width="15" height="15" viewBox="0 0 15 15" fill="none"
							xmlns="http://www.w3.org/2000/svg">
							<path
								d="M7.5 0L9.18386 5.52786H14.6329L10.2245 8.94427L11.9084 14.4721L7.5 11.0557L3.09161 14.4721L4.77547 8.94427L0.367076 5.52786H5.81614L7.5 0Z"
								fill="currentColor" />
						</svg>
						<svg class="filled" width="15" height="15" viewBox="0 0 15 15" fill="none"
							xmlns="http://www.w3.org/2000/svg">
							<path
								d="M7.5 0L9.18386 5.52786H14.6329L10.2245 8.94427L11.9084 14.4721L7.5 11.0557L3.09161 14.4721L4.77547 8.94427L0.367076 5.52786H5.81614L7.5 0Z"
								fill="currentColor" />
						</svg>
						<svg class="filled" width="15" height="15" viewBox="0 0 15 15" fill="none"
							xmlns="http://www.w3.org/2000/svg">
							<path
								d="M7.5 0L9.18386 5.52786H14.6329L10.2245 8.94427L11.9084 14.4721L7.5 11.0557L3.09161 14.4721L4.77547 8.94427L0.367076 5.52786H5.81614L7.5 0Z"
								fill="currentColor" />
						</svg>
						<svg width="15" height="15" viewBox="0 0 15 15" fill="none" xmlns="http://www.w3.org/2000/svg">
							<path
								d="M7.5 0L9.18386 5.52786H14.6329L10.2245 8.94427L11.9084 14.4721L7.5 11.0557L3.09161 14.4721L4.77547 8.94427L0.367076 5.52786H5.81614L7.5 0Z"
								fill="currentColor" />
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

				</div>
				<div class="price-bar">
					<div class="act-price">$379.90</div> <span>$499.90</span>
				</div>
				<div class="bar-progress">
					<progress value="3" max="50"></progress>
					<span>Only 3 left in stock</span>
				</div>
				<div class="add-to-cart">
					<button class="add-button">ADD TO CART</button>
					<div class="container-button">
						<button class="minus-button">-</button>
						<input type="number" id="quantity" value="0">
						<button class="plus-button">+</button>
					</div>
				</div>
				<div class="delivery">
					Expected Delivery Date to Russian Federation 
					<span>янв. 17 - янв. 19</span>
				</div>
				<div class="block-choose-size mobile-hidden">
					<button class="choose-your-size" id="toggleButton">
						Choose Your Size
						<img src="images/choose-size.svg" alt="">
					</button>
					<div class="hidden-slider" id="dropdown">
						<div class="swiper mySwiper">
							<div class="swiper-pagination"></div>
							<div class="swiper-wrapper">
								<div class="swiper-slide"><img src="images/card-slider-2-1.png" alt=""></div>
								<div class="swiper-slide"><img src="images/card-slider-2-2.png" alt=""></div>
								<div class="swiper-slide"><img src="images/card-slider-2-3.png" alt=""></div>
							</div>
							<div class="swiper-button-prev"></div>
							<div class="swiper-button-next"></div>
						</div>
					</div>
				</div>
				<div class="choose-size-text mobile-hidden">
					Get your own framed hoop for fun and games at your home or office. Imagine how much of a
					conversation starter this would be in your home.
				</div>
				<div class="container-text-comment mobile-hidden">
					<img src="images/comment.png">
					<div class="text-comment">
						<p>A conversation starter.</p>
						<p>Shows off your impeccable taste.</p>
						<p>Increases the amount of gold in your house.</p>
						<p>Dunk on your friends. (It’s functional, but we recommend lay ups, as we wouldn’t want you to
							damage it!)</p>
					</div>
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
	<div class="block-line-shadow mobile-hidden">
		<div class="content">
			<div class="block-slider-chosen">
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
				<div class="chosen-desc">
					<span>Get your own framed hoop for fun and games at your home or office. Imagine how much of a
						conversation starter this would be in your home.</span>
					<h3>We are being chosen</h3>
					<p>Get your own framed hoop for fun and games at your home or office. Imagine how much of a
						conversation starter this would be in your home. Get your own framed hoop for fun and games at
						your home or office.</p>
					<a href="">
						@gimmehoop
						<img src="images/instagram-icon.png" alt="">
					</a>
				</div>
			</div>
		</div>
	</div>
	<div class="block-line-shadow1 desktop-hidden">
		<div class="content">
			<div class="block-slider-chosen">
				<hr>
				<div class="chosen-desc">
					<span>Get your own framed hoop for fun and games at your home or office. Imagine how much of a
						conversation starter this would be in your home.</span>
					<h3>We are being chosen</h3>
				</div>
				<div class="slider-cart">
					<div class="swiper mySwiper">
						<div class="swiper-pagination"></div>
						<div class="swiper-wrapper">
							<div class="swiper-slide"><img src="images/card-slider-1-1.png" alt=""></div>
							<div class="swiper-slide"><img src="images/card-slider-1-1.png" alt=""></div>
							<div class="swiper-slide"><img src="images/card-slider-1-1.png" alt=""></div>
						</div>
					</div>
				</div>
				<div class="chosen-desc">
					<p>Get your own framed hoop for fun and games at your home or office. Imagine how much of a
						conversation starter this would be in your home. Get your own framed hoop for fun and games at
						your home or office.</p>
					<a href="">
						@gimmehoop
						<img src="images/instagram-icon.png" alt="">
					</a>
				</div>
			</div>
		</div>
	</div>
	<!-- 4 блок -->
	<div class="image-line">
		<div class="content content-image-line">
			<span>
				<img src="images/line-image-1.png" alt="">
				FAST WORLDWIDE DELIVERY
			</span>
			<span>
				<img src="images/line-image-2.png" alt="">
				100% SAFE & SECURE CHECKOUT
			</span>
			<span>
				<img src="images/line-image-3.png" alt="">
				HIGH QUALITY PRODUCT
			</span>
		</div>
	</div>
	<!-- 5 блок -->
	<div class="content">
		<div class="block-reviews">
			<div class="customer-reviews mobile-hidden">
				<div class="cust-rev-text">CUSTOMER REVIEWS</div>
				<div class="rait">
					<div class="bar-stars-rev">
						<svg class="filled" width="15" height="15" viewBox="0 0 15 15" fill="none"
							xmlns="http://www.w3.org/2000/svg">
							<path
								d="M7.5 0L9.18386 5.52786H14.6329L10.2245 8.94427L11.9084 14.4721L7.5 11.0557L3.09161 14.4721L4.77547 8.94427L0.367076 5.52786H5.81614L7.5 0Z"
								fill="currentColor" />
						</svg>
						<svg class="filled" width="15" height="15" viewBox="0 0 15 15" fill="none"
							xmlns="http://www.w3.org/2000/svg">
							<path
								d="M7.5 0L9.18386 5.52786H14.6329L10.2245 8.94427L11.9084 14.4721L7.5 11.0557L3.09161 14.4721L4.77547 8.94427L0.367076 5.52786H5.81614L7.5 0Z"
								fill="currentColor" />
						</svg>
						<svg class="filled" width="15" height="15" viewBox="0 0 15 15" fill="none"
							xmlns="http://www.w3.org/2000/svg">
							<path
								d="M7.5 0L9.18386 5.52786H14.6329L10.2245 8.94427L11.9084 14.4721L7.5 11.0557L3.09161 14.4721L4.77547 8.94427L0.367076 5.52786H5.81614L7.5 0Z"
								fill="currentColor" />
						</svg>
						<svg class="filled" width="15" height="15" viewBox="0 0 15 15" fill="none"
							xmlns="http://www.w3.org/2000/svg">
							<path
								d="M7.5 0L9.18386 5.52786H14.6329L10.2245 8.94427L11.9084 14.4721L7.5 11.0557L3.09161 14.4721L4.77547 8.94427L0.367076 5.52786H5.81614L7.5 0Z"
								fill="currentColor" />
						</svg>
						<svg width="15" height="15" viewBox="0 0 15 15" fill="none" xmlns="http://www.w3.org/2000/svg">
							<path
								d="M7.5 0L9.18386 5.52786H14.6329L10.2245 8.94427L11.9084 14.4721L7.5 11.0557L3.09161 14.4721L4.77547 8.94427L0.367076 5.52786H5.81614L7.5 0Z"
								fill="currentColor" />
						</svg>
					</div>
					<div class="numb-rait">4.9 out of 5.0</div>
				</div>
				<div class="count-rev">3182 Reviews</div>
				<div class="rait-progress-bar">
					<div class="rait-num">5</div>
					<svg class="filled" width="15" height="15" viewBox="0 0 15 15" fill="none"
						xmlns="http://www.w3.org/2000/svg">
						<path
							d="M7.5 0L9.18386 5.52786H14.6329L10.2245 8.94427L11.9084 14.4721L7.5 11.0557L3.09161 14.4721L4.77547 8.94427L0.367076 5.52786H5.81614L7.5 0Z"
							fill="currentColor" />
					</svg>
					<progress value="90" max="100"></progress>
				</div>
				<div class="rait-progress-bar">
					<div class="rait-num">4</div>
					<svg class="filled" width="15" height="15" viewBox="0 0 15 15" fill="none"
						xmlns="http://www.w3.org/2000/svg">
						<path
							d="M7.5 0L9.18386 5.52786H14.6329L10.2245 8.94427L11.9084 14.4721L7.5 11.0557L3.09161 14.4721L4.77547 8.94427L0.367076 5.52786H5.81614L7.5 0Z"
							fill="currentColor" />
					</svg>
					<progress value="7" max="100"></progress>
				</div>
				<div class="rait-progress-bar">
					<div class="rait-num">3</div>
					<svg class="filled" width="15" height="15" viewBox="0 0 15 15" fill="none"
						xmlns="http://www.w3.org/2000/svg">
						<path
							d="M7.5 0L9.18386 5.52786H14.6329L10.2245 8.94427L11.9084 14.4721L7.5 11.0557L3.09161 14.4721L4.77547 8.94427L0.367076 5.52786H5.81614L7.5 0Z"
							fill="currentColor" />
					</svg>
					<progress value="3" max="100"></progress>
				</div>
				<div class="rait-progress-bar">
					<div class="rait-num">2</div>
					<svg class="filled" width="15" height="15" viewBox="0 0 15 15" fill="none"
						xmlns="http://www.w3.org/2000/svg">
						<path
							d="M7.5 0L9.18386 5.52786H14.6329L10.2245 8.94427L11.9084 14.4721L7.5 11.0557L3.09161 14.4721L4.77547 8.94427L0.367076 5.52786H5.81614L7.5 0Z"
							fill="currentColor" />
					</svg>
					<progress value="0" max="100"></progress>
				</div>
				<div class="rait-progress-bar">
					<div class="rait-num">1</div>
					<svg class="filled" width="15" height="15" viewBox="0 0 15 15" fill="none"
						xmlns="http://www.w3.org/2000/svg">
						<path
							d="M7.5 0L9.18386 5.52786H14.6329L10.2245 8.94427L11.9084 14.4721L7.5 11.0557L3.09161 14.4721L4.77547 8.94427L0.367076 5.52786H5.81614L7.5 0Z"
							fill="currentColor" />
					</svg>
					<progress value="0" max="100"></progress>
				</div>
				<button class="rait-work mobile-hidden" data-elem=".review-popup">
					How customer reviews and ratings work
					<img src="images/arrow.svg" alt="">
				</button>

				<div class="review-popup">
					Тут текст о том, как работают отзывы. Тут текст о том, как работают отзывы. Тут текст о том, как
					работают отзывы. Тут текст о том, как работают отзывы. Тут текст о том, как работают отзывы.
				</div>
				<hr>
				<div class="rev-this-product">Review this product</div>
				<div class="share-rev">Share your thoughts with other customers</div>
				<button class="view-all-rev">VIEW ALL REVIEWS</button>
			</div>

			<div class="customer-say">
				<div class="cust-say-head">Customers say</div>
				<div class="cust-say-text">Customers find the board game enjoyable and creative. They appreciate its
					artistic design and easy learning process. The game pieces are well-made and of good quality. Many
					consider it a great value for money, though some are disappointed with the kickstarter exclusivity.
				</div>
				<div class="rev-images-block">
					<div class="rev-images-text">Reviews with images</div>
					<button class="see-all-photo">
						<span>See all photo</span>
						<img src="images/arrow.svg" alt="">
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
				<div class="slider-rev mobile-hidden">
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
					<hr>
					
				</div>
				<div class="slider-rev1 desktop-hidden">
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
					</div>
					<hr>
				</div>
			</div>
		</div>
		</div>
		<!-- 6 блок -->
		<div class="content">
			<div class="block-top-reviews">
				<div class="top-rev-header">
					<div class="top-rew-1">Top reviews</div>
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
				<div class="rewiew">
					<img src="images/rewiew1.png" alt="">
					<div class="rewiew-block">
						<div class="name">JASON</div>
						<div class="product">
							<div class="product-name">Fluffy Mona Lisa</div>
							<div class="product-size">30*26 inches (75*65cm)</div>
						</div>
						<div class="bar-stars">
							<svg class="filled" width="15" height="15" viewBox="0 0 15 15" fill="none"
								xmlns="http://www.w3.org/2000/svg">
								<path
									d="M7.5 0L9.18386 5.52786H14.6329L10.2245 8.94427L11.9084 14.4721L7.5 11.0557L3.09161 14.4721L4.77547 8.94427L0.367076 5.52786H5.81614L7.5 0Z"
									fill="currentColor" />
							</svg>
							<svg class="filled" width="15" height="15" viewBox="0 0 15 15" fill="none"
								xmlns="http://www.w3.org/2000/svg">
								<path
									d="M7.5 0L9.18386 5.52786H14.6329L10.2245 8.94427L11.9084 14.4721L7.5 11.0557L3.09161 14.4721L4.77547 8.94427L0.367076 5.52786H5.81614L7.5 0Z"
									fill="currentColor" />
							</svg>
							<svg class="filled" width="15" height="15" viewBox="0 0 15 15" fill="none"
								xmlns="http://www.w3.org/2000/svg">
								<path
									d="M7.5 0L9.18386 5.52786H14.6329L10.2245 8.94427L11.9084 14.4721L7.5 11.0557L3.09161 14.4721L4.77547 8.94427L0.367076 5.52786H5.81614L7.5 0Z"
									fill="currentColor" />
							</svg>
							<svg class="filled" width="15" height="15" viewBox="0 0 15 15" fill="none"
								xmlns="http://www.w3.org/2000/svg">
								<path
									d="M7.5 0L9.18386 5.52786H14.6329L10.2245 8.94427L11.9084 14.4721L7.5 11.0557L3.09161 14.4721L4.77547 8.94427L0.367076 5.52786H5.81614L7.5 0Z"
									fill="currentColor" />
							</svg>
							<svg width="15" height="15" viewBox="0 0 15 15" fill="none"
								xmlns="http://www.w3.org/2000/svg">
								<path
									d="M7.5 0L9.18386 5.52786H14.6329L10.2245 8.94427L11.9084 14.4721L7.5 11.0557L3.09161 14.4721L4.77547 8.94427L0.367076 5.52786H5.81614L7.5 0Z"
									fill="currentColor" />
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
						<div class="name">JASON</div>
						<div class="product">
							<div class="product-name">Fluffy Mona Lisa</div>
							<div class="product-size">30*26 inches (75*65cm)</div>
						</div>
						<div class="bar-stars">
							<svg class="filled" width="15" height="15" viewBox="0 0 15 15" fill="none"
								xmlns="http://www.w3.org/2000/svg">
								<path
									d="M7.5 0L9.18386 5.52786H14.6329L10.2245 8.94427L11.9084 14.4721L7.5 11.0557L3.09161 14.4721L4.77547 8.94427L0.367076 5.52786H5.81614L7.5 0Z"
									fill="currentColor" />
							</svg>
							<svg class="filled" width="15" height="15" viewBox="0 0 15 15" fill="none"
								xmlns="http://www.w3.org/2000/svg">
								<path
									d="M7.5 0L9.18386 5.52786H14.6329L10.2245 8.94427L11.9084 14.4721L7.5 11.0557L3.09161 14.4721L4.77547 8.94427L0.367076 5.52786H5.81614L7.5 0Z"
									fill="currentColor" />
							</svg>
							<svg class="filled" width="15" height="15" viewBox="0 0 15 15" fill="none"
								xmlns="http://www.w3.org/2000/svg">
								<path
									d="M7.5 0L9.18386 5.52786H14.6329L10.2245 8.94427L11.9084 14.4721L7.5 11.0557L3.09161 14.4721L4.77547 8.94427L0.367076 5.52786H5.81614L7.5 0Z"
									fill="currentColor" />
							</svg>
							<svg class="filled" width="15" height="15" viewBox="0 0 15 15" fill="none"
								xmlns="http://www.w3.org/2000/svg">
								<path
									d="M7.5 0L9.18386 5.52786H14.6329L10.2245 8.94427L11.9084 14.4721L7.5 11.0557L3.09161 14.4721L4.77547 8.94427L0.367076 5.52786H5.81614L7.5 0Z"
									fill="currentColor" />
							</svg>
							<svg width="15" height="15" viewBox="0 0 15 15" fill="none"
								xmlns="http://www.w3.org/2000/svg">
								<path
									d="M7.5 0L9.18386 5.52786H14.6329L10.2245 8.94427L11.9084 14.4721L7.5 11.0557L3.09161 14.4721L4.77547 8.94427L0.367076 5.52786H5.81614L7.5 0Z"
									fill="currentColor" />
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
						<div class="name">JASON</div>
						<div class="product">
							<div class="product-name">Fluffy Mona Lisa</div>
							<div class="product-size">30*26 inches (75*65cm)</div>
						</div>
						<div class="bar-stars">
							<svg class="filled" width="15" height="15" viewBox="0 0 15 15" fill="none"
								xmlns="http://www.w3.org/2000/svg">
								<path
									d="M7.5 0L9.18386 5.52786H14.6329L10.2245 8.94427L11.9084 14.4721L7.5 11.0557L3.09161 14.4721L4.77547 8.94427L0.367076 5.52786H5.81614L7.5 0Z"
									fill="currentColor" />
							</svg>
							<svg class="filled" width="15" height="15" viewBox="0 0 15 15" fill="none"
								xmlns="http://www.w3.org/2000/svg">
								<path
									d="M7.5 0L9.18386 5.52786H14.6329L10.2245 8.94427L11.9084 14.4721L7.5 11.0557L3.09161 14.4721L4.77547 8.94427L0.367076 5.52786H5.81614L7.5 0Z"
									fill="currentColor" />
							</svg>
							<svg class="filled" width="15" height="15" viewBox="0 0 15 15" fill="none"
								xmlns="http://www.w3.org/2000/svg">
								<path
									d="M7.5 0L9.18386 5.52786H14.6329L10.2245 8.94427L11.9084 14.4721L7.5 11.0557L3.09161 14.4721L4.77547 8.94427L0.367076 5.52786H5.81614L7.5 0Z"
									fill="currentColor" />
							</svg>
							<svg class="filled" width="15" height="15" viewBox="0 0 15 15" fill="none"
								xmlns="http://www.w3.org/2000/svg">
								<path
									d="M7.5 0L9.18386 5.52786H14.6329L10.2245 8.94427L11.9084 14.4721L7.5 11.0557L3.09161 14.4721L4.77547 8.94427L0.367076 5.52786H5.81614L7.5 0Z"
									fill="currentColor" />
							</svg>
							<svg width="15" height="15" viewBox="0 0 15 15" fill="none"
								xmlns="http://www.w3.org/2000/svg">
								<path
									d="M7.5 0L9.18386 5.52786H14.6329L10.2245 8.94427L11.9084 14.4721L7.5 11.0557L3.09161 14.4721L4.77547 8.94427L0.367076 5.52786H5.81614L7.5 0Z"
									fill="currentColor" />
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
						<div class="name">JASON</div>
						<div class="product">
							<div class="product-name">Fluffy Mona Lisa</div>
							<div class="product-size">30*26 inches (75*65cm)</div>
						</div>
						<div class="bar-stars">
							<svg class="filled" width="15" height="15" viewBox="0 0 15 15" fill="none"
								xmlns="http://www.w3.org/2000/svg">
								<path
									d="M7.5 0L9.18386 5.52786H14.6329L10.2245 8.94427L11.9084 14.4721L7.5 11.0557L3.09161 14.4721L4.77547 8.94427L0.367076 5.52786H5.81614L7.5 0Z"
									fill="currentColor" />
							</svg>
							<svg class="filled" width="15" height="15" viewBox="0 0 15 15" fill="none"
								xmlns="http://www.w3.org/2000/svg">
								<path
									d="M7.5 0L9.18386 5.52786H14.6329L10.2245 8.94427L11.9084 14.4721L7.5 11.0557L3.09161 14.4721L4.77547 8.94427L0.367076 5.52786H5.81614L7.5 0Z"
									fill="currentColor" />
							</svg>
							<svg class="filled" width="15" height="15" viewBox="0 0 15 15" fill="none"
								xmlns="http://www.w3.org/2000/svg">
								<path
									d="M7.5 0L9.18386 5.52786H14.6329L10.2245 8.94427L11.9084 14.4721L7.5 11.0557L3.09161 14.4721L4.77547 8.94427L0.367076 5.52786H5.81614L7.5 0Z"
									fill="currentColor" />
							</svg>
							<svg class="filled" width="15" height="15" viewBox="0 0 15 15" fill="none"
								xmlns="http://www.w3.org/2000/svg">
								<path
									d="M7.5 0L9.18386 5.52786H14.6329L10.2245 8.94427L11.9084 14.4721L7.5 11.0557L3.09161 14.4721L4.77547 8.94427L0.367076 5.52786H5.81614L7.5 0Z"
									fill="currentColor" />
							</svg>
							<svg width="15" height="15" viewBox="0 0 15 15" fill="none"
								xmlns="http://www.w3.org/2000/svg">
								<path
									d="M7.5 0L9.18386 5.52786H14.6329L10.2245 8.94427L11.9084 14.4721L7.5 11.0557L3.09161 14.4721L4.77547 8.94427L0.367076 5.52786H5.81614L7.5 0Z"
									fill="currentColor" />
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
					<div class="mini-faq-text">
						<span>CUSTOMER SUPPORT</span>
						<p>Any questions you may have, we're here waiting and ready to answer them. Speak to a rep today,
							9am - 6pm PST.</p>
					</div>
					<div class="mini-faq-text">
						<span>WE ARE PRODUCERS</span>
						<p>We produce Baroque framed Hoops / Arts, that is why our prices are so low. Major brands markup
							their products 8-10x the actual cost. We do things differently. To make our prices accessible,
							we sell directly to you from our production but without the traditional markups.</p>
					</div>
					<div class="mini-faq-text">
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
