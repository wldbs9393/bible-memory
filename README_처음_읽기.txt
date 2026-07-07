말씀 암송 사이트 GitHub Pages 배포용

이 폴더 안 파일을 GitHub 저장소 최상위(root)에 올리세요.

업로드할 파일:
1) index.html
2) .nojekyll  (선택이지만 같이 올리는 것을 권장)
3) README_처음_읽기.txt (올리지 않아도 됨)

중요:
- ZIP 파일 자체를 GitHub에 올리지 마세요.
- ZIP 압축을 풀고, 안에 있는 index.html을 올리세요.
- index.html은 반드시 저장소 최상위(root)에 있어야 합니다.
- 예: /index.html
- 안 되는 예: /github-pages-deploy/index.html

GitHub Pages 설정:
Settings → Pages → Build and deployment
Source: Deploy from a branch
Branch: main
Folder: / (root)
Save

예상 접속 주소:
https://깃허브아이디.github.io/저장소이름/

예:
GitHub 아이디: wldbs9393
저장소 이름: bible-memory
주소: https://wldbs9393.github.io/bible-memory/
