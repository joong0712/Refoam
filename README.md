# 🧠 Re:Foam – 스마트팩토리 품질 예측 및 공정 관리 시스템

Re:Foam은 제조 공정 데이터를 기반으로 품질을 예측하고, 실시간 공정 상태를 시각화하여 효율적인 생산 관리를 돕는 스마트팩토리 솔루션입니다.  
본 저장소는 팀 프로젝트 중 제가 맡았던 **AI 품질 예측 모델 개발, Flask API 구축, WebSocket 실시간 처리, OpenAI 기반 리포트 자동화** 파트를 중심으로 정리된 코드 및 문서입니다.

---

## 🔧 주요 기능 (담당 파트)

- 품질 예측 모델 개발 (SVM, Random Forest, Linear Regression 등) 및 성능 비교
- 최종 모델을 Flask API로 배포하고 Spring Boot 서버와 연동
- WebSocket(STOMP)을 활용한 공정 상태 실시간 모니터링 및 대시보드 시각화
- OpenAI API를 활용한 품질 검수 리포트 자동 생성
- EC2 기반 배포 환경 구성 및 테스트

---

## 🛠 사용 기술

| 분야 | 기술 스택 |
|------|------------|
| AI/ML | Python, scikit-learn, pandas, TensorFlow (실험용) |
| 백엔드 | Flask, Spring Boot, JPA |
| 프론트 | Thymeleaf, Chart.js |
| 실시간 처리 | WebSocket, STOMP, SockJS |
| 기타 | AWS EC2, MySQL(RDS), Git, GitHub |

---

## 🙋‍♂️ Contributor

- **이현중 (AI / 데이터 분석)**  
  품질 예측 모델링, API 개발, 실시간 처리, OpenAI 리포트 자동화 담당, 에러모니터링 페이지 구현  
---




## 📌 참고 사항

- 본 저장소는 팀 프로젝트의 일부 기능을 개인 기준으로 정리한 것입니다.
- 상세 구현 방식 및 시연 화면은 팀장 저장소 또는 발표 자료를 참고해 주세요.
