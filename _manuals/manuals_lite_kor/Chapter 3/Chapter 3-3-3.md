---
layout: post_manual
title: 3.3.3.	Level 탭
date: 2025-03-31 13:20:23 +0900
category: "lite_kor"
lang: ko
order: 3330
---

# 3.3.3. Level 탭

<br/> <!-- 한줄 띄기 -->

<!-- 중앙 정렬 이미지 -->
<p align="center"> 
  <img src="/assets/Chapter-3/Level 탭.png">
</p>

<!-- 이미지 설명 -->
<div align="center"> 
<h5>Figure 42. Level 탭</h5>
</div>

Stage에 마운트 되어 있는 Chip의 기울기를 측정 및 수정하는 기능을 합니다. 사용자는 측정할 축(x, y, both), 측정 범위를 설정해서 이를 수행합니다. 현재 위치로부터 설정한 범위만큼 z축 50μm를 빠르게 측정합니다. 이후 정확도를 높이기 위해 앞선 빠른 스캔으로 찾은 부분의 주위를 측정합니다. 그러기 때문에 Chip이 너무 많이 기울어 있어서 측정 범위 내 Chip 높이가 50μm 이상 차이 나면 안되고, Leveling을 수행하기 전에 기준점에서의 Focus가 어느정도 맞지 않으면 기능 수행에 실패 할 수 있습니다. 반도체 Chip의 패키지, 납땜 상태 등등 여러 요인으로 육안으로 보았을 시에 평평해 보이더라도 레이저 테스트 시에는 10μm나 0.5도의 차이만으로도 결과에 영향을 줄 수 있습니다.
-	Leveling Mode: Both- XY축에 대한 수평을 측정, X / Y- 선택한 축에 대한 수평만 측정.
-	Area Size: Leveling을 수행할 때 일정 범위의 스캔을 수행하는데 이 때의 스캔 범위
-	Auto Level 버튼: 해당 기능 시작
-	Fix 버튼: 해당 기능을 통해서 찾은 leveling 값 적용


사용 순서 예시
1.	Chip의 내부로(대강 중심) XY Stage를 이동.
2.	Auto Focus 기능을 이용하거나 수동으로 대략적인 Focus를 맞춤. (Chip 내부와 외각이 구분되는 정도)
3.	Mode와 Size를 설정.
4.	Auto Level 버튼을 클릭하여 실행.
5.	그래프로 보이는 결과를 확인해서 측정과 기울기 계산이 정확한지 판단.
6.	계산된 기울기 값을 Fix 버튼을 클릭하여 적용.


<!-- 이전/다음 페이지 버튼 -->
<br/>
<br/>
