# 컨빌 블로그 대행 랜딩페이지

시공사 대표님을 위한 블로그 마케팅 대행 영업 랜딩페이지입니다.
정적 단일 HTML 파일이라 별도 빌드·서버 없이 바로 사용 가능합니다.

## 빠른 시작

### 1) 로컬에서 미리보기
- `index.html` 파일을 더블클릭 → 크롬에서 열림
- 모바일 화면 점검: 크롬 → F12 → 좌상단 "기기 도구 모음" 토글 → iPhone/Galaxy 선택

### 2) 외부에 공개 (무료)
가장 쉬운 두 가지 방법:

**방법 A. Vercel (드래그 앤 드롭, 5분)**
1. https://vercel.com 가입 → "Add New" → "Project"
2. 이 폴더 통째로 드래그 → Deploy
3. `https://convil-blog-landing.vercel.app` 같은 주소가 즉시 발급됩니다.

**방법 B. Netlify Drop (가입 없이)**
1. https://app.netlify.com/drop 접속
2. 이 폴더 통째로 드롭 → 즉시 임시 주소 발급

도메인을 따로 가지고 계시면 둘 다 무료로 연결 가능합니다.

## 자주 수정하는 곳

`index.html` 안에서 다음 텍스트를 검색해 일괄 변경하세요.

| 변경하고 싶은 항목 | 검색할 텍스트 |
|---|---|
| 전화번호 (하이픈 포함) | `010-7204-8009` |
| 전화번호 (tel: 링크용) | `01072048009` |
| YouTube 채널 링크 | `youtube.com/@convil.interior` |
| Instagram 계정 링크 | `instagram.com/convil.design` |
| Naver Blog 링크 | `blog.naver.com/convil_interior` |
| 메인 색상(컨빌 블루) | `#1A3FA7` |
| 페인 강조 색(레드) | `#E63946` |
| 통계 강조 색(옐로우) | `#FFD60A` |

색상은 `<style>` 안의 `:root` 블록에 모여 있습니다. 한 곳만 바꾸면 페이지 전체에 반영됩니다.

## 사례 카드 추가/삭제

`<!-- ====== CASES -->` 주석 아래 `<article class="case">...</article>` 블록을 통째로 복사·붙여넣기 하시면 카드 한 개가 추가됩니다.

## 이미지를 넣고 싶을 때

`assets/images/README.txt`에 파일명 가이드가 있습니다. 이미지를 넣으면 더 풍성해지지만, 현재 상태로도 페이지는 깨지지 않습니다.

## 추적 코드 추가 (선택)

Google Analytics, Meta Pixel 등은 `</head>` 직전에 붙여 넣으세요.
