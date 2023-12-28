# Awesome Rhymix 😎

- [디자인](#디자인)
  - [레이아웃](#레이아웃)
  - [스킨](#스킨)
- [확장기능](#확장기능)
  - [모듈](#모듈)
  - [애드온](#애드온)
  - [위젯](#위젯)
- [레퍼런스](#레퍼런스)
  - [라이믹스 이슈](#라이믹스-이슈)

---

- [라이믹스 공식 사이트](https://rhymix.org) — 라이믹스의 공식 사이트로 뉴스와 매뉴얼 제공
- [XETOWN - 웹마스터 커뮤니티](https://xetown.com)

---

<!-- PR 필수 확인 사항
!!! 디자인, 확장기능 추가는 GNU GPL 라이선스 필수 !!!
디자인, 확장기능 자료의 소개를 추가하는 변경사항은
반드시 PR 내용에 GNU GPL 라이선스 적용을 확인할 수 있는 링크 및 개발자 또는 판매자로부터 서면 확인한 내용을 첨부해야 합니다.
-->

> [!NOTE]
> 디자인 및 확장기능은 유무료에 관계 없이 GNU GPL 라이선스가 명시되었거나 적용된 자료만 포함하였습니다.

## 디자인

### 레이아웃

- [FLEX 레이아웃](https://xetown.com/download/1455172) — 다크모드 지원를 지원하는 블로그 형식의 깔끔한 레이아웃

### 스킨

---

## 확장기능

### 모듈

- [링크 프리뷰](https://xetown.com/download/1724355) — 위지윅 에디터에 URL을 붙여 넣으면 미리보기 카드 또는 동영상 등 Embed 코드로 변환해주는 기능
- [IndexNow](https://xetown.com/download/1781819) — [IndexNow 프로토콜](https://www.indexnow.org/ko_kr/index)을 이용해 네이버, Bing(Microsoft) 등과 같은 검색엔진에 가장 빠르게 새 컨텐츠 생성을 알려주는 기능
- [제휴마케팅 링크 변환 모듈 (링크프라이스)](https://xetown.com/download/1196234) — 글 내용에서 링크를 자동으로 링크프라이스 제휴마케팅의 링크로 변환해주는 기능

### 애드온

- [사용자 지정 lang 변경 애드온](https://xetown.com/download/1730001) — 코드를 변경하지 않고도 간단하게 화면에 표시되는 주요 단어(다국어 기능으로 출력하는 항목)를 변경할 수 있는 기능

### 위젯

---

## 레퍼런스

- 📖 [Rhymix 매뉴얼(공식)](https://rhymix.org/manual) — 라이믹스 공식 매뉴얼
- 📖 [Rhymix 가이드](https://rhymix-guide.github.io)

### 라이믹스 이슈

라이믹스의 새로운 기능이나 개선 사항에 대한 내용을 참고할 수 있다.

- **v2.1.8** [템플릿 언어 v2 #2200](https://github.com/rhymix/rhymix/pull/2200) — Blade 문법 기반의 템플릿 엔진 추가
- **v2.1** [공식 지원 PHP 버전 및 브라우저 범위 조정 #1562](https://github.com/rhymix/rhymix/issues/1562) — 라이믹스 v2.1부터 적용된 PHP 및 브라우저 지원 범위
- **v2.0** [다크모드 감지 및 설정을 위한 rx_color_scheme 쿠키값의 표준화 #1482](https://github.com/rhymix/rhymix/pull/1482) — 방문자의 다크모드 설정을 감지하고 설정을 저장하는 쿠키
- **v2.0** [DB 접속 방법 변경 및 XML 문법 확장 #1332](https://github.com/rhymix/rhymix/pull/1332) — PDO 사용 전환과 XML 쿼리, 스키마 해석 엔진 재설계, XML 파일을 이용하지 않은 PDO 기반 인터페이스 추가
- **v2.0** [라우터(Router) 기능 추가 #1322](https://github.com/rhymix/rhymix/pull/1322) — 모듈에서 라우터를 정의하는 기능 추가
