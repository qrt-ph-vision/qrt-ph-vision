---
layout: post_manual
title: 3.7.1.2.	오실로스코프(MSO)를 이용한 민감 영역 분석(Sensitive Area) 이미지 생성
date: 2025-03-31 13:20:23 +0900
category: "lite_kor"
lang: ko
order: 3712
---

# 3.7.1.2. 오실로스코프(MSO)를 이용한 민감 영역 분석(Sensitive Area) 이미지 생성

<br/> <!-- 한줄 띄기 -->

<!-- 2x2 이미지 테이블 -->
<table align="center" style="border-collapse: collapse; border: none;">
  <tr>
    <td align="center" style="border: none;">
      <img src="/assets/Chapter-3/S-Map Generator.png" alt="S-Map Generator">
      <div>Figure 55. S-Map Generator 탭</div>
    </td>
    <td align="center" style="border: none;">
      <img src="/assets/Chapter-3/S-Map.png" alt="S-Map">
      <div>Figure 56. S-Map Example</div>
    </td>
  </tr>
</table>

Chip의 Sensitive Area를 분석한 이미지를 생성하는 탭입니다.
-	Image: Chip Image file
-	Image QTPA file: Image file폴더에 있는 QTPA파일
-	MSO folder: MSO trigger log folder
-	Scan log: Scan log folder
-	Base Color: 단일 색으로 표현 시 사용할 색 설정
-	Shift: 실제 좌표와 S-Map의 좌표 쉬프트가 생겼을 시 사용
-	Pixel size of an error: 에러 하나당 표시할 픽셀 수
-	Convert base to Gray Image: Chip Image 흑백모드
-	Gradient Enable: 체크 시 2개의 색으로 S-Map 생성
-	Top / Bottom Color: 상위 색과 하위 색 설정(2 / 3개의 색으로 표현 시)
-	Top / Bottom Voltage: Voltage Range
-	Add Color Bar: 좌측 상단의 컬러 바 on / off
-	3 Color Mode: 활성화 시 Top, Base, Bottom 3가지 색으로 S-Map 생성
-	Use Max Peak: SET발생 전압이 양수일 시 체크

<!-- 이전/다음 페이지 버튼 -->
<br/>
<br/>
