## Use Case Description

### **1. 회원 가입**

| Actor Action (비회원) | System Response |
| --- | --- |
| 1. None | 2. 회원 가입 양식 표시 |
| 3. ID, 비밀번호, 전화번호 입력 | 4. 메뉴 이름과 번호 및 회원 가입한 회원의 ID, 비밀번호, 전화번호 출력 |

### **2. 로그인**

| Actor Action (회원/관리자) | System Response |
| --- | --- |
| 1. None | 2. 로그인 양식 표시 |
| 3. ID와 비밀번호 입력 | 4. 메뉴 이름과 번호 및 로그인한 ID, 비밀번호 출력 |

### **3. 로그아웃**

| Actor Action (회원/관리자) | System Response |
| --- | --- |
| 1. None | 2.  메뉴 이름과 번호 및 로그아웃 한 사용자의 ID 출력 |

### **4. 자전거 정보 등록**

| Actor Action(관리자) | System Response |
| --- | --- |
| 1. None | 2.  자전거 정보 등록 양식 표시 |
| 3. 등록할 자전거 ID와 자전거 제품명 입력 | 4. 메뉴 이름과 번호 및 등록한 자전거의 ID, 제품명 출력 |

### **5. 자전거 대여**

| Actor Action (회원) | System Response |
| --- | --- |
| 1. None | 2.  자전거 대여 양식 표시 |
| 3. 대여할 자전거 ID 입력 | 4. 메뉴 이름과 번호 및 대여한 자전거의 ID, 제품명 출력 |

### **6. 자전거 대여 정보 조회**

| Actor Action (회원) | System Response |
| --- | --- |
| 1. None | 2. 메뉴 이름과 번호 및 현재 대여 중인 자전거 (자전거 ID, 자전거 제품명 포함) 목록 출력 |