# Javascript Plugin
## 공통 주의사항
* 각 플러그인 사용 시 해당 플러그인의 필수 연결파일 먼저 확인하기!
* css, js 파일확장자가 서로 다른 경우 있으니 이름과 함께 확장자 반드시 확인! 
## Swiper
*swiper, swiper-wrapper, swiper-slide
*위 3개의 클래스명은 swiper 적용의 기본명칭이므로 반드시 수정없이 그대로 작성하기!
*위 공통 명칭 외에 각 swiper 구분용으로 `div class="swiper"` 시작태그에 한칸띄고 별도의 구분용 클래스 적용하기 예: `div class="swiper main_slide"`
* swiper 플러그인 적용 대상에 nth 관련 수열선택자 사용하지 않기! 
* `swiper-slide`를 개별로 구분하고 싶다면? nth 수열선택자 사용하지 않고 개별 적용해서 디자인 또는 동적 결과 사용하기 예: `div class="swiper-slide slide1`
* swiper 적용 대상에 원하는 태그 추가는 swipe-slide 안에서만 사용하기(태그제한없음)
### Swiper option css 주의사항
*prev, next, pagination, scroll-bar
* 위 옵션들은 필요한 경우에만 선택적으로 작성한다.
* 기본적으로 swiper 시작태그의 자식요소로 작성한다.
* swiper 시작태그의 바깥쪽 위치로 디자인하고 싶은 경우만 swiper 바깥쪽 위치에 태그를 구성하고 해당 위치의 새로운 부모 대상에 position:relative를 설정한다.
(swiper 옵션들에 absolute가 내장되어 있기 때문!)