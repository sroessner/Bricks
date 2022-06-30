<!DOCTYPE HTML>
<html>
<head>
<link rel="stylesheet" type="text/css" href="css/Base.css" />
<link rel="stylesheet" type="text/css" href="css/dropdown.css" />
<script src="js/classie.js"></script>
<script src="js/list.js"></script>
<script src="js/snap.svg-min.js"></script>
<link id="CurrentStyle" rel="stylesheet" type="text/css" href="css/Ocean.css" media="screen" />
<script src="js/Scripts.js"></script>
</head>
<body>
<div id="header">
<div id="namelogo">FIT BRICKS</div>
<nav id="menu" class="menu">
	<div class="morph-shape" data-morph-open="M260,500H0c0,0,8-120,8-250C8,110,0,0,0,0h260c0,0-8,110-8,250C252,380,260,500,260,500z">
		<svg width="500px" height="100%" viewBox="0 0 260 500" preserveAspectRatio="none">
		<path fill="none" d="M260,500H0c0,0,0-120,0-250C0,110,0,0,0,0h260c0,0,0,110,0,250C260,380,260,500,260,500z"/>
		</svg>
	</div>
	<button class="menu__label"><span>Customize Colors</span></button>
	<div class="menu__inner">
		<table>
			<tr>
				<td><span onclick="ColorChanger('css/Ocean.css')">Ocean<br><svg width="75" height="15"><rect fill="rgb(246,239,247)" width="15" height="15" x="0"></rect><rect fill="rgb(189,201,225)" width="15" height="15" x="15"></rect><rect fill="rgb(103,169,207)" width="15" height="15" x="30"></rect><rect fill="rgb(28,144,153)" width="15" height="15" x="45"></rect><rect fill="rgb(1,108,89)" width="15" height="15" x="60"></rect></svg></span></td>
				<td><span onclick="ColorChanger('css/Purple.css')">Purple<br><svg width="75" height="15"><rect fill="rgb(242,240,247)" width="15" height="15" x="0"></rect><rect fill="rgb(203,201,226)" width="15" height="15" x="15"></rect><rect fill="rgb(158,154,200)" width="15" height="15" x="30"></rect><rect fill="rgb(117,107,177)" width="15" height="15" x="45"></rect><rect fill="rgb(84,39,143)" width="15" height="15" x="60"></rect></svg></span></td>
				<td><span onclick="ColorChanger('css/Rose.css')">Rose<br><svg width="75" height="15"><rect fill="rgb(254,229,217)" width="15" height="15" x="0"></rect><rect fill="rgb(252,174,145)" width="15" height="15" x="15"></rect><rect fill="rgb(251,106,74)" width="15" height="15" x="30"></rect><rect fill="rgb(222,45,38)" width="15" height="15" x="45"></rect><rect fill="rgb(165,15,21)" width="15" height="15" x="60"></rect></svg></span></td>
				<td><span onclick="ColorChanger('css/Orange.css')">Orange<br><svg width="75" height="15"><rect fill="rgb(254,237,222)" width="15" height="15" x="0"></rect><rect fill="rgb(253,190,133)" width="15" height="15" x="15"></rect><rect fill="rgb(253,141,60)" width="15" height="15" x="30"></rect><rect fill="rgb(230,85,13)" width="15" height="15" x="45"></rect><rect fill="rgb(166,54,3)" width="15" height="15" x="60"></rect></svg></span></td>
			</tr>
			<tr>
				<td><span onclick="ColorChanger('css/Green.css')">Green<br><svg width="75" height="15"><rect fill="rgb(237,248,233)" width="15" height="15" x="0"></rect><rect fill="rgb(186,228,179)" width="15" height="15" x="15"></rect><rect fill="rgb(116,196,118)" width="15" height="15" x="30"></rect><rect fill="rgb(49,163,84)" width="15" height="15" x="45"></rect><rect fill="rgb(0,109,44)" width="15" height="15" x="60"></rect></svg></span></td>
				<td><span onclick="ColorChanger('css/Blue.css')">Blue<br><svg width="75" height="15"><rect fill="rgb(239,243,255)" width="15" height="15" x="0"></rect><rect fill="rgb(189,215,231)" width="15" height="15" x="15"></rect><rect fill="rgb(107,174,214)" width="15" height="15" x="30"></rect><rect fill="rgb(49,130,189)" width="15" height="15" x="45"></rect><rect fill="rgb(8,81,156)" width="15" height="15" x="60"></rect></svg></span></td>
				<td><span onclick="ColorChanger('css/Autumn.css')">Autumn<br><svg width="75" height="15"><rect fill="rgb(255,255,212)" width="15" height="15" x="0"></rect><rect fill="rgb(254,217,142)" width="15" height="15" x="15"></rect><rect fill="rgb(254,153,41)" width="15" height="15" x="30"></rect><rect fill="rgb(217,95,14)" width="15" height="15" x="45"></rect><rect fill="rgb(153,52,4)" width="15" height="15" x="60"></rect></svg></span></td>
				<td><span onclick="ColorChanger('css/Pink.css')">Pink<br><svg width="75" height="15"><rect fill="rgb(241,238,246)" width="15" height="15" x="0"></rect><rect fill="rgb(215,181,216)" width="15" height="15" x="15"></rect><rect fill="rgb(223,101,176)" width="15" height="15" x="30"></rect><rect fill="rgb(221,28,119)" width="15" height="15" x="45"></rect><rect fill="rgb(152,0,67)" width="15" height="15" x="60"></rect></svg></span></td>
			</tr>
			<tr>
				<td><span onclick="ColorChanger('css/LightBlue.css')">Light Blue<br><svg width="75" height="15"><rect fill="rgb(240,249,232)" width="15" height="15" x="0"></rect><rect fill="rgb(186,228,188)" width="15" height="15" x="15"></rect><rect fill="rgb(123,204,196)" width="15" height="15" x="30"></rect><rect fill="rgb(67,162,202)" width="15" height="15" x="45"></rect><rect fill="rgb(8,104,172)" width="15" height="15" x="60"></rect></svg></span></td>
				<td><span onclick="ColorChanger('css/PurplePink.css')">Magenta<br><svg width="75" height="15"><rect fill="rgb(254,235,226)" width="15" height="15" x="0"></rect><rect fill="rgb(251,180,185)" width="15" height="15" x="15"></rect><rect fill="rgb(247,104,161)" width="15" height="15" x="30"></rect><rect fill="rgb(197,27,138)" width="15" height="15" x="45"></rect><rect fill="rgb(122,1,119)" width="15" height="15" x="60"></rect></svg></span></td>
				<td><span onclick="ColorChanger('css/Twilight.css')">Twilight<br><svg width="75" height="15"><rect fill="rgb(237,248,251)" width="15" height="15" x="0"></rect><rect fill="rgb(179,205,227)" width="15" height="15" x="15"></rect><rect fill="rgb(140,150,198)" width="15" height="15" x="30"></rect><rect fill="rgb(136,86,167)" width="15" height="15" x="45"></rect><rect fill="rgb(129,15,124)" width="15" height="15" x="60"></rect></svg></span></td>
				<td><span onclick="ColorChanger('css/Gray.css')">Gray<br><svg width="75" height="15"><rect fill="rgb(247,247,247)" width="15" height="15" x="0"></rect><rect fill="rgb(204,204,204)" width="15" height="15" x="15"></rect><rect fill="rgb(150,150,150)" width="15" height="15" x="30"></rect><rect fill="rgb(99,99,99)" width="15" height="15" x="45"></rect><rect fill="rgb(37,37,37)" width="15" height="15" x="60"></rect></svg></span></td>
			</tr>

		</table>
	</div>
</nav>
</div>
<div id="canvas" ondrop="dropbrick(event)" ondragover="allowDrop(event)">
</div>
<div id="sidebar" ondragover="allowDrop(event)">
<div id="minibrick" class="minibrick" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"><div class="container"><div class="repeat">X<input type="number" value="1"></div></div></div>
<div id="medibrick" class="medibrick" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"><div class="container"><div class="repeat">X<input type="number" value="1"></div></div></div>
<div id="megabrick" class="megabrick" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"><div class="container"><div class="repeat">X<input type="number" value="1"></div></div></div>

<div id="exercises">
  <div class="searchdiv"><input class="search" placeholder="Search" /></div>


<ul class="list">
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Row-body-weight">Row body-weight<div class="ecat">strength, body weight, arm</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Bicep-Curl">Bicep Curl<div class="ecat">kettle bell, dumbbell, strength, arm</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Bent-Over-Row">Bent-Over Row<div class="ecat">kettle bell, dumbbell, strength, core</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Lunge-Row">Lunge Row<div class="ecat">kettle bell, dumbbell, strength, core</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Shoulder-Press">Shoulder Press<div class="ecat">kettle bell, dumbbell, strength, arm</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Kneel-to-Stand">Kneel-to-Stand<div class="ecat">kettle bell, dumbbell, strength, arm</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Squat">Squat<div class="ecat">kettle bell, dumbbell, strength</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Crunch">Crunch<div class="ecat">core, body weight</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Pull-Over-Crunch">Pull-Over Crunch<div class="ecat">kettle bell, dumbbell, core</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Flutter-Kicks">Flutter Kicks<div class="ecat">core, body weight</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Around-the-World">Around the World<div class="ecat">kettle bell, dumbbell</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Burpees">Burpees<div class="ecat">body weight, cardio</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="High-Knees">High Knees<div class="ecat">body weight, cardio</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Side-Skaters">Side Skaters<div class="ecat">body weight, cardio, active stretch</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Fast-Feet-to-Floor">Fast-Feet-to-Floor<div class="ecat">body weight, cardio</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Tuck-Jumps">Tuck Jumps<div class="ecat">body weight, jump, cardio</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Mountain-Climbers">Mountain Climbers<div class="ecat">body weight, cardio</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Body-Row-TRX">Body Row TRX<div class="ecat">TRX, core</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Chest-Press-TRX">Chest Press TRX<div class="ecat">TRX, arms</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Bicep-Curl-TRX">Bicep Curl TRX<div class="ecat">TRX, arms</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Superman">Superman<div class="ecat">body weight, core</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Superman-BOSU">Superman BOSU<div class="ecat">bosu, core, body weight</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Single-Leg-Squat-TRX">Single-Leg Squat TRX<div class="ecat">TRX, leg, strength</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Curtsy-Lunge-TRX">Curtsy Lunge TRX<div class="ecat">TRX, leg, strength</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Balance-Squat">Balance Squat<div class="ecat">bosu, leg</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Side-Lunge-BOSU">Side Lunge BOSU<div class="ecat">bosu, leg, active stretch</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Single-Leg-Dead-Lift">Single Leg Dead Lift<div class="ecat">body weight, kettle bell, dumbbell, leg, strength</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Single-Leg-Dead-Lift-BOSU">Single Leg Dead Lift BOSU<div class="ecat">body weight, kettle bell, dumbbell, leg, strength, bosu</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Push-Up">Push-Up<div class="ecat">body weight, arm</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Push-Up-BOSU">Push-Up BOSU<div class="ecat">body weight, arm, bosu</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Power-Pull">Power Pull<div class="ecat">TRX, arms</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Knees-to-Elbows">Knees-to-Elbows<div class="ecat">TRX, core</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Squat-Press">Squat Press<div class="ecat">kettle bell, dumbbell, strength</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Windmill">Windmill<div class="ecat">kettle bell, dumbbell, core</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Lunge">Lunge<div class="ecat">leg, body weight</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Star-Jump">Star Jump<div class="ecat">body weight, cardio, jump, plyo</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Jumping-Jacks">Jumping Jacks<div class="ecat">body weight, cardio, jump, plyo</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Mountain-Climbers-TRX">Mountain Climbers TRX<div class="ecat">TRX, core, cardio</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Snatch">Snatch<div class="ecat">kettle bell, strength</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Turkish-Get-Up">Turkish Get-Up<div class="ecat">kettle bell, body weight</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Leg-Lifts">Leg Lifts<div class="ecat">core, body weight</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Russian-Twist">Russian Twist<div class="ecat">core, body weight, kettle bell, dumbbell</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Dead-Bug">Dead Bug<div class="ecat">core, body weight</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="In-and-Out">In and Out<div class="ecat">core, body weight</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="In-and-Out-BOSU">In and Out BOSU<div class="ecat">core, body weight, bosu</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Goblet-Squat">Goblet Squat<div class="ecat">kettle bell, dumbbell, strength, leg</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Renegade-Row">Renegade Row<div class="ecat">body weight, core</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="High-Pull">High Pull<div class="ecat">kettle bell, dumbbell, arm</div></div</li>
<li><div class="eitem" draggable="true" ondragstart="drag(event)" ondrop="dropeitem(event)"  id="Alternating-Swing">Alternating Swing<div class="ecat">kettle bell, cardio</div></div</li>
</ul>

</div>

</div>
</body>
<script>
var options = {
  valueNames: [ 'eitem' ,'ecat']
};
var userList = new List('exercises', options);
</script>
<script>
			(function() {

				function SVGDDMenu( el, options ) {
					this.el = el;
					this.init();
				}

				SVGDDMenu.prototype.init = function() {
					this.shapeEl = this.el.querySelector( 'div.morph-shape' );

					var s = Snap( this.shapeEl.querySelector( 'svg' ) );
					this.pathEl = s.select( 'path' );
					this.paths = {
						reset : this.pathEl.attr( 'd' ),
						open : this.shapeEl.getAttribute( 'data-morph-open' )
					};

					this.isOpen = false;

					this.initEvents();
				};

				SVGDDMenu.prototype.initEvents = function() {
					this.el.addEventListener( 'click', this.toggle.bind(this) );
						
					// For Demo purposes only
					[].slice.call( this.el.querySelectorAll('a') ).forEach( function(el) {
						el.onclick = function() { return false; }
					} );
				};

				SVGDDMenu.prototype.toggle = function() {
					var self = this;

					if( this.isOpen ) {
						classie.remove( self.el, 'menu--open' );
					}
					else {
						classie.add( self.el, 'menu--open' );
					}

					this.pathEl.stop().animate( { 'path' : this.paths.open }, 320, mina.easeinout, function() {
						self.pathEl.stop().animate( { 'path' : self.paths.reset }, 1000, mina.elastic );
					} );

					this.isOpen = !this.isOpen;	
				};

				new SVGDDMenu( document.getElementById( 'menu' ) );

			})();
</script>

</html>
