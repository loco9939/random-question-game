# 랜덤 질문 게임 (Random Question Game)

모임이나 파티에서 사용할 수 있는 간단한 랜덤 질문 게임 웹 애플리케이션입니다.

## 🚀 배포 방법 (Deployment)

이 프로젝트는 정적 웹사이트(Static Website)로, 서버 없이 무료로 쉽게 배포할 수 있습니다.

### 옵션 1: GitHub Pages (추천)
1. GitHub에 새로운 저장소(Repository)를 만듭니다.
2. 이 폴더의 파일들을 해당 저장소에 업로드(Push)합니다.
   ```bash
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/당신의아이디/저장소이름.git
   git push -u origin main
   ```
3. GitHub 저장소 페이지에서 **Settings** > **Pages**로 이동합니다.
4. **Branch**를 `main`, 폴더를 `/ (root)`로 설정하고 **Save**를 누릅니다.
5. 잠시 후 상단에 생성된 웹사이트 주소가 표시됩니다.

### 옵션 2: Vercel / Netlify
1. [Vercel](https://vercel.com) 또는 [Netlify](https://netlify.com)에 로그인합니다.
2. 'Add New Project'를 클릭합니다.
3. 이 `random-question-game` 폴더를 브라우저 창으로 드래그 앤 드롭하거나, GitHub 저장소를 연결합니다.
4. 별도의 설정 없이 **Deploy** 버튼을 누르면 즉시 배포됩니다.

## 🛠 로컬 실행 방법
`index.html` 파일을 더블 클릭하여 브라우저에서 바로 실행할 수 있습니다.
