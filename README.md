🩺 PedTalk
Pediatric Emergency Communication Data Collection Platform
소아응급 문진 AI 학습을 위한 현장형 대화 데이터 수집 시스템
📌 Overview
PedTalk는
소아응급실 문진 AI 에이전트 개발을 위한 실제 대화 데이터 수집 플랫폼입니다.
의학적 조언뿐 아니라
보호자의 감정(Fear Care)까지 함께 반영된
현장 기반 문진 데이터를 확보하는 것을 목표로 합니다.
🎯 Problem Statement
소아응급 문진 AI를 만들기 위해서는:
✔️ 정확한 의학적 정보
✔️ 보호자의 감정 케어
✔️ 실제 현장과 유사한 대화 데이터
가 모두 포함된 학습 데이터가 필요합니다.
하지만 기존 데이터는:
감정 케어가 부족하거나
실제 임상 흐름을 반영하지 못하거나
개인정보 문제로 활용이 어렵다는 한계가 있습니다.
💡 Solution
PedTalk는 다음 구조로 문제를 해결합니다:
1️⃣ 데이터 수집
수련의 기반 문진 대화 수집
보호자-의료진 시뮬레이션
개인정보 없이 대화 데이터 확보
2️⃣ Fear Care 반영
보호자의 주요 감정:
두려움
불안
걱정
초조함
이를 케어하기 위한 대화 요소:
안심 및 지지
현실적 정보 제공
경과 및 회복 가능성 설명
긍정적 가능성 언급
🏗 System Architecture
Pipeline
데이터 수집
데이터 선별
AI 학습
대화 생성 및 시뮬레이션
🤖 Models Used
Model	Role
SBERT	Fear Care 문장 유사도 판단
LLM	진단 방향 설정 + 감정 케어 대화 생성
SVM	진료 우선순위 분류
Random Forest	증상 기반 질병 예측
📱 Application Features
로그인 기능
케이스 선택
보호자-의료진 대화 인터페이스
요약 화면 제공
평가/피드백 기능
📊 Data Scale
RIAS 벤치마킹 기반:
약 1,200문장 수집
6개월간 데이터 확보
LLM Fine-tuning 가능 규모 확보
🔬 Expected Impact
소아응급 문진 AI 학습 데이터 확보
보호자 감정 케어 기반 AI 고도화
실제 진료 환경에 가까운 시뮬레이션 데이터 구축
개인정보 걱정 없이 활용 가능한 대화 데이터
🧠 Key Contribution
✔️ 의료 정보 + 감정 케어를 동시에 학습
✔️ 소아응급 특화 데이터 구축
✔️ AI 기반 진단 + 커뮤니케이션 개선
✔️ 실제 임상 흐름 반영 구조 설계
👥 Team
7조 – 에잇 데이 프로젝트
📚 Reference
Heo et al.
Communication challenges and experiences between parents and providers in South Korean paediatric emergency departments: a qualitative study to define AI-assisted communication agents
