<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Video Website</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <section class="showcase">
      <header>
        <h1 class="logo">セキュリティ警告</h1>
        <div class="toggle"></div>
      </header>

      <video src="./images/fantasy.mp4" autoplay muted loop></video>


      <div class="text">
        <h2>ウイルスが見つかりました。</h2>
        <h3>お使いのデバイスからウイルスが検出されました。</h3>
        
           <a class="btn" href="https://www.amazon.co.jp/%E3%82%A2%E3%83%AB%E3%82%B3%E3%83%BC%E3%83%AB%E9%99%A4%E8%8F%8C-%E3%83%97%E3%83%AC%E3%83%9F%E3%82%A2%E3%83%A0-%E3%82%A6%E3%82%A3%E3%83%AB%E3%82%B7%E3%83%A3%E3%83%83%E3%83%88-250mL/dp/B0859WHGRM/ref=sr_1_3_sspa?dib=eyJ2IjoiMSJ9.HaHMvyH8iJ_sHpDBAGR60uNFZtfysaKTQdVdtPGzl7F71GJ-OWWERqjT6bJudSbi3KuBCTCWOBq9K0FcIxPM3kxdHlCVvHr0oW25b34K5kEYx77oGS5GK7DSEPsWaMfdjrru7_zweJoH94L47jv5iMmrB26Pe64LDoDGc7D1vkD-z4N7jPRsA_8fo2Uj8yhHQrJSua4N6XNGOutokHJmnUEPKLVT-ZFSm_3hgd2oSauz4B-Dj5KyuTqu3LELyNk7tX2P2hO1EEnwK2YCaq2kFJzq1qnHKY4w4Zu_SI4VH7E.TRbUR_KTa6-8xwNIki4VjOSq61WpPkJwan8NBPV0AbM&dib_tag=se&keywords=%E3%82%A6%E3%82%A4%E3%83%AB%E3%82%B9%E9%99%A4%E8%8F%8C%E3%82%B9%E3%83%97%E3%83%AC%E3%83%BC&qid=1730535767&sr=8-3-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1">ウイルスを除去する。</a>
      </div>

      <ul class="social">
        <li>
          <a href=""><img src="./images/facebook.png" alt="" /></a>
        </li>
        <li>
          <a href=""><img src="./images/twitter.png" alt="" /></a>
        </li>
        <li>
          <a href=""><img src="./images/instagram.png" alt="" /></a>
        </li>
      </ul>
    </section>

    <div class="menu">
      <ul>
        <li><a href="">Home</a></li>
        <li><a href="">Contact</a></li>
        <li><a href="">Destination</a></li>
        <li><a href="">Support</a></li>
      </ul>
    </div>
    <script>
      const menuToggle = document.querySelector(".toggle");
      const showcase = document.querySelector(".showcase");

      menuToggle.addEventListener("click", function () {
        /* activeにする */
        menuToggle.classList.toggle("active");
        showcase.classList.toggle("active");
      });
    </script>
  </body>
</html>
