#### html
```html
<!DOCTYPE html>
<html lang="ko">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>NETFLEX - 홈(메인)</title>
    <link rel="stylesheet" href="//spoqa.github.io/spoqa-han-sans/css/SpoqaHanSansNeo.css" type="text/css">
    <link rel="stylesheet" href="./css/style.css" />
    <link rel="stylesheet" href="./mission-03.css" />
  </head>
  <body>
    <div class="container">
      <header class="header">
        <div class="header-inner">
          <h1 class="brand">
            <a href="/" class="logo-link">
              <img src="./images/brand.svg" alt="NETFLIX" />
            </a>
          </h1>
          <div class="menu">
            <div class="selectbox">
              <select aria-label="언어 선택">
                <option value="korean">한국어</option>
                <option value="english">영어</option>
              </select>
            </div>
            <a href="/" class="login-link">로그인</a>
          </div>
        </div>
      </header>
      <main class="main">
        <div class="promotion">
          <p class="promotion-description-1">영화, TV 프로그램을 <span>무제한으로.</span></p>
          <p class="promotion-description-2">다양한 디바이스에서 시청하세요. <span>언제든 해지하실 수 있습니다.</span></p>
          <p class="promotion-description-3">시청할 준비가 되셨나요? 멤버십을 등록하거나 <span>재시작하려면 이메일 주소를 입력하세요.</span></p>
          <form action="/" method="POST" class="promotion-form">
            <div class="form-input-wrapper member-id is--invalid is--focus">
              <label for="userEmail" class="form-input-label">이메일 주소</label>
              <input
                type="email"
                class="form-input"
                id="userEmail"
                name="userEmail"
                aria-required="true"
                aria-invalid="false"
                aria-describedby="emailErrorFeedback"
              />
              <span role="alert" id="emailErrorFeedback" class="form-message"
                >정확한 이메일 주소를 입력하세요.</span
              >
            </div>
            <div class="button-container">
              <button
                type="submit"
                class="button-signin button-fill"
                disabled="disabled"
              >
                30일 무료 이용
              </button>
            </div>
          </form>
          <p class="promotion-description-4">신규 회원만 이 프로모션을 이용하실 수 있습니다.</p>
        </div>
      </main>
      <footer class="footer">
        <div class="footer-inner">
          <div class="footer-wrapper-1">
            <p><em>질문이 있으신가요?</em> 문의 전화: 00-308-321-0058</p>
          </div>
          <div class="footer-wrapper-2">
            <ul class="guide">
                <li><a href="/">자주 묻는 질문</a></li>
                <li><a href="/">고객센터</a></li>
                <li><a href="/">계정</a></li>
                <li><a href="/">미디어 센터</a></li>
                <li><a href="/">투자 정보(IR)</a></li>
                <li><a href="/">입사 정보</a></li>
                <li><a href="/"><span lang="en">Netflix</span> 지원 디바이스</a></li>
                <li><a href="/">이용 약관</a></li>
                <li><a href="/">개인정보</a></li>
                <li><a href="/">쿠키 설정</a></li>
                <li><a href="/">회사 정보</a></li>
                <li><a href="/">문의하기</a></li>
                <li><a href="/">속도 테스트</a></li>
                <li><a href="/">법적 고지</a></li>
                <li><a href="/"><span lang="en">Netflix</span> 오리지널</a></li>
            </ul>
          </div>
          <div class="footer-wrapper-3">
            <div class="selectbox">
              <select aria-label="언어 선택">
                <option value="korean">한국어</option>
                <option value="english">영어</option>
              </select>
            </div>
          </div>
          <div class="footer-wrapper-4">
            <strong class="footer-logo"><span lang="en">Netflix</span> 대한민국</strong>
            <address class="address">
              <p>넷플릭스서비시스코리아 유한회사</p>
              <p>통신판매업신고번호: 제2018-서울종로-0426호</p>
              <p>전화번호: 00-308-321-0058</p>
              <p>대표: 레지널드 숀 톰프슨</p>
              <p>이메일 주소: korea@netflix.com</p>
              <p>주소: 대한민국 서울특별시 종로구 우정국로 26, 센트로폴리스 A동 20층 우편번호 03161</p>
              <p>사업자 등록번호: 165-87-00119</p>
              <p>클라우드 호스팅: <span lang="en">Amazon Web Services Inc.</span></p>
              <p>공정거래위원회 웹사이트</p>
            </address>
          </div>
        </div>
      </footer>
    </div>
  </body>
</html>
```

###### 반응형 css

```css
// 모바일

@media (min-width: 768px) {
  // 태블릿, 데스크탑 등
}
```

###### 다크모드 화면
![title](https://rnssue.github.io/home-work/mission-03/readme/darkmode.png)

#### 상태 설명
| normal | focus | invalid | disabled |
| --- | --- | --- | --- |
| ![title](https://rnssue.github.io/home-work/mission-03/readme/1.png) | ![title](https://rnssue.github.io/home-work/mission-03/readme/2.png) | ![title](https://rnssue.github.io/home-work/mission-03/readme/3.png) | ![title](https://rnssue.github.io/home-work/mission-03/readme/4.png) |

#### 페이지
[mission-03.html](https://rnssue.github.io/home-work/mission-03/mission-03.html)
