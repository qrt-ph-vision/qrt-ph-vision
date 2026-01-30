---
layout: post_manual
title: 3.3.1.	Focus 탭
date: 2025-03-31 13:20:23 +0900
category: "lite_kor"
lang: ko
order: 3310
---

# 3.3.1. Focus 탭

<br/> <!-- 한줄 띄기 -->

<!-- 중앙 정렬 이미지 -->
<p align="center"> 
  <img src="/assets/Chapter-3/Focus 탭.png">
</p>

<!-- 이미지 설명 -->
<div align="center"> 
<h5>Figure 40. Focus 탭</h5>
</div>

### 1. Focus Mode
5가지의 자동 초점 방식이 있으며Auto Focus를 수행할 방식을 설정합니다. 모드 마다 포커스 되는 지점의 수준이 다를 수 있습니다. 각 방법은 유사한 결과를 내지만 반도체의 표면처리 상태에 따라, Front-side injection이냐 Back-side injection이냐에 따라서 Focus 방식을 선택할 수 있습니다. 예를 들어 FFT(Fast Fourier Transform 방식의 경우 만약 미러 폴리싱(mirror polishing)된 Back-side를 사용한다면 표면의 고 주파수 성분을 찾는 해당 방법은 유효하지 않을 수 있고(Mirror polishing된 표면은 고주파 성분이 많아, FFT를 통해 분석할 때 노이즈가 증가할 수 있습니다. 이는 초점 잡기에 필요한 신호 대 잡음 비율(SNR)을 저하시킬 수 있습니다.) 이런 경우 STD(Standard Deviation)나 휘도(Brightness) 방식이 더 선호될 것입니다.  
-	Check: 단순 포커스 계산 값을 도출함, 포커스 지점으로의 이동 안함
-	FFT: FFT 방법을 이용해서 포커스를 도출 후 해당 지점으로 이동 
-	FFT STD: FFT로 주파수 도메인으로 변환한 이후 STD값을 구하는 방식으로 포커스 도출 후 해당 지점으로 이동
-	STD: STD 값을 포커스 정도의 지표로 이용, 도출 후 해당 지점으로 이동
-	Brightness(휘도): 밝기를 기준으로 포커스 정도를 파악, 도출 후 해당 지점으로 이동


### 2. Camera
Visual(가시광선) 또는 IR(적외선) 카메라로 설정할 수 있습니다.


### 3. Depth Range
현재 높이부터 위아래로 탐색할 영역을 설정합니다. 예) 1mm → +/- 0.5mm


### 4. 3가지 버튼의 기능
-	Auto Focus: 오토 포커스 수행
-	Rough Focus: 먼 거리에서 대략적인 포커스를 수행하는 기능(미구현)
-	Stop: 정지








<!-- 이전/다음 페이지 버튼 -->
<br/>
<br/>
