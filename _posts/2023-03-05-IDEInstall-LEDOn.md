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

### 1. 아두이노 IDE 열기

### 2. 왼쪽 상단 파일 > 환경설정 > 추가적인 보드 매니저 URLs > 우측 버튼 클릭
<img src= "https://user-images.githubusercontent.com/63178658/223050088-ce9e3ce4-b1c4-4ae6-967a-f8320445745c.png"/>
<br>
<img src= "https://user-images.githubusercontent.com/63178658/223050090-c122f353-8abe-4ee9-aaf8-4635e95a79b1.png"/>
<br/><br>
### 3. https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_dev_index.json
<br/><img src= "https://user-images.githubusercontent.com/63178658/223050093-a236922c-8385-4bba-80ec-df46f53ad6a8.png"/>
위 URL 붙여넣기 후 확인<br/><br>
### 4. 툴 > 보드 > 보드매니저 클릭
<img src= "https://user-images.githubusercontent.com/63178658/223050098-b0c9a4f6-189d-4c3d-ae66-1dc9ddc318a5.png"/>
<br/><br>
### 5. esp32 검색 후 install
<img src= "https://user-images.githubusercontent.com/63178658/223050082-b726529e-364b-4b54-b97f-c740cee37292.png"/>
<br><br/>

## ESP32 연결 
<hr/>
### 1. 툴 > 보드 > ESP32 > 해당 esp32 종류 확인 후 설정
<img src= "https://user-images.githubusercontent.com/63178658/223051835-105d1043-d271-4aa3-89d4-670d91351a2e.png"/>
<br>
### 2. esp32 노트북과 연결
<img src = "https://user-images.githubusercontent.com/63178658/223051944-66b8d24c-0246-4728-b688-ca75904658a3.jpg"/>
<br>
### 3. 툴 > Port > Port 연결 확인
<img src = "https://user-images.githubusercontent.com/63178658/223053471-997780fa-02f6-4483-a58a-5b59312fc72b.png"/>
<br>
### 4. esp32 LED 아래와 같이 연결
<img src = "https://user-images.githubusercontent.com/63178658/223055291-ea943bd9-f871-4d79-8535-69b0c0637d92.jpg"/>
<img src = "https://user-images.githubusercontent.com/63178658/223055284-71e94a94-1f33-46dc-b09c-712292c31092.jpg"/>
<br>
### 5. IDE에 코드 입력
<img src = "https://user-images.githubusercontent.com/63178658/223054958-606854b5-d8d5-48ec-a23e-541ae1b7b449.png"/>
<br>
### 6. Upload ( 왼쪽 상단에 ' -> ' 표시 클릭)
<img src = "https://user-images.githubusercontent.com/63178658/223057009-1aa64ec1-a67c-4c7b-baac-f8553626753f.png"/>
Connecting...이 뜰 때 esp32에 BOOT 버튼 2초 이상 Press
<img src="https://user-images.githubusercontent.com/63178658/223057014-c7f12fef-6238-4f56-9618-30a3d3888535.png"/>
<img src="https://user-images.githubusercontent.com/63178658/223056791-e6dfc507-0279-4194-aea5-ee70db659ea0.jpg"/>
<br>
### 7. 점등 확인
<img src = "https://user-images.githubusercontent.com/63178658/223054964-78939bb2-7d3a-4fab-9a4b-66b84c8366bd.png"/>
<img src="https://user-images.githubusercontent.com/63178658/223055278-61aabaa6-d98e-495f-8d2f-f3f7d1570b34.jpg"/>
<br>

