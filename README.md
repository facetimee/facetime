# facetime


>**딥러닝을 이용한 인물 분류기** 

<h2> 팀원</h2>
<ul>
  <li>17011780 김연우</li>
  <li>17011850 이세정</li>
  <li>17011830 백소현</li>
  <li>17011820 송민주</li>
</ul>

</hr>

<h2>현재까지의 진행사항</h2>

* **주제 변경**: 표정 분류기->인물 분류기<br>

  -> 이유 : 표정 분류기보단 인물 분류기가 데이터셋을 직접 모아 가공하고 학습하는 부분에서 더 적합하다고 생각했다. 

* **개발 환경 구축을 위한 프로그램 설치** <br>
: open cv, dlib, face_recognition, cmake, numpy 등

* **코드 작성** <br>
camera open, face-detect, eye-detct, face-recognition를 수행할 코드를 작성

* **코드에 대한 이해** <br>
코드에 대한 이해와 분석의 시간 가짐

* **데이터셋** <br>
분류기가 인식할 인물 사진 수집 -> 이 부분은 진행중에 있음

<h3> https://drive.google.com/open?id=1KDPgsvNACyX8onYHCFgIrQQq6upLZRbY </h3>

<h2>전체 계획대비 진행상황</h2> 

 **<진행 중 및 앞으로의 계획>**
 * 분류기가 인식할 인물의 범위 확대(더 다양한 인물의 데이터 수집 후 데이터 셋 구성) <br>
 * 데이터 셋을 통해 분류기가 학습을 통해 인물을 식별해 내고 결과를 화면에 표시할 수 있도록 코드 작성. <br>
 * 분류기 자체의 정확도와 오차 계산 후 정확도 높이기 및 오차 줄이기 <br>
 * 인식하는 카메라의 속도가 느린 현재 상황에서, 카메라의 문제인지 분류기의 성능 문제인지분석, 만약 분류기의 성능 문제라면 이를 보완할 수 있는 코드 추가 작성 <br>
 * 분류기가 적용될 수 있는 상황에 대해 이를 응용하여 사용할 수 있도록 이를 엑셀,홈페이지 와 같은 외부 프로그램과 연동하는 여러가지 기능들을 추가. <br>

 **<인물 분류기 수행 목표>**
 * 카메라에 비춰진 모습에서 얼굴과 눈을 인식하는 코드를 작성한다. <br>
 * 인식할 인물들의 사진을 모아 각각 데이터 셋으로 구성하고 이를 이용하여 학습을 수행한다. <br>
 * 작성된 코드와 학습한 데이터를 바탕으로 해당 인물을 식별해낸다. <br>
 * 데이터 셋에 있는 인물일 경우 인식한 얼굴 옆에 인물의 이름이 표시되고, 그렇지 않은 경우에 ‘unknown’으로 표시된다. <br>
 * 적용될 수 있는 여러가지 상황을 설정 한 후, 이를 수행할 수 있게하는 기능들을 추가한다. (코드 작성, 데이터 셋 구성, 트레이닝, 다른 프로그램과의 연동 등을 통해) <br>

 **<인물 분류기 실생활 적용 목표>**<br>
 
* **프라이버시 지킴이** <br>
개인적인 용무의 창을 띄워두었다가 카메라에 본인이 아닌 다른 사람이 비춰지면 분류기가 이를인식해, 자동으로 다른 창으로 바뀔 수 있도록 한다. <br>
* **출석 체크** <br>
부정 출석을 방지하기 위해, 교수님이 class전체를 카메라로 비추면 분류기가 인물을 인식하고 출석한 학생들의 이름이 엑셀 창에 자동으로 등록된다. <br>


  


<h2>참고자료</h2>

num| 사이트
--------- | ---------
1 | <https://medium.com/data-science-lab-amsterdam/face-recognition-with-python-in-an-hour-or-two-d271324cbeb3>
2 | https://www.codemade.io/the-worlds-simplest-facial-recognition-api-for-python-and-the-command-line/
3 | https://m.blog.naver.com/PostView.nhn?blogId=samsjang&logNo=220699662173&proxyReferer=https%3A%2F%2Fwww.google.com%2F
4 | https://blog.naver.com/jh_p0415/221327006301
5 | https://gyeongju.tistory.com/entry/DLIB-C-Library







