---
layout: post_manual
title: 3.4.2.	Scan Setting
date: 2025-03-31 13:20:23 +0900
category: "lite_kor"
lang: ko
order: 3420
---

# 3.4.2. Scan Setting

<br/> <!-- 한줄 띄기 -->

<!-- 중앙 정렬 이미지 -->
<p align="center"> 
  <img src="/assets/Chapter-3/Scan setting.png">
</p>

<!-- 이미지 설명 -->
<div align="center"> 
<h5>Figure 46. Scan setting</h5>
</div>

-	Single pulse delay: 싱글 모드로 설정 시 각 레이저 사이에 들어갈 delay, 해당 값을 0으로 하면 스캔 속도는 대략적으로 20Hz 정도가 됨. (Spacing 값에 따라서 다름) 이때 스캐닝의 속도를 느리게 해야 된다면 해당 딜레이 값을 설정해서 조절 가능.
-	Periodic Scanning Speed: 1Hz ~ 1000Hz 등 레이저가 일정 주파수로 설정 되었을 때 스캔 이동 속도, 1~1000 의 정수 값
-	Pulse Freq: 레이저 발진 주파수, [0, 1, 10, 100, 500, 1000]으로 설정 가능, 0일 경우 Single shot 모드이다. Single shot에서는 위치에 도달하고 레이저 1회 발진 수행.
-	Energy: 레이저 에너지를 nJ 단위로 입력, 해당에너지를 기준으로 스캐닝 시의 편광자를 조절함, 이를 위해서 스캔 이전에 알맞은 에너지 측정 파일을 세팅해야 함.
-	X1, Y1: 스캔 시작 기준 좌표
-	Width, Height: 스캔 할 범위의 넓이
-	Depth: 스캔을 진행할 깊이를 설정하고 테스트의 일관성을 확보하기 위해, 스캔 시작 전에 Chip 표면에 대한 포커스를 조정하고 해당 값을 명확히 지정한 후 테스트를 수행할 것을 권장.
-	Spacing: single shot 모드일 시 각 레이저의 간격 (단위: μm)
-	Point: 주어진 값으로 계산된 포인트 개수 (자동 출력 값)
-	Exp time: 추정 시간 값 (자동 출력 값, 미구현)
-	Segment: 선택 항목의 영역을 분할
-	Up / Down: 선택 항목을 이동
-	Duplicate: 선택 항목 복사
-	Delete: 선택 항목 삭제

<!-- 이전/다음 페이지 버튼 -->
<br/>
<br/>
