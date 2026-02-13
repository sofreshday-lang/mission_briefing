# 배포 가이드 (Deployment Guide)

시스템 환경에서 `git` 명령어를 찾을 수 없어 자동 업로드가 실패했습니다.
아래의 간단한 절차를 따라 수동으로 배포하실 수 있습니다.

## 1단계: GitHub에 코드 업로드

1. [GitHub](https://github.com/)에 로그인합니다.
2. 우측 상단의 **+** 버튼을 누르고 **New repository**를 클릭합니다.
3. **Repository name**에 `mission-briefing` (또는 원하는 이름)을 입력하고 **Create repository**를 클릭합니다.
4. 생성된 화면에서 **"uploading an existing file"** 링크를 클릭합니다.
5. `d:\test\police\mission_briefing` 폴더에 있는 다음 파일들을 드래그하여 업로드합니다:
   - `index.html`
   - `style.css`
   - `README.md`
6. 하단의 **Commit changes** 버튼을 클릭하여 저장합니다.

## 2단계: Vercel 배포

1. [Vercel](https://vercel.com/)에 로그인합니다.
2. 대시보드 우측 상단의 **Add New...** 버튼을 누르고 **Project**를 선택합니다.
3. **Import Git Repository** 목록에서 방금 생성한 `mission-briefing` 리포지토리 옆의 **Import** 버튼을 클릭합니다.
4. 설정 변경 없이 **Deploy** 버튼을 클릭합니다.
5. 약 1분 후 배포가 완료되면 **Visit** 버튼을 눌러 생성된 URL을 확인합니다.

---
**Tip**: 배포된 URL은 `https://mission-briefing-custom-name.vercel.app` 형태가 됩니다.
