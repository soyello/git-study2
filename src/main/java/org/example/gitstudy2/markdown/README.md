# 소개. Blog Service
_______________________

- 블로그 검색과 관련된 서비스를 제공합니다.

# 빌드 결과물
________________________
-[결과물 다운로드](https://www.google.com)

# 환경 소개
___________________
- JAVA17
- Spring Boot 2.7.3

# module - application
______________________
- 도메인 엔티티, 입력 포트, 출력 포트, 그리고 서비스 로직이 포함되어 있습니다.
  - `domain`
  - `service`
  - `port/input`
  - `port/output`

### 사용
> $ http GET https://localhost'

### 요청
Parameter

| Name | Type | Description                    | Required |
|------|------|--------------------------------|-----------|
|`keyword` | `String` | 검색 키워드                         | ㅇ |
| `url`|`string`| 블로그 url (특정 블로그 글만 검색하고 싶은 경우) | x|

  