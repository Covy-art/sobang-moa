# 소방 모아

**[웹앱 열기 → https://sobang-moa.vercel.app/](https://sobang-moa.vercel.app/)**

소방 자료 취합 업무를 시험하는 웹앱입니다. 공개 시연 계정에는 가상 자료만 입력해 주세요.

## 접속 방법

| 위치 | 열리는 내용 |
| --- | --- |
| 위의 ‘웹앱 열기’ 링크 | Vercel에 배포된 웹앱 |
| GitHub에서 `index.html` 클릭 | HTML 소스와 변경 기록 |
| PC의 `index.html`을 브라우저로 열기 | 그 PC에 저장된 앱 파일 |
| PC의 `웹앱_열기.url` 더블클릭 | 배포된 웹앱 |

로컬 파일은 배포 주소로 자동 이동하지 않습니다. `index.html`이 편집기로 열리면 Windows의 HTML 기본 연결 프로그램이 편집기로 지정된 상태입니다. 실제 사용자 시연에는 위 웹 주소를 사용하세요.

## 개발과 배포

- 현재 배포본은 외부 글꼴·아이콘 요청 없이 실행되는 단일 `index.html`입니다.
- Vercel의 기존 프로젝트가 이 GitHub 저장소에 연결되어 있습니다.
- `main`에 변경을 푸시하면 Vercel이 배포를 수행합니다. 배포 성공 후 웹 주소에 반영됩니다.
- GitHub Desktop의 Commit은 PC에 기록하는 단계이고, Push origin은 GitHub로 보내는 단계입니다.
- Supabase 주소는 프로젝트 식별자로 구성되어 있으므로 앱이나 폴더 이름에 맞춰 임의로 바꾸지 않습니다.
- `.env*`와 `.vercel`은 로컬 설정이며 Git에 올리지 않습니다. 관리자 비밀 키도 배포 HTML에 넣지 않습니다.

