<h2>📌 PART 5. 데이터 사전 처리</h2>

**전체 코드 및 결과를 확인하시려면 [여기](https://github.com/tae2On/Technical_Books_Notes/blob/main/%ED%8C%8C%EC%9D%B4%EC%8D%AC%20%EB%A8%B8%EC%8B%A0%EB%9F%AC%EB%8B%9D%20%ED%8C%90%EB%8B%A4%EC%8A%A4%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EB%B6%84%EC%84%9D/05.%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%82%AC%EC%A0%84%20%EC%B2%98%EB%A6%AC/%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%82%AC%EC%A0%84%20%EC%B2%98%EB%A6%AC.ipynb "전체 코드 보기") 를 클릭하세요.<br> 각 예제 코드와 그 결과를 자세히 확인하실 수 있습니다.**

<h3><a href="https://github.com/tae2On/Technical_Books_Notes/blob/main/%ED%8C%8C%EC%9D%B4%EC%8D%AC%20%EB%A8%B8%EC%8B%A0%EB%9F%AC%EB%8B%9D%20%ED%8C%90%EB%8B%A4%EC%8A%A4%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EB%B6%84%EC%84%9D/05.%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%82%AC%EC%A0%84%20%EC%B2%98%EB%A6%AC/1.%20%EB%88%84%EB%9D%BD%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%B2%98%EB%A6%AC.md">1. 누락 데이터 처리</a></h3>

<h3><a href="https://github.com/tae2On/Technical_Books_Notes/blob/main/%ED%8C%8C%EC%9D%B4%EC%8D%AC%20%EB%A8%B8%EC%8B%A0%EB%9F%AC%EB%8B%9D%20%ED%8C%90%EB%8B%A4%EC%8A%A4%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EB%B6%84%EC%84%9D/05.%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%82%AC%EC%A0%84%20%EC%B2%98%EB%A6%AC/2.%20%EC%A4%91%EB%B3%B5%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%B2%98%EB%A6%AC.md">2. 중복 데이터 처리</a></h3>

<h3><a href="https://github.com/tae2On/Technical_Books_Notes/blob/main/%ED%8C%8C%EC%9D%B4%EC%8D%AC%20%EB%A8%B8%EC%8B%A0%EB%9F%AC%EB%8B%9D%20%ED%8C%90%EB%8B%A4%EC%8A%A4%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EB%B6%84%EC%84%9D/05.%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%82%AC%EC%A0%84%20%EC%B2%98%EB%A6%AC/3.%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20%ED%91%9C%EC%A4%80%ED%99%94.md">3. 데이터 표준화</a></h3>

*단위 환산, 자료형 변환*

<h3><a href="https://github.com/tae2On/Technical_Books_Notes/blob/main/%ED%8C%8C%EC%9D%B4%EC%8D%AC%20%EB%A8%B8%EC%8B%A0%EB%9F%AC%EB%8B%9D%20%ED%8C%90%EB%8B%A4%EC%8A%A4%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EB%B6%84%EC%84%9D/05.%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%82%AC%EC%A0%84%20%EC%B2%98%EB%A6%AC/4.%20%EB%B2%94%EC%A3%BC%ED%98%95(%EC%B9%B4%ED%85%8C%EA%B3%A0%EB%A6%AC)%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%B2%98%EB%A6%AC.md">4. 범주형(카테고리) 데이터 처리</a></h3>

*구간 분할, 더미 변수*

<h3><a href="https://github.com/tae2On/Technical_Books_Notes/blob/main/%ED%8C%8C%EC%9D%B4%EC%8D%AC%20%EB%A8%B8%EC%8B%A0%EB%9F%AC%EB%8B%9D%20%ED%8C%90%EB%8B%A4%EC%8A%A4%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EB%B6%84%EC%84%9D/05.%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%82%AC%EC%A0%84%20%EC%B2%98%EB%A6%AC/5.%20%EC%A0%95%EA%B7%9C%ED%99%94.md">5. 정규화</a></h3>

<h3><a href="https://github.com/tae2On/Technical_Books_Notes/blob/main/%ED%8C%8C%EC%9D%B4%EC%8D%AC%20%EB%A8%B8%EC%8B%A0%EB%9F%AC%EB%8B%9D%20%ED%8C%90%EB%8B%A4%EC%8A%A4%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EB%B6%84%EC%84%9D/05.%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%82%AC%EC%A0%84%20%EC%B2%98%EB%A6%AC/6.%20%EC%8B%9C%EA%B3%84%EC%97%B4%20%EB%8D%B0%EC%9D%B4%ED%84%B0.md">6. 시계열 데이터</a></h3>

*다른 자료형을 시계열 객체로 변환, 시계열 데이터 만들기, 시계열 데이터 활용*
