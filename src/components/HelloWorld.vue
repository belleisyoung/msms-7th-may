<template>
  <title>MSMS </title>

  <!--META TAGS-->
  <meta name="viewport" content="width=device-width, initial-scal=1, user-scalable=no">
  <meta name="author" content="Mahesh">

  <!--FONT AWESOME-->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

  <!--EXTERNAL CSS
  <link rel="stylesheet" href="css/style.css">-->

  <!--GOOGLE FONTS-->
  <link rel="preconnect" href="https://fonts.gstatic.com">
  <link href="https://fonts.googleapis.com/css2?family=notosans:wght@600&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=montserrat&display=swap" rel="stylesheet">


  <header>
    <div class="menu">
      <table>
        <tr>
          <td>
            <div class="logo-container"><img src="../assets/MSMSLOGOO.png" alt="MSMS" class="logo"></div>
          </td>
          <td>
            <input type="text" class="search" name="search" placeholder="Search"><button type="submit"><i
                class="fa fa-search"></i></button>
          </td>
          <td>
            <span>
              <div class="navbar">
                <div class="dropdown">
                  <button class="dropbtn">Account
                    <i class="fa fa-caret-down"></i>
                  </button>
                  <div class="dropdown-content">
                    <a href="#">Profile</a>
                    <a href="#">Orders</a>
                    <a href="#">Wishlist</a>
                    <router-link to="/supplierRegistration">
                      <li class="dropdown-submenu">
                        <a class="dropbtn">LogIn/SignUp

                        </a>



                      </li>
                    </router-link>

                  </div>
                </div>
                <div class="card">
                  <div class="card-content">
                    <span class="submenu">
                      <a href="#">Log in as Supplier</a>
                      <a href="#">Log in as Customer</a>
                    </span>
                  </div>
                </div>
                <div class="dropdown">
                  <button class="dropbtn cart"><i class="fa fa-shopping-cart"></i> <span class="value">2</span>
                  </button>
                  <div class="dropdown-content cart-content">
                    <a>
                      <ul>
                        <li>
                          <img src="https://i.ibb.co/RpnQq12/01.webp" alt="Item">
                        </li>
                        <li>
                          <span class="title">Samsung Galaxy POP</span>
                          <span class="sub-title">$ 5999</span>
                        </li>
                        <li><i class="fa fa-trash"></i></li>
                      </ul>
                      <ul>
                        <li>
                          <img src="https://i.ibb.co/RpnQq12/01.webp" alt="Item">
                        </li>
                        <li>
                          <span class="title">Samsung Galaxy POP</span>
                          <span class="sub-title">$ 5999</span>
                        </li>
                        <li><i class="fa fa-trash"></i></li>
                      </ul>
                      <button type="submit" class="btn1">CheckOut</button>
                    </a>
                  </div>
                </div>
              </div>
            </span>
          </td>
        </tr>
      </table>
    </div>

    <div class="topnav" id="myTopnav">
      <div class="dropdown">
        <button class="dropbtn">Electronics
          <i class="fa fa-caret-down"></i>
        </button>
        <div class="dropdown-content mega-dropdown">
          <div class="row  column1">
            <div class="column">
              <h3>Mobiles</h3>
              <a href="#">Mi</a>
              <a href="#">Samsung</a>
              <a href="#">RealMe</a>
            </div>
            <div class="column">
              <h3>Mobile Accessories</h3>
              <a href="#">Power Bank</a>
              <a href="#">OTG</a>
              <a href="#">Covers</a>
            </div>
            <div class="column">
              <h3>Speakers</h3>
              <a href="#">Home Theater</a>
              <a href="#">Portable</a>
              <a href="#">Sound Bars</a>
            </div>
            <div class="column">
              <h3>Featured</h3>
              <a href="#">Apple Store</a>
              <a href="#">Mcrosoft Store</a>
              <a href="#">MSMS Store</a>
            </div>
          </div>
        </div>
      </div>

      <div class="dropdown">
        <button class="dropbtn">Men & Women
          <i class="fa fa-caret-down"></i>
        </button>
        <div class="dropdown-content mega-dropdown">
          <div class="row">
            <div class="column">
              <h3>Clothing</h3>
              <a href="#">Men Jeans</a>
              <a href="#">Women Jeggings</a>
              <a href="#">Trousers</a>
            </div>
            <div class="column">
              <h3>Grooming</h3>
              <a href="#">Perfumes</a>
              <a href="#">Deodrants</a>
              <a href="#">Hair Groom</a>
            </div>
            <div class="column">
              <h3>Footware</h3>
              <a href="#">Casual</a>
              <a href="#">Boots</a>
              <a href="#">Slippers</a>
            </div>
          </div>
        </div>
      </div>

      <div class="dropdown">
        <button class="dropbtn">Home & Furniture
          <i class="fa fa-caret-down"></i>
        </button>
        <div class="dropdown-content mega-dropdown">
          <div class="row">
            <div class="column">
              <h3>Kitchen</h3>
              <a href="#">Cook Ware</a>
              <a href="#">Electric Corner</a>
              <a href="#">Infrastructure</a>
            </div>
            <div class="column">
              <h3>Home Improvements</h3>
              <a href="#">Cleaners</a>
              <a href="#">Perfumes</a>
              <a href="#">Sanitizer</a>
            </div>
            <div class="column">
              <h3>Living Room</h3>
              <a href="#">Lightning</a>
              <a href="#">Dining Table</a>
              <a href="#">Jugs</a>
            </div>
          </div>
        </div>
      </div>

      <div class="dropdown">
        <button class="dropbtn">Sport & Fitness
          <i class="fa fa-caret-down"></i>
        </button>
        <div class="dropdown-content mega-dropdown">
          <div class="row">
            <div class="column">
              <h3>Sport</h3>
              <a href="#">Cricket</a>
              <a href="#">Football</a>
              <a href="#">Volley Ball</a>
            </div>
            <div class="column">
              <h3>Fitness</h3>
              <a href="#">Dumbells</a>
              <a href="#">Mini-Set</a>
              <a href="#">Powders</a>
            </div>
            <div class="column">
              <h3>Featured</h3>
              <a href="#">Suppliments</a>
              <a href="#">Gadgets</a>
              <a href="#">Kits</a>
            </div>
          </div>
        </div>
      </div>

      <div class="dropdown">
        <button class="dropbtn">Kids Store
          <i class="fa fa-caret-down"></i>
        </button>
        <div class="dropdown-content mega-dropdown">
          <div class="row">
            <div class="column">
              <h3>Toys</h3>
              <a href="#">Dolls</a>
              <a href="#">E-Gadgets</a>
              <a href="#">Tabs</a>
            </div>
            <div class="column">
              <h3>Books</h3>
              <a href="#">Story Books</a>
              <a href="#">Educational</a>
              <a href="#">Guidlines</a>
            </div>
            <div class="column">
              <h3>Care</h3>
              <a href="#">Body Care</a>
              <a href="#">Hair Care</a>
              <a href="#">Growth</a>
            </div>
          </div>
        </div>
      </div>

      <div class="dropdown">
        <button class="dropbtn">More
          <i class="fa fa-caret-down"></i>
        </button>
        <div class="dropdown-content">
          <a href="#">Notifications</a>
          <a href="#">Customer Care</a>
          <a href="#">Download App</a>
        </div>
      </div>

      <a href="#about">Coupons</a>

      <div class="dropdown responsive">
        <button class="dropbtn">Account
          <i class="fa fa-caret-down"></i>
        </button>
        <div class="dropdown-content">
          <a href="#">Profile</a>
          <a href="#">Orders</a>
          <a href="#">Wishlist</a>
          <a href="/supplierRegistration">Login</a>
        </div>
      </div>


      <div class="dropdown responsive">
        <button class="dropbtn"><i class="fa fa-shopping-cart"></i><span class="value">2</span>
        </button>
        <div class="dropdown-content">
          <a>
            <ul>
              <li>
                <img src="https://i.ibb.co/RpnQq12/01.webp" alt="Item">
              </li>
              <li>
                <span class="title">Samsung Galaxy POP</span>
                <span class="sub-title"><i class="fa fa-rupee"></i>5999</span>
              </li>
              <li><i class="fa fa-trash"></i></li>
            </ul>
            <ul>
              <li>
                <img src="https://i.ibb.co/RpnQq12/01.webp" alt="Item">
              </li>
              <li>
                <span class="title">Samsung Galaxy POP</span>
                <span class="sub-title">$ 5999</span>
              </li>
              <li><i class="fa fa-trash"></i></li>
            </ul>
            <button type="submit" class="btn1">CheckOut</button>
          </a>
        </div>
      </div>
      <a href="javascript:void(0);" style="font-size:15px;" class="icon" onclick="myFunction()">&#9776;</a>
    </div>
  </header>


  <div class="content-width">
    <!--CAROUSEL-->
    <div class="slideshow">
      <!-- Slideshow Items -->
      <div class="slideshow-items">
        <div v-for="(slide, index) in slides" :key="index" :class="{ item: true, active: index === currentSlideIndex }">
          <div class="item-image-container">
            <img class="item-image" :src="slide.image" />
          </div>
          <!-- Staggered Header Elements -->
          <div class="item-header">
            <span class="vertical-part"><b>{{ slide.header }}</b></span>
          </div>
          <!-- Staggered Description Elements -->
          <div class="item-description">
            <span class="vertical-part desc"><b>{{ slide.description }}</b></span>
          </div>
        </div>
      </div>
      <!-- Controls -->
      <div class="controls">
        <ul>
          <li v-for="(slide, index) in slides" :key="index" class="control" @click="goToSlide(index)"
            :class="{ active: index === currentSlideIndex }"></li>
        </ul>
      </div>
    </div>
  </div>

  <section class="section1">
    <div class="add-card"
      style="background: linear-gradient(rgba(1,1,1,.5), rgba(1,1,1,.5)), url(https://i.ibb.co/zmnBPpr/card1.jpg);">
      <section>
        <span class="title">New Year Bonanza</span>
        <span class="sub-title">Upto 25% Off On Washing Machines</span>
        <a href="" class="btn1">Grab Now</a>
      </section>
    </div>
    <div class="add-card"
      style="background: linear-gradient(rgba(1,1,1,.5), rgba(1,1,1,.5)), url(https://i.ibb.co/rH35598/card2.jpg);">
      <section>
        <span class="title">New Year Bonanza</span>
        <span class="sub-title">Upto 25% Off On Washing Machines</span>
        <a href="" class="btn1">Grab Now</a>
      </section>
    </div>
    <div class="add-card"
      style="background: linear-gradient(rgba(1,1,1,.5), rgba(1,1,1,.5)), url(https://i.ibb.co/b1pfh8c/card3.jpg);">
      <section>
        <span class="title">New Year Bonanza</span>
        <span class="sub-title">Upto 25% Off On Washing Machines</span>
        <a href="" class="btn1">Grab Now</a>
      </section>
    </div>
  </section>

  <h1 class="title section2-header">MOST POPULAR <span id="timer"><i class="fa fa-clock-o"></i></span></h1>
  <section class="section2">
    <div class="section2a">
    <div class="deal-card1">
      <img src="../assets/dufflebags.jpg" alt="Deals">
        <span class="tag-2"><i class="fa fa-times"></i> Sold Out</span>
        <span class="title">Travel Bag </span>
        <span class="title0" style="font-weight: bold; font-family:'Poppins'">KES 3,000
      </span>
        <span class="sub-title" >Lorem ipsum dolor sit amet, consectetur adipiscing elit.</span> 
    </div>

    <div class="deal-card2">
      <img src="../assets/speaker.jpg" alt="Deals">
      <span class="tag-1"><i class="fa fa-check-circle-o"></i> Available</span>
      <span class="title" >Bluetooth Speakers</span>
      <span class="title1" style="font-weight: bold; font-family:'Poppins'">KES 50,000</span>
      <span class="sub-title">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</span>   
    </div>

    <div class="deal-card3">
      <img src="../assets/iphone.jpg" alt="Deals">
      <span class="tag-1"><i class="fa fa-check-circle-o"></i> Available</span>
      <span class="title" >Iphone 12 Pro Max</span>
      <span class="title2" style="font-weight: bold; font-family:'Poppins'">KES 120,000
      </span>
      <span class="sub-title" >Lorem ipsum dolor sit amet, consectetur adipiscing elit.</span>
    </div>

    <div class="deal-card4">
      <img src="../assets/paints.jpg" alt="Deals">
     
      <span class="tag-1"><i class="fa fa-check-circle-o"></i> Available</span>
      <span class="title" >Paint</span> 
      <span class="title3" style="font-weight: bold; font-family:'Poppins'">KES 8,000
      </span>
      <span class="sub-title">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</span>
     
    </div></div>
<div class=" section2b">
    <div class="deal-card5">
      <img src="../assets/shoes.jpg" alt="Deals">
      <span class="tag-1"><i class="fa fa-check-circle-o"></i> Available</span>
      <span class="title">Sneakers</span>
      <span class="title4" style="font-weight: bold; font-family:'Poppins' " >KES 2,200
      </span>
      <span class="sub-title">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</span>
</div>  
    </div>

    <div class="deal-card6">
      <img src="../assets/chain.jpg" alt="Deals">
      <span class="tag-1"><i class="fa fa-check-circle-o"></i> Available</span>
      <span class="title" >Chain</span>
      <span class="title5" style="font-weight: bold; font-family:'Poppins' ">KES 1,200
      </span>
      <span class="sub-title">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</span>
    

    </div>
    <div class="deal-card7">
      <img src="../assets/kit.jpg" alt="Deals">
      <span class="tag-1"><i class="fa fa-check-circle-o"></i> Available</span>
      <span class="title">Kit</span>
      <span class="title6" style="font-weight: bold; font-family:'Poppins' " >KES 5,700
      </span>
      <span class="sub-title" >Lorem ipsum dolor sit amet, consectetur adipiscing elit.</span>
      

    </div>
    <div class="deal-card8">
      <img src="../assets/watch.jpg" alt="Deals">
      <span class="tag-1"><i class="fa fa-check-circle-o"></i> Available</span>
      <span class="title">Watch</span>
      <span class="title7" style="font-weight: bold; font-family:'Poppins' " >KES 10,500
      </span>
      <span class="sub-title" >Lorem ipsum dolor sit amet, consectetur adipiscing elit.</span>
     

  </div>


  </section>

   


  <!--ADDS-->
  <center>
    <div class="Advertisement">
      <img class="myAdds" src="https://i.ibb.co/r5f5GgH/1.png" style="width:100%">
      <img class="myAdds" src="https://i.ibb.co/bN4XFXp/2.png" style="width:100%">
      <img class="myAdds" src="https://i.ibb.co/nfpZj9p/3.png" style="width:100%">
    </div>
  </center>




  <section class="section6">
    <table>
      <tr>
        <!-- This is an image of the app -->
        <td>
          <img src="../assets/feitianf29.jpg" alt="APP" style="background: orange;">
        </td>
        <td>
          <span class="title">Download MSMS App Now</span>
          <span class="sub-title">Fast, Simple & Delightful. All it takes is 15 seconds to Download.</span>
          <a href="#" class="btn1"><i class="fa fa-android"></i> DOWNLOAD</a>
        </td>
      </tr>
    </table>
  </section>



  <footer>
    <div class="footer">
      <ul>
        <li>MSMS</li>
        <li>
          <select>
            <option value="english">English</option>
            <option value="chinese">Chinese</option>
            <option value="deutsch">Deutsch</option>
            <option value="hindi">Hindi</option>
            <option value="portuguese">Portuguese</option>
            <option value="spanish">Spanish</option>
          </select>
        </li>
        <li>
          <select>
            <option value="Dollar">USD: US-Dollar</option>
          </select>
        </li>
      </ul>

      <ul>
        <li class="title">OTHER LINKS</li>
        <li>Contact Us</li>
        <li>Privacy Policy</li>
        <li>Terms & Conditions</li>
        <li>Tickets</li>
        <li>Customer Service</li>
        <li>Our App</li>
      </ul>

      <ul>
        <li class="title">SHORTCUT</li>
        <li>Electronics</li>
        <li>Men & Women</li>
        <li>House Hold</li>
        <li>Sport & Fitness</li>
        <li>Books</li>
        <li>Kids Corner</li>
      </ul>

      <ul>
        <li class="title">LET HELP YOU</li>
        <li>Covid-19</li>
        <li>Your Account</li>
        <li>Shipping Rates</li>
        <li>Replacement</li>
        <li>Help</li>
        <li>
          <a href="#"><i class="fa fa-facebook"></i></a>
          <a href="#"><i class="fa fa-instagram"></i></a>
          <a href="#"><i class="fa fa-twitter"></i></a>
          <a href="#"><i class="fa fa-youtube"></i></a>
        </li>
      </ul>
    </div>
    <div class="sub-footer">
      <em>MSMS</em> Copyright © 2021 MSMS - All rights reserved || Designed By: Cynthia & Rosebell
    </div>
  </footer>
  <div id="id01" class="modal">

    <section class="modal-content animate" action="/action_page.php" method="post">
      <div class="imgcontainer">
        <span onclick="document.getElementById('id01').style.display='none'" class="close"
          title="Close Modal">&times;</span>
      </div>
    </section>
  </div>






</template>
<script>
export default {
  name: 'DashboardPage',
  data() {
    return {
      showModal: false,
      slides: [
        {
          image: "https://images.pexels.com/photos/1456706/pexels-photo-1456706.jpeg?cs=srgb&dl=pexels-ray-piedra-1456706.jpg&fm=jpg&_gl=1*9kspzy*_ga*ODQzMDk4NjQwLjE3MDgwNjk5NTU.*_ga_8JE65Q40S6*MTcxMjIyNjc2NS4xNC4xLjE3MTIyMjc4NjQuMC4wLjA.",
          header: "Striking Deals On Men's FootWear",
          description: "Offers you cannot miss! upto 80% off",
        },
        {
          image: "https://i.ibb.co/fQrPPpR/slide2.jpg",
          header: "Top Deals On Cook Ware",
          description: "Upto 10% off on cart value more than ksh.5000",
        },
        {
          image: "https://i.ibb.co/GJ9C3kV/slide3.jpg",
          header: "ShopNow On MSMS",
          description:
            "Shop bags at an afforable price for better  shopping experience.",

        },
      ],
      currentSlideIndex: 0,
      intervalDuration: 5000, // Duration in milliseconds
    };
  },
  mounted() {
    this.startSlideshow();
    // Set modal event listener
    document.addEventListener("keydown", this.closeModalOnEscape);
    window.onclick = this.closeModalOnClickOutside;
  },
  beforeUnmount() {
    // Remove modal event listener
    document.removeEventListener("keydown", this.closeModalOnEscape);
  },
  methods: {
    startSlideshow() {
      setInterval(this.nextSlide, this.intervalDuration);
    },
    nextSlide() {
      this.currentSlideIndex =
        (this.currentSlideIndex + 1) % this.slides.length;
    },
    goToSlide(index) {
      this.currentSlideIndex = index;
    },
    closeModalOnEscape(event) {
      const modal = document.getElementById("id01");
      if (event.key === "Escape" && modal.style.display === "block") {
        modal.style.display = "none";
      }
    },
    closeModalOnClickOutside(event) {
      const modal = document.getElementById("id01");
      if (event.target === modal) {
        modal.style.display = "none";
      }
    },
    scrollright(section3) {
      var container = document.getElementById(section3);
      this.sideScroll(container, 'right', 25, 300, 10);
    },
    scrollleft(section3) {
      var container = document.getElementById(section3);
      this.sideScroll(container, 'left', 25, 300, 10);
    },
    sideScroll(element, direction, speed, distance, step) {
      var scrollAmount = 0;
      var slideTimer = setInterval(function() {
        if (direction == 'left') {
          element.scrollLeft -= step;
        } else {
          element.scrollLeft += step;
        }
        scrollAmount += step;
        if (scrollAmount >= distance) {
          clearInterval(slideTimer);
        }
      }, speed);
    }
  }


  };




</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans&display=swap');





html {
  scroll-behavior: smooth;
}

body {

  margin: 0;
  overflow-x: hidden;
  font-family: 'Noto sans', sans-serif;
}

.card {
  display: none;
  position: absolute;
  top: 100%;
  left: 0;
  width: 100%;
  background-color: #f9f9f9;
  box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.2);
  z-index: 1;
}

.card-content {
  padding: 12px 16px;
}

.dropdown-content .login-signup:hover+.card {
  display: block;
}

.sub-menu-alt {
  display: none;
  position: absolute;
  top: 0;
  left: calc(100% + 10px);
  /* Adjust the offset as needed */
  background-color: #fff;
  min-width: 160px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  z-index: 1;
}

.login-signup:hover .sub-menu-alt {
  display: block;
}

:root {
  scrollbar-color: rgb(210, 210, 210) rgb(46, 54, 69) !important;
  scrollbar-width: thin !important;
}

.responsive {
  display: none;
}

em {
  font-style: normal;
  color: #eebf4d;
}

.title {
  font-size: 2em;
  display: block;
  font-family: 'Montserrat', sans-serif;
  font-style: bold;
}

.sub-title {
  font-size: 1em;
  display: block;
  font-family: 'noto sans', sans-serif;
}

.btn1 {
  background: #1e1e1e;
  box-shadow: 0px 6px 16px -6px rgba(1, 1, 1, 0.5);
  color: #fff;
  padding: 5px 10px;
  transition: 0.5s;
  border: 0;
  outline: none;
  display: block;
  width: 100px;
  text-align: center;
  border-radius: none;
  margin: 15px 0px;
}

.btn1:hover {
  background: #fff;
  color: #000;
  border: 1px solid #1e1e1e;
}

.btn2 {
  color: green;
  display: block;
}

.soldout {
  background: gray;
  box-shadow: 0px 6px 16px -6px rgba(1, 1, 1, 0.5);
  color: #fff;
  padding: 5px 10px;
  transition: 0.5s;
  border: 0;
  outline: none;
  display: block;
  width: 100px;
  text-align: center;
  border-radius: 20px;
  margin: 15px 0px;
}

.soldout:hover {
  background: none;
  border: none;
}

a {
  text-decoration: none;
}

li {
  list-style: none;
}

.slideshow {
  position: relative;
  background-position: center center;
  max-width: 100%;
  overflow: hidden;
}

.slideshow-items {
  display: flex;
  transition: transform 0.5s ease;
}

.item {
  flex: 0 0 100%;
}

.item-image {
  max-width: 100%;
  height: auto;

}

.controls ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

.control {
  width: 10px;
  height: 10px;
  border-radius: 50%;
  background-color: #ccc;
  display: inline-block;
  margin-right: 5px;
  cursor: pointer;
}

.control.active {
  background-color: #000;
}




/*HEADER*/
header {
  width: 100%;
  box-shadow: 0px 6px 16px -6px rgba(1, 1, 1, 0.5);
  position: fixed;
  top: 0;
  z-index: 9;
}

.menu {
  width: 100%;
  background: #000;
  color: #fff;
  padding: 10px;
}

.menu table {
  width: 100%;
}

.menu table td {
  width: 33%;
}

.logo-container {
  margin-left: 190px;

}

.menu .logo {
  width: 110px;
  height: 120px;
}

.menu input {
  padding: 10px;
  outline: none;
  border: 0;
  width: 80%;
}

.menu button {
  background: #eebf4d;
  color: #fff;
  padding: 10px;
  outline: none;
  border: 0;
}

@media (max-width:900px) {
  .menu input {
    width: 60%;
  }
}

@media (max-width:600px) {
  .menu table td {
    width: 50%;
  }

  .menu table td:nth-child(3) {
    display: none;
  }

  .menu input {
    width: 65%;
  }
}


.menu span {
  float: right;
  margin-right: 15%;
}

.menu .dropdown {
  float: left;
  overflow: hidden;
}

.menu .dropdown .dropbtn {
  font-size: 16px;
  border: none;
  outline: none;
  color: #fff;
  padding: 14px 16px;
  background-color: inherit;
  font-family: inherit;
  margin: 0;
}

.value {
  text-align: center;
  padding: 2px;
  color: #fff;
  background: red;
  position: relative;
  top: -30px;
  left: 10px;
  z-index: 1;
  border-radius: 50%;
  width: 15px;
  height: 15px;
  font-size: 10px;
  transition: 0.5s;
}

.menu .navbar a:hover,
.menu .dropdown:hover .dropbtn {
  background-color: #eebf4d;
}

.menu .dropdown .cart:hover {
  background: none;
  color: #eebf4d;
}

.dropdown-content {
  border-top: 2px solid #eebf4d;
  display: none;
  position: absolute;
  background-color: #fff;
  min-width: 260px;
  box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
  z-index: 1;
}

.cart-content {
  min-width: 180px;
  margin-bottom: 20px;
  position: absolute;
  right: 0;
}

.cart-content ul:hover {
  background: #fff;
}

.cart-content ul {
  width: 100%;
  padding: 10px;
  border-bottom: 1px solid rgba(1, 1, 1, 0.1);
}

.cart-content ul li {
  display: inline-block;
}

.cart-content ul li img {
  width: 100%;
  height: 50px;
}

.cart-content ul li:nth-child(1) {
  width: 30%;
}

.cart-content ul li:nth-child(2) {
  width: 50%;
}

.cart-content ul li:nth-child(3) {
  width: 10%;
}

.cart-content ul li:nth-child(3) i {
  position: relative;
  top: -15px;
  transition: 0.5s;
}

.cart-content ul li:nth-child(3) i:hover {
  color: red;
}

.cart-content ul li .title {
  font-size: 0.7em;
  display: inline-block;
}

.cart-content ul li .sub-title {
  font-size: 0.6em;
  color: gray;
  display: inline-block;
}

.dropdown-content a {
  float: none;
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  text-align: left;
}

.dropdown-content a:hover {
  background-color: #ddd;
}

.dropdown:hover .dropdown-content {
  display: block;
}

.topnav {
  overflow-x: hidden;
  overflow-y: auto;
  background-color: #fff;
  padding: 0px 188px 0px 188px
}

.topnav a {
  float: left;
  display: block;
  color: #1e1e1e;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 15px;
  margin: 0px 20px;
}

.topnav .icon {
  display: none;
}

.dropdown {
  float: left;
  overflow: hidden;
}

.dropdown .dropbtn {
  font-size: 15px;
  border: none;
  outline: none;
  color: #1e1e1e;
  padding: 14px 16px;
  background-color: inherit;
  font-family: inherit;
  margin: 0px 30px;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #fff;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
  z-index: 1;
  overflow-y: auto;
  scrollbar-width: none;
  scroll-behavior: smooth;
}

.dropdown-content a {
  float: none;
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  text-align: left;
}

.topnav a:hover,
.dropdown:hover .dropbtn {
  background-color: #555;
  color: white;
}

.dropdown-content a:hover {
  background-color: #ddd;
  color: black;
}

.dropdown:hover .dropdown-content {
  display: block;
}

@media (max-width:1000px) {

  .dropdown .dropbtn,
  .topnav a {
    margin: 0px 10px;
    font-size: 14px;
    padding: 14px 8px;
  }
}

@media screen and (max-width: 600px) {

  .topnav a:not(:first-child),
  .dropdown .dropbtn {
    display: none;
  }

  .topnav a.icon {
    float: right;
    display: block;
  }

  .value {
    text-align: center;
    padding: 2px;
    color: #fff;
    background: red;
    position: relative;
    top: -10px;
    left: 5px;
    z-index: 1;
    border-radius: 50%;
    width: 20px;
    height: 10px;
    font-size: 10px;
    transition: 0.5s;
  }
}

@media screen and (max-width: 600px) {
  .topnav {
    padding: 0px 0%;
  }

  .topnav.responsive {
    position: relative;
  }

  .topnav.responsive .icon {
    position: absolute;
    right: 0;
    top: 0;
  }

  .topnav a,
  .dropdown .dropbtn {
    margin: 0px 0px;
  }

  .topnav.responsive a {
    float: none;
    display: block;
    text-align: left;
  }

  .topnav.responsive .dropdown {
    float: none;
  }

  .topnav.responsive .dropdown-content {
    position: relative;
  }

  .topnav.responsive .dropdown .dropbtn {
    display: block;
    width: 100%;
    text-align: left;
  }
}

.column {
  float: left;
  width: 31.33%;
  background-color: #fff;
  height: 250px;
  padding: 1%;
}

.column1 .column {
  float: left;
  width: 23%;
  background-color: #fff;
  height: 250px;
  padding: 1%;
}

.column a {
  float: none;
  color: black;
  padding: 6px;
  text-decoration: none;
  display: block;
  text-align: left;
}

.column a:hover {
  background-color: #ddd;
}

.column a:before {
  content: "\f0da ";
  font-family: "FontAwesome";
  color: #eebf4d;
  margin: 0px 2px;
}

.column h3:after {
  content: "\f0d7 ";
  font-family: "FontAwesome";
  color: #eebf4d;
  margin: 0px 2px;
}

.mega-dropdown {
  width: 100%;
  float: left;
  position: absolute;
  left: 0;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive layout - makes the three columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 90%;
    height: auto;
    padding: 3%;
  }

  .column1 .column {
    float: left;
    width: 90%;
    background-color: #fff;
    height: auto;
    padding: 3%;
  }

  .responsive {
    display: block;

  }
}





/*CAROUSEL*/
.content-width {
  width: 100%;
  height: 70vh;
  margin: 0 auto;
  margin-top: 10%;
}

.slideshow {
  position: relative;
  width: 100%;
  height: 70vh;
  display: flex;
  flex-direction: column;
  justify-content: space-around;
}

.slideshow-items {
  position: relative;
  width: 100%;
  height: 70vh;
}

.item {
  position: absolute;
  width: 100%;
  height: auto;
}

.item-image-container {
  position: relative;
  justify-content: center;
  width: 100%;
  height: 100%;
  background-position: top center;
}

.item-image-container::before {
  content: '';
  position: absolute;
  top: -1px;
  left: 0;
  width: 101%;
  height: 90vh;
  background: #22222A;
  opacity: 0;

}

.item-image {
  position: relative;
  width: 100%;
  height: 100%;
  opacity: 0;
  display: block;
  /* transition: property name | duration | timing-function | delay  */
  transition: opacity .3s ease-out .45s;
}

.item.active .item-image {
  opacity: 1;
}

.item.active .item-image-container::before {
  opacity: .0;
}

.item-description {
  position: absolute;
  top: 50vh;
  left: 1.8%;
  width: 50%;
  color: #000;
  padding-right: 4%;
  line-height: 1.8;
  font-family: 'Exo 2', sans-serif;
}

/* Staggered Vertical Items ------------------------------------------------------*/
.item-header {
  position: absolute;
  top: 40vh;
  left: 1.8%;
}

.item-header .vertical-part {
  margin: 0 -4px;
  -webkit-font-smoothing: auto;
  font-size: 2vw;
  color: #000;
  font-family: 'Yusei Magic', sans-serif;
}

.desc b {
  font-family: 'Titillium Web', sans-serif;
}

@media (max-width:600px) {
  .item-header .vertical-part {
    font-size: 3vw;
  }

  .content-width {
    height: 50vh;
  }

  .slideshow {
    position: relative;
    width: 100%;
    min-height: 50vh;
    display: flex;
    flex-direction: column;
    justify-content: space-around;

  }

  .slideshow-items {
    min-height: 60vh;
    background-position: center center;
  }

  .item-image-container {
    height: 60vh;
  }

  .item-image-container::before {
    height: 60vh;
  }

  .item-description {
    position: absolute;
    top: 40vh;
    width: 90%;
    font-size: 14px;
  }

  .item-header {
    position: absolute;
    top: 30vh;
  }
}

.vertical-part {
  overflow: hidden;
  display: inline-block;
}

.vertical-part b {
  display: inline-block;
  transform: translateY(100%);
}

.item-header .vertical-part b {
  transition: .5s;
}

.item-description .vertical-part b {
  transition: .21s;
}

.item.active .item-header .vertical-part b {
  transform: translateY(0);
}

.item.active .item-description .vertical-part b {
  transform: translateY(0);
}

/* Controls ----------------------------------------------------------------------*/
.controls {
  position: relative;
  text-align: right;
  display: block;
}

.controls ul {
  list-style: none;
  float: left;
}

.controls ul li {
  display: inline-block;
  width: 10px;
  height: 10px;
  margin: 3px;
  background: #bdbdd5;
  ;
  cursor: pointer;
}

.controls ul li.active {
  background: #6a6a77;
  ;
}


@media (max-width:600px) {
  .content-width {
    margin-top: 15%;
  }

  .controls ul {
    list-style: none;
    position: absolute;
    top: -20vh;
  }
}






/*SECTION1*/
.section1 {
  width: 100%;
  margin-right: auto;
  margin-left: auto;
  padding: 20px;
  overflow-x: hidden;
  scrollbar-width: none;
  scroll-behavior: smooth;
}

.section1 .add-card {
  padding: 20px;
  border-radius: 5px;
  box-shadow: 0px 6px 16px -6px rgba(1, 1, 1, 0.5);
  width: 26%;
  margin: 2%;
  display: inline-block;
  height: 250px;
  background-size: cover;
  background: linear-gradient(rgba(1, 1, 1, .5), rgba(1, 1, 1, .5));
}

.section1 section {
  color: #fff;
  padding: 30px 0px;
}

.section1 .btn1:hover {
  background: transparent;
  color: #fff;
  border: 1px solid #fff;
}

.section1 .title {
  color: #eebf4d;
}

@media (max-width:1280px) {
  .section1 .add-card {
    min-width: 20%;
    margin: 1%;
  }
}

@media (max-width:600px) {
  .section1 {
    position: relative;
    display: flex;
    align-items: left;
    justify-content: left;
    margin-top: 10vh;
  }

  .section1 .add-card {
    min-width: 80%;
    height: 200px;
  }
}





/*SECTION2*/
/* General Section Styles */
.section2a, .section2b {
  column-width: -300px;
}

.section2 {
  width: 70%;
  padding: 0 290px 290px 290px; /* Uniform padding */
  display: flex;
  flex-wrap: wrap;
  align-items: flex-start;
  justify-content: flex-start;
  overflow-x: hidden;
  scrollbar-width: none;
  scroll-behavior: smooth;
  margin-top: 0;
  text-align: left; /* Ensure text is left-aligned */
}

.section2-header {
  font-size: 1.5em;
  padding: 20px;
  margin-top: 10vh;
}

#timer {
  font-size: 16px;
  color: gray;
}

/* Deal Card Styles */
.section2 .deal-card1,
.section2 .deal-card2,
.section2 .deal-card3,
.section2 .deal-card4,
.section2 .deal-card5,
.section2 .deal-card6,
.section2 .deal-card7,
.section2 .deal-card8 {
  display: inline-block;
  padding: 30px 30px 50px 30px;
  height: 310px;
  width: 250px;
  position: relative;
  box-shadow: 0px 6px 16px -6px rgba(1, 1, 1, 0.5);
  transition: 0.5s;
  margin: 10px;
  text-align: left; /* Ensure text is left-aligned */
}

.section2 .deal-card1 img,
.section2 .deal-card2 img,
.section2 .deal-card3 img,
.section2 .deal-card4 img,
.section2 .deal-card5 img,
.section2 .deal-card6 img,
.section2 .deal-card7 img,
.section2 .deal-card8 img {
  width: 100%;
  height: 200px;
  transition: 0.5s;
}

.section2 .deal-card1:hover img,
.section2 .deal-card2:hover img,
.section2 .deal-card3:hover img,
.section2 .deal-card4:hover img,
.section2 .deal-card5:hover img,
.section2 .deal-card6:hover img,
.section2 .deal-card7:hover img,
.section2 .deal-card8:hover img {
  transform: scale(1.1);
}

/* Deal Card Tags and Discount Styles */
.section2 .deal-card1 .discount,
.section2 .deal-card2 .discount,
.section2 .deal-card3 .discount,
.section2 .deal-card4 .discount,
.section2 .deal-card5 .discount,
.section2 .deal-card6 .discount,
.section2 .deal-card7 .discount,
.section2 .deal-card8 .discount {
  position: absolute;
  left: 20px;
}

.section2 .deal-card1 .tag-1,
.section2 .deal-card2 .tag-1,
.section2 .deal-card3 .tag-1,
.section2 .deal-card4 .tag-1,
.section2 .deal-card5 .tag-1,
.section2 .deal-card6 .tag-1,
.section2 .deal-card7 .tag-1,
.section2 .deal-card8 .tag-1 {
  background: green;
  padding: 5px 20px;
  text-align: center;
  color: #fff;
  position: absolute;
  right: 20px;
  font-size: 13px;
  z-index: 1;
  top: 20px;
}

.section2 .deal-card1 .tag-2,
.section2 .deal-card2 .tag-2,
.section2 .deal-card3 .tag-2,
.section2 .deal-card4 .tag-2,
.section2 .deal-card5 .tag-2,
.section2 .deal-card6 .tag-2,
.section2 .deal-card7 .tag-2,
.section2 .deal-card8 .tag-2 {
  background: red;
  padding: 5px 20px;
  text-align: center;
  color: #fff;
  position: absolute;
  right: 20px;
  font-size: 13px;
  z-index: 1;
  top: 20px;
}

/* Card Titles and Subtitles */
.section2 .deal-card1 .title,
.section2 .deal-card2 .title,
.section2 .deal-card3 .title,
.section2 .deal-card4 .title,
.section2 .deal-card5 .title,
.section2 .deal-card6 .title,
.section2 .deal-card7 .title,
.section2 .deal-card8 .title {
  font-size: 1px;
  font-weight: bold;
  padding: 20px 0px 10px;
}

.section2 .deal-card1 .sub-title,
.section2 .deal-card2 .sub-title,
.section2 .deal-card3 .sub-title,
.section2 .deal-card4 .sub-title,
.section2 .deal-card5 .sub-title,
.section2 .deal-card6 .sub-title,
.section2 .deal-card7 .sub-title,
.section2 .deal-card8 .sub-title {
  
  font-size: 14px;
  color:#000;
  position: relative;
  padding: 10px 0px;

}

/* Button Styles */
.section2 .deal-card2 .title0
.section2 .deal-card2 .title1
.section2 .deal-card3 .title2 
.section2 .deal-card4 .title3
.section2 .deal-card5 .title4 
.section2 .deal-card6 .title5
.section2 .deal-card7 .title6 
.section2 .deal-card8 .title7 {
  font-size: 18px;
  font-family: 'Poppins';
  font-weight: bold;
  color: black;
  width: 100%;
  position: relative;

 
}


/* Advertise Card Styles */
.section2 .advertise-card {
  background-image: url("https://i.ibb.co/VMHGgsk/add-card.png");
  background-size: cover;
  background-position: center;
  height: 330px;
  position: relative;
  top: 50px;
  width: 550px;
  border-radius: 5px;
}

/* Media Queries */
@media (max-width: 600px) {
  .section2 .title {
    display: block;
    min-width: 90%;
    height: 10vh;
  }

  .section2 .advertise-card {
    display: none;
  }

  .section2 {
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
  }

  .section2 .deal-card {
    min-width: 80%;
    height: 330px;
  }
}

@media (max-width: 200px) {
  .section2 .title {
    display: block;
    min-width: 200%;
    height: 10vh;
  }

  .section2 .advertise-card {
    display: none;
  }

  .section2 {
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
  }
}









/*ADDS*/
.Advertisement {
  width: 60%;
  margin-left: auto;
  margin-right: auto;
  margin: 10% 0%;
}

.Advertisement .myAdds {
  height: 150px;
  display: none;
}




/*SECTION6*/
.section6 {
  width: 100%;
  background: #eebf4d;
  position: relative;
}

.section6 table {
  width: 90%;
}

.section6 table td {
  width: 40%;
  padding: 30px;
}

.section6 table td img {
  width: 400px;
  height: 50vh;
  position: absolute;
  bottom: 0;
  margin-right: auto;
  margin-left: auto;
  pointer-events: none;
}

@media (max-width:600px) {
  .Advertisement {
    width: 90%;
  }

  .Advertisement .myAdds {
    display: none;
  }


  .section6 table td {
    padding: 10px;
  }

  .section6 table td img {
    width: 40%;
    height: 40vh;
  }

  .section6 .title {
    font-size: 1.2em;
  }

  .section6 .sub-title {
    font-size: 0.8em;
  }
}



/*FOOTER*/
.footer {
  width: 100%;
  padding: 30px 0px;
  background: #000;
}

.footer ul {
  width: 20%;
  padding: 2%;
  display: inline-block;
  font-family: 'Play', sans-serif;
}

.footer ul .title {
  color: #fff;
  font-size: 16px;
  cursor: default;
}

.footer ul li {
  color: gray;
  font-size: 13px;
  padding: 5px 0px;
  cursor: pointer;
  transition: 0.5s;
}

.footer ul:not(:first-child) li:hover {
  color: #f8a01a;
}

.footer ul li a {
  color: gray;
  transition: 0.5s;
  font-size: 23px;
  margin: 0px 10px;
}

.footer ul li a:hover {
  color: #fff;
}

.footer ul li input {
  padding: 10px 10px;
  border: 0;
  outline: none;
  width: 100%;
}

.footer ul li select {
  padding: 5px;
  background: #fff;
  border: 0;
  outline: none;
  width: 60%;
}

.footer ul li .btn1 {
  padding: 5px 10px;
  font-size: 14px;
  width: 50%;
  height: 50px;
}

.sub-footer {
  text-align: center;
  color: gray;
  font-size: 13px;
  background: #1e1e1e;
  padding: 5px 0px;
}

@media (max-width:600px) {
  .footer ul {
    width: 90%;
    display: block;
  }

  .footer ul:nth-child(2),
  .footer ul:nth-child(3) {
    width: 45%;
    display: inline-block;
  }

  .footer ul li input {
    width: 70%;
  }
}









/*ADDITIONAL*/
/* Center the image and position the close button */
.imgcontainer {
  text-align: center;
  margin: 24px 0 12px 0;
  position: relative;
}

.container {
  padding: 16px;
}

span.psw {
  float: right;
  padding-top: 16px;
}

/* The Modal (background) */
.modal {
  display: none;
  /* Hidden by default */
  position: fixed;
  /* Stay in place */
  z-index: 999;
  /* Sit on top */
  left: 0;
  top: 0;
  width: 100%;
  /* Full width */
  height: 100%;
  /* Full height */
  overflow: auto;
  /* Enable scroll if needed */
  background-color: rgb(0, 0, 0);
  /* Fallback color */
  background-color: rgba(0, 0, 0, 0.4);
  /* Black w/ opacity */
  padding-top: 60px;
}

/* Modal Content/Box */
.modal-content {
  background-image: url("https://i.ibb.co/nmFGXfD/banner.png");
  background-size: cover;
  background-position: center;
  margin: 5% auto 5% auto;
  /* 5% from the top, 15% from the bottom and centered */
  border: 1px solid #888;
  width: 80%;
  height: 70vh;
  /* Could be more or less, depending on screen size */
}

/* The Close Button (x) */
.close {
  position: absolute;
  right: 25px;
  top: 0;
  color: #000;
  font-size: 35px;
  font-weight: bold;
}

.close:hover,
.close:focus {
  color: #eebf4d;
  cursor: pointer;
}

/* Add Zoom Animation */
.animate {
  -webkit-animation: animatezoom 0.6s;
  animation: animatezoom 0.6s
}

@-webkit-keyframes animatezoom {
  from {
    -webkit-transform: scale(0)
  }

  to {
    -webkit-transform: scale(1)
  }
}

@keyframes animatezoom {
  from {
    transform: scale(0)
  }

  to {
    transform: scale(1)
  }
}

/* Change styles for span and cancel button on extra small screens */
@media screen and (max-width: 300px) {
  span.psw {
    display: block;
    float: none;
  }

  .cancelbtn {
    width: 100%;
  }
}



.credits {
  background: #1e1e1e;
  padding: 10px;
  position: fixed;
  bottom: 20px;
  right: 0;
  color: gray;
  font-size: 12px;
  z-index: 9999;
}

.credits a {
  text-decoration: none;
  color: gray;
}
</style>