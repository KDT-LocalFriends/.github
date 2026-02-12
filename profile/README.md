<img width="1126" height="638" alt="Image" src="https://github.com/user-attachments/assets/aaf1bb66-dc3b-4c37-8ac6-7203d5357914" />

## 📜 서비스 소개

---

마스코트 키우기는 AI 추천, 챗봇, 게임화를 결합하여 **새로운 국내 여행지 탐색과 지역 소비를 촉진하는 참여형 플랫폼**입니다.

특히 정보 부족으로 여행지를 결정하지 못하는 **2030 청년층**을 주요 타겟으로, 개인화된 코스 추천과 방문 인증 보상을 통해 **탐색 → 방문/체험 → 재참여**의 선순환을 만들어냅니다.

## 🏆 성과

---

### **고용노동부 장관상 수상**

## 🧩 주요 기능

---

### 여행지 추천

전국의 지역소멸 위기 도시와 인근 지역을 대상으로, 성별·연령 등 기본 정보와 추가 설문(선호 환경, 차량 보유 여부, 여행 스타일, 소비 성향)을 기반으로 맞춤 여행지를 추천

### 마스코트 키우기

지역 마스코트를 캐릭터화하여, 앱 내 활동으로 아이템을 장착하거나 먹이를 주어 꾸미기 및 진화가 가능

### 챗봇 관광 안내

마스코트와 대화하며 위치 기반으로 관광지·식당·숙소를 테마별 3곳씩 추천받고 상세 정보를 제공

## 🛠️ 기술 스택

---

**Backend**

- Java, Spring Boot, JPA, Spring Security
- JWT, Redis, H2 Database

**AI/Chat Server**

- Python, FastAPI
- GPT-4, BGE-Reranker

**Infrastructure**

- AWS EC2, Route 53
- Swagger, Git

## 💻 개발 내용

---

### 인증 시스템

- JWT 토큰 기반 인증 및 회원가입 후 자동 로그인 처리

### 게임 시스템

- 경험치 기반 캐릭터 자동 진화 (EGG→DUCK) 및 일일 활동 제한 시스템
- 인벤토리 카테고리별 필터링 및 실시간 착용 상태 조회

### 결제/상점 시스템

- 포인트 기반 인 앱 결제 기능 구현
- 상품 구매, 기부, 영상 시청 보상 기능 구현
- `@Version` 낙관적 락으로 동시성 제어 및 `@Cacheable`로 조회 성능 최적화

### AI 챗봇 시스템 (FastAPI)

- 김해시 공식 API 실시간 연동 및 BGE-Reranker 기반 하이브리드 검색
- GPT-4 답변 생성 및 Redis 캐싱으로 응답 속도 88% 개선 (16초 → 2초)

## 📺 서비스 화면

---

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/ec19bbaf-90d1-4dda-8ff2-f4a123dad2c4" width="250" /></td>
    <td><img src="https://github.com/user-attachments/assets/bf412143-9973-49fb-aa12-cb957d847d35" width="250" /></td>
    <td><img src="https://github.com/user-attachments/assets/028d1e45-ca16-4674-80bc-f4cb17edc02f" width="250" /></td>
    <td><img src="https://github.com/user-attachments/assets/449438a1-2c3d-4356-8763-0effd5406a48" width="250" /></td>
  </tr>
</table>

[![demo](https://github.com/user-attachments/assets/a343b66f-9266-4646-9aca-d1578b2e6bb6)](https://github.com/user-attachments/assets/b258d76e-50fa-4b8e-bf2b-6f20af327e6a)

