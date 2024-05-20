
<!DOCTYPE html>
<html lang="ko">

<head>
<title>ARBITRA</title>
<meta charset="utf-8">
<meta name="viewport" 
content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Arial, Helvetica, sans-serif;
}

/* Style the header */
header {
  background-color: #666;
	text-align: center; 
	font-size: 25px; /*글자크기*/
	color: white;
	padding: 20px; /*테두리안쪽여백*/
}

/* Create two columns/boxes that floats next to each other */
nav {
 float: left;
 width: 30%; /*너비*/
 height: 300px; /* only for demonstration, should be removed */
 padding: 20px;
 background: #ccc;
}

	/* Style the list inside the menu */
	nav ul {
		list-style-type: none; /*목록없애기*/
		padding: 0;
	}


article {
  float: left;
  padding : 20px;
  width: 70%;
  background-color: #f1f1f1;
  height: 300px; /* only for demonstration, should be removed */
}

/* Clear floats after the columns */
section:after {
  content: "";
  display: table;
  clear: both; /*float속성해제 : left | right | both*/
}

footer {
  background-color: #777;
  padding: 10px;
  text-align: center;
  color: white;
}

/* Responsive layout - 
  makes the menu and the content (inside the section) 
	sit on top of each other 
	instead of next to each other */
	
@media (max-width: 600px) {
  section {
    -webkit-flex-direction: column;
    flex-direction: column;
  }
}
</style>
</head>
<body>

<h2>We stand here for good</h2>

<p>BESPOKE Portfolio 알고리즘을 개발하는 아비트라 주식회사는 다음과 같은 핵심 전략을 통해 사업화를 진행하고 있습니다.</p>

<p>- 국내외 주식, 이자율, ETF외 ELS, ELN, 장내외파생상품등 비선형상품군을 Pool에 편입하여 시장 기저 파라메터 추출, 시장 발견, 리스크 헤지, 차익 기회 탐지</p>

<p>- 빅데이터, 딥러닝, 블록체인, 오픈플랫폼, 마이데이터 등 진화된 기술 환경과 확장된 데이터 외연을 적극 채용하여, 혁신적 서비스 창출과 고객 가치 실현</p>

<header>
	<h2>ARBITRA Robo Advisor</h2>
</header>

<section id="main">
  <nav>
    <ul>
      <li><a href="/about/">About</a></li>
      <li><a href="/strategy/">Strategy</a></li>
      <li><a href="/technology/">Tchnology</a></li>
	  <li><a href="/plan/">Plan</a></li>
      <li><a href="/founder/">Founder</a></li>
    </ul>
  </nav>
  
  <article>
    <h1>Founder</h1>
    <div class="founder">
		<ul> 
			<li> - 투자은행 제이피모건, 코메르츠방크 Tokyo, DBS Bank Singapore </li>
			<li> - 신한금융투자 서울, Lukens Energy Group Houston </li>
            <li> - SAS 데이터마이닝 프로젝트 국민은행, 삼성카드, 신한은행 </li>
			<li> - 시카고대학교 금융수학 석사, 연세대학교 수학 학사 </li>			
            <li> - 투자자산운용사, 증권3종 권유대행인, FRM, 일본택지건물취인사 </li>
			<li> - Python, SAS, Matlab, Gauss, R, Javascript, Java, NoSQL </li>
            <li> - Equity, Rate, Credit, Commodity, Exotic Options, Structured Product </li>      
		</ul>
  </article>
</section>

        <section id="office">
            <div class="container">
                <div class="section-header text-center">
                    <h3>Here for you</h3>
                </div>
                <div class="section-body text-center">
                            <img src="/site/images/arbitra.PNG"/>
                </div>
            </div>
        </section>


<footer>
  <p>Footer</p>
                <div class="info">
                    <ul>
                        <li>아비트라 주식회사</li>
                        <li>사업자등록번호 853-87-01651</li>
                        <li>서울시 마포구 월드컵북로 47길 42</li>
                        <li>arbitracorporation@gmail.com</li>
                    </ul>
				</div>
	<p>COPYRIGHT © 2020. ALL RIGHTS RESERVED BY ARBITRA Co. Ltd</p>
</footer>

</body>
</html>
