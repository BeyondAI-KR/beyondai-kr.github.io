---
layout: page
title: Contact Us
---

#### ㈜비욘드아이 위치안내

서울 서초구 남부순환로 2636, 501-에이4호 

---

![map](./assets/img/map.png)


#### 오시는 길

지하철 3호선 양재역 -> 양재전화국사거리쪽 도보 5분 거리


<p>
<script>
var mapContainer = document.getElementById('map'), // 지도를 표시할 div 
    mapOption = { 
        center: new daum.maps.LatLng(37.4848651314049, 127.03911387726), // 지도의 중심좌표
        level: 3 // 지도의 확대 레벨
    };

var map = new daum.maps.Map(mapContainer, mapOption); // 지도를 생성합니다

// 커스텀 오버레이에 표시할 내용입니다     
// HTML 문자열 또는 Dom Element 입니다 
var content = '<div class="daum_map bd_name">성문빌딩</div><div class="daum_map_arrow"></div>';

// 커스텀 오버레이가 표시될 위치입니다 
var position = new daum.maps.LatLng(37.4848651314049, 127.03911387726);  

// 커스텀 오버레이를 생성합니다
var customOverlay = new daum.maps.CustomOverlay({
    position: position,
    content: content   
});

// 커스텀 오버레이를 지도에 표시합니다
customOverlay.setMap(map);

var markerPosition  = new daum.maps.LatLng(37.4848651314049, 127.03911387726);  

// 마커를 생성합니다
var marker = new daum.maps.Marker({
    position: markerPosition
});

// 마커가 지도 위에 표시되도록 설정합니다
marker.setMap(map);

</script>
</p>
