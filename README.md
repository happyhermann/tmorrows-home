# 내일의 집

| MOBILE | Tablet | Desktop | class
| O | X | X | `.sm-only`
| O | O | X | `.lg-hidden`
| X | O | O | `.md-only`
| X | X | O | `.lg-only`  
| O | X | O | `.md-hidden`

<!-- NOTE : Responsive Class Name -->

### 1. GNB

- 로그인 하지 않은 경우

```html
     <div class="button-group">
                  <button
                    class="gnb-icon-button is-search lg-hidden"
                    type="button"
                    aria-label="검색창 열기 버튼"
                  >
                    <i class="ic-search"></i>
                  </button>
                  <a
                    class="gnb-icon-button is-cart"
                    href="/"
                    aria-label="장바구니 페이지로 이동"
                  >
                    <i class="ic-cart"></i>
                  </a>
                  <div class="gnb-auth sm-hidden">
                    <a href="/">로그인</a>
                    <a href="/">회원가입</a>
                  </div>
                </div>
                <button class="btn-primary btn-40 sm-hidden" type="button">
                  글쓰기
                  <i class="ic-chevron" aria-hidden=""></i>
                </button>
              </div>

```

- NOTE : 로그인 한 경우

```html
<div class="button-group">
   <button
      class="gnb-icon-button is-search lg-hidden"
      type="button"
      aria-label="검색창 열기 버튼"
   >
      <i class="ic-search"></i>
   </button>

   <a
      class="gnb-icon-button sm-hidden"
      href="/"
      aria-label="스크랩북 페이지로 이동"
   >
      <i class="ic-bookmark"></i>
   </a>

   <a
      class="gnb-icon-button sm-hidden"
      href="/"
      aria-label="내 소식 페이지로 이동"
   >
      <i class="ic-bell"></i>
   </a>

   <a
      class="gnb-icon-button is-cart"
      href="/"
      aria-label="장바구니 페이지로 이동"
   >
      <i class="ic-cart"></i>
      <strong class="badge">1</strong>
   </a>

   <button
      class="gnb-avatar-button sm-hidden"
      type="button"
      aria-label="마이메뉴 열기 버튼"
   >
      <div class="avatar-32">
         <img src="./assets/imgs/img-user-01.jpg" />
      </div>
   </button>
</div>
```

### 2. Sidebar

- 로그인 하지 않은 경우

```html
<div class="sidebar-auth">
   <a class="btn-outlined btn-40" href="/">로그인</a>
   <a class="btn-primary btn-40" href="/">회원가입</a>
</div>
```

- 로그인 한 경우

```html
<div class="sidebar-user">
   <a href="/">
      <div class="avatar-24">
         <!-- <img src="./assets/imgs/img-user-01.jpg" /> -->
      </div>

      <strong class="username">김두한</strong>
   </a>
</div>
```
