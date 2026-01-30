---
layout: post_manual
title: 3.3.2.	Corner Detection 탭
date: 2025-03-31 13:20:23 +0900
category: "lite_kor"
lang: ko
order: 3320
---

# 3.3.2. Corner Detection 탭

<br/> <!-- 한줄 띄기 -->

<!-- 중앙 정렬 이미지 -->
<p align="center"> 
  <img src="/assets/Chapter-3/Corner Detection 탭.png">
</p>

<!-- 이미지 설명 -->
<div align="center"> 
<h5>Figure 41. Corner Detection 탭</h5>
</div>

Chip Image와 실제 DUT의 좌표를 동기화하는 좌표Set-up 작업의 편리성을 위해 부착된 Chip의 4 모서리를 찾아주는 기능입니다.
Pulsed Laser 장비 GUI는 Chip의 이미지를 활용하여 여러가지 기능들을 제공합니다. 이를 사용하기 위해서는 Chip의 이미지와 스테이지의 위치의 4점(4point)을 매핑해 주어야 합니다. 이 작업 시에 사각형 반도체의 네 모서리를 찾아주는 해당 기능을 사용 할 수 있습니다.
-	Scan size: XY축으로 스캔할 사이즈, Chip의 사이즈 보다 크게 설정.
-	Camera: 해당 기능을 사용할 때 사용할 카메라
-	Sensitivity: 해당 기능은 이미지의 밝기 차이를 사용하는데 이때 밝기 차이의 기준이 되는 수치. 해당 기능이 오작동 할 시 이 수치를 변경.
-	Auto Corner Detection 버튼: 기능 시작
-	Move 버튼: 탐색한 4개의 포인트를 해당 버튼을 통해 해당 포인트로 이동


사용 순서 예시
1.	Auto Focus기능을 이용하거나 수동으로 대략적인 Focus맟춤. (Chip 내부와 외각이 구분되는 정도)
2.	Chip의 내부로(대강 중심) XY Stage를 이동.
3.	반도체 Chip의 사이즈를 고려하여 Scan size를 설정.
4.	Auto Corner Detection을 클릭하여 기능을 수행. 자동으로 Stage가 상하좌우로 이동하며 코너를 탐색.
5.	탐색된 결과값을 Move 버튼을 통해 확인.

<!-- 이전/다음 페이지 버튼 -->
<br/>
<br/>
