
#### html
```html
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>mission-02</title>
  <link href="//spoqa.github.io/spoqa-han-sans/css/SpoqaHanSans-kr.css" rel="stylesheet" type="text/css" />
  <link rel="stylesheet" href="./normalize.css" />
  <link rel="stylesheet" href="./mission-02.css" />
</head>
<body>
  <main class="main">
    <section class="login">
      <div class="title-box">
        <h2 class="title">로그인</h2>
        <p class="title-sub">Welcome, Ediya Coffee</p>
        <p class="title-sub-2">이디야커피에 오신 것을 환영합니다.</p>
      </div>
      <form action="/" class="login-form">
        <fieldset class="reset-box">
          <legend>회원 로그인 폼</legend>
          <div class="user-email is--focus is--valid"><!-- .is--focus : 포커스 상태 / .is--invalid : 오류 / .is--valid : 정상 -->
            <label for="userEmail">이메일</label>
            <input
              type="email"
              id="userEmail"
              placeholder="yamoo9@euid.dev"
              required
              name="userEmail"
              class="form-input"
            />
            <p class="form-message">이메일 입력 방법이 잘못되었습니다. (예: user@domain.io)</p>
          </div>
          <div class="user-pwd is--focus is--invalid"><!-- .is--focus : 포커스 상태 / .is--invalid : 오류 / .is--valid : 정상 -->
            <label for="userPwd">패스워드</label>
            <input
              type="password"
              id="userPwd"
              placeholder="숫자, 영어 조합 6자 이상"
              required
              name="userPwd"
              minlength="6"
              class="form-input"
            />
            <button class="button-password is--visible"><!-- .is--visible : 눈 아이콘 보이기 -->
              <span class="sr-only">패스워드 보이지 않기</span>
            </button>
            <p class="form-message">패스워드는 숫자, 영어 조합 6자 이상 입력해야 합니다.</p>
          </div>
          <div class="email-check">
            <input type="checkbox" id="emailCheck">
            <label for="emailCheck">이메일 저장</label>
          </div>
        </fieldset>
      </form>
      <ul class="login-link-box reset-list">
        <li class="icon-right-arrow login-button"><button>로그인</button></li>
        <li class="icon-right-arrow"><a href="/">회원가입</a></li>
      </ul>
    </section>
  </main>
</body>
</html>
```

###### 반응형 css

```css
// 모바일

@media (min-width: 600px) {
  // 태블릿, 데스크탑 등
}
```

###### 태블릿, 데스크탑 화면
![title](https://rnssue.github.io/home-work/mission-02/readme/desktop.JPG)   


#### 상태 설명
| normal | focus | invalid | valid |
| --- | --- | --- | --- |
| ![title](https://rnssue.github.io/home-work/mission-02/readme/1_normal.JPG) | ![title](https://rnssue.github.io/home-work/mission-02/readme/2_focus.JPG) | ![title](https://rnssue.github.io/home-work/mission-02/readme/3_invalid.JPG) | ![title](https://rnssue.github.io/home-work/mission-02/readme/4_valid.JPG) |

#### 페이지
[mission-02.html](https://rnssue.github.io/home-work/mission-02/mission-02.html)
