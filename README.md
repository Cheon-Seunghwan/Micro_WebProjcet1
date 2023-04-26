# 2열 4조 
## 팀 소개 
* 이소민 🙋🏻‍♀️
* 정경연 🙋🏻‍♀️
* 유재원 🙋🏻‍♂️
* 전승환 🙋🏻‍♂️

## 주제 ✨
기프티콘 중고 거래 사이트

## 구현 화면 💻
* Header / Footer
* Section1 - 메인
* Section2 - 거래
* Section3 - 후기
* [notion1 - 참조](https://www.notion.so/8e7a9abe57554581a2e723e7ea0163b3)
* [notion2 - 구현](https://www.notion.so/cac194ef37574591a0b8d60ec4d1120a)
* [호스팅](https://woori-miniproject-01.w3spaces.com/)

## 간단한 코드 소개 📃
* Header / Footer
```html
<header>
            <div>
                <a href="#"><img
                        src="https://file.miricanvas.com/template_thumb/2019/07/10/4533-1562694278007/4381abfd-0106-4473-b084-ce45f564fd5b/thumb.jpg"
                        alt="marcket logo"></a>
                <nav>
                    <ul>
                        <li><a href="#">기프티콘 거래</a></li>
                        <li><a href="#">동네 가게</a></li>
                        <li><a href="#">알바</a></li>
                        <li><a href="#">쿠폰 거래</a></li>
                        <li><a href="#">상품 직거래</a></li>
                    </ul>
                </nav>
                <span>
                    <form href="">
                        <input type="search" class="searching" placeholder="물품이나 동네를 검색해 보세요">
                        <button>채팅하기</button>
                    </form>
                </span>
            </div>
        </header>
```
* Section1 - 메인
```html
<section class="home-main-section-2">
                <div class="home-main-2">
                    <div>
                        <img class="imgsize2"
                            src="https://d1unjqcospf8gs.cloudfront.net/assets/home/main/3x/image-1-cc678e9a217b96f5cb459f7f0684f5ba67706f9889801618b8cf879fbc2c0ea7.webp"
                            alt="이미지2">
                    </div>
                    <div class="home-main-left">
                        <h1 class="main-text">요즘 핫한<br>기프티콘 추천</h1>
                        <p class="sub-text">요즘 핫한 기프티콘을 찾아보고<br>필요한 기프티콘을 검색해보세요</p>
                    </div>
                    <div class="botton-section">
                        <a href="blueshare.tistory.com" style="text-decoration: none;" class="botton-text1">
                            베스트 상품
                        </a>
                        <a href="blueshare.tistory.com" style="text-decoration: none;" class="botton-text2">
                            특가 상품
                        </a>
                    </div>
                </div>
            </section> 
```

* Section2 - 거래
```html
<section>
    <div class="category-box">
        <h1>기프티콘 인기 카테고리</h1>
        <ul class="category-lists">
            <li>
                <a href="#">
                    <img class="category-img" src="/assets/images/coffee.png" alt="coffee-image" />
                    <p>커피/음료</p>
                </a>
            </li>
            <li>
                <a href="#">
                    <img class="category-img" src="/assets/images/icecream.png" alt="icecream-image" />
                    <p>디저트</p>
                </a>
            </li>
            <li>
                <a href="#">
                    <img class="category-img" src="/assets/images/popcorn.png" alt="movie-image" />
                    <p>영화</p>
                </a>
            </li>
            <li>
                <a href="#">
                    <img class="category-img" src="/assets/images/cake.png" alt="bakery-image" />
                    <p>베이커리</p>
                </a>
            </li>
            <li>
                <a href="#">
                    <img class="category-img" src="/assets/images/chicken.png" alt="food-image" />
                    <p>외식</p>
                </a>
            </li>
            <li>
                <a href="#">
                    <img class="category-img" src="/assets/images/uniq.png" alt="daily-item-image" />
                    <p>생활문화</p>
                </a>
            </li>
            <li>
                <a href="#">
                    <img class="category-img" src="/assets/images/convenience.png"
                        alt="convenience-item-image" />
                    <p>편의점</p>
                </a>
            </li>
            <li>
                <a href="#">
                    <img class="category-img" src="/assets/images/giftcard.png" alt="giftcard-image" />
                    <p>상품권</p>
                </a>
            </li>
        </ul>
    </div>
</section>
```
* Section3 - 후기
```html
<!-- 3. 후기 파트 -->
            <section class="review-section">
                <h1>동네 이웃이 남긴 후기를 찾아보세요.</h1>
                <!-- 게시물 1 -->
                <article class="article">
                    <div>
                        <!-- 프로필 사진 -->
                        <img class="profile-img" style="float : left;" src="/assets/images/철수.png" alt="철수 프로필">
                        <!-- 사용자 ID -->
                        <span class="id">
                            철수
                            <!-- 단골이미지 -->
                            <img src="/assets/images/단골.PNG" alt="단골 마크">
                        </span>
                        <br>
                        <!-- 사는 곳 -->
                        <span class="city">
                            서울시 마포구
                        </span>
                    </div>
                    <!-- 상세 기프티콘 -->
                    <div class="content">
                        <h2 class="title">
                            상품 설명
                        </h2>
                        <div class="review-box">
                            <a href="https://m.happymoney.co.kr/svc/view/use/useMain#"><img class="gifticon"
                                    src="assets/images/상품권.jpg" alt="해피머니 상품권 기프티콘"></a>
                            <span>
                                이것은 해머머니 상품권 기프티콘 입니다.<br>
                                정가는 10,000원 입니다.<br>
                                50%할인된 5,000원 으로 구매하셨습니다.
                            </span>
                        </div>

                        <!-- 후기 내용 -->
                        <p class="review">
                        <h2 class="title">
                            상세 후기
                        </h2>
                        너무 싸게 잘 샀습니다.<br>
                        영화볼 때 사용하려구요!
                        </p>
                        <!-- 상품권 설명 -->
                    </div>
                </article>
```
## 어려웠던 점, 트러블슈팅 해결방법 📢
* 서로 다른 속성을 가진 요소들을 원하는 위치로 정렬하는 것에 어려움을 겪었습니다.
  * 의도치 않은 곳으로 이동하거나 설정이 적용되지 않는 경우가 많았는데, 작성한 코드들과 요소의 관계를 찬찬히 보고 관련 정보를 찾아보며 해결할 수 있었습니다.
* 상품 설명의 내용이 <span>태그 및 CSS 정렬을 이용하였음에도 불구하고 이미지 바로 옆 최상단에 위치하지 않았습니다.
  * 상품 이미지와 설명을 <div>태그로 묶고 CSS flex 레이아웃을 이용함으로써 해결하였습니다.
## 느낀점 🎈
* 일상적으로 접하는 웹사이트를 실질적으로 구성하는데 고려해야할 부분이 많다는것을 알게되었습니다.
* 기본기에 대한 중요성을 뼈저리게 느꼈습니다.
* 시맨틱 태그와 SEO에 관련해서 제대로 알아야겠다고 생각했습니다.
* CSS 레이아웃과 관련해서 스스로 공부가 필요하다고 느꼈습니다.
