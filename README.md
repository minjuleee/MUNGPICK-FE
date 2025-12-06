# 🐶 MungPick - 반려견 매칭 & 일정 관리 어플

---

## 📌 1. 프로젝트 소개

**멍픽(MungPick)** 은 반려견을 위한 매칭 기반 SNS 서비스입니다.
반려견의 성향과 정보에 맞춰 다른 강아지와 매칭을 연결해주며, 매칭이 성사되면 채팅을 통해 서로 교류하고 산책이나 놀이 약속도 잡을 수 있습니다.

매칭된 강아지들이 잡은 일정은 캘린더에 자동으로 공유되어 편리한 스케줄 관리가 가능하며, 사용자는 커뮤니티에서 반려견 정보를 공유하거나 멍비티아이(MBTI) 성향 검사 기능도 이용할 수 있습니다.

---

## 🕹️ 2. 서비스 주요 기능

1. **회원가입 / 로그인**
   - 기본 회원가입 & 로그인
   - 카카오/네이버/구글 소셜 로그인 지원
  
2. **강아지 건강 프로필 등록**
   - 반려견 기본 정보 입력 (이름, 나이, 견종 등)
   - 건강 상태, 예방 접종 여부, 특이사항 등록 

3. **매칭 페이지**
   - 반려견 프로필 기반 추천
   - 매칭 성공 시 채팅방 생성
   - 성공한 강아지들은 친구로 등록
  
4. **채팅 기능**
   - 매칭된 사용자끼리 실시간 채팅
   - 산책/놀이 약속 조율 가능
  
5. **캘린더**
   - 일정 등록 및 공유
   - 매칭된 강아지끼리 잡은 일정이 자동으로 동기화
  
6. **커뮤니티**
   - 정보, 노하우 교류
   - 댓글 및 좋아요 기능
  
7. **멍비티아이(DBTI) 검사**
   - 반려견 성향 테스트

8. **질문 및 문의**
   - 이용자 문의 접수
   - 서비스 관련 FAQ 제공

---

## 🖼️ 3. 실행 화면

### ✔ 캘린더 일정 추가 화면
<img width="3360" height="2100" alt="image" src="https://github.com/user-attachments/assets/c14866ad-470f-4187-b426-8234de070a06" />
일정 제목 / 일정 시간 / 일정 장소 / 함께 할 친구 선택 후 일정 추가

### ✔ 캘린더 초기 화면
<img width="3360" height="2100" alt="image" src="https://github.com/user-attachments/assets/618a14ae-491c-40f6-a77e-51cd9958c741" />
일정이 추가 된 캘린더 화면, 왼쪽 바에서 미니 캘린더와 오늘을 기준으로 일정을 분류해 날짜별로 리스트 정렬

### ✔ 일정 상세 화면
<img width="3360" height="2100" alt="image" src="https://github.com/user-attachments/assets/17033286-fa27-4cf9-9676-0b7377d73dc8" />
캘린더에서 일정을 클릭 시, 
일정 화면과 일기 화면이 나오는데 일기 화면은 사진 업로드 가능,
일정, 일기 수정 및 삭제 가능

### ✔ 채팅 화면
<img width="3360" height="2100" alt="image" src="https://github.com/user-attachments/assets/595345a5-2885-46ad-9c69-02e7f7cbb914" />
<img width="3360" height="2100" alt="image" src="https://github.com/user-attachments/assets/30d49d96-1ff5-4d19-bbd7-9c5e318f199b" />
<img width="3360" height="2100" alt="image" src="https://github.com/user-attachments/assets/71b35bad-eb7a-4bca-a2e1-0cf9254ca5ae" />
채팅 바에서 텍스트와 사진을 업로드하여 채팅 가능

### ✔ 채팅 일정 추가 화면
<img width="3360" height="2100" alt="image" src="https://github.com/user-attachments/assets/eb87bc66-609a-490f-a979-2d2fbaeed51f" />
채팅화면에서도 일정 추가 가능, 캘린더에서 연동

### ✔ 최종 결과 화면
<img width="3360" height="2100" alt="image" src="https://github.com/user-attachments/assets/e1351766-eabb-49f6-95e7-053471e5fbd0" />
<img width="3360" height="2100" alt="image" src="https://github.com/user-attachments/assets/d65cce9f-1ba9-4d7c-b06a-f8f7cc0ba8ce" />
오른쪽 바에서 상대와 함께 공유한 일정과 이미지 모두 한 눈에 볼 수 있음

---

## 📹 4. 시연 영상
ㅡ

[Demo 영상 보기](https://www.youtube.com/watch?v=nm-d-1po4gE)

---

## ⚙️ 5. 빌드 & 실행 방법

### ✔ Visual Studio
1. 프로젝트 클론
```bash
git clone <repository-url>
cd <project-folder>
```
2. Frontend 실행
```
// 패키지 설치
cd portfolio
yarn install

// 서버 실행
yarn start
```
3. Backed 실행
```
// 패키지 설치
cd portfolio-back
yarn install

// 서버 실행
nodemon app
```

---

## 🛠️ 6. 사용 기술

### **Frontend**
- React
- JavaScript
- React Router
- Fetch API
- Styled-components

### **Backend**
- Node.js
- Express
- REST API
- Nodemon (개발 환경)

### **Database**
- MongoDB

### **DevOps / 기타**
- Git & GitHub
- Yarn
- Postman

---

## 📄 7. 라이선스 & 개발자

Developer: minjuleee

License: MIT License

Contact: lmj26106058@gmail.com

