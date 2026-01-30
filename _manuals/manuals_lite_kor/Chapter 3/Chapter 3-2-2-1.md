---
layout: post_manual
title: 3.2.2.1.	XYZ
date: 2025-03-31 13:20:23 +0900
category: "lite_kor"
lang: ko
order: 3221
---

# 3.2.2.1. XYZ

<br/> <!-- 한줄 띄기 -->

<!-- 2x2 이미지 테이블 -->
<table align="center">
  <tr>
    <td align="center">
      <img src="/assets/Chapter-3/XYZ.png" alt="XYZ">
      <div style="margin-top: 10px;">Figure 23. XYZ 탭</div>
    </td>
    <td align="center">
      <img src="/assets/Chapter-3/XYZ Stage.png" alt="XYZ Stage">
      <div style="margin-top: 10px;">Figure 24. XYZ Stage</div>
    </td>
  </tr>
</table>

Pulsed Laser 장비의 XYZ 스테이지를 컨트롤 하는 페이지입니다. 각 기능의 설명은 다음과 같습니다.
-	XY Step: XY에 해당하는 방향키를 한 번 클릭했을 때 이동하는 거리 (Continuous control이 아닐 때 적용)
-	Z Step: Z에 해당하는 방향키를 한 번 클릭했을 때 이동하는 거리 (Continuous control이 아닐 때 적용)
-	XY Manual Speed: XY축 이동 스피드 (Continuous control일 때 적용)
-	Z Manual Speed: Z축 이동 스피드 (Continuous control일 때 적용)
-	XY Step per μm: 모터 스텝 당 거리 이동 비 (기본 값: 32, Setting에서 Developer Edit mode를 세팅하여 수정 가능)
-	Z Step per μm: 모터 스텝 당 거리 이동 비 (기본 값: 5, Setting에서 Developer Edit mode를 세팅하여 수정 가능)
-	Speed factor: 거리 변수 단순 곱 증가
-	Continuous control: 설정 시 클릭을 유지하는 것으로 이동, 비 설정 시 한 번의 클릭으로 세팅 된 거리(Step값) 만큼 이동
-	Auto Position Check: 설정 시 실시간으로 현재 위치를 계산해서 Chip Image 위에 원형 점으로 위치를 표시. (미 설정 후 Scan시 현재 위치 표시x)
-	방향키: 해당 방향으로 스테이지를 이동 (Z 스테이지의 경우 위 방향키는 렌즈와 가까워지는 방향 임으로 충돌에 유의를 요함)
-	Set XY zero: 현재 위치로 zeroing 수행
-	Set Z zero: 현재 위치로 zeroing 수행
-	Status: 스테이지로부터 스테이터스 값 read
-	Position: 스테이지로부터 포지션 값 read
 


<!-- 이전/다음 페이지 버튼 -->
<br/>
<br/>
