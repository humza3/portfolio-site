<template>
	<div class="home">
		<header id="a">
			<div class="title">				
				<h1><span id="h1span">Humza</span> Butt</h1>
				<h2>Web Developer</h2>
			</div>
		</header>			
		<div id="aboutb">
			<div id="g">
				<img class="cvimg" src="../assets/education.png"  alt="education" title="education">
				
			</div>
			<div id="h">
				<h3>Education</h3>
						
			</div>
			<div id="i">
				<ul>
					<li>2019 - 2021</li>
					<li>London</li>
				</ul>
						
			</div>
			<div id="j">
				<ul>
					<li><h5>Openclassrooms</h5></li>
					<li>Level 5 Web Development Diploma</li>
					<li>I am currently studying Web development, where I will learn how to work on the front end of websites, utilising HTML, CSS and JavaScript to make mobile responsive and interactive web-based applications.</li>
				</ul>
						
			</div>
			<div id="k">
				<ul>
					<li>2008 - 2011</li>
					<li>London</li>
				</ul>
						
			</div>
			<div id="l">
				<ul>
					<li><h5>London Metropolitan University</h5></li>
					<li>Financial Economics Bsc</li>
					<li>I studied financial economics where I gained an in-depth knowledge of how financial markets operate and how variables affect them whether positively or negatively. </li>
				</ul>
						
			</div>
			<div id="m">
				<img class="cvimg" src="../assets/experience.png"  alt="experience" title="experience">
						
			</div>
			<div id="n">
				<h3>Experience</h3>
						
			</div>
			<div id="o">
				<ul>
					<li> September 2018 - present</li>
					<li>London</li>
				</ul>
						
			</div>
			<div id="p">
				<ul>
					<li><h5>Amazon</h5></li>
					<li>Warehouse Associate</li>
					<li>I work in the stow department of Amazon FC my primary role is to make sure Amazon’s stock is replenished and customer demands are met in a timely fashion.</li>
				</ul>								
			</div>
			<div id="q">
				<ul>
					<li>2015 - 2018</li>
					<li>London</li>
				</ul>
						
			</div>
			<div id="r">
				<ul>
					<li><h5>Self Employed</h5></li>
					<li>Day Trader</li>
					<li>I traded mostly ordinary shares as well as trading on the futures market. I analysed stock/commodity prices through predominantly technical analysis whilst using some fundamental analysis to gain an edge on the market.</li>
				</ul>							
			</div>
			<div id="s">
				<ul>
					<li>2012 - 2015</li>
					<li>London</li>
				</ul>								
			</div>
			<div id="t">
				<ul>
					<li><h5>Natrinza Ceramics</h5></li>
					<li>General Administrator</li>
					<li>I worked in a dental technician’s laboratory where I helped with office work, prospective sales phone calls as well as door to door appointments to new clients as well as helped in the production of Crowns and bridges.</li>
				</ul>								
			</div>
		</div>  

		<div id="c">
			<img id="cat" src="../assets/cat.jpg"  alt="cat picture" title="picture of cat">
		</div>
		<div id="d">
			<h3 class= "aside-title">Contact</h3>
			<ul>
				<li>Linkedin:</li>
				<li>www.linkedin.com/in/humzabutt3/</li>
				<li></li>
				<li>Website:</li>
				<li>www.drawablestudios.co.uk</li>
				<li></li>
				<li>GitHub</li>
				<li>www.github.com/humza3</li>
			</ul>
		</div>
		<div id="e">
			<h3 class= "aside-title">About Me</h3>
			<p>
			I am an Economics graduate who is currently studying for a career change into Web development.
			A few years prior, I taught myself how to make websites and android apps by studying Web and app
			development books and utilising online resources. Although my pursuits in web and mobile development
			were at a hobbyist level, in that time I managed to create four websites and nine apps.
			I made the websites with a combination of HTML, CSS, JavaScript and PHP, I produced the apps with Java.
			Previously, I worked as a self-employed day trader for three years where I employed my knowledge from
			my university studies in Financial Economics to trade on the share and futures market but after some time,
			I decided that this field was not providing the prosperity that I required in a career. 
			Currently, I am gaining a professional qualification in website development via Openclassrooms
			whilst working full-time at an Amazon Fulfilment Centre.
			</p>
		</div>
		<div id="f">
			<h3 class= "aside-title">Hobbies</h3>
			<img src="../assets/cooking.png"  alt="cooker" title="I like to cook">	
			<img src="../assets/gaming.png"  alt="controller" title="I like to game">	
			<img src="../assets/trading.png"  alt="trading" title="I like to trade">	
			<img src="../assets/reading.png"  alt="reading books" title="I like to read">	
		</div>	
	</div>
</template>
<script>
export default {
  name: 'Home',
  components: {
  }
}
</script>
<style>
	* {
    box-sizing: border-box;
    font-family: arial;
    color: #24305e;
    list-style-type: none;
}
body {
    font-size: 14;
}
@media screen and (max-width: 768px) {
    body {
        width: 100%;
        background-color: #a8d0e6;
    }
}
.home {
    display: grid;
    grid-template-columns: 30% 70%;
    grid-template-areas: "c a" "c nav" "d b" "e b" "f b";
    width: 960px;
    height: auto;
    margin: 0 auto;
}
@media screen and (max-width: 768px) {
    .home {
        width: 100%;
        display: grid;
        grid-template-columns: 50%;
        grid-template-areas: "c a" "nav nav" "b b" "e e" "f f" "d d";
    }
}
.title {
    grid-area: title;
    margin: 40px 50px;
    text-align: right;
    animation-name: title;
    animation-duration: 2s;
    animation-timing-function: cubic-bezier(0.28, 0.84, 0.42, 1);
}
@media screen and (max-width: 768px) {
    .title {
        margin: 80px auto;
    }
}
.title h1 {
    font-size: 40px;
    margin: 0 auto;
}
@media screen and (max-width: 768px) {
    .title h1 {
        text-align: left;
    }
}
.title h2 {
    font-size: 20px;
    text-align: center-right;
    margin: 0 auto;
    text-decoration: underline solid #f8e9a1;
}
@media screen and (max-width: 768px) {
    .title h2 {
        text-align: left;
    }
}
@keyframes title {
    0% {
        transform: translateX(0);
    }
    10% {
        transform: translateX(0);
    }
    30% {
        transform: translateX(-35px);
    }
    50% {
        transform: translateX(0);
    }
    57% {
        transform: translateX(-7px);
    }
    64% {
        transform: translateX(0);
    }
    100% {
        transform: translateX(0);
    }
}
#h1span {
    color: #f8e9a1;
    font-size: 40px;
    text-align: center-right;
    margin: 0 auto;
}
@media screen and (max-width: 768px) {
    #h1span {
        text-align: left;
    }
}
nav {
    grid-area: nav;
    width: 100%;
    background-color: #a8d0e6;
}
nav ul {
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: #24305e;
}
nav ul li {
    float: left;
    margin: 0 40px;
}
@media screen and (max-width: 768px) {
    nav ul li {
        margin: 0 5%;
    }
}
nav ul li a {
    display: block;
    color: #a8d0e6;
    font-size: 14px;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
    transition: transform 300ms ease-in, background-color 300ms ease-in;
}
nav ul li a:hover {
    background-color: #161d39;
    color: #f8e9a1;
    transform: scale(1.15);
}
.active {
    transform: scale(1.15);
}
.active a {
    background-color: #161d39;
    color: #f8e9a1;
}
#cat {
    width: 175px;
    height: 175px;
    margin: 55px 57px;
    border: 3px solid #f8e9a1;
    border-radius: 50%;
    animation-name: cat;
    animation-duration: 2s;
    animation-timing-function: cubic-bezier(0.28, 0.84, 0.42, 1);
}
@media screen and (max-width: 768px) {
    #cat {
        margin: 40px 10px;
        border: 3px solid #f8e9a1;
        border-radius: 50%;
    }
}
@keyframes cat {
    0% {
        transform: scale(1, 1) translateY(0);
    }
    10% {
        transform: scale(1.1, 0.9) translateY(0);
    }
    30% {
        transform: scale(0.9, 1.1) translateY(-35px);
    }
    50% {
        transform: scale(1.05, 0.95) translateY(0);
    }
    57% {
        transform: scale(1, 1) translateY(-7px);
    }
    64% {
        transform: scale(1, 1) translateY(0);
    }
    100% {
        transform: scale(1, 1) translateY(0);
    }
}
#a {
    grid-area: a;
    background-color: #a8d0e6;
}
@media screen and (max-width: 768px) {
    #a {
        width: 100%;
        min-width: 300px;
        padding: 10px 5px;
    }
}
#c {
    background-color: #f76c6c;
    grid-area: c;
    height: 250px;
}
@media screen and (max-width: 768px) {
    #c {
        max-width: 175px;
        background-color: #a8d0e6;
    }
}
.aside-title {
    background-color: #24305e;
    font-size: 20px;
    font-weight: 700;
    color: #f8e9a1;
    padding: 4px 0;
    text-align: center;
    width: 288px;
    height: 30px;
    margin: 10px auto;
}
@media screen and (max-width: 768px) {
    .aside-title {
        width: 100%;
    }
}
#d {
    grid-area: d;
    background-color: #f76c6c;
}
#d ul {
    padding-inline-start: 0;
}
#d ul li {
    padding: 5px 30px;
    text-align: center;
    animation-name: aside;
    animation-duration: 2s;
}
@media screen and (max-width: 768px) {
    #d ul li {
        padding: 2px 30px;
    }
}
@keyframes aside {
    0% {
        color: #f76c6c;
    }
    100% {
        color: #24305e;
    }
}
#e {
    grid-area: e;
    background-color: #f76c6c;
}
#e p {
    padding: 10px 30px;
    text-align: center;
    animation-name: aside;
    animation-duration: 2s;
}
@media screen and (max-width: 768px) {
    #e p {
        padding: 10px 60px;
    }
}
#f {
    grid-area: f;
    background-color: #f76c6c;
}
#f img {
    margin: 10px 9px;
    animation: wiggle 0.5s;
}
@media screen and (max-width: 768px) {
    #f img {
        margin-left: 7%;
        margin-right: 7%;
    }
}
@keyframes wiggle {
    0% {
        transform: translate(1px, 1px) rotate(0deg);
    }
    10% {
        transform: translate(-1px, -2px) rotate(-1deg);
    }
    20% {
        transform: translate(-3px, 0px) rotate(1deg);
    }
    30% {
        transform: translate(3px, 2px) rotate(0deg);
    }
    40% {
        transform: translate(1px, -1px) rotate(1deg);
    }
    50% {
        transform: translate(-1px, 2px) rotate(-1deg);
    }
    60% {
        transform: translate(-3px, 1px) rotate(0deg);
    }
    70% {
        transform: translate(3px, 1px) rotate(-1deg);
    }
    80% {
        transform: translate(-1px, -1px) rotate(1deg);
    }
    90% {
        transform: translate(1px, 2px) rotate(0deg);
    }
    100% {
        transform: translate(1px, -2px) rotate(-1deg);
    }
}
footer {
    background-color: #24305e;
    margin: 0;
    padding: 0;
}
@media screen and (max-width: 768px) {
    footer {
        width: 100%;
    }
}
footer p {
    color: #f8e9a1;
    margin: 0;
    padding: 0;
}
footer a {
    color: #f8e9a1;
}
#homeb {
    grid-area: b;
    background-color: #a8d0e6;
}
#slideshow {
    overflow: hidden;
    height: 340px;
    width: 600px;
    margin: 0 auto;
}
@media screen and (max-width: 768px) {
    #slideshow {
        height: 283‬px;
        width: 500px;
    }
}
.slide-wrapper {
    width: 2400px;
    animation: slide 18s ease infinite;
}
@media screen and (max-width: 768px) {
    .slide-wrapper {
        width: 2000px;
        animation: mobile-slide 18s ease infinite;
    }
}
.slide {
    float: left;
    height: 340px;
    width: 600px;
}
@media screen and (max-width: 768px) {
    .slide {
        height: 283‬px;
        width: 500px;
    }
}
@keyframes slide {
    0% {
        margin-left: 0px;
    }
    15% {
        margin-left: 0px;
    }
    25% {
        margin-left: -600px;
    }
    40% {
        margin-left: -600px;
    }
    50% {
        margin-left: -1200px;
    }
    65% {
        margin-left: -1200px;
    }
    80% {
        margin-left: -1800px;
    }
    95% {
        margin-left: -1800px;
    }
}
@keyframes mobile-slide {
    0% {
        margin-left: 0px;
    }
    15% {
        margin-left: 0px;
    }
    25% {
        margin-left: -500px;
    }
    40% {
        margin-left: -500px;
    }
    50% {
        margin-left: -1000px;
    }
    65% {
        margin-left: -1000px;
    }
    80% {
        margin-left: -1500px;
    }
    95% {
        margin-left: -1500px;
    }
}
#aboutb {
    grid-area: b;
    padding: 30px 40px;
    background-color: #a8d0e6;
    display: grid;
    grid-template-columns: 20% 20% 20% 20% 20%;
    grid-template-areas: "g h h h h" "i j j j j" "k l l l l" "m n n n n" "o p p p p" "q r r r r" "s t t t t" "u v v v v" ". w w x x";
}
@media screen and (max-width: 768px) {
    #aboutb {
        width: 100%;
        min-width: 300px;
        padding: 10px 5px;
    }
}
#aboutb h3 {
    background-color: #24305e;
    font-size: 20px;
    font-weight: 700;
    text-align: center;
    padding: 10px 0;
    color: #f8e9a1;
    width: 540.33px;
    margin: 4px 0px 0px -27px;
}
#aboutb h3 include mobile-only {
    width: 100%;
    margin: 4px 0px 0px 5px;
}
#aboutb h5 {
    margin-block-start: 0;
    margin-block-end: 0;
}
#aboutb li {
    margin: 5px 0;
}
@media screen and (max-width: 768px) {
    #aboutb li {
        margin: 5px 0px;
        white-space: normal;
        padding: 0 4px;
    }
}
.cvimg {
    border: 2px solid #f8e9a1;
    margin: 0px 0px 0px 37px;
}
@media screen and (max-width: 768px) {
    .cvimg {
        margin: 0px 0px 0px 20px;
    }
}
#g {
    grid-area: g;
}
#h {
    grid-area: h;
}
#i {
    grid-area: i;
}
#j {
    grid-area: j;
}
#k {
    grid-area: k;
}
#l {
    grid-area: l;
}
#m {
    grid-area: m;
}
#n {
    grid-area: n;
}
#o {
    grid-area: o;
}
#p {
    grid-area: p;
}
#q {
    grid-area: q;
}
#r {
    grid-area: r;
}
#s {
    grid-area: s;
}
#t {
    grid-area: t;
}
#u {
    grid-area: u;
}
#v {
    grid-area: v;
}
#w {
    grid-area: w;
}
#x {
    grid-area: x;
}
#portb {
    grid-area: b;
    background-color: #a8d0e6;
    display: grid;
    padding: 10px 3%;
    grid-template-columns: 33.3333% 33.3333% 33.3333%;
    grid-template-areas: "portg porth porti" "portj portk portl" "portm portn porto";
}
@media screen and (max-width: 768px) {
    #portb {
        grid-template-columns: 50% 50%;
        grid-template-areas: "portg porth" "porti portj" "portk portl" "portm portn" "porto .";
    }
}
#portg {
    grid-area: portg;
}
#porth {
    grid-area: porth;
}
#porti {
    grid-area: porti;
}
#portj {
    grid-area: portj;
}
#portk {
    grid-area: portk;
}
#portl {
    grid-area: portl;
}
#portm {
    grid-area: portm;
}
#portn {
    grid-area: portn;
}
#porto {
    grid-area: porto;
}
.imgcontent {
    padding: 10px;
    border-radius: 10px;
    color: #24305e;
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
.tile img {
    width: 100%;
}
#contb {
    grid-area: b;
    background-color: #a8d0e6;
    padding: 20px;
}
.contact {
    width: 100%;
}
.form__group input {
    border: 2px solid #f8e9a1;
    border-radius: 4px;
    color: #24305e;
    padding: 12px 20px;
    width: 100%;
    transition: border-color 500ms;
}
.form__group input:focus {
    border: 2px solid #f8e9a1;
}
.form__group input:not(:focus):invalid {
    border: 2px solid red;
}
#message {
    height: 150px;
    border: 2px solid #f8e9a1;
    border-radius: 2px;
    color: #24305e;
    padding: 12px 20px;
    width: 100%;
    border-radius: 4px;
    resize: none;
} /*# sourceMappingURL=style.css.map */

</style>
