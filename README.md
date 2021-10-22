<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
    <link href="https://unpkg.com/tailwindcss@^2/dist/tailwind.min.css" rel="stylesheet">
   <link rel="stylesheet" href="Css for af.css">
   <link rel="stylesheet" href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css" integrity="sha384-AYmEC3Yw5cVb3ZcuHtOA93w35dYTsvhLPVnYs9eStHfGJvOvKxVfELGroGkvsg+p" crossorigin="anonymous"/>

	<title></title>
</head>
<body>
    <header class="text-gray-600 body-font">
        <div class="container mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center">
          <a class="flex title-font font-medium items-center ">
             <img src="https://www.collegenp.com/uploads/2020/04/Paragon-Public-School.png" id="1" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-20 h-18 text-white p-2 bg-green-500 rounded-full" viewBox="0 0 24 24">
              <path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"></path>
            </svg>
            <span class="white">Paragon Public School </span>
          </a>
          <nav class="md:mr-auto md:ml-4 md:py-1 md:pl-4 md:border-l md:border-gray-400	flex flex-wrap items-center text-base justify-center">
            <a href="PPS home.html" class="red">Home</a>
            <a href="Contact Us.html" class="red">Contact Us</a>
            <a href=  "Our Team.html" class="red">Our Team</a>
            <a href = "Af.html" class="red">Admission</a>
          </nav>
          <button class="inline-flex items-center bg-gray-100 border-0 py-1 px-3 focus:outline-none hover:bg-gray-200 rounded text-base mt-4 md:mt-0">Enroll now
            <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-4 h-4 ml-1" viewBox="0 0 24 24">
              <path d="M5 12h14M12 5l7 7-7 7"></path>
            </svg>
          </button>
        </div>
      </header>
      <div class="all">
        <div class="container-1 px-5 py-24 mx-auto">
          <div class="relative mb-4">
            <div class="form">
              <fieldset>
              <h1 class="h1"><u>Child's personal information</u></h1>
            
          <div class="ame">
            
            <label >Name</label><br>
            <i class="fas fa-user-tie fa-2x" id="d" aria-hidden="true"></i>
            <input type="text" name="name"  placeholder="Name*" required class="ad">
            </div>
            
            <div class="relative mb-4">
             
              <div class="mail">
                
                <label>Email</label><br>
                <i class="fas fa-envelope-open-text fa-2x"id="is"></i>
                <input type="email" name="Email" placeholder="Email*" required class="ad">
              </div>
            </div>
          
          <div class="relative mb-4">
             
            <div class="gender">
              
              <label>Gender</label><br>
<select id="dd">
  <div class="male">
  <i class="fas fa-male" id="cd" aria-hidden="true"></i>
  <option value="fas fa-male"id="cd">&#xf183;Male</option></div>
  <option value="fas fa-male" aria-hidden="true " id="cd">&#xf182;Female</option>
  <option value="fas fa-transgender"id="cd">&#xf224;Transgender</option>
  </div>
</select><br>
<label>Grade</label><br>
<select id="dd">
  <option>Nursery</option>
  <option>LKG</option>
<option>UKG</option>
<option>One</option>
<option>Two</option>
<option>Three</option>
<option>Four</option>
<option>Five</option>
<option>Six</option>
<option>Seven</option>
<option>Eight</option>
<option>Nine</option>
<option>Ten

</option>
</select>
</fieldset>
<div class="all">
  <div class="container-1 px-0 py-10 mx-auto">
    <div class="relative mb-1">
      <div class="form">
        <fieldset>
        <h1 class="h1"><u>Child's School Information</u></h1>
        <h2 class="h2"><b>Child's school experieince including the present institution</b></h2><br>
      
    <div class="ame">
      
      <label >Name of School</label><br>
      <i class="fas fa-graduation-cap fa-2x" id="af" aria-hidden="true"></i>
  
      <input type="text" name="name"  placeholder="School Name*" required class="ad">
      </div><br>

      
     
    <div class="relative mb-4">
       
      <div class="gender">
        
        
<label>Grade:</label>
<select id="bd">
<option>Nursery</option>
<option>LKG</option>
<option>UKG</option>
<option>One</option>
<option>Two</option>
<option>Three</option>
<option>Four</option>
<option>Five</option>
<option>Six</option>
<option>Seven</option>
<option>Eight</option>
<option>Nine</option>
<option>Ten

</option>
</select>

               <label>Year</label>
               <input type="number" maxlength="10" placeholder="From" id="rd" required>
<input type="number" max="10" placeholder="To" id="td"required>
               </div>
             </div>
            <div class="relative mb-4            ">
              <div class="address">
                <label>Address</label>
                <i class="far fa-address-card  fa-2x" aria-hidden="true" id="ff"></i>
                <input type="text" placeholder="Your current address*" required class="ad
              ">
              </div>
            </div><br>
            <div class="relative mb-4">
              <div class="Telephone">
                <label> Telephone Number : </label><br>
                <i class="fas fa-phone-square-alt fa-2x" aria-hidden="true" id="bf"></i>
                <input type="number" placeholder="Your telephone number*" maxlength="10" required class="ad "  >
              </div>
            </div>
            <br>
          </fieldset>
          <div class="all">
            <div class="container-1 px-0 py-10 mx-auto">
              <div class="relative mb-1">
                <div class="form">
                  <fieldset>
                  <h1 class="h1"><u>Parents Information</u></h1>
                  <h2 class="h2"><b>Please fill the correct information only and check once before submitting</b></h2><br>
                  <div class="relative mb-4            "><div class="ptm-1">
<label> Full name </label><br>
<i class="fas fa-user-circle fa-2x" aria-hidden="true" id="ptm-1"></i>
<input type="text" placeholder="Enter your full name*" id="ptm-11" required>

</div></div><br>
<div class="relative mb-4">
  <div class="ptm-2">
    <label>
      Nationality
    </label>
    <i class="far fa-globe-asia fa-2x" aria-hidden="true" id="ptm-2"></i>
    <input type="text" maxlength="20" required id="ptm-111" placeholder="Enter your nationality">
  <label>Tel:</label>
  <i class="far fa-phone-square-alt fa-2x" aria-hidden="true" id="ptm-22"></i>
<input type="number"  maxlength="10" required placeholder="Enter a valid phone number" id="ptm-222">

</div>
</div>
<div class="relative mb-4            ">
  <div class="address">
    <label>Address</label>
    <i class="far fa-address-card  fa-2x" aria-hidden="true" id="ff"></i>
    <input type="text" placeholder="Your current address*" required class="ad
  ">
  </div>
</div><br>
<div class="relative mb-4            ">
  <div class="address">
    <label>Education : </label>
    <i class="fas fa-graduation-cap fa-2x" aria-hidden="true" id="ff"></i>
    <input type="text" placeholder="Your Educational level*" required class="ad
  ">
  </div>
</div><br>
<div class="relative mb-4">
  <div class="ptm-2">
    <label>
      Email
    </label>
    <i class="fal fa-envelope fa-2x" aria-hidden="true" id="ptm-3"></i>
    <input type="email" required id="ptm-111" placeholder="Enter your valid email">
  <label>Mobile:</label>
  <i class="far fa-phone-square-alt fa-2x" aria-hidden="true" id="ptm-33"></i>
<input type="number"  maxlength="10" required placeholder="Enter a valid phone number" id="ptm-222">

</div>
</div>

                </fieldset></div></div></div></div></div></div>          


            <div class="relative mb-4">
              <div class="mee">
              <label>Message</label>  <br>
              <i class="far fa-comments fa-2x" id="r">
                
              </i>
              
              <textarea id="abd"placeholder="Message"></textarea>
              </div><div class="a">
              <button class="su">Submit</button>
            </div></div></div></div><br>
      <footer >
        <div class="inclsuive">
        <div class="container px-5 py-8 mx-auto">
          <div class="flex flex-wrap md:text-left text-center ">
            <div class="inclusion">
            <div class="category">
            <div class="lg:w-1/4 md:w-1/2 w-full px-4">
              <div class="co">
              <h2 class="white">Contact US</h2>
              <nav class="list-none mb-10">
                <li>
                  <a class="white">Phone
                    4592006/ 4113786/ 5900784 / 5900785/ 4580249</a>
                </li>
                <li>
                  <a class="white">Email
                    info@paragonpublicschool.edu.np
                  </a>
                </li>
               </nav>
            </div></div>
            <div class="lg:w-1/4 md:w-1/2 w-full px-4">
              <div class="location">
                          <h2 class="white">Our Location</h2>
              <nav class="list-none mb-10">
                <li>
                  <a class="white">First Tilgana, Kathmandu 4460</a>
                </li>
                <li>
                  <a class="map">Maps
                    <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d56519.16015400367!2d85.349505!3d27.703466!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0xb858aeac6780ef5c!2sParagon%20Public%20School!5e0!3m2!1sen!2sus!4v1633156404417!5m2!1sen!2sus" width="200" height="350" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
                  </a>
                </li>
                <li>
                 
              </nav>
             </div></div>
            <div class="lg:w-1/4 md:w-1/2 w-full px-4">
              <div class="appointment">
              <h2 class="white">Appointment booker</h2>
              <div class="relative mb-4">
              <div class="name">
                <label >Name</label><br>
                <i class="fas fa-user" aria-hidden="true"></i>
                <input type="text" name="name"  placeholder="Name*" required class="ab">
                </div>
                <div class="relative mb-4">
                  <div class="email">
                    
                    <label>Email</label><br>
                    <i class="fas fa-envelope-open-text"></i>
                    <input type="email" name="Email" placeholder="Email*" required class="ad">
                  </div>
                </div>

                <div class="relative mb-4">
                  <div class="me">
                  <label>Message</label>  <br>
                  <i class="far fa-comments">
                    
                  </i>
                  
                  <textarea id="abc"placeholder="Message"></textarea>
                  </div><div class="sub">
                  <button class="sub">Submit</button>
                </div></div></div>
          </div></div>
          </div></div>
</div>
            </div>
                  
          </div>
        </div></div>
        <br>
        <div class="bg-gray-100">
          <div class="container px-8 py-0 mx-auto flex items-center sm:flex-row flex-col">
            <div class="feet">
            <a class="flex title-font font-medium items-center md:justify-start justify-center text-gray-900" id="ral">
              <img src="https://www.collegenp.com/uploads/2020/04/Paragon-Public-School.png" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-20 h-18 text-white p-2 bg-indigo-500 rounded-full" viewBox="0 0 24 24">
                <path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"></path>
              </svg>
              <span class="rel">Paragon-Public-School
            </a>
            <p class="re">© 2021 Tilak Neupane 
              
            </p>
            <span class="inline-flex sm:ml-auto sm:mt-0 mt-10 justify-center sm:justify-start">
            <div class="feet">
              <a class="text-white-500">
                <svg fill="blue" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
                  <path d="M18 2h-3a5 5 0 00-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 011-1h3z"></path>
                </svg>
              </a>
              <a class="ml-3 text-white-500">
                <svg fill="blue" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
                  <path d="M23 3a10.9 10.9 0 01-3.14 1.53 4.48 4.48 0 00-7.86 3v1A10.66 10.66 0 013 4s-4 9 5 13a11.64 11.64 0 01-7 2c9 5 20 0 20-11.5a4.5 4.5 0 00-.08-.83A7.72 7.72 0 0023 3z"></path>
                </svg>
              </a>
              <a class="ml-3 text-white-500">
                <svg fill="#8a3ab9" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-5 h-5" viewBox="0 0 24 24">
                  <rect width="20" height="20" x="2" y="2" rx="5" ry="5"></rect>
                  <path d="M16 11.37A4 4 0 1112.63 8 4 4 0 0116 11.37zm1.5-4.87h.01"></path>
                </svg>
              </a>
              <a class="ml-3 text-white-500">
                <svg fill="royalblue" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="0" class="w-5 h-5" viewBox="0 0 24 24">
                  <path stroke="none" d="M16 8a6 6 0 016 6v7h-4v-7a2 2 0 00-2-2 2 2 0 00-2 2v7h-4v-7a6 6 0 016-6zM2 9h4v12H2z"></path>
                  <circle cx="4" cy="2" r="2" stroke="none"></circle>
                </svg>
              </a></div>
            </div>
          </span>
            </span>
          </div>
        </div>
      </div> </footer>
</body>
</html>
