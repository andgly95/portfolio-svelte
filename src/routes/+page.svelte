
	<section class="hero">
		<div class="left">
			<h1 class="name">Hi, I'm Andrew Glyadchenko</h1>
			<p class="text">
				A passionate front-end developer with a knack for creating intuitive and visually appealing
				user experiences. I specialize in Angular development and have a strong focus on writing
				clean, maintainable code.
			</p>
			<a href="#portfolio" class="cta-button">View my work</a>
		</div>
		<div class="right">
			<img src="andrew1.jpeg" alt="Andrew Glyadchenko" />
		</div>
	</section>
	<div class="flex">
		<section id="about" class="about">
			<h2>About Me</h2>
			<p>
				I'm a skilled front-end developer with over 5 years of experience in the industry. I have a
				strong background in Angular development and have worked on a variety of projects, from
				small business websites to large-scale enterprise applications.
			</p>
			<p>
				I'm passionate about creating user-friendly and accessible web experiences that not only
				look great but also perform well. I'm always eager to learn new technologies and stay
				up-to-date with the latest trends in web development.
			</p>
		</section>
		<section class="skills">
			<h2>Skills</h2>
			<ul>
				<li>Angular</li>
				<li>TypeScript</li>
				<li>JavaScript</li>
				<li>HTML5</li>
				<li>CSS3</li>
				<li>Responsive Web Design</li>
				<li>Git</li>
				<li>NgRx State Management</li>
				<li>Jest</li>
				<li>Storybook</li>
				<li>Agile Development</li>
				<li>React</li>
				<li>Next.js</li>
				<li>Rust</li>
			</ul>
		</section>
	</div>
	<section id="experience" class="experience">
		<h2>Experience</h2>
		<div class="job">
			<h3>Write Label</h3>
			<h4>Front End Engineer</h4>
			<p class="date">November 2021 - April 2024</p>
			<ul>
				<li>
					Implemented a UI component library from scratch based on the company's new design system,
					enhancing the consistency and reusability of front-end components across the application.
				</li>
				<li>
					Developed and maintained complex front-end features using Angular, leveraging NgRx for
					efficient state management and ensuring a smooth user experience.
				</li>
				<li>
					Collaborated closely with the backend team, providing guidance on API design and websocket
					integration to support front-end functionality.
				</li>
			</ul>
		</div>
		<div class="job">
			<h3>Like Minded Software</h3>
			<h4>Front End Implementation Expert</h4>
			<p class="date">January 2019 - November 2021</p>
			<ul>
				<li>
					Design and implementation of front-end Angular components for the New York City Department
					of Social Services Landlord Management portal
				</li>
				<li>
					Built and debugged features for the New York City Housing Preservation and Development
					Housing Connect 2, using Angular and .NET C#
				</li>
			</ul>
		</div>
		<div class="job">
			<h3>Truebird Coffee</h3>
			<h4>Web Developer Intern</h4>
			<p class="date">June 2018 - August 2018</p>
			<ul>
				<li>
					Designed and built a React-based ordering kiosk frontend for an automated micro-cafe
				</li>
				<li>Created assets and mockup sketches for a mobile-ordering UI</li>
				<li>Tested and debugged the JavaScript backend server, using Node-RED</li>
			</ul>
		</div>
		<!-- Add more job experiences here -->
	</section>
	<section id="portfolio" class="portfolio">
		<h2>Portfolio</h2>
		<div class="projects">
			<div class="project">
				<div class="left">
					<h3>WriteLabel.ai</h3>
					<p>
						A web application for crowdsourcing solutions for creative written and digital conten.
					</p>
					<a href="https://ai.writelabel.com" target="_blank" class="button">View Project</a>
				</div>
				<div class="right">
					<img src="WriteLabel_logo_AI.png" alt="WriteLabel.ai" />
				</div>
			</div>
			<div class="project">
				<div class="left">
					<h3>NYC Housing Connect 2.0</h3>
					<p>A web portal for New Yorkers to find and apply for affordable housing.</p>
					<a href="https://housingconnect.nyc.gov/PublicWeb/" target="_blank" class="button"
						>View Project</a
					>
				</div>
				<div class="right">
					<img src="Housing Connect 2.0 logo.png" alt="NYC Housing Connect 2.0" />
				</div>
			</div>
			<div class="project">
				<div class="left">
					<h3>ImagiChat</h3>
					<p>An AI-powered chat interface that engages in conversations and generates images.</p>
					<a href="https://guess-ai.app/" target="_blank" class="button">View Project</a>
				</div>
				<div class="right">
					<img src="imagichat.png" alt="ImagiChat" />
				</div>
			</div>
		</div>
	</section>
	<section id="contact" class="contact">
		<h2>Get in Touch</h2>
		<p>
			I'm always interested in new opportunities and collaborations. If you have a project in mind
			or just want to say hi, feel free to reach out to me using the form below or send me an email
			at
			<a href="mailto:andrew@andrewglyadchenko.dev">andrew&#64;andrewglyadchenko.dev</a>.
		</p>
		<form>
			<label for="name">Name:</label>
			<input type="text" id="name" name="name" required /><label for="email">Email:</label>
			<input type="email" id="email" name="email" required />

			<label for="message">Message:</label>
			<textarea id="message" name="message" required></textarea>

			<button type="submit">Send Message</button>
		</form>
	</section>