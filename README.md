# data-visualization
📊 numpy와 pandas를 활용한 데이터 분석 및 시각화
## 서울시 공공자전거 이용 현황 🚲
- http://data.seoul.go.kr/dataList/OA-14994/F/1/datasetView.do
### 분석 배경
코로나19에 대한 걱정으로 대중교통을 이용하던 사람들이 공공자전거(이하 따릉이)를 타면서 [전년 대비 이용률이 약 67% 증가](https://news.seoul.go.kr/traffic/archives/503031)하였다.
비록 경기도인이라 따릉이를 이용하지는 못하지만, 날이 풀려서 따뜻한 봄날에 집에만 있기도 답답하고 찌뿌둥할 때 자전거를 타면 기분 전환도 되고 좋을 것 같아 분석 주제로 잡았다😁
### 분석 요약
<ul>
  <li>서울시 공공자전거 대여소 현황</li>
    <ul>
      <li>분석 당시 봄~초여름 시즌이라 summer 색상을 사용하여 파릇파릇한 느낌을 주었다고 발표했는데 생각하지 못한 곳에서 좋은 평가를 받았다😊</li>
      <img src="https://github.com/coding-Benny/data-visualization/blob/master/images/status-of-bicycle-rental-locations.png" alt="서울시 공공자전거 대여소 현황">
    </ul>
  <li>서울시 공공자전거 연간 대여건수</li>
    <ul>
      <li>viridis라는 다른 색상을 적용해보았고, 지역구 이름의 길이에 비해 그래프 사이의 간격이 촘촘해서 발생한 공간의 한계를 해결하고자 라벨을 살짝 기울여주었다.</li>
      <img src="https://github.com/coding-Benny/data-visualization/blob/master/images/number-of-annual-rentals-of-bicycles.png" alt="서울시 공공자전거 연간 대여건수">
    </ul>
  <li>서울시 공공자전거 지역별 대여소 수 대비 연간 대여 비율</li>
  <ul>
    <li>전체 데이터의 대표 값을 나타내는 직선을 기준으로 대여소 수 대비 대여 건수의 오차를 확인했다.</li>
    <img src="https://github.com/coding-Benny/data-visualization/blob/master/images/annual-rental-rate.png" alt="서울시 공공자전거 지역별 대여소 수 대비 연간 대여 비율">
  </ul>
</ul>
