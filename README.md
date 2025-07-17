## Hi there 👋

<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>자기소개</title>

  <!-- Google Fonts 불러오기 -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600&family=Nanum+Gothic:wght@400;700&display=swap" rel="stylesheet">

  <style>
    /* 기본 설정 */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background-color: #fff8f0; /* 따뜻한 크림색 배경 */
      color: #444;
      padding: 30px;
      line-height: 1.6;
      animation: fadeIn 1s ease-in-out; /* 부드러운 애니메이션 */
    }

    h2 {
      font-size: 28px;
      font-weight: 600;
      margin-bottom: 15px;
      color: #f76c6c;  /* 산뜻한 따뜻한 핑크색 */
      border-bottom: 2px solid #f1c6c6; /* 부드러운 핑크색 */
      padding-bottom: 8px;
      margin-top: 40px;
    }

    p {
      font-size: 16px;
      margin-bottom: 25px;
      padding-left: 20px;
      color: #555;  /* 더 부드럽고 따뜻한 그레이 */
    }

    strong {
      color: #ff8f72;  /* 따뜻한 오렌지 색상 */
      font-weight: 600;
    }

    /* 링크 스타일 */
    a {
      color: #ff8f72;
      text-decoration: none;
      font-weight: 500;
      transition: color 0.3s ease;
    }

    a:hover {
      color: #ff7f50; /* 링크 호버 색상 (산뜻한 오렌지) */
    }

    /* 이메일 스타일 (plain-email 클래스 추가) */
    .plain-email {
      color: #000 !important;       /* 검정색 */
      font-weight: normal !important; /* bold 해제 */
    }

    /* 이미지 스타일 */
    img {
      border-radius: 12px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s ease;
    }

    img:hover {
      transform: scale(1.05);  /* 이미지 확대 효과 */
    }

    /* 부드러운 페이드 인 애니메이션 */
    @keyframes fadeIn {
      from {
        opacity: 0;
        transform: translateY(10px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    /* 반응형 디자인 */
    @media (max-width: 600px) {
      body {
        padding: 20px;
      }

      h2 {
        font-size: 22px;
      }

      p {
        font-size: 14px;
      }
    }
  </style>
</head>

<body>

  <h2>ABOUT ME 💖</h2>
  <p>
    <strong>name</strong> 유은채 <br>
    <strong>birth</strong> 1999.07.08 <br>
    <strong>major</strong> 간호학과 <br>
    <strong>hobby</strong> 조용한 카페 가기 , 드라이브 , 산책하기 <br>
    <strong>today's mood</strong> 피곤 😴<br>
    <strong>E-mail</strong> <a href="mailto:yuec1226@gmail.com" class="plain-email">yuec1226@gmail.com</a>
  </p>

  <h2>HISTORY 🗓️</h2>
  <p>
    <strong>경력사항</strong> 2023.08-2024.11 이대서울병원 근무 <br>
    2025.01-2025.04 임상연구코디네이터 근무
  </p>
  <p><strong>가장 좋았던 여행지</strong> 스페인 세비야 , 이탈리아 마테라 </p>

  <h2>I WANT.. 💭</h2>
  <p><img src="images.jpg" alt="휴일 이미지" width="50" height="50"></p>
  <p>포근한 침대에서의 휴일 🛏️<br>1년 이내 개발직무 취업 💻<br>맛있는 산미가 적은 고소한 커피 ☕</p>

  <h2>ETC 🔗</h2>
  <p><a href="https://namu.wiki/w/ISFJ">MBTI 🧠</a></p>
  <p><a href="https://www.youtube.com/watch?v=ILTHidJwGkA">좋아하는 유튜브 영상 🎥</a></p>

</body>
</html>

