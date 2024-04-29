<!--info-header-start--><h1>Hello World <img src="https://img.shields.io/badge/-warm--up-teal" alt="warm-up"/> </h1><blockquote><p>bởi Anthony Fu <a href="https://github.com/antfu" target="_blank">@antfu</a></p></blockquote><p><a href="https://tsch.js.org/13/play" target="_blank"><img src="https://img.shields.io/badge/-Take%20the%20Challenge-3178c6?logo=typescript&logoColor=white" alt="Take the Challenge"/></a> &nbsp;&nbsp;&nbsp;<a href="./README.zh-CN.md" target="_blank"><img src="https://img.shields.io/badge/-%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-gray" alt="简体中文"/></a>  <a href="./README.ja.md" target="_blank"><img src="https://img.shields.io/badge/-%E6%97%A5%E6%9C%AC%E8%AA%9E-gray" alt="日本語"/></a>  <a href="./README.ko.md" target="_blank"><img src="https://img.shields.io/badge/-%ED%95%9C%EA%B5%AD%EC%96%B4-gray" alt="한국어"/></a> </p><!--info-header-end-->

Hello, World!

Ở Type Challanges, chúng ta sử dụng hệ thống kiểu dữ liệu (type system) để thực hiện mệnh đề khẳng định (assertion).

Trong thử thách này, bạn sẽ cần phải thay đổi đoạn code sau để qua được các tests (không có lỗi kiểu dữ liệu).

```ts
// đây sẽ phải là kiểu string
type HelloWorld = any
```

```ts
// bạn phải làm cho dòng này không bị lỗi
type test = Expect<Equal<HelloWorld, string>>
```

Nhấn vào nút `Thực hiện Thử thách` để bắt đầu code! Happy Hacking!

<!--info-footer-start--><br><a href="../../README.md" target="_blank"><img src="https://img.shields.io/badge/-Back-grey" alt="Back"/></a> <a href="https://tsch.js.org/13/answer" target="_blank"><img src="https://img.shields.io/badge/-Share%20your%20Solutions-teal" alt="Share your Solutions"/></a> <a href="https://tsch.js.org/13/solutions" target="_blank"><img src="https://img.shields.io/badge/-Check%20out%20Solutions-de5a77?logo=awesome-lists&logoColor=white" alt="Check out Solutions"/></a> <!--info-footer-end-->
