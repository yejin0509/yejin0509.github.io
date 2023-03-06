---
layout: post
title: "2주차 - 기초 설정"
subtitle: IDE 설치 및 LED 점등
---

## 아두이노 IDE 설치
<hr style="1"/>
[https://www.arduino.cc/en/software](https://www.arduino.cc/en/software)<br/>
<a href="https://www.arduino.cc/en/software"></a>
<img src="https://user-images.githubusercontent.com/63178658/223021248-17441d33-53a8-461a-97a2-d528fc809069.png"/>
위에 링크에 접속하여 Arduino IDE 설치
<br/><br/>

## 아두이노 IDE에서 ESP32 설정
---

1. 아두이노 IDE 열기
<img src= "https://user-images.githubusercontent.com/63178658/223050088-ce9e3ce4-b1c4-4ae6-967a-f8320445745c.png"/>
<br/>
2. 왼쪽 상단 파일 > 환경설정 > 추가적인 보드 매니저 URLs > 우측 버튼 클릭
<img src= "https://user-images.githubusercontent.com/63178658/223050090-c122f353-8abe-4ee9-aaf8-4635e95a79b1.png"/>
<br/>
3. https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_dev_index.json
<br/><img src= "https://user-images.githubusercontent.com/63178658/223050093-a236922c-8385-4bba-80ec-df46f53ad6a8.png"/>
위 URL 붙여넣기 후 확인<br/>
4. 툴 > 보드 > 보드매니저 클릭
<img src= "https://user-images.githubusercontent.com/63178658/223050098-b0c9a4f6-189d-4c3d-ae66-1dc9ddc318a5.png"/>
<br/>
5. esp32 검색 후 install
<img src= "https://user-images.githubusercontent.com/63178658/223050082-b726529e-364b-4b54-b97f-c740cee37292.png"/>
<br/><br/>

## ESP32 연결 
<hr/>
1. 툴 > 보드 > ESP32 Arduino 설정
