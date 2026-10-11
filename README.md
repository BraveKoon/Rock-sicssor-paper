# Rock-sicssor-paper

가위바위보 첫수 시뮬레이터. `index.html`을 브라우저로 열면 됩니다.

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
