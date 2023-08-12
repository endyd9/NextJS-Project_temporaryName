# 부동산 거래내역 조회및 가격 비교 서비스

### 공공데이터 국토교통부 아파트매매 실거래 상세 자료 사용

# ToDo

## Page 명세

- 메인✅
- 회원가입 기능구현✅
- 로그인, 로그아웃 기능구현✅
- 검색✅
- 마이페이지✅
- 내 정보 수정✅

## DB 명세

### User

- id : number(auto)
- createdAt : DateTime
- updatedAt : DateTime
- email : string
- password : string
- nickName : string

### Like

- id : number(auto)
- createdAt : DateTime
- updatedAt : DateTime
- user : User
- Apt : Apt

### Apt

- id : number(auto)
- name : string
- dedicatedArea : number
- floor : number
- buildYear : number
- treadDate : number
- treadAmount : number
- cityCode : number
- dong : string
- roadName : string
- buildingNumber : number
- buildingMinorNumber : number
- view : number
