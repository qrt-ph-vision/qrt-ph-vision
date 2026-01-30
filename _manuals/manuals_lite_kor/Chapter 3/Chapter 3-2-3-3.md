---
layout: post_manual
title: 3.2.3.3.	PEM(Pulse Energy Meter)탭
date: 2025-03-31 13:20:23 +0900
category: "lite_kor"
lang: ko
order: 3233
---

# 3.2.3.3. PEM(Pulse Energy Meter)탭

Pulsed Laser 조사, Pulse Energy측정 등 레이저 장비의 Control을 할 수 있는 탭입니다.

<br/> <!-- 한줄 띄기 -->

<!-- 2x2 이미지 테이블 -->
<table align="center">
  <tr>
    <td align="center">
      <img src="/assets/Chapter-3/PEM 탭.png" alt="PEM 탭">
      <div>Figure 33. PEM 탭</div>
    </td>
    <td align="center">
      <img src="/assets/Chapter-3/PEM.png" alt="PEM">
      <div>Figure 34. PEM</div>
    </td>
  </tr>
</table>

Polarizer 각도에 따른 Pulse 에너지를 측정하는 부분입니다. DUT 위치에서 PEM 설치 후 Visual Camera를 통해서 초점을 맞춘 후 300μm 정도 PEM와 objective lens가 가까워지게 하여(결과 consistency를 위해서) 측정을 수행합니다.
-	Pulse meter: refresh를 눌러서 연결된 펄스 미터 컨트롤 박스를 검색 후 설정.
-	Channel: 컨트롤 박스에 연결된 위치에 따라서 맞는 Channel를 설정.
-	Wave Length: 측정할 레이저의 파장을 입력.
-	Measure Delay: 각 측정 사이의 시간 딜레이 값 (추천 값 500ms)
-	Range: 내부 Polarizer의 회전 각도 범위(레이저 에너지는 90도 기준으로 반복되므로 45도 정도로 설정)
-	Step Size: 각 측정 각도의 단위
-	Measure 버튼: 측정 시작
-	Stop 버튼: 현 지점에서 측정 정지
-	Save 버튼: 측정된 데이터 저장 

<!-- 이전/다음 페이지 버튼 -->
<br/>
<br/>
