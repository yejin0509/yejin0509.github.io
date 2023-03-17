---
layout: post
title: "Week2_SetUp"
subtitle: IDE 설치 및 내부 LED 점멸
tag: Smart_Device
thumbnail-img: "https://user-images.githubusercontent.com/63178658/223021248-17441d33-53a8-461a-97a2-d528fc809069.png"
---
<br><br>
<br><br>



## 1️⃣ 아두이노 IDE 설치
<hr/>
<br>
[https://www.arduino.cc/en/software](https://www.arduino.cc/en/software)<br/>
#### 위에 링크에 접속하여 Arduino IDE 설치<br>
<img src="https://user-images.githubusercontent.com/63178658/223021248-17441d33-53a8-461a-97a2-d528fc809069.png"/>
<br><br>
<br><br>
<br><br>



## 2️⃣ 아두이노 IDE에서 ESP32 설정
---
<br>
### 1. 아두이노 IDE 열기
<br><br>


### 2. 왼쪽 상단 파일 > 환경설정 > 추가적인 보드 매니저 URLs > 우측 버튼 클릭
<br>
<img src= "https://user-images.githubusercontent.com/63178658/223050088-ce9e3ce4-b1c4-4ae6-967a-f8320445745c.png"/>
<br>
<img src= "https://user-images.githubusercontent.com/63178658/223050090-c122f353-8abe-4ee9-aaf8-4635e95a79b1.png"/>
<br><br>


### 3. 아래 URL 붙여넣기 후 확인
<br>
#### https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_dev_index.json
<br><img src= "https://user-images.githubusercontent.com/63178658/223050093-a236922c-8385-4bba-80ec-df46f53ad6a8.png"/>
<br><br>


### 4. 툴 > 보드 > 보드매니저 클릭
<img src= "https://user-images.githubusercontent.com/63178658/223050098-b0c9a4f6-189d-4c3d-ae66-1dc9ddc318a5.png"/>
<br><br>
### 5. esp32 검색 후 install
<img src= "https://user-images.githubusercontent.com/63178658/223050082-b726529e-364b-4b54-b97f-c740cee37292.png"/>
<br><br>
<br><br>
<br><br>



## 3️⃣ ESP32 연결 
<hr/>
<br>
### 1. 툴 > 보드 > ESP32 > 해당 esp32 종류 확인 후 설정
<img src= "https://user-images.githubusercontent.com/63178658/223051835-105d1043-d271-4aa3-89d4-670d91351a2e.png"/>
<br><br>


### 2. esp32 노트북과 연결
<img src = "https://user-images.githubusercontent.com/63178658/223051944-66b8d24c-0246-4728-b688-ca75904658a3.jpg"/>
<br><br>


### 3. 툴 > Port > Port 연결 확인
<img src = "https://user-images.githubusercontent.com/63178658/223053471-997780fa-02f6-4483-a58a-5b59312fc72b.png"/>
<br><br>
<br><br>
<br><br>

## 4️⃣ 내부 LED 점멸
<hr/>
<br>

### 1. IDE에 코드 입력
<img src = "https://user-images.githubusercontent.com/63178658/224239018-c12cffb7-55bb-4cb3-b957-c6ba2c9f042d.png"/>
<img src = "https://user-images.githubusercontent.com/63178658/224238791-1b2cc901-ce04-4cf4-a9f5-2ca7caace2b2.png"/>
<br><br>


### 3. Upload ( 왼쪽 상단에 ' -> ' 표시 클릭)
<img src = "https://user-images.githubusercontent.com/63178658/224239408-14da4d79-f19a-497c-b3f2-5867b645c18f.png"/><br>
<br><br>

#### Connecting...이 뜰 때 esp32에 BOOT 버튼 2초 이상 Press
<br>
<img src="https://user-images.githubusercontent.com/63178658/223057014-c7f12fef-6238-4f56-9618-30a3d3888535.png"/>
<br>
<img src="https://user-images.githubusercontent.com/63178658/224239868-d5cbe1d4-ec2a-4e2c-b2af-0c961f2a4139.jpg"/>
<br><br>


### 4. 점멸 확인
<img src = "https://user-images.githubusercontent.com/63178658/224239162-e68f6337-40ad-4bcd-9ebc-0185696d4b66.jpg"/>
<br>
<img src = "https://user-images.githubusercontent.com/63178658/224246427-5f176c27-a0ee-4165-86ee-d097253fa15d.gif"/>


<br><br><br>

