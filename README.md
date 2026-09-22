# Personal Portfolio

개인 이력, 경력, 프로젝트, 자격증, 수상경력을 한 곳에서 관리하기 위한 확장형 포트폴리오입니다.

## 구조
- `index.html`: 포트폴리오 화면
- `portfolio-data.js`: 이력/자격증/수상/프로젝트 데이터
- `projects/`: 실제 프로젝트 파일을 연결하거나 보관할 공간

## 프로젝트 추가
`portfolio-data.js`의 `projects` 배열에 프로젝트를 추가합니다.

지원 필드:
- title
- category
- description
- tech
- repo
- demo
- files

## 현재 연결된 프로젝트
- 엔트리 RPG 프로젝트: 실제 파일 연결 대기
- 번역 앱: jakekim-7/tran
- 중2 영어 통합 마스터: jakekim-7/eng

## 업데이트 방향
앞으로 프로젝트 파일을 제공하면 `projects/<project-name>/` 아래에 연결하고, 포트폴리오 카드에서 GitHub/실행/파일 링크를 함께 보여줄 수 있습니다.
