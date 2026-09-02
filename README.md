# SH Lab Homepage

Jekyll 기반 연구실 홈페이지. 흰 배경을 기본으로 하고 초록은 배지·버튼 등 포인트에만 쓰는 팔레트를 사용합니다.

## 로컬 실행

```bash
bundle install
bundle exec jekyll serve
```

`http://localhost:4000` 에서 확인합니다.

## 콘텐츠 수정

- 구성원 추가/수정: `_data/members.yml`
- 논문 추가/수정: `_data/publications.yml`
- 연구분야 소개 문구: `research.html`
- 색상/타이포: `assets/css/main.scss`

## GitHub Pages 배포

1. 이 폴더를 그대로 GitHub 저장소에 push합니다.
2. 저장소 Settings → Pages → Source에서 `Deploy from a branch`를 선택하고 `main` 브랜치, 루트(`/`)를 지정합니다.
3. 몇 분 후 `https://<username>.github.io/<repo>/`에서 확인 가능합니다.
4. 저장소 이름이 `<username>.github.io`가 아니라면 `_config.yml`의 `baseurl`을 `/저장소이름`으로 설정해야 링크가 깨지지 않습니다.
