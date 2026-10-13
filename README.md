# Rock-sicssor-paper

[![사이트 열기](https://img.shields.io/badge/%EC%82%AC%EC%9D%B4%ED%8A%B8-%EB%B0%94%EB%A1%9C%20%EC%97%B4%EA%B8%B0-6a4cc2?style=for-the-badge&logo=githubpages&logoColor=white)](https://bravekoon.github.io/Rock-sicssor-paper/)
[![Deploy to GitHub Pages](https://github.com/BraveKoon/Rock-sicssor-paper/actions/workflows/pages.yml/badge.svg)](https://github.com/BraveKoon/Rock-sicssor-paper/actions/workflows/pages.yml)

가위바위보 첫수 시뮬레이터. `index.html`을 브라우저로 열거나 GitHub Pages 사이트에서 바로 볼 수 있습니다.

**사이트:** https://bravekoon.github.io/Rock-sicssor-paper/

- 상대가 내는 손의 비율(사람 통계 / 완전 무작위 / 직접 설정)을 고르고
- 첫 판에 가위·바위·보를 낼 때 각각의 승·무·패와 승률(비김 제외)을 수천 판 시뮬레이션해 이론값과 비교합니다.
- 직접 한 판씩 해볼 수도 있습니다.

## 릴리즈

`v1.0.0` 형식의 태그를 push하면 GitHub Actions(`.github/workflows/release.yml`)가 릴리즈를 만들고 `index.html`과 zip 파일을 첨부합니다.

```bash
git tag v1.0.0
git push origin v1.0.0
```

또는 GitHub의 **Actions → Release → Run workflow**에서 버전을 입력해 실행해도 됩니다.

## GitHub Pages 배포

`main`에 push하면 GitHub Actions(`.github/workflows/pages.yml`)가 `index.html`을 GitHub Pages에 배포합니다.
처음 한 번은 저장소 **Settings → Pages → Build and deployment → Source**를 **GitHub Actions**로 설정해야 합니다.
