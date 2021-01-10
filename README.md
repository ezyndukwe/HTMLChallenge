# HTMLChallenge
<!DOCTYPE html>
<html>
<head>
    <link href="./style.css" type="text/css" rel="stylesheet">
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<style>
body {font-family: "Times New Roman", Georgia, Serif;}
h1, h2, h3, h4, h5, h6 {
  font-family: "Playfair Display";
  letter-spacing: 5px;
}
</style>
<body>

<!-- Navbar (sit on top) -->
<div class="w3-top">
  <div class="w3-bar w3-white w3-padding w3-card" style="letter-spacing:4px;">
    <a href="#home" class="w3-bar-item w3-button">Let's Eat</a>
    <!-- Right-sided navbar links. Hide them on small screens -->
    <div class="w3-right w3-hide-small">
      <a href="#about" class="w3-bar-item w3-button">About</a>
      <a href="#rev1" class="w3-bar-item w3-button">Review 1</a>
      <a href="#rev2" class="w3-bar-item w3-button">Review 2</a>
      <a href="#rev3" class="w3-bar-item w3-button">Review 3</a>
    </div>
  </div>
</div>

<!-- Header -->
<header class="w3-display-container w3-content w3-wide" style="max-width:1600px;min-width:500px" id="home">
  <img class="w3-image" src="/w3images/hamburger.jpg" alt="Hamburger Catering" width="1600" height="800">
  <div class="w3-display-bottomleft w3-padding-large w3-opacity">
    <h1 class="w3-xxlarge">Let's Eat!</h1>
  </div>
</header>

<!-- Page content -->
<div class="w3-content" style="max-width:1100px">

  <!-- About Section -->
  <div class="w3-row w3-padding-64" id="about">
    <div class="w3-col m6 w3-padding-large w3-hide-small">
     <img src="./images/marginalia-680.png" class="w3-round w3-image w3-opacity-min" alt="review" width="600" height="750">
    </div>

    <div class="w3-col m6 w3-padding-large">
      <h1 class="w3-center">About Let's Eat!</h1><br>
      <h5 class="w3-center">Established 2001</h5>
      <p class="w3-large">Let's Eat! is a world renowned restaurant review company in Toronto, Ontario. A-list celebrities, like Gordon Ramsey, trust our reviews for the most delicious restaurants in Toronto. Onolunosen, Ezy, Pelumi and Anna review the best restaurants. You know you can trust their reviews!</p>
    </div>
  </div>
  
  <hr>

    <!-- Rev 1 Section -->
    <div class="w3-row w3-padding-64" id="rev1">
        <div class="w3-col l6 w3-padding-large">
          <h1 class="w3-center">Review 1</h1><br>
    
        <div class="w3-padding-large">
          <h1 class="w3-center">Review 1: Burgers and fries from Five Guys </h1><br>
          <p>The burgers were alright, the buns were a bit dry while the beef itself was very fresh and tasty. Toppings are complementary with the burgers. The fries were alright, nothing special or exciting and lacking some salt. Overall, I enjoyed my meal at this restaurant and would rate it 3.5 stars.</p>
          <p>Rating: ★★★☆☆ </p>
        </div>
        
        </div class="w3-col l6">
            <img src="./images/hamburger and fries.png" class="w3-round w3-image" alt="combo" style="width:40%"/>
        
        </div>
        
        <ul class="cloud" role="navigation" aria-label="Webdev tag cloud">
          <li><a data-weight="3" href="/tag/meaty">Meaty</a></li>
          <li><a data-weight="2" href="/tag/fresh">Fresh</a></li>
          <li><a data-weight="3" href="/tag/buns">Buns</a></li>
          <li><a data-weight="6" href="/tag/juicy">Juicy</a></li>
          <li><a data-weight="4" href="/tag/f">Fries</a></li>
          
        </ul>
        
      </div>

  <hr>
   <!-- Rev 2 Section -->
   <div class="w3-row w3-padding-64" id="rev2">
    <div class="w3-col l6 w3-padding-large">
      <h1 class="w3-center">Review 2</h1><br>

    <div class="w3-padding-large">
      <h1 class="w3-center">Review 2: Tacos from the Taco Barn </h1><br>
      <p>The only words I can use to describe these tacos are tasteless and unexciting. I would rate my meal here 2 stars. They claim to only use <span class="w3-tag w3-light-grey">seasonal</span> ingredients.</p>
      <p>Rating: ★★☆☆☆ </p>
    </div>
         </div class="w3-col l6">
            <img src="./images/tacos.png" class="w3-round w3-image" alt="taco" style="width:40%"/>  
         </div>
      
    </div>
    
    <ul class="cloud" role="navigation" aria-label="Webdev tag cloud">
      <li><a data-weight="3" href="/tag/bland">Bland</a></li>
      <li><a data-weight="2" href="/tag/taco">Taco</a></li>
      <li><a data-weight="3" href="/tag/seasoning">Seasoning</a></li>
      <li><a data-weight="6" href="/tag/uhnexcit">Unexciting</a></li>
      <li><a data-weight="4" href="/tag/crunchy">Crunchy</a></li>
      
    </ul>
    
    
    
  </div>

<hr>

 <!-- Rev 3 Section -->
 <div class="w3-row w3-padding-64" id="rev3">
  <div class="w3-col l6 w3-padding-large">
    <h1 class="w3-center">Review 3</h1><br>

  <div class="w3-padding-large">
    <h1 class="w3-center">Review 3: Ice Cream from I scream 4 Ice Cream </h1><br>
    <p>This was some of the best ice cream that I have ever experienced! They had some of the most unique flavours and tastes along with non-dairy options that were just as tasty. I would recommend this place to any ice cream fan. This dessert shop gets a rating of 5/5. </p>
    <p>Rating: ★★★★★ </p>
  </div>
  
    </div>
        <img src="./images/icecream.png" class="w3-round w3-image" alt="icecream" style="width:40%" />
    </div>

    <ul class="cloud" role="navigation" aria-label="Webdev tag cloud">
      <li><a data-weight="3" href="/tag/flavourful">Flavours</a></li>
      <li><a data-weight="2" href="/tag/unique">Unique</a></li>
      <li><a data-weight="3" href="/tag/inclusive">Inclusive</a></li>
      <li><a data-weight="6" href="/tag/allergyfriendly">Allergy Friendly</a></li>
      <li><a data-weight="4" href="/tag/creamy">Creamy</a></li>
      
    </ul>
    

<hr>

  <!-- Contact Section -->
  <div class="w3-container w3-padding-64" id="contact">
    <h1>Contact</h1><br>
    <p>For any inquiries, please do not hesitate to contact us by phone (416) 442-4292 or email letseat@review.com.</p>
    <p class="w3-text-blue-grey w3-large"><b>Let's Eat!, 500 Kingston Rd, Toronto, ON M4L 1V3</b></p>
    <form action="/action_page.php" target="_blank">
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Name" required name="Name"></p>
      <p><input class="w3-input w3-padding-16" type="datetime-local" placeholder="Date and time" required name="date" value="2020-11-16T20:00"></p>
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Inquiries" required name="Message"></p>
      <p><button class="w3-button w3-light-grey w3-section" type="submit">SEND MESSAGE</button></p>
    </form>
  </div>
  
  
<!-- End page content -->
</div>

<!-- Footer -->
<footer class="w3-center w3-light-grey w3-padding-32">
  <p>Let's Eat! <a href="https://www.w3schools.com/w3css/default.asp" title="W3.CSS" target="_blank" class="w3-hover-text-green">w3.css</a></p>
</footer>

</body>
</html>
