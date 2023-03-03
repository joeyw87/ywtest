# Sample Project Template

## 프로젝트 개요
- Back-end 개발을 위한 Spring Boot 샘플 프로젝트 입니다.

<!-- 
    주석 부분
-->

## 프로젝트 기간
- 2022.08.01 ~ 2022.12.30

## 주요 기능
- 공용 로그함수 사용 API 샘플
- 암호화 사용 API 샘플
  - MAP
  - 모델 
- API Handler 구조 구현 샘플
- 쿼리 조회 API 샘플
- 쿼리 아이디 리스트 조회 API 
- 개발자 로그인 API 샘플

## 개선 사항 ###
- 개선이 필요한 사항 미진행된 사항 
- 개선 일정이 필요한것들

## 이슈 기능 ###
- [x] 버그 및 오류 내용
- [x] ~~수정 완료시 취소선~~
- [ ] 12312  



## 기타 작성 예시
## 머리말 (Header)
* # H1 입니다.

* ## H2 입니다.

* ### H3 입니다.

* #### H4 입니다.

* ##### H5 입니다.

* ###### H6 입니다.

### 수평선 (Horizon)

***

### 개행(New line)

강제개행 문법입니다.  
문장끝의 공백을 통해 개행이 적용됩니다.

단락바꿈 문법입니다.

Enter키를 통해 개행이 적용됩니다.

### 인용구 (BlockQuote)

> 인용구입니다.

>> 인용구안에 인용구를 사용할 수 있습니다.

### 목록 (List)

* 순서가 없는 리스트입니다.
    * 리스트1
    * 리스트2
    * 리스트3

* 순서가 있는 리스트입니다.
    1. 리스트1
    2. 리스트2
    3. 리스트3

* 상위 리스트1
    * 하위 리스트1
    * 하위 리스트2
        * 하위의 하위 리스트1
        * 하위의 하위 리스트2

* 리스트('*')
+ 리스트('+')
- 리스트('-')

---

### 코드 (Code)

* 문장속 코드 `example code inline` 삽입 예시입니다.

* 박스형 코드 삽입예시입니다.
```
example code box
```

java형 예제
```java
if(CollectionUtils.isNotEmpty(param.getConfirmCancelList())) {
            
    //수당반영건 체크
    int sendCnt = mapper.selectWorkScheduleSendCnt(session, param);
    if(sendCnt > 0) {
        return 1002;
    }
    
    /* 근무표 update */
    mapper.updateWorkScheduleConfirmCancel(session, param);
    
    /* 마감 테이블 */
    mapper.deleteScheduleConfirm(session, param);
    result = 0;
}
```

### 링크

* <https://www.github.com>
* [Github](https://www.github.com)

### 강조

* 강조 문법 **강조된 부분** 예시입니다.

### 이미지

![예시 이미지](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FcSny4z%2FbtqLscBsylh%2F664ohYXuzsxiYLiJdRBtSk%2Fimg.jpg)

### 표
| 이름  | 영어  | 정보  | 수학  |
|-----|-----|-----|-----|
| 홍길동 | 97점 | 78점 | 93점 |
| 이순신 | 89점 | 93점 | 97점 |
