# 프로젝트 세팅(4조)
- npm install
- axios
- styled-components
- react-bootstrap bootstrap //app.jsx 파일에 상단에 붙여넣기 - import 'bootstrap/dist/css/bootstrap.min.css';
- @tanstack/react-query
- react-hook-form
- framer-motion@5.0.0
- react-router-dom@6
- react-icons --save
## 리셋css
- public>font(폴더생성)>공유한폰트파일넣기
- /font/YES24GothicR.ttf
- 컬러지정 
- Bg,Text,Accent:#ff9c46
~~~
@font-face {
  font-family: 'yesGo';  // 폰트이름지정
  src: url('/font/YES24GothicR.ttf'); //public폴더에서 경로찾기
}
/* @import url('https://fonts.googleapis.com/css2?family=Noto+Sans:wght@300;400&family=Source+Sans+3:wght@300;400&display=swap'); */
html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, menu, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed,
figure, figcaption, footer, header, hgroup,
main, menu, nav, output, ruby, section, summary,
time, mark, audio, video {
  margin: 0;
  padding: 0;
  border: 0;
  font-size: 100%;
  font: inherit;
  vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure,
footer, header, hgroup, main, menu, nav, section {
  display: block;
}
/* HTML5 hidden-attribute fix for newer browsers */
*[hidden] {
    display: none;
}
body {
  line-height: 1;
}
menu, ol, ul {
  list-style: none;
}
blockquote, q {
  quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
  content: '';
  content: none;
}
table {
  border-collapse: collapse;
  border-spacing: 0;
}
*{
  box-sizing: border-box;
}
body{
  font-family: 'yesGo';
  background-color: #f5f6fa; //배경색상 지정해야합니다
  color:#2f3640; // 폰트색상 지정해야합니다
}
a{
  text-decoration: none;
  color:inherit;
}
~~~