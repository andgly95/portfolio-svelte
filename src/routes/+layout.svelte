<script>
	import '../app.scss';
  let showNavOptions = true;

  function toggleNavOptions() {
    showNavOptions = !showNavOptions;
  }
</script>
<main class="main">
	<header>
		<div class="logo" on:click="{toggleNavOptions}">
			<img src="wordmark.png" alt="Andrew Glyadchenko" />
		</div>
 
		<nav class:active="{showNavOptions}">
			<ul class="links">
				<li><a href="#about">About</a></li>
				<li><a href="#skills">Skills</a></li>
				<li>
					<a href="#experience">Experience</a>
				</li>
				<li>
					<a href="#projects">Projects</a>
				</li>
				<li><a href="#contact">Contact</a></li>
			</ul>
		</nav>
	</header>
<slot />

	<footer>
		<p>&copy; 2024 Andrew Glyadchenko. All rights reserved.</p>
		<ul class="social-links">
			<li>
				<a href="https://www.linkedin.com/in/andrew-glyadchenko-13b85498/" target="_blank"
					><img src="linkedin-mark.png" /></a
				>
			</li>
			<li>
				<a href="https://github.com/andgly95" target="_blank"
					><img src="github-mark.png" /></a
				>
			</li>
			<li>
				<a href="https://twitter.com/andgly95" target="_blank"><span>𝕏</span></a>
			</li>
		</ul>
	</footer>
</main>