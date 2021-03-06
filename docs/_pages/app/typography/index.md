---
---

# Android

## 글꼴

Android는 제조사가 시스템 글꼴을 바꿀 수 있고 사용자도 원하는 시스템 글꼴을 선택할 수 있습니다. 그러므로 일관된 느낌을 유지하기 어렵습니다. 하지만 기준은 필요합니다. 리디북스 앱에서 국문은 Noto Sans, 영문과 숫자는 Roboto를 기준으로 사용합니다.

## 글자 크기

단위는 dp를 사용합니다. sp를 사용하는 게 이상적이지만 레이아웃에 제약이 많아 dp를 사용합니다.

| 명칭         | textSize | 예시                                                         |
| ------------ | -------- | ------------------------------------------------------------ |
| Big headline | 20dp     | App bar 타이틀                                               |
| Headline     | 18dp     | 튜토리얼 제목 글자 크기                                      |
| Title        | 16-17dp  | App bar의 저장, 닫기 등 / Big button의 글자 크기             |
| Body         | 14-15dp  | 목록보기 제목, 토스트 글자 크기 / 뷰어 설정 내 설정 이름     |
| Sub body     | 13dp     | 튜토리얼 body, 뷰어 페이지 번호, 책장 목록 편집              |
| Caption      | 12dp     | 표지만 보기 대여기간, 뷰어 설정 설정 값, Small button 글자 크기, 목록보기 저자명 |
| Sub caption  | 10-11dp  | 목록보기 대여기간, 알림센터 뱃지 숫자 / 목록보기 독서 진행률, 뷰어 설정 설명 |

## 행간

글자 크기마다 절대 값을 입력해야 하는 `lineSpacingExtra` 속성보다는 한 가지 수치를 입력하면 모든 글자 크기에서 적절하게 보이는 `lineSpacingMultiplier` 속성을 사용합니다. 주로 1.15를 값으로 사용합니다.

# iOS

## 글꼴

국문은 Apple SD Gothic Neo, 숫자와 영문은 Avenir 글꼴을 사용합니다.

## 글자 크기

단위는 pt를 사용합니다. 

| 명칭        | textSize | 예시                                                    |
| ----------- | -------- | ------------------------------------------------------- |
| Headline    | 19pt     | 독서노트 헤더 내 책 제목                                |
| Title       | 16-17pt  | Big button의 글자 크기 / 설정명, Navigation 내 텍스트들 |
| Body        | 14-15pt  | 목록보기 제목 / 독서노트 형광펜 문구, 목차명            |
| Sub body    | 13pt     | 토스트 메시지, 기기 대체 테이블 레이블, 기기 등록일     |
| Caption     | 12pt     | 목록보기 저자명                                         |
| Sub caption | 10-11pt  | iPhone Tabbar 아이콘 하단 텍스트 / 목록보기 대여기간    |
