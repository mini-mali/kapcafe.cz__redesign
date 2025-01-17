# 01 – Create a SEO optimised copy for Metadata
------------------------------------------------

		You are a professional copywriter. Please help me to create a SEO optimised copy  for my website, particularly for:

		<title>
		<meta name="description">
		<meta property="og:title">
		<meta property="og:description">

		The copy should meet standards (like maximal characters count etc.)

		I'll provide you source text based on which you can create the copy. 

		Important note: In the provided text is mentioned that my place is a Guesthouse. Thats not correct, it is a Bed and Breakfasts (and Family run coffee)




		# RESULT
		--------

		<title>Kap Kafé | Family-Run Bed & Breakfast and Café in Kaplice</title>

		<meta name="description" content="Discover Kap Kafé, a cozy family-run Bed & Breakfast and Café in the heart of Kaplice. Enjoy charming accommodations, delightful breakfasts, and locally loved coffee.">

		<meta property="og:title" content="Kap Kafé | Cozy Bed & Breakfast and Café in Kaplice">
		<meta property="og:description" content="Welcome to Kap Kafé, your serene escape in Kaplice. Savor homemade delights, comfortable rooms, and the warm ambiance of our family-run café and B&B.">
	<div class="award d-flex align-items-center gap-2">
		<div class="award__img">
			<img
				src="./img/awards/seznam.cz--120x120.png"
				width="60"
				height="60"
				alt="Seznam.cz - Firmy">
		</div>
		<div class="award__text text-start">
			2024<br><b>The best café in the Český Krumlov district</b>
		</div>


# 02 – Create an engaging and SEO-optimized Hero section copy
------------------------------------------------


# 03 – Hero section - create Bootstrap 5 HTML code (SEO friendly, Accessibility if needed)
------------------------------------------------


# 04 – Create structured data markup (JSON-LD) for Google Search
------------------------------------------------


		Some facts:

		Address:
		Masná 200, 382 41 Kaplice, Česká republika

		website:
		https://www.kapcafe.cz/


		Phone:
		+420 384 391 764

		E-mail:
		svobodova@kapcafe.cz


		Facebook:
		https://www.facebook.com/KapCafe


		Opening Hours:

		Otevřeno
		Po–Čt 8 – 20
		Pá  8 – 22
		So 14 – 18
		Ne 14 – 18


		Další služby:
		Wi-Fi, Platba kartou, Salonek, Zahrádka, Dětský koute



		---------- for CZ only ----------
		IČO:
		0531926

		Datová schránka
		w79zxvh



		# RESULT
		--------

		{
			"@context": "https://schema.org",
			"@type": "BedAndBreakfast",
			"name": "Kap Café",
			...
			...
			...
			complete results here: kapcafe.cz__redesign/src/structured-data.json
		}




# 04 – Extend structured data markup (JSON-LD) for Google Search
------------------------------------------------

		Prompt
		------
		What other informations are valued by customers for "@type": "BedAndBreakfast",



		# RESULT
		--------

		...
		...
		...
		"starRating": {
			"@type": "Rating",
			"ratingValue": "4.8",
			"bestRating": "5"
		},
		...
		...
		...


# 05 – Primary navigation
-------------------------

		Prompt
		------
		from SEO perspective - what items should be ideally for my Café and BnB accomodation?



# 06 – Awards component
-------------------------

		Prompt
		------
		You are a Front-end developer. Please help me with my project build with Bootstrap 5.3.3. 

		I need to align "award__text" next to the "award__img". The gap between these two divs should be 8px. Is it possible to do it using Bootstrap utilility classes?

		Text inside "award__text" should be aligned to the left.


		This is my code:
			<div class="award">
				<div class="award__img">
					<img
						src="./img/awards/seznam.cz--120x120.png"
						width="60"
						height="60"
						alt="Seznam.cz - Firmy">
				</div>
				<div class="award__text">
					2024<br><b>The best café in the Český Krumlov district</b>
				</div>
			</div>


		# RESULT
		--------

			<div class="award d-flex align-items-center gap-2">
				<div class="award__img">
					<img
						src="./img/awards/seznam.cz--120x120.png"
						width="60"
						height="60"
						alt="Seznam.cz - Firmy">
				</div>
				<div class="award__text text-start">
					2024<br><b>The best café in the Český Krumlov district</b>
				</div>
			</div>


# 07 – Media object
-------------------------



# 08 – Section: Contact information
-------------------------


# 09 – Footer
-------------------------


		Prompt
		------

			here are structured data (upload structured-data.json)

			Please create a <footer> which will inlude:
			- logo
			- copyright with year

			Social media section (please use the Bootstrap SVG icons)
			- link to Facebook
			- link to Instagram

			- Created by mini-mali (https://www.mini-mali.com/)



		# RESULT
		--------

			<footer class="bg-light py-4 mt-5">
				<div class="container">
					<div class="row align-items-center">
						<!-- Logo Section -->
						<div class="col-md-4 text-center text-md-start">
							<a href="https://www.kapcafe.cz/" target="_blank" rel="noopener">
								<img src="https://www.kapcafe.cz/assets/images/hero.jpg" alt="Kap Café Logo" class="img-fluid" style="max-height: 80px;">
							</a>
						</div>

						<!-- Copyright Section -->
						<div class="col-md-4 text-center my-3 my-md-0">
							<small>© 2025 Kap Café. All Rights Reserved.</small>
						</div>

						<!-- Social Media Section -->
						<div class="col-md-4 text-center text-md-end">
						<a href="https://www.facebook.com/KapCafe" target="_blank" class="text-dark me-3">
							<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor" class="bi bi-facebook" viewBox="0 0 16 16">
							<path d="M8 0C3.58 0 0 3.58 0 8c0 3.99 3.058 7.302 7.031 7.92v-5.59H5.02V8h2.01V6.275c0-1.99 1.192-3.092 3.018-3.092.86 0 1.76.153 1.76.153v1.93h-.99c-.975 0-1.283.607-1.283 1.23V8h2.177l-.348 2.33h-1.83v5.59C12.942 15.302 16 11.99 16 8c0-4.42-3.58-8-8-8z"/>
							</svg>
						</a>
						<a href="https://www.instagram.com/kapcafekaplice" target="_blank" class="text-dark">
							<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor" class="bi bi-instagram" viewBox="0 0 16 16">
							<path d="M8 0c2.2 0 2.464.008 3.326.048.862.04 1.454.182 1.985.384.536.202.988.49 1.457.958.47.47.756.922.958 1.457.202.53.344 1.123.384 1.985.04.862.048 1.126.048 3.326s-.008 2.464-.048 3.326c-.04.862-.182 1.454-.384 1.985-.202.536-.49.988-.958 1.457-.47.47-.922.756-1.457.958-.53.202-1.123.344-1.985.384-.862.04-1.126.048-3.326.048s-2.464-.008-3.326-.048c-.862-.04-1.454-.182-1.985-.384a4.305 4.305 0 0 1-1.457-.958 4.305 4.305 0 0 1-.958-1.457c-.202-.53-.344-1.123-.384-1.985-.04-.862-.048-1.126-.048-3.326s.008-2.464.048-3.326c.04-.862.182-1.454.384-1.985.202-.536.49-.988.958-1.457A4.305 4.305 0 0 1 2.68.432c.53-.202 1.123-.344 1.985-.384C5.526.008 5.8 0 8 0zM8 1.438c-2.2 0-2.466.008-3.327.048-.853.039-1.267.167-1.554.273a3.046 3.046 0 0 0-1.152.766 3.046 3.046 0 0 0-.766 1.152c-.106.287-.234.701-.273 1.554C1.446 5.534 1.438 5.8 1.438 8c0 2.2.008 2.466.048 3.327.039.853.167 1.267.273 1.554.176.438.409.72.766 1.152.357.357.64.59 1.152.766.287.106.701.234 1.554.273C5.534 14.554 5.8 14.562 8 14.562c2.2 0 2.466-.008 3.327-.048.853-.039 1.267-.167 1.554-.273a3.046 3.046 0 0 0 1.152-.766c.357-.357.59-.64.766-1.152.106-.287.234-.701.273-1.554.039-.853.048-1.127.048-3.327 0-2.2-.008-2.466-.048-3.327-.039-.853-.167-1.267-.273-1.554a3.046 3.046 0 0 0-.766-1.152 3.046 3.046 0 0 0-1.152-.766c-.287-.106-.701-.234-1.554-.273C10.466 1.446 10.2 1.438 8 1.438zm0 1.846a4.718 4.718 0 1 0 0 9.438 4.718 4.718 0 0 0 0-9.438zM8 4.063a3.938 3.938 0 1 1 0 7.876 3.938 3.938 0 0 1 0-7.876zm5.25-.781a.937.937 0 1 0 0 1.876.937.937 0 0 0 0-1.876z"/>
							</svg>
						</a>
						</div>
					</div>
					<div class="text-center mt-4">
						<small>Created by <a href="https://www.mini-mali.com/" target="_blank" rel="noopener" class="text-decoration-none">mini-mali</a></small>
					</div>
				</div>
			</footer>
