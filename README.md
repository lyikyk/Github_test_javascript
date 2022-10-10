# github_study
dev lecture for github test \
간단하게 자바스크립트로 구현 해봤습니다.

![image](https://user-images.githubusercontent.com/94099726/194860703-8a42f5c1-0a0a-4b2d-8cd1-8a7e5ffcc4ce.png)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

    <style>  /*  클래스 추가  */
        .color-primary{
            color:rgb(5, 23, 199);
        }
        .font-50{
            font-size: 50px;
        }

        .tb>thead>tr>td{
            border: 1px solid red;
        }
    </style>
</head>

<body>
    <h1 style="color: blue;">Hello Github</h1>  <!-- 문자에 컬러 style 추가 -->
    <h2 class="font-50">Subtitle.</h2>   <!-- class로 font 50크기 조정 -->
    <p class="color-primary">My First Paragraph</p>   <!-- class로 색 red 바꿈 -->

    <input type="text" />   #text 입력칸
    <input type="number" />   #숫자만 입력할 수 있는 입력칸
    <select style="height: 40px;font-size: 20px;color: green;">  <!-- select - style로 박스 크기 40px, 글자 크기 20px, 색 초록 조정 -->
        <option>Seoul</option>   <!-- 옵션 서울과 제주로 나뉨 -->
        <option>Jeju</option>
    </select>

    <table class="tb">   <!-- 테이블, class 적용 -->
        <thead>
            <tr>
                <td>이름</td>
                <td>지역</td>
                <td>전화번호</td>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>김용겸</td>
                <td>안양</td>
                <td>010-0000-0000</td>
            </tr>
        </tbody>
    </table>

    <a href="https://www.naver.com" target="_blank">네이버</a>

    <button type="button" onclick="javascript:alert('click!');">click</button>
    <img  width="400px"
    src="https://i0.wp.com/icnweb.kr/wp-content/uploads/2022/03/KU_korea-logo-600web.jpg?resize=600%2C193&ssl=1" alt="">
</body>
</html>
