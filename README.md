<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Document</title>
    <style>
    @font-face {
        font-family: 'RixYeoljeongdo_Regular';
        src: url('https://cdn.jsdelivr.net/gh/projectnoonnu/noonfonts_2102-01@1.0/RixYeoljeongdo_Regular.woff') format('woff');
        font-weight: normal;
        font-style: normal;
    }</style>
    <link rel="stylesheet" href="homework_page.css"/>
  </head>

  <body>
    <header class="header">
      <h1 class="logo">
        <img src="images/logo.png" alt="로고 이미지"/>
      </h1>
      <nav class="gnb">
        <ul class="gnb-list">
          <li class="gnb-item"><a href="" class="gnb-link">ABOUT</a></li>
          <li class="gnb-item"><a href="" class="gnb-link">NEWS</a></li>
          <li class="gnb-item"><a href="" class="gnb-link">CONTACT</a></li>
        </ul>
      </nav>
      <button type="button" class="hamburger">
        <img src="images/hamburger-menu.svg" alt="햄버거 메뉴"/>
      </button>
    </header>
    <!-- section1. 제목 부분 -->
    <section class="section1"> 
      <h1 class="section-heading">Team. 스우파</h1>
      <p class="section-paragraph">
        안녕하세요, 팀 ‘스쿨미투우먼파이터’(이하 스우파)의 김규희, 정채원, 하주언입니다.
        스우파라는 팀명이 있기 전, 저희는 각자의 자리에서 ‘기자’라고 불렸습니다.
        선후배로 함께한 ‘동덕여대 학보사 기자’부터 ‘여성신문 기자’까지 그 이름은 다양했지만, 
        전하고 싶은 이야기는 같습니다. <br>
        바로 ‘여성의 목소리’입니다.          
      </p>
    </section>
    <!-- section2. 사진 및 영상 부분 -->
    <section class="section2">
      <!-- 사진 1행 -->
      <div class="group">
        <!-- 유튜브 영상 가져올 때에는 태그 입력하지 말고 유튜브 -> 공유 -> 퍼가기 -> 소스코드 복사-->
        <!-- 유튜브 영상 크기는 HTML 소스코드에서 삭제 후 CSS에서 조정 -->
        
        <iframe
          class="visual-content" 
          src="https://www.youtube.com/embed/NSYFu_x9BXA?autoplay=1&mute=1" 
          title="YouTube video player" 
          frameborder="0" 
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
          allowfullscreen>
        </iframe>
        <img class="visual-content" src="images_swf/image (1).jpg" alt="단체사진1" />
        <img class="visual-content" src="images_swf/image (2).jpg" alt="단체사진2" />
        <img class="visual-content" src="images_swf/image (3).jpg" alt="단체사진3" />
      </div>
      <!-- 사진 2행 -->
      <div class="group">
        <img class="visual-content" src="images_swf/image (4).jpg" alt="단체사진4" />
        <img class="visual-content" src="images_swf/image (5).jpg" alt="단체사진5" />
        <iframe
          class="visual-content" 
          src="https://www.youtube.com/embed/NSYFu_x9BXA?autoplay=1&mute=1" 
          title="YouTube video player" 
          frameborder="0" 
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
          allowfullscreen>
        </iframe>
        <img class="visual-content" src="images_swf/image (1).jpg" alt="단체사진1" />
      </div>
      <!-- 사징 3행 -->
      <div class="group">
        <img class="visual-content" src="images_swf/image (2).jpg" alt="단체사진2" />
        <iframe
          class="visual-content" 
          src="https://www.youtube.com/embed/NSYFu_x9BXA?autoplay=1&mute=1" 
          title="YouTube video player" 
          frameborder="0" 
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
          allowfullscreen>
        </iframe>
        <img class="visual-content" src="images_swf/image (3).jpg" alt="단체사진3" />
        <img class="visual-content" src="images_swf/image (4).jpg" alt="단체사진4" />
      </div>
    </section>
    <footer class="footer">
      <h4 class="title">Gyu Design, Inc.</h4>
      <p class="copyright">
        © 2021 Gyu. All right reserved.
        Designed by gyu.
      </p>
      <ul class="sns-list">
        <li class="sns-list">Facebook</li>
        <li class="sns-item">Instagram</li>
        <li class="sns-item">YouTube</li>
        <li class="sns-item">Notion</li>
      </ul>
    </footer>
  </body>
</html>
