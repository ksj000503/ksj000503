<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0E1128&height=220&section=header&text=Kim%20Seongjae&fontSize=45&fontColor=FFFFFF&desc=Game%20Client%20Developer&descAlignY=65&descSize=18" />
</div>

## 👋 안녕하세요, 김성재입니다

- 🎮 언리얼 엔진 5 기반 멀티플레이어 게임 클라이언트 개발에 관심
- 🧩 Blueprint 기반 시작 → C++ 게임 시스템 및 네트워크 리플리케이션으로 영역 확장
- 🛠️ 문제 원인을 끝까지 추적해 해결하는 과정에서 재미를 느낌

<br>

## ✨ Tech Stack

### 🎮 Engine & Language
<div align="left">
  <img src="https://img.shields.io/badge/Unreal%20Engine%205-0E1128?style=for-the-badge&logo=unrealengine&logoColor=white" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white" />
  <img src="https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white" />
</div>

### 🛠️ Tools
<div align="left">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white" />
</div>

<br>

## 🚀 Projects

### 🎯 EternalReturn — 이터널 리턴 모작 (UE5, 진행중)
> 이터널 리턴(Eternal Return)을 언리얼 엔진으로 재현한 멀티플레이어 포트폴리오 프로젝트

- **선정 이유:** 이터널 리턴 플레이 중 게임 구조에 대한 궁금증에서 시작
  상용 게임 수준의 전투/스킬, 인벤토리, 시야 시스템, 몬스터 AI 등을 직접 설계·구현하며 멀티플레이어 개발 파이프라인 전반 경험 목표
- **기술 스택:** Unreal Engine 5.7 · C++ / Blueprint · Listen Server · 자체 TCP 백엔드(Winsock2, MySQL 8.4)
- **주요 기능:** 스킬 컴포넌트, 스탯 컴포넌트, Seamless Travel
- **Troubleshooting:** RepNotify 패턴 적용해 클라이언트 간 상태 동기화 문제 해결
  Accessed None 에러 단계별 추적 및 디버깅
- **개발 방식:** C++, Blueprint


<img width="446" height="250" alt="Skill" src="https://github.com/user-attachments/assets/ad6d1089-1302-44f8-858a-ec143ea3ec6c" />


<img width="446" height="250" alt="Inven" src="https://github.com/user-attachments/assets/7c53e4a5-1bfb-4fa7-a264-2bef2b7a2e43" />

- [📂 레포지토리 바로가기](https://github.com/ksj000503/EternalReturn)


### 🥔 POTATO SURVIVORS — 로그라이트 서바이버 (Unity, 완료)
> Brotato 스타일 탑다운 서바이버 — 데이터 주도 설계 + 자동화 QA
- **선정 이유:** Unity·C#로 시스템 설계 역량을 확장하고, 구현과 별개로 QA(자동 테스트·검증) 프로세스를 직접 세워보는 목표
  ScriptableObject 데이터 주도로 오브젝트 추가 시 코드 수정 없이 콘텐츠 확장 가능한 구조 설계
- **기술 스택:** C# — 전체 게임 로직 / ScriptableObject — 무기·아이템·설정 데이터화 / Resources 자동 로드 — 씬 수동 배선 제거 / New Input System / uGUI — 런타임 자가 생성 UI / Unity Test Framework — 단위 테스트
- **주요 기능:** 6슬롯 자동 공격 무기(레벨 강화 + 근접/원거리 세트 효과), 오브젝트 풀 기반 몬스터·보스 웨이브, 등급·행운 상점, 이벤트 기반 HUD/상점 UI
- **QA:** 자동 단위 테스트(Unity Test Framework), 테스트 케이스 55개로 버그 6건 검출·수정, 인게임 디버그 콘솔(F1)
- **개발 방식:** 데이터 주도(ScriptableObject) + 이벤트(Observer) 기반, AI 페어 프로그래밍(Claude) 활용
- 🔗 [GitHub](https://github.com/ksj000503/Unity-Project) · [상세(Notion)](https://app.notion.com/p/3d4a0fe77a6d81bcafb9ec83901137d0)

<img width="336" height="188" alt="gameplay" src="https://github.com/user-attachments/assets/d98b0f2f-d348-4c50-8790-791d2878a86d" />

<img width="372" height="210" alt="debug" src="https://github.com/user-attachments/assets/baddabba-5e08-476c-be82-376c71e1ba41" />


### 🚪 Project_EscapeRoom — 방탈출 시뮬레이션 (UE5, 완료)
> Data-Driven 방식으로 구현한 방탈출 프레임워크

- **선정 이유:** Blueprint만으로 확장성 있는 시스템 설계 가능성 검증 목표
  오브젝트별 로직 재작성 없이 콘텐츠 확장 가능한 데이터드리븐 구조 설계
- **기술 스택:** Blueprint — 전체 게임 로직 / DataTable — 인터랙션 오브젝트 데이터 관리 / UMG — 인벤토리 UI (드래그 앤 드랍, 퀵 슬롯)
- **주요 기능:** DataTable 기반 공통 인터랙션 시스템 (문/열쇠 통합 관리, 그래프 수정 없이 콘텐츠 확장 가능)
  드래그 앤 드랍 인벤토리, 퀵 인벤토리 슬롯
- **개발 방식:** Blueprint Only


<img width="400" height="225" alt="2026-06-19 23-11-14" src="https://github.com/user-attachments/assets/8e102d9b-1389-48ff-a6fb-8cdede15f80e" />


<img width="400" height="225" alt="2026-06-19 23-09-38" src="https://github.com/user-attachments/assets/cb44414a-0d4e-45d9-8eaa-5133b252d4c7" />

- [📂 레포지토리 바로가기](https://github.com/ksj000503/Project_EscapeRoom)

<br>

## 📜 Certificates & Education

- 🏆 **리눅스 마스터 2급** (2022.10)
- 🎓 **서원대학교** 정보보안학과 졸업 (2025.02)

<br>

## 📫 Contact

<div align="left">
  <a href="mailto:rlatjdwi0503@naver.com">
    <img src="https://img.shields.io/badge/rlatjdwi0503@naver.com-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://github.com/ksj000503">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</div>

---
<div align="right">
  Last Updated: 2026.06
</div>
