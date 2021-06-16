<template>
	
	<div id="portfolio">
		<div id="portnav">
				<button @click="show">All Projects</button>
				<button @click="Node">VUE.js and Node.js</button>
				<button @click="Php">PHP & MYSQL</button>
				<button @click="Android">Android Apps</button>
		</div>		
		<div class="tileproducts">
			<div class ="imgcontent" v-if="!AndroidApps">
				<div class="tile">
					<a href="https://play.google.com/store/apps/details?id=com.drawablestudios.animalrun.android"><img class="img" src="../assets/hiresAR.png"/></a>
				</div>
				<a href="https://play.google.com/store/apps/details?id=com.drawablestudios.animalrun.android">
					<p class="label">Animal Run!</p>
					<p id="description">Made with: Java, Android SDK, XML, Photoshop illustrator & FL studio</p>
					<p class="label"> Download Now</p>
				</a>
			</div>
			<div class ="imgcontent" v-if="!Nodesites">
				<div class="tile">
					<a href="https://github.com/humza3/API-backend"><img class="img" src="../assets/reviewsite.jpg"/></a>
				</div>
				<a href="https://github.com/humza3/API-backend">
					<p class="label">Backend for API review site</p>
					<p id="description">Made with: Node.js, Express & MongoDB</p>
					<p class="label">Visit Repository Here</p>
				</a>
			</div>
			<div class ="imgcontent" v-if="!Nodesites">
				<div class="tile">
					<a href="https://github.com/humza3/eCommerce"><img class="img" src="../assets/ecommerce.jpg"/></a>
				</div>
				<a href="https://github.com/humza3/eCommerce">
					<p class="label">Frontend for Ecommerce site</p>
					<p id="description">Made with: HTML, CSS, Javascript, AJAX, GULP & Bootstrap 4</p>
					<p class="label">Visit Repository Here</p>
				</a>
			</div>
			<div class ="imgcontent" v-if="!AndroidApps">
				<div class="tile">
					<a href="https://play.google.com/store/apps/details?id=com.drawablestudios.jumper.android"><img class="img" src="../assets/hiresgj.png"/></a>
				</div>
				<a href="https://play.google.com/store/apps/details?id=com.drawablestudios.jumper.android">
					<p class="label">Gnome Jumper</p>
					<p id="description">Made with: Java, Android SDK, XML, Photoshop illustrator & FL studio</p>
					<p class="label"> Download Now</p>
				</a>
			</div>
			<div class ="imgcontent" v-if="!Nodesites">
				<div class="tile">
					<a href="https://github.com/humza3/interactive-portfolio"><img class="img" src="../assets/interactive-portfolio.jpg"/></a>
				</div>
				<a href="https://github.com/humza3/interactive-portfolio">
					<p class="label">Interactive Portfolio</p>
					<p id="description">Made with: HTML, CSS & SASS</p>
					<p class="label">Visit Repository Here</p>
				</a>
			</div>
			<div class ="imgcontent" v-if="!Nodesites">
				<div class="tile">
					<a href="https://github.com/humza3/Groupmania"><img class="img" src="../assets/social-network.jpg"/></a>
				</div>
				<a href="https://github.com/humza3/Groupmania">
					<p class="label">Internal Social Network</p>
					<p id="description">Made with: HTML, CSS, Vue.js, Node.js, MySQL & Sequelize</p>
					<p class="label">Visit Repository Here</p>
				</a>
			</div>
			<div class ="imgcontent" v-if="!PhPsites">
				<div class="tile">
					<a href="http://www.kitchen5.co.uk/"><img class="img" src="../assets/kitchen5.jpg"/></a>
				</div>
				<a href="http://www.kitchen5.co.uk/">
					<p class="label">Kitchen 5</p>
					<p id="description">Made with: PHP, SQL, JQuery, AJAX, JSON & Apache language</p>
					<p class="label">Visit Here</p>
				</a>
			</div>			
			<div class ="imgcontent" v-if="!AndroidApps">
				<div class="tile">
					<a href="https://play.google.com/store/apps/details?id=com.drawablestudios.catcher.android"><img class="img" src="../assets/hiresleak.png"/></a>
				</div>
				<a href="https://play.google.com/store/apps/details?id=com.drawablestudios.catcher.android">
					<p class="label">Leak</p>
					<p id="description">Made with: Java, Android SDK, XML, Photoshop illustrator & FL studio</p>
					<p class="label"> Download Now</p>
				</a>
			</div>
			<div class ="imgcontent" v-if="!AndroidApps">
				<div class="tile">
					<a href="https://play.google.com/store/apps/details?id=com.drawablestudios.invaders.android"><img class="img" src="../assets/invadershires.png"/></a>
				</div>
				<a href="https://play.google.com/store/apps/details?id=com.drawablestudios.invaders.android">
					<p class="label">The Life On Mars</p>
					<p id="description">Made with: Java, Android SDK, XML, Photoshop illustrator & FL studio</p>
					<p class="label"> Download Now</p>
				</a>
			</div>
			<div class ="imgcontent" v-if="!AndroidApps">
				<div class="tile">
					<a href="https://play.google.com/store/apps/details?id=com.drawablestudios.blocko.android"><img class="img" src="../assets/Hiresmem.png"/></a>
				</div>
				<a href="https://play.google.com/store/apps/details?id=com.drawablestudios.blocko.android">
					<p class="label">MEM</p>
					<p id="description">Made with: Java, Android SDK, XML, Photoshop illustrator & FL studio</p>
					<p class="label"> Download Now</p>
				</a>
			</div>
			<div class ="imgcontent"  v-if="!PhPsites">
				<div class="tile">
					<a href="http://www.mzlim.com/"><img class="img" src="../assets/mzlim.jpg"/></a>
				</div>
				<a href="http://www.mzlim.com/">
					<p class="label">Mzlim</p>
					<p id="description">Made with: PHP, SQL, JQuery, AJAX, JSON & Apache language</p>
					<p class="label">Visit Here</p>
				</a>
			</div>
			<div class ="imgcontent" v-if="!AndroidApps">
				<div class="tile">
					<a href="https://play.google.com/store/apps/details?id=com.drawablestudios.slider.android"><img class="img" src="../assets/sliderhires.png"/></a>
				</div>
				<a href="https://play.google.com/store/apps/details?id=com.drawablestudios.slider.android">
					<p class="label">Number Slider</p>
					<p id="description">Made with: Java, Android SDK, XML, Photoshop illustrator & FL studio</p>
					<p class="label"> Download Now</p>
				</a>
			</div>
			<div class ="imgcontent" v-if="!AndroidApps">
				<div class="tile">
					<a href="https://play.google.com/store/apps/details?id=com.drawablestudios.game.android"><img class="img" src="../assets/PiggieHires.png"/></a>
				</div>
				<a href="https://play.google.com/store/apps/details?id=com.drawablestudios.game.android">
					<p class="label">Piggie Bird</p>
					<p id="description">Made with: Java, Android SDK, XML, Photoshop illustrator & FL studio</p>
					<p class="label"> Download Now</p>
				</a>
			</div>
			<div class ="imgcontent" v-if="!AndroidApps">
				<div class="tile">
					<a href="https://play.google.com/store/apps/details?id=com.drawblestudios.puzlock.android"><img class="img" src="../assets/hires.png"/></a>
				</div>
				<a href="https://play.google.com/store/apps/details?id=com.drawblestudios.puzlock.android">
					<p class="label">PuzLock</p>
					<p id="description">Made with: Java, Android SDK, XML, Photoshop illustrator & FL studio</p>
					<p class="label"> Download Now</p>
				</a>
			</div>
			<div class ="imgcontent" v-if="!AndroidApps">
				<div class="tile">
					<a href="https://play.google.com/store/apps/details?id=com.drawablestudios.turtlerunner.android"><img class="img" src="../assets/Turtle-Hi-Res.png"/></a>
				</div>
				<a href="https://play.google.com/store/apps/details?id=com.drawablestudios.turtlerunner.android">
					<p class="label">Tiler the Turtle</p>
					<p id="description">Made with: Java, Android SDK, XML, Photoshop illustrator & FL studio</p>
					<p class="label"> Download Now</p>
				</a>
			</div>
			<div class ="imgcontent" v-if="!PhPsites">
				<div class="tile">
					<a href="http://www.weirldnews.com/"><img class="img" src="../assets/weirldnews.jpg"/></a>
				</div>
				<a href="http://www.weirldnews.com/">
					<p class="label">Weirld News</p>
					<p id="description">Made with: PHP, SQL, JQuery, AJAX, JSON & Apache language</p>
					<p class="label">Visit Here</p>
				</a>
			</div>			
		</div>	
	</div>
</template>
<script>
	export default {
		el: '#portfolio',
		data() {
			return {
				AndroidApps:false,
				PhPsites:false,
				Nodesites:false,
			}
		},
		methods: {
			Android () {
				this.AndroidApps = false;
				this.PhPsites = true;
				this.Nodesites = true;
			},
			Php () {
				this.AndroidApps = true;
				this.PhPsites = false;
				this.Nodesites = true;
			},
			Node () {
				this.AndroidApps = true;
				this.PhPsites = true;
				this.Nodesites = false;
			},
			show() {
				this.AndroidApps = false;
				this.PhPsites = false;
				this.Nodesites = false;
			}
		}
	}
	
</script>

<style>
	#portfolio {
		width: 960px;
		height: auto;
		margin: 0 auto;
	}
	#description {
		font-size:10px;
	}
	.tileproducts {
		display: grid;
		grid-gap: 15px;
		padding:55px;
		grid-template-columns: repeat(auto-fit, 200px);
		align-items: center;
	}
	.tile img {
		width: 175px;
	}
	button {
		background-color: white;
		border: 2px solid #555555;
		color: black;
		padding: 16px 32px;
		text-align: center;
		text-decoration: none;
		display: inline-block;
		font-size: 16px;
		margin: 4px 2px;
		transition-duration: 0.4s;
		cursor: pointer;
	}

	button:hover {
		background-color: #555555;
		color: white;
	}
	
	.imgcontent {
		padding: 15px;
		width:200px;
		height:330px;
		border-radius: 10px;
		color: #24305e;;
		box-shadow: 5px 10px 18px #888888;
		transition: background-color 500ms;
	}
	.imgcontent:hover {
		background-color: #f76c6c;
	}
	.imgcontent a {
		text-decoration: none;
	}
	.imgcontent p {
		font-size: 14px;
		font-weight: 600;
		text-align: center;
	}
</style>
