<template>
  <div class="back">
    <div>
      <ul id="navbar">
        <li><a href="#">Home</a></li>
        <li><a href="#">News</a></li>
        <li>
          <a href="http://localhost:3000/users">Contacts</a>
          <ul>
            <li><a href="#">Managers</a></li>
            <li><a href="#">Email</a></li>
            <li><a href="#">Who are we?</a></li>
          </ul>
        </li>
        <li><a href="#">About</a></li>
      </ul>
    </div>
    <div class="container">
      <input type="radio" name="slider" id="item-1" checked />
      <input type="radio" name="slider" id="item-2" />
      <input type="radio" name="slider" id="item-3" />
      <div class="cards">
        <label class="card" for="item-1" id="song-1">
          <img
            src="https://is4-ssl.mzstatic.com/image/thumb/Features124/v4/eb/13/ec/eb13ecfa-fc97-31a5-e757-0faad8f9c6d6/mzl.clsxkycv.jpg/800x800bb.jpeg"
            alt="song"
          />
        </label>
        <label class="card" for="item-2" id="song-2">
          <img
            src="https://knews.kg/wp-content/uploads/2018/08/Bitlz.jpg"
            alt="song"
          />
        </label>
        <label class="card" for="item-3" id="song-3">
          <img
            src="https://sun9-39.userapi.com/impf/r0yB6ossf4Zor1EkgZwgnykHU672Cg08Rb-3Ww/p1dEa0SJ_7w.jpg?size=848x1080&quality=96&sign=7ca73d6fdeaccd47b08dfec524d940e7&type=album"
            alt="song"
          />
        </label>
      </div>
      <div class="player">
        <div class="upper-part">
          <div class="play-icon">
            <svg
              width="20"
              height="20"
              fill="#2992dc"
              stroke="#2992dc"
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              class="feather feather-play"
              viewBox="0 0 24 24"
            >
              <defs />
              <path d="M5 3l14 9-14 9V3z" />
            </svg>
          </div>
          <div class="info-area" id="test">
            <label class="song-info" id="song-info-1">
              <div class="title">Billie Jean</div>
              <div class="sub-line">
                <div class="subtitle">Michael Jackson</div>
                <div class="time">4.05</div>
              </div>
            </label>
            <label class="song-info" id="song-info-2">
              <div class="title">Lady Madonna</div>
              <div class="sub-line">
                <div class="subtitle">The Beatles</div>
                <div class="time">4.05</div>
              </div>
            </label>
            <label class="song-info" id="song-info-3">
              <div class="title">Dynamite</div>
              <div class="sub-line">
                <div class="subtitle">BTS</div>
                <div class="time">4.05</div>
              </div>
            </label>
          </div>
        </div>
        <div class="progress-bar">
          <span class="progress"></span>
        </div>
      </div>
    </div>
    <div class="second grid grid-cols-3 gap-1">
      <div>
        <h3 class="zag">Latest News</h3>
        <div class="krug">
          <h4 class="py-2 dat" align="center">
            24 <br />
            March
          </h4>
        </div>
        <div class="okno">
          <p class="pol" align="justify">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptate
            temporibus et nulla non ex ab, natus numquam eius. Excepturi
            assumenda dignissimos, dolorum aliquam iusto hic ullam laborum sed
            error ea aliquid asperiores doloremque ipsum sapiente quidem atque
            qui commodi non unde inventore temporibus explicabo! Repellendus,
            accusamus accusantium aut fugiat, culpa consectetur maiores dolore
            nisi veniam aperiam vitae excepturi doloremque voluptatum.
          </p>
        </div>
        <div class="krug">
          <h4 class="py-2 dat" align="center">
            26 <br />
            March
          </h4>
        </div>
        <div class="okno">
          <p class="pol" align="justify">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptate
            temporibus et nulla non ex ab, natus numquam eius. Excepturi
            assumenda dignissimos, dolorum aliquam iusto hic ullam laborum sed
            error ea aliquid asperiores doloremque ipsum sapiente quidem atque
            qui commodi non unde inventore temporibus explicabo! Repellendus,
            accusamus accusantium aut fugiat, culpa consectetur maiores dolore
            nisi veniam aperiam vitae excepturi doloremque voluptatum.
          </p>
        </div>
      </div>
      <div>
        <p class="zag">Tour</p>
        <div class="krugdva">
          <h4 class="py-2 dat" align="center">
            28 <br />
            March
          </h4>
        </div>
        <div class="okno">
          <h4 class="py-1 vtoroe">LA</h4>
          <p class="pol" align="justify">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet,
            incidunt.
          </p>
        </div>
        <div class="krugdva">
          <h4 class="py-2 dat" align="center">
            30 <br />
            March
          </h4>
        </div>
        <div class="okno">
          <h4 class="py-1 vtoroe">New Your City</h4>
          <p class="pol" align="justify">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquam,
            nostrum?
          </p>
        </div>
        <div class="krugdva">
          <h4 class="py-2 dat" align="center">
            12 <br />
            May
          </h4>
        </div>
        <div class="okno">
          <h4 class="py-1 vtoroe">Moskva</h4>
          <p class="pol" align="justify">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquam,
            nostrum?
          </p>
        </div>
        <div class="krugdva">
          <h4 class="py-2 dat" align="center">
            18 <br />
            June
          </h4>
        </div>
        <div class="okno">
          <h4 class="py-1 vtoroe">Seoul</h4>
          <p class="pol" align="justify">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquam,
            nostrum?
          </p>
        </div>
        <div class="krugdva">
          <h4 class="py-2 dat" align="center">
            27 <br />
            June
          </h4>
        </div>
        <div class="okno">
          <h4 class="py-1 vtoroe">London</h4>
          <p class="pol" align="justify">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquam,
            nostrum?
          </p>
        </div>
      </div>

      <div>
        <p class="zag">PR-group</p>
        <div class="oknodva">
          <p class="pol" align="justify">
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quis
            mollitia voluptatum pariatur doloremque porro quos ut dignissimos
            excepturi rerum, dicta exercitationem fugiat molestias laboriosam
            sunt eos aliquid ipsam reprehenderit minus aliquam officia, sint
            inventore quia. Libero non laborum ipsam quo, quasi modi beatae
            quia, quam laudantium reprehenderit blanditiis veritatis sint
            recusandae reiciendis dolore ab necessitatibus sed suscipit eos
            pariatur nemo? Quidem eum molestias nemo expedita nesciunt cum
            blanditiis beatae natus illo voluptates. Reiciendis sed placeat
            sequi minima, vitae est, eligendi eveniet maxime architecto hic
            obcaecati quae! Quibusdam reiciendis non id, quia beatae unde
            laudantium blanditiis, sapiente explicabo labore eum molestiae atque
            illum hic facilis expedita sunt obcaecati ipsam vero placeat
            repellendus! Tenetur distinctio nesciunt itaque similique in quae ad
            unde, neque, reprehenderit id dicta rerum? Suscipit placeat
            inventore quae voluptatibus.
          </p>
        </div>
        <div class="raspolozh">
          <p class="sb circle gradient glossy embossed black">
            	<a href="#" class="twitter">Twitter</a>
            	<a href="#" class="facebook">Facebook</a>
              <a href="#" class="heart">heart</a>
              <a href="#" class="sb youtube">YouTube</a>
	            <a href="#" class="sb email">Email</a>
          </p>
        </div>
      </div>
    </div>
    <div class="inf">
      <footer>
        <hr />
        <strong>© 2017 STRONGER</strong>
        <hr />
      </footer>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.back {
  width: 100%;
  height: 95rem;
  background-color: rgb(37, 37, 37);
  margin-left: auto;
  margin-right: auto;
}
#navbar ul {
  display: none;
}
#navbar li:hover ul {
  display: block;
}
#navbar ul {
  display: none;
  background-color: rgb(212, 159, 42);
  position: absolute;
  top: 100%;
}
#navbar li:hover ul {
  display: block;
}
#navbar,
#navbar ul {
  margin: 0;
  padding: 0;
  list-style-type: none;
}
#navbar {
  height: 40px;
  background-color: #666;
  padding-left: 25px;
  min-width: 470px;
}
#navbar li {
  float: left;
  position: relative;
  height: 100%;
}
#navbar li a {
  display: block;
  padding: 6px;
  width: 100px;
  color: #fff;
  text-decoration: none;
  text-align: center;
}
#navbar ul li {
  float: none;
}
#navbar li:hover {
  background-color: rgb(212, 159, 42);
}
#navbar ul li:hover {
  background-color: #666;
}
@import url("https://fonts.googleapis.com/css?family=DM+Sans:400,500,700&display=swap");

input[type="radio"] {
  display: none;
}

.card {
  position: absolute;
  width: 60%;
  height: 100%;
  left: 0;
  right: 0;
  margin: auto;
  transition: transform 0.4s ease;
  cursor: pointer;
}

.container {
  width: 100%;
  max-width: 800px;
  max-height: 600px;
  height: 100%;
  transform-style: preserve-3d;
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;
  margin: auto;
  margin-top: 30px;
}

.cards {
  position: relative;
  width: 100%;
  height: 100%;
  margin-bottom: 20px;
}

img {
  width: 100%;
  height: 100%;
  border-radius: 10px;
  object-fit: cover;
}

#item-1:checked ~ .cards #song-3,
#item-2:checked ~ .cards #song-1,
#item-3:checked ~ .cards #song-2 {
  transform: translatex(-40%) scale(0.8);
  opacity: 0.5;
  z-index: 0;
}

#item-1:checked ~ .cards #song-2,
#item-2:checked ~ .cards #song-3,
#item-3:checked ~ .cards #song-1 {
  transform: translatex(40%) scale(0.8);
  opacity: 0.5;
  z-index: 0;
}

#item-1:checked ~ .cards #song-1,
#item-2:checked ~ .cards #song-2,
#item-3:checked ~ .cards #song-3 {
  transform: translatex(0) scale(1);
  opacity: 1;
  z-index: 1;
}
img {
  box-shadow: 0px 0px 5px 0px rgba(81, 81, 81, 0.47);
}

.player {
  background-color: #fff;
  border-radius: 8px;
  min-width: 320px;
  padding: 16px 10px;
}

.upper-part {
  position: relative;
  display: flex;
  align-items: center;
  margin-bottom: 12px;
  height: 36px;
  overflow: hidden;
}

.play-icon {
  margin-right: 10px;
}

.song-info {
  width: calc(100% - 32px);
  display: block;
}

.song-info .title {
  color: #403d40;
  font-size: 14px;
  line-height: 24px;
}

.sub-line {
  display: flex;
  justify-content: space-between;
  width: 100%;
}

.subtitle,
.time {
  font-size: 12px;
  line-height: 16px;
  color: #c6c5c6;
}

.time {
  font-size: 12px;
  line-height: 16px;
  color: #a5a5a5;
  font-weight: 500;
  margin-left: auto;
}

.progress-bar {
  height: 3px;
  width: 100%;
  background-color: #e9efff;
  border-radius: 2px;
  overflow: hidden;
}

.progress {
  display: block;
  position: relative;
  width: 60%;
  height: 100%;
  background-color: #5946aa;
  border-radius: 6px;
}

.info-area {
  width: 100%;
  position: absolute;
  top: 0;
  left: 30px;
  transition: transform 0.4s ease-in;
}

#item-2:checked ~ .player #test {
  transform: translateY(0);
}

#item-2:checked ~ .player #test {
  transform: translateY(-40px);
}

#item-3:checked ~ .player #test {
  transform: translateY(-80px);
}
.second {
  background-color: #666;
  height: 700px;
  width: 1200px;
  margin: auto;
  margin-top: 30px;
}
.zag {
  color: white;
  font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
  font-size: 20px;
  margin-top: 30px;
  margin-left: 30px;
}
.krug {
  border-radius: 50%;
  background-color: lightblue;
  width: 70px;
  height: 70px;
  margin-left: 10px;
  margin-top: 10px;
}
.pol {
  color: #c6c5c6;
  font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS", sans-serif;
  font-size: 15px;
}
.okno {
  margin-left: 100px;
  padding-right: 20px;
  margin-top: -60px;
}
.dat {
  font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
  font-size: 17px;
}
.vtoroe {
  color: #e7e5e7;
  font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
  font-size: 20px;
}
.krugdva {
  border-radius: 50%;
  background-color: rgb(223, 162, 218);
  width: 70px;
  height: 70px;
  margin-left: 10px;
  margin-top: 10px;
}
.oknodva {
  margin-left: 20px;
  margin-right: 40px;
  margin-top: 20px;
}
footer {
  width: 100%;
  position: relative;
  overflow: hidden;
  text-align: center;
  color: rgb(192, 189, 189);
  padding: 50px 0 20px 0;
}
hr {
  padding: 2px 2px 2px 2px;
}
a.sb,
.sb a {
	width: 32px;
	height: 32px;
	background-repeat: no-repeat;
	background-position: center;
	text-indent: -900em;
	color: rgb(19, 18, 18);
	text-decoration: none;
	line-height: 100%;
	white-space: nowrap;
	display: inline-block;
	position: relative;
	vertical-align: middle;
	margin: 0 2px 5px 0;
	
	/* default button color */
	background-color: #ececec;
	border: solid 1px #b8b8b9;
	
	/* default box shadow */
	-webkit-box-shadow: inset 0 1px 0 rgba(255,255,255,.3), 0 1px 0 rgba(0,0,0,.1);
	-moz-box-shadow: inset 0 1px 0 rgba(255,255,255,.3), 0 1px 0 rgba(0,0,0,.1);
	box-shadow: inset 0 1px 0 rgba(255,255,255,.3), 0 1px 0 rgba(0,0,0,.1);

	/* default border radius */
	-webkit-border-radius: 5px;
	-moz-border-radius: 5px;
	border-radius: 5px;
}


/* SB LIST
================================================ */
.sb {
	margin: 0;
	padding: 0;
}
.sb li {
	margin: 0;
	padding: 0;
	display: inline;
}



/* gradient black */
a.sb.gradient.black:after,
.sb.gradient.black a:after {

	background-image: linear-gradient(top,  rgb(184, 189, 188) 0%,rgba(3,3,3,1) 100%);
}
/* black color */
a.sb.black,
.sb.black a,
a.sb.black:after,
.sb.black a:after {
	background-color: #252525;
	border-color: #000000;
	color: #fff;
}
a.sb.black:hover:after,
.sb.black a:hover:after {
	background-image: none;
}
a.sb.black:hover,
.sb.black a:hover,
a.sb.black:hover:after,
.sb.black a:hover:after {
	background-color: #000000;
}
/* circle style */
a.sb.circle,
.sb.circle a,
a.sb.circle:before,
.sb.circle a:before,
a.sb.circle:after,
.sb.circle a:after {
	-webkit-border-radius: 10em;
	-moz-border-radius: 10em;
	border-radius: 10em;
}

/* reset bottom border-radius for round and circle */
a.sb.circle:before,
.sb.circle a:before,
a.sb:before,
.sb a:before {
	border-bottom-right-radius: 0;
	border-bottom-left-radius: 0;
	-moz-border-radius-bottomright: 0;
	-moz-border-radius-bottomleft: 0;
	-webkit-border-bottom-right-radius: 0;
	-webkit-border-bottom-left-radius: 0;
}


/* embossed style */
a.sb.embossed,
.sb.embossed a {
	-webkit-box-shadow: inset 0 1px 0 rgba(255,255,255,.5), inset 0 -2px 0 rgba(0,0,0,.25), inset 0 -3px 0 rgba(255,255,255,.2), 0 1px 0 rgba(0,0,0,.1);
	-moz-box-shadow: inset 0 1px 0 rgba(255,255,255,.5), inset 0 -2px 0 rgba(0,0,0,.25), inset 0 -3px 0 rgba(255,255,255,.2), 0 1px 0 rgba(0,0,0,.1);
	box-shadow: inset 0 1px 0 rgba(255,255,255,.5), inset 0 -2px 0 rgba(0,0,0,.25), inset 0 -3px 0 rgba(255,255,255,.2), 0 1px 0 rgba(0,0,0,.1);
}

/* glossy style */
a.sb.glossy:before,
.sb.glossy a:before {
	content: "";
	width: 100%;
	height: 50%;
	position: absolute;
	top: 0;
	left: 0;
	
	/* glossy overlay */
	background: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiA/Pgo8c3ZnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgd2lkdGg9IjEwMCUiIGhlaWdodD0iMTAwJSIgdmlld0JveD0iMCAwIDEgMSIgcHJlc2VydmVBc3BlY3RSYXRpbz0ibm9uZSI+CiAgPGxpbmVhckdyYWRpZW50IGlkPSJncmFkLXVjZ2ctZ2VuZXJhdGVkIiBncmFkaWVudFVuaXRzPSJ1c2VyU3BhY2VPblVzZSIgeDE9IjAlIiB5MT0iMCUiIHgyPSIwJSIgeTI9IjEwMCUiPgogICAgPHN0b3Agb2Zmc2V0PSIwJSIgc3RvcC1jb2xvcj0iI2ZmZmZmZiIgc3RvcC1vcGFjaXR5PSIwLjQiLz4KICAgIDxzdG9wIG9mZnNldD0iMTAwJSIgc3RvcC1jb2xvcj0iI2ZmZmZmZiIgc3RvcC1vcGFjaXR5PSIwLjEiLz4KICA8L2xpbmVhckdyYWRpZW50PgogIDxyZWN0IHg9IjAiIHk9IjAiIHdpZHRoPSIxIiBoZWlnaHQ9IjEiIGZpbGw9InVybCgjZ3JhZC11Y2dnLWdlbmVyYXRlZCkiIC8+Cjwvc3ZnPg==);
	background: -moz-linear-gradient(top,  rgba(255,255,255,0.5) 0%, rgba(255,255,255,0.2) 100%);
	background: -webkit-linear-gradient(top,  rgba(255,255,255,0.5) 0%,rgba(255,255,255,0.2) 100%);
	background: linear-gradient(top,  rgba(255,255,255,0.5) 0%,rgba(255,255,255,0.2) 100%);
}

a.sb.black.twitter,
.sb.black a.twitter {
	background-image: url(~/assets/images/white_twitter_bird.png);
}
a.sb.black.facebook,
.sb.black a.facebook{
  background-image: url(~/assets/images/white_facebook.png);
}
a.sb.black.heart,
.sb.black a.heart{
  background-image: url(~/assets/images/white_heart.png);
}
a.sb.youtube {
	background-image: url(~/assets/images/w_youtube.png);
}
a.sb.email {
	background-image: url(~/assets/images/w_email.png);
}
a.sb.custom {
	width: 80px;
	height: 80px;
  border-radius: 15px;
}

.raspolozh{
  text-align: center;
  margin-top: 120px;
  margin-right: 40px;
  float: right;
}
</style>
