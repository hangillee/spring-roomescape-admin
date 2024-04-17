## 구현 기능 목록

### 어드민 메인 페이지

- `localhost:8080` 요청 시 Welcome 페이지 응답
- `localhost:8080/admin` 요청 시 어드민 메인 페이지 응답

### 예약 관리 페이지

- `/admin/reservation` 요청 시 예약 관리 페이지 응답
- `/reservations` GET 요청 시 예약 목록 응답
- `/reservations` POST 요청 시 예약 생성
- `/reservations/{id}` DELETE 요청 시 예약 삭제

### 시간 관리 페이지
- `/times` POST 요청 시 시간 추가
- `/times` GET 요청 시 시간 목록 응답
- `/times/{id}` DELETE 요청 시 시간 삭제