---
layout: post_manual
title: 2.3.1. Intelligent SEU Manager(ISM) 설정하기
date: 2025-03-31 13:20:23 +0900
category: "lite_kor"
lang: ko
order: 2310
---

# 2.3.1. Intelligent SEU Manager(ISM) 설정하기

ISM은 QRT에서 제작한 방사선 평가를 위한 프로그램입니다. GUI 기반 실시간 데이터 모니터링은 Laser SEE Test를 수행하기에 적합한 사용성을 제공합니다 
1.	DUT제대로 연결 되었는지 확인.
2.	좌측 상단에 Setup클릭
3.	Test PGM Setup에서는 Test name 입력 및 PGM 파일을 설정.
4.	Recipe에는 Test를 진행할 Recipe파일을 설정하고 필요시 Pretest Recipe 설정.
※	Recipe의 수정이 필요하다면 메인 화면 상단에 Recipe Editor를 통한 수정이 가능.
5.	Apply To Close를 누르면 Setup이 저장되고 테스트 가능
-	Test Abort 시 Test결과가 C/SEU/Result에 Test시작 시간 및 DUT정보로 폴더 생성 및 저장
-	Test 재 시작 시 Initialize 누른 뒤 Test Start

<br/> <!-- 한줄 띄기 -->

<!-- 2x2 이미지 테이블 -->
<table align="center">
  <tr>
    <td align="center">
      <img src="/assets/Chapter-2/ISM.png" alt="Intelligent SEU Manager">
      <div style="margin-top: 10px;">Figure 12. ISM</div>
    </td>
    <td align="center">
      <img src="/assets/Chapter-2/ISM Set-up.png" alt="ISM Set-up">
      <div style="margin-top: 10px;">Figure 13. ISM Set-up</div>
    </td>
  </tr>
</table>



<!-- 이전/다음 페이지 버튼 -->
<br/>
<br/>
