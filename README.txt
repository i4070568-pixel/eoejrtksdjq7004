대덕산업 홈페이지 GitHub/Vercel 배포용 패키지

업로드 방법:
1. GitHub 저장소의 기존 파일을 모두 삭제합니다.
2. 이 압축파일을 풀고, 안에 있는 index.html / vercel.json / README.txt 파일을 저장소 최상단(root)에 업로드합니다.
3. Vercel에서 해당 GitHub 저장소를 다시 Redeploy 합니다.
4. Vercel 설정에서 Build Command가 있으면 비워두고, Output Directory도 비워둡니다. Framework Preset은 Other로 선택합니다.

중요:
- index.html 파일명이 반드시 소문자 index.html 이어야 합니다.
- 폴더 안에 넣지 말고 저장소 첫 화면에 바로 보여야 합니다.
