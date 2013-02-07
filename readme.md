<div class="container">
		<!-- CONTENT HERE -->
		<header class="col-12">
			<hgroup>
				<h1>MW Framework Documentation</h1>
				<h2>A simple easy to use base to start each project from.</h2>
			</hgroup>
		</header>
	
		<section>
			<article class="main col-12">
			
				<h1>Introduction</h1>
				
				<p>The MW Framework is a basic/simple CSS/HTML5 framework to use as a starting point for web projects. Developed in Sass which is an extension of CSS3, adding nested rules, variables, mixins, selector inheritance, and more.</p>
					
				<p>This framework aims to be fully responsive down to mobile, supporting browsers from IE8 up (IE7-6 hacks might be added at some point in the future).</p>
				
				<p>The MW Frameowrk uses the JQuery JavaScript library to make writing JavaScript functionaility simpler.</p>
				
				<p>Note that this is a work in progress and the specification could change along the way.</p>
				
			</article>
			
			<article class="main col-12">
			
				<h1>Folder Structure</h1>
				
				<p>The idea behind the folder structure is to keep the framework files seperate from the specific project files. You could even have multiple theme folders for redesigns for example. The frameowrk folder shouldn't need any changes the only changes would take place in the theme folders.</p>
					
				<ul>
					<li>framework
						<ul>
							<li>_sass
								<ul>
									<li>_base.scss</li>
									<li>_grid.scss</li>
									<li>_normalize.scss</li>
									<li>_variables.scss</li>
								</ul>
							</li>
							<li>img</li>
							<li>js
								<ul>
									<li>libs</li>
								</ul>
							</li>
						</ul>
					</li>
					<li>themes
						<ul>
							<li>your_theme_folder
								<ul>
									<li>_sass
										<ul>
											<li>_default.scss</li>
											<li>_fonts.scss</li>
											<li>_grid.scss</li>
											<li>_mobile.scss</li>
											<li>_settings.scss</li>
											<li>_tablet.scss</li>
											<li>_variables.scss</li>
											<li>styles.scss</li>
										</ul>
									</li>
									<li>css</li>
									<li>img</li>
									<li>js</li>
								</ul>
							</li>
						</ul>
					</li>
					<li>.htaccess</li>
					<li>config.rb</li>
					<li>sample.html</li>
				</ul>
					
			</article>
			
			<article class="main col-12">
			
				<h1>Grid</h1>
				
				<p>The aim is to create a fully responsive grid using percentages using box-sizing a CSS property that incorporates the padding into the width of the element. This means we can have four elements on 25% to make up 100% while adding padding too.</p>
				
				<p></p>
				
				
			</article>
			
		</section>
		
		<footer>
			<p>&nbsp;</p>
		</footer>
	</div>
