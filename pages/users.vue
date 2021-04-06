<template>
    <div class="back">
          <ul id="navbar">
     <li><a href="http://localhost:3000">Home</a></li>
     <li><a href="#">News</a></li>
     <li><a href="#">Contacts</a>
        <ul>
          <li><a href="#">Managers</a></li>
          <li><a href="#">Email</a></li>
          <li><a href="#">Who are we?</a></li>
        </ul>
      </li>
      <li><a href="#">About</a></li>
    </ul>
      <br>
     <div class="container grid grid-cols-2 gap-2" id="registration-form">
       <div class="frm">
          <h1>Request</h1>
            <form>
                <div class="form-group">
                    <label for="username">First name:</label>
                    <input type="text" class="form-control" id="username" placeholder="Enter First name">
                </div>
                <div class="form-group">
                    <label for="email">Last name:</label>
                    <input type="email" class="form-control" id="email" placeholder="Enter Last name">
                </div>
                <div class="form-group">
                    <label for="pwd">Email:</label>
                    <input type="password" class="form-control" id="pwd" placeholder="Enter Email">
                </div>
                <div class="form-group">
                    <button type="submit" class="btn btn-success btn-lg">Send</button>
                </div>
            </form>
       </div>
        <div class="Contacts">
        <div v-for="user in users" :key="user.id">
          <div
          class="p-6 max-w-sm mx-auto bg-white rounded-xl shadow-md flex items-center space-x-4 m-4 zoom"
        >
          <div class="flex-shrink-0">
            <img
              class="h-12 w-12"
              :src="user.avatar"
              alt="ChitChat Logo"
            />
          </div>
             <div>
          <div class="text-xl font-medium text-black">{{ user.first_name }} {{ user.last_name }}</div>
          <button class="button transf"><span>Select </span></button>
          <h6 class="ttx">PR-manager</h6>
       </div>
         </div>
       </div>
      </div>
     </div>
     
      <div class="inf">
         <footer>
           <hr><strong>© 2017 STRONGER</strong><hr>
           <p style="padding-top: 9px">Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi necessitatibus culpa tenetur. <br>
           Lorem ipsum dolor sit amet consectetur adipisicing elit. Eos. <br>
           Lorem ipsum dolor sit amet.</p>
         </footer> 
      </div>
      
    </div>
</template>

<script>
import axios from "axios";
export default {
  data() {
    return {
      users: [],
    };
  },
  async mounted() {
    const { status, data } = await axios.get("https://reqres.in/api/users?page=1");
    this.users = data.data;
  },
};
</script>

<style scoped>
.back{
    height: 50rem;
    background-image: url(assets/images/see.jpg);
    margin-left: auto;
    margin-right: auto;
}
img {
    border-radius: 50%;
}
#navbar ul {
    display: none; }
 #navbar li:hover ul { 
   display: block; }
 #navbar ul {
  display: none;
  background-color: rgb(212, 159, 42);
  position: absolute;
  top: 100%;
}
#navbar li:hover ul { 
  display: block; }
#navbar, #navbar ul {
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
#navbar ul li { float: none; }
#navbar li:hover { background-color: rgb(212, 159, 42); }
#navbar ul li:hover { background-color: #666; }
 .zoom:hover{
    transform: scale(1.2);
 }
 .ttx{
   font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
   font-size: 12px;
   color: rgb(70, 68, 68);
   margin-top: -30px;
 }
 .button {
  border-radius: 4px;
  background-color: rgb(249, 159, 42);
  border: none;
  color: #FFFFFF;
  text-align: center;
  font-size: 15px;
  padding: 7px;
  width: 80px;
  transition: all 0.5s;
  cursor: pointer;
  margin-left: center;
}

.transf{
  margin-left: 150px;
  margin-top: -2em;
}

.button span {
  cursor: pointer;
  display: inline-block;
  position: relative;
  transition: 0.5s;
}

.button span:after {
  content: '\00bb';
  position: absolute;
  opacity: 0;
  top: 0;
  right: -20px;
  transition: 0.5s;
}

.button:hover span {
  padding-right: 25px;
}

.button:hover span:after {
  opacity: 1;
  right: 0;
}
.inf{
  height: 160px;
  width: 100%;
  background-color: rgb(39, 39, 43);
}
.Contacts{
  float: right;
  width: 600px;
  margin-right: 80px;
}
footer { width:100%; position:relative; overflow:hidden; text-align:center; color:rgb(192, 189, 189); padding:25px 0 20px 0; }
hr{
  padding: 2px 2px 2px 2px;
}
.container{
  width: 100%;
  margin: auto;
}
 #registration-form{
	max-width: 900px;
 }
 #registration-form .frm{
	float:left;
	height: 400px;
    width: 70%;
    min-width: 250px;
    padding: 0 35px;
    background-size: 100% 100%;
    background-color: white;
    margin-top: 100px;
}
#registration-form h1{
	margin-top: 25px;
	margin-bottom: 20px;
  font-size: 30px;
  text-align: center;
}
#registration-form .form-control{
	width: 90%;
	padding: 12px 20px;
	height: auto;
  background-color: rgb(235, 230, 230);
  border-radius: 5px;
}
#registration-form .btn{
		width: 100%;
		margin-top: 20px;
    color: cadetblue;
    background-color: darkblue;
    border-radius: 3px;
	}
</style>