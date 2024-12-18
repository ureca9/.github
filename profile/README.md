# 🐾 강아지 동반 시설 공유 플랫폼, 멍티비티
<img src="https://github.com/user-attachments/assets/c235d4cd-6332-48f8-bd19-211a31f2a7f5" width="400">
<img src="https://github.com/user-attachments/assets/6f07a9de-d098-44da-86ae-fe03204dbef8" width="200">
<img src="https://github.com/user-attachments/assets/74634f39-bf1f-40d0-8177-fadec20ee1ec" width="200">

---
# 👩‍💻 주요 기능
### 1. 소셜 로그인
- 카카오 소셜 로그인<br>
  <img src="https://github.com/user-attachments/assets/d2252adf-1129-466d-a8fc-43e70b03be4e" width="400">

<br>
  
### 2. 반려동물 정보 관리
- 반려동물 프로필 관리 (CRUD)

<br>

### 3. 검색
- 검색어로 검색 <br>
  <img src="https://github.com/user-attachments/assets/a5ce31d5-1cf8-4729-bc17-0af179335a4c" width="400">
  
- 지역, 날짜, 같이 갈 반려동물 선택 후 해당 정보를 반영하여 장소 검색
- JooQ를 도입하여 로그인 여부에 따른 좋아요 검색, 페이징 여부에 따른 검색 등 동적으로 검색 가능
- 기상청 단기 예보 조회 API와 중기 예보 조회 API를 사용하여 지역 선택 시 당일부터 10일 후까지의 날씨 정보 제공
  <img src="https://github.com/user-attachments/assets/2aaadc01-9fde-482a-a4fd-c20028501cdd" width="500">
  
<br>

### 4. 즐겨찾기
- 장소에 즐겨찾기를 할 수 있고, 즐겨찾기 한 장소를 모아 볼 수 있다.



<br>

### 5. 후기
- 장소에 사진, 영상을 포함한 후기를 남길 수 있고, 내가 쓴 후기를 모아 볼 수 있다.
  <img src="https://github.com/user-attachments/assets/0fbcbd6f-c071-43fc-9153-798fae13bdb7" width="500">
  <img src="https://github.com/user-attachments/assets/98ad9968-101d-45ea-b40c-a23eadaebe6f" width="500">

<br>

### 6. 지도
- 즐겨찾기 한 장소의 정보를 알 수 있다.
  
- 즐겨찾기 한 장소의 위치를 핀을 통해 알 수 있다.
  
- 지도에서 장소를 검색할 수 있다.

<br>

### 7. 길찾기

<br>

### 8. 추천
- 콘텐츠 기반 필터링과 협업 필터링을 사용하여 보다 정확한 추천
  
- 협업 필터링에서 대규모 데이터 처리와 기계 학습 기반 추천 라이브러리 Mahout을 사용
  
- 사용자의 리뷰 데이터와 선호 지역을 기반으로 개인 별 맞춤 펜션 추천 제공<br>
  <img src="https://github.com/user-attachments/assets/0dbf1aea-7945-46ee-8f21-0a4198875aec" width="500">
  
- 사용자의 리뷰 데이터와 거리를 기반으로 펜션 연관 시설 추천 제공<br>
  <img src="https://github.com/user-attachments/assets/84fc8f52-8342-4dae-aae3-16bffba65c35" width="500">

<br>

### 9. 조회 수 기반 핫한 장소
- 조회 수를 기반으로 핫한 장소를 카테고리 별로 조회할 수 있다. <br>
  <img src="https://github.com/user-attachments/assets/eff33e23-8282-4f3c-a4e5-60f5ff722dc1" width="500">

<br>

### 10. 최근 본 장소
- 최근 본 장소를 조회할 수 있다. <br>
  <img src="https://github.com/user-attachments/assets/fd0a9bee-f673-480f-98c6-f26cc56aa677" width="400">
  <img src="https://github.com/user-attachments/assets/9ec52872-f1d1-4f1e-a9bc-eee631e8e52e" width="400">

<br>

### 11. 멍생네컷
- 프레임과 이미지 4장을 골라 멍생네컷을 만들 수 있다. <br>
  <img src="https://github.com/user-attachments/assets/04b02e95-2c74-4b40-a53d-bca7416e0b55" width="300">
  <img src="https://github.com/user-attachments/assets/b7a833f8-88fd-4f0e-8d19-66f4e5194599" width="300">
  <img src="https://github.com/user-attachments/assets/3b48ad9a-01b2-4442-be59-c3067f78a3b3" width="300">

<br>

- 이미지는 공유할 수 있고, 나의 멍생네컷 목록과 전체 멍생네컷 목록을 조회 할 수 있다. <br>
  <img src="https://github.com/user-attachments/assets/26849813-adcc-41cd-aa4e-d766e38b28a0" width="400">

<br>

---
# 💡 소프트웨어 아키텍처
![image](https://github.com/user-attachments/assets/b6312b78-f23a-465c-9829-630489901d36)

# 💡 ERD
![멍멍99](https://github.com/user-attachments/assets/6f3e987f-a69f-4df8-9e6f-70fcd05f6e65)
