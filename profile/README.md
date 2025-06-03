# 🥚 반숙이 (Bansoogi) – 조금 더 나은 일상을 위하여

<p align="center">
  <img src="https://github.com/user-attachments/assets/cdd28192-9f08-4397-974d-ed5e28e31c70" width="250" alt="반숙이 로고"/>
</p>

<h1 align="center"> 반숙이 (Bansoogi)</h1>
<p align="center">
  귀여운 캐릭터와 함께<br>
  조금 더 움직이고, 조금 덜 보게 만드는<br>
  습관 변화 서비스
</p>

<p align="center">
  <i>“귀여움은 보너스, 행동 변화는 확실하게”</i>
</p>

---

> 반숙이는 갤럭시 워치와 스마트폰 센서를 활용해  
> 사용자의 일상 데이터를 실시간으로 감지하고,  
> 즉각적인 피드백과 보상으로 건강한 루틴 형성을 돕는 서비스입니다.  
> **30분 이상 앉거나 스마트폰을 사용할 경우**, 캐릭터가 알림과 함께 행동을 유도하고,  
> 변화된 행동에는 에너지 보상을 제공해 지속적인 습관 개선을 유도합니다.

---



## 🚀 앱 배포 현황

| Store | Mobile App | Watch App |
|--------|------------|----------|
| **ONE Store** | ✅ 배포 완료<br>[바로가기](https://m.onestore.co.kr/ko-kr/apps/appsDetail.omp?prodId=0001000633) | ❌ 미지원 |
| **Google Play** | 🔧 준비 중 | 🔧 준비 중 |
| **Galaxy Store** | 🔧 준비 중 | 🔧 준비 중 |


## 🔧 기술 스택

| 분류 | 세부 기술 |
|------|-----------|
| **개발** | Kotlin + Jetpack Compose (모바일)<br>Wear OS (워치) |
| **데이터 저장** | Realm (로컬 DB) |
| **센서 처리** | SensorManager<br>Samsung Health Sensor SDK<br>UsageStatsManager |
| **데이터** | Samsung Health Data SDK |
| **통신 및 연동** | Bluetooth Low Energy (BLE, GATT 기반 통신) |
| **추론 알고리즘** | LightGBM / TFLite + 슬라이딩 윈도우 |


---

## 🎮 주요 기능

| 기능군 | 세부 내용 |
|--------|----------|
| ⏰ 실시간 알림 | - 30분 이상 좌식 또는 스마트폰 사용 시 푸시 / 워치 진동<br>- 행동 변화 시 즉각 보상 (에너지 +10) |
| 🐥 캐릭터 동기화 | - 7가지 상태 반영 (앉음, 누움, 걷기 등)<br>- 실시간 애니메이션 상태 반영 |
| ⚡ 에너지 시스템 | - 하루 최대 100점 에너지 획득<br>- 누적에 따라 일반 / 특별 반숙이 지급 |
| 📊 히스토리 & 도감 | - 일별 활동 기록<br>- 수집한 Bansoogi 확인 가능 |
| 🌙 수면-연동 | - 기상 / 취침 시점 기반으로 에너지 초기화 |
| 🍽 식사 미션 | - 알림 기반 체크 → 에너지 추가 획득 |

---

## 🎯 기획 배경

- 대한민국 국민은 하루 평균 **9시간 좌식**, **5시간 이상 스크린 타임**
- WHO, ACS 연구 등에서는 **"30분 앉기 → 5분 걷기"**만으로도 건강 개선 가능
- **즉각적인 피드백 + 시각화 + 수집 요소**가 행동 변화 유도에 효과적이라는 수많은 사례 존재

---

## 👥 팀원 소개

|  | 이름 / GitHub | 역할 | 비고 |
|--|----------------|------|------|
| <img src="https://avatars.githubusercontent.com/u/77507952?v=4" width="150"/> | [윤병희](https://github.com/username1) | 팀장 / Android | - |
| <img src="" width="150"/> | [김영진](https://github.com/haochaen73) | Android | - |
| <img src="" width="150"/> | [엄윤준](https://github.com/june2301) | Android | - |
| <img src="" width="150"/> | [원기훈](https://github.com/nOOne-is-hier) | ML / Android | - |
| <img src="" width="150"/> | [정유진](https://github.com/jjuj99) | Android | - |
| <img src="" width="150"/> | [형서희](https://github.com/Seohui-Hyung) | Android | - |

---

## 🎓 이론 기반 설계

| 목표 | 반숙이 설계 요소 | 관련 이론 |
|------|------------------|-----------|
| 움직임 유도 | 좌식 30분 이상 시 알림 | Operant 강화 이론 |
| 스마트폰 줄이기 | 화면 시청 30분 이상 시 하품 & 경고 | 자기결정이론 (SDT - 관계성) |
| 자기 인식 | 상태 → 캐릭터 표정 실시간 동기화 | CASA 이론, 자기효능감 |
| 감정 유대 | 행동 시 점수 + 레벨업 + 진화 | Operant 조건화, SDT - 유능감 |

---

## 🧠 기대 효과

- **작은 실천** → 건강 증진 & 자기 인식 강화 (메타인지)
- **감정 기반 피드백** → 사용자와 캐릭터의 유대감 형성
- **루틴 형성 & 유지** → Transtheoretical Model 기반의 행동 변화 단계 설계

---

## 🚀 향후 목표

- **BLE 기반 퍼스널 디바이스 연동 고도화**
- **성별/나이대별 맞춤형 행동 유도 패턴 적용**
- **Bansoogi IP 확장 (굿즈 / 캐릭터 컬렉션 콘텐츠)**

---

## 💌 Contact & Community
- Instagram: [@bansoogi_official](https://www.instagram.com/bansoogi?igsh=ZHl4cDZ1YnljczBy)
- 문의: ddc.manager25@gmail.com
