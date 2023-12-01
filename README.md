# lab6
<html>
<head>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Karma">
<style>
body,h1,h2,h3,h4,h5,h6 {font-family: "Karma", sans-serif}
.w3-bar-block .w3-bar-item {padding:20px}
</style>
</head>
<body>

<!-- Sidebar (hidden by default) -->
<nav class="w3-sidebar w3-bar-block w3-card w3-top w3-xlarge w3-animate-left" style="display:none;z-index:2;width:40%;min-width:300px" id="mySidebar">
  <a href="javascript:void(0)" onclick="w3_close()"
  class="w3-bar-item w3-button">Close Menu</a>
  <a href="#food" onclick="w3_close()" class="w3-bar-item w3-button">Food</a>
  <a href="#about" onclick="w3_close()" class="w3-bar-item w3-button">About</a>
</nav>

<!-- Top menu -->
<div class="w3-top">
  <div class="w3-white w3-xlarge" style="max-width:1200px;margin:auto">
    <div class="w3-button w3-padding-16 w3-left" onclick="w3_open()">☰</div>
    <div class="w3-right w3-padding-16">Mail</div>
    <div class="w3-center w3-padding-16">Jessica Drinks</div>
  </div>
</div>
  
<!-- !PAGE CONTENT! -->
<div class="w3-main w3-content w3-padding" style="max-width:1200px;margin-top:100px">

  <!-- First Photo Grid-->
  <div class="w3-row-padding w3-padding-16 w3-center" id="food">
    <div class="w3-quarter">
      <img src="image/chanhbacha.jpg" alt="Sandwich" style="width:100%">
      <h3>MOJITO BACARD</h3>
      <p>Chanh bạc hà cho mùa hè tươi mát</p>
    </div>
    <div class="w3-quarter">
      <img src="image/sodadaiduong.jpg" alt="Steak" style="width:100%">
      <h3>MARGARITA</h3>
      <p>Đại dương xanh mát</p>
    </div>
    <div class="w3-quarter">
      <img src="image/chanhoai.jpg" alt="Cherries" style="width:100%">
      <h3>CAIPIRISIMA</h3>
      <p>Tình yêu chung thủy</p>
      <p>???</p>
    </div>
    <div class="w3-quarter">
      <img src="image/cam3mau.jpg" alt="Pasta and Wine" style="width:100%">
      <h3>DESTORNILLA-DOR</h3>
      <p>Cuộc sống sắc màu</p>
    </div>
  </div>
  
  <!-- Second Photo Grid-->
  <div class="w3-row-padding w3-padding-16 w3-center">
    <div class="w3-quarter">
      <img src="image/cherychanh.jpg" alt="Popsicle" style="width:100%">
      <h3>DAIQUIRI DE FRUTILLA</h3>
      <p>Món quà đặc biệt cho người phụ nữ</p>
    </div>
    <div class="w3-quarter">
      <img src="image/duahauep.jpg" alt="Salmon" style="width:100%">
      <h3>COSMOPOLITAN</h3>
      <p>Trà dưa hấu, làm gấu mình nha</p>
    </div>
    <div class="w3-quarter">
      <img src="image/mamsoibacha.jpg" alt="Sandwich" style="width:100%">
      <h3>BOODY MARY</h3>
      <p>Kết nối đam mê</p>
    </div>
    <div class="w3-quarter">
      <img src="image/chanhleobacha.jpg" alt="Croissant" style="width:100%">
      <h3>SIDECA</h3>
      <p>Thổi bay uể oải, mệt mỏi tức thì</p>
    </div>
  </div>

  <!-- Pagination -->
  <div class="w3-center w3-padding-32">
    <div class="w3-bar">
      <a href="#" class="w3-bar-item w3-button w3-hover-black">«</a>
      <a href="#" class="w3-bar-item w3-black w3-button">1</a>
      <a href="#" class="w3-bar-item w3-button w3-hover-black">2</a>
      <a href="#" class="w3-bar-item w3-button w3-hover-black">3</a>
      <a href="#" class="w3-bar-item w3-button w3-hover-black">4</a>
      <a href="#" class="w3-bar-item w3-button w3-hover-black">»</a>
    </div>
  
<!-- About Section -->
<div class="w3-row w3-padding-64" id="about">
  <div class="w3-col m6 w3-padding-large w3-hide-small">
   <img src="image/jessica.jpg" class="w3-round w3-image w3-opacity-min" alt="Table Setting" width="750" height="750">
  </div>

  <div class="w3-col m6 w3-padding-large">
    <h1 class="w3-center">Jessica Drinks</h1><br>
    <h3 class="w3-center">Life happens</h3>
    <p class="w3-large">Bạn đã và đang băn khoăn mình nên đi đâu và làm gì sau một ngày dài mệt mỏi! Hãy đến với chúng tôi! Jessica Drinks sẽ cho bạn một không gian thoáng đãng với concept mới lạ theo xu hướng nhẹ nhàng.
      Không gian yên tĩnh , cảnh đẹp , phục vụ nhiệt tình , đồ uống sạch và an toàn , đẹp mắt là nơi lý tưởng cho những người bạn gặp mặt👨‍💻👨🏻‍💻</p>
    <p class="w3-large w3-text-grey w3-hide-medium">Jessica mang phong cách đơn giản, mộc mạc, thư giãn và dễ chịu. Đến với TÔI bạn sẽ có một không gian thoáng mát và thư giãn. Bạn có thể lựa chọn không gian trong phòng với điều hòa mát lạnh, hay tụ tập bạn bè với không gian ngoài trời thoáng mát, còn nếu bạn là người thích ở nhà tránh nóng thì đừng lo Jessica sẽ giao hàng đến tận nơi cho bạn với menu đa dạng! </p>

  </div>
  <hr id="about">

  <div class="w3-container w3-padding-32 w3-center">  
    <h3>About Me, The Drink Girl</h3><br>
    <img src="image/tranthibichngoc.jpg" alt="Me" class="w3-image" style="display:block;margin:auto" width="700" height="533">
    <div class="w3-padding-32">
      <h4><b>Trần Thị Bích Ngọc</b></h4>
      <h6><i>Đam mê màu sắc từ các đồ uống</i></h6>
      <p>Sự sáng tạo mà họ đã kết hợp các nguyên liệu để tạo ra những công thức nước uống đầy hấp dẫn, chinh phục thị giác lẫn vị giác của người thưởng thức</p>
    </div>

  <div class="w3-container w3-padding-64" id="contact">
    <h1>Liên Hệ</h1><br>
    <p>Tôi luôn muốn mang tới cho các bạn các nguồn cảm hứng và trải nghiệm thú vị thông qua các màu sắc tươi mới được cảm nhận thông qua từ thị giác lẫn vị giác</p>
    <p class="w3-text-blue-grey w3-large"><b>Địa chỉ: Vân Nội - Đông Anh - Hà Nội</b></p>
    <p>Bạn có thể liên hệ với chúng tôi theo số điện thoại 0375646828 hoặc email baolamm.1402@gmail.com , hặc bạn có thể nhắn tin ở dưới đây:</p>
    <form action="/action_page.php" target="_blank">
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Name" required name="Name"></p>
      <p><input class="w3-input w3-padding-16" type="number" placeholder="How many people" required name="People"></p>
      <p><input class="w3-input w3-padding-16" type="datetime-local" placeholder="Date and time" required name="date" value="2023-11-24T20:00"></p>
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Message \ Special requirements" required name="Message"></p>
      <p><button class="w3-button w3-light-grey w3-section" type="submit">SEND MESSAGE</button></p>
    </form>
  </div>
  <!-- Footer -->
  <footer class="w3-row-padding w3-padding-32">
    <div class="w3-third">
      <h3>FOOTER</h3>
      <p>Praesent tincidunt sed tellus ut rutrum. Sed vitae justo condimentum, porta lectus vitae, ultricies congue gravida diam non fringilla.</p>
      <p>Powered by <a href="https://www.w3schools.com/w3css/default.asp" target="_blank">w3.css</a></p>
    </div>
  
    <div class="w3-third">
      <h3>BLOG POSTS</h3>
      <ul class="w3-ul w3-hoverable">
        <li class="w3-padding-16">
          <img src="image/Bánh ngọt.jpg" class="w3-left w3-margin-right" style="width:50px">
          <span class="w3-large">Bánh Ngọt</span><br>
          <span>Hương vị ngọt ngào của niềm vui và hạnh phúc</span>
        </li>
        <li class="w3-padding-16">
          <img src="image/Du lịch.jpg" class="w3-left w3-margin-right" style="width:50px">
          <span class="w3-large">Du Lịch</span><br>
          <span>Khám phá thế giới</span>
        </li> 
      </ul>
    </div>

    <div class="w3-third w3-serif">
      <h3>POPULAR TAGS</h3>
      <p>
        <span class="w3-tag w3-black w3-margin-bottom">Travel</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">New York</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Dinner</span>
        <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Salmon</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">France</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Drinks</span>
        <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Ideas</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Flavors</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Cuisine</span>
        <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Chicken</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Dressing</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Fried</span>
        <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Fish</span> <span class="w3-tag w3-dark-grey w3-small w3-margin-bottom">Duck</span>
      </p>
    </div>
  </footer>

<!-- End page content -->
</div>

<script>
// Script to open and close sidebar
function w3_open() {
  document.getElementById("mySidebar").style.display = "block";
}
 
function w3_close() {
  document.getElementById("mySidebar").style.display = "none";
}
</script>

</body>
</html>
