# 삼일단지내부동산 (대표: 허정미) 웹사이트

> **100% 순수 HTML5 / CSS3 / Vanilla JavaScript로만 제작된 정적 웹사이트입니다.**  
> React, Node.js, npm, 빌드 과정이 일절 없으므로 **GitHub 및 GitHub Pages에 1초 만에 배포**할 수 있습니다.

---

## 1. 프로젝트 파일 구조 (완전 정적 파일)

```
c:\AI_HJM\sreal_e\
├── index.html        # 메인 웹페이지 (시맨틱 HTML5, SEO 최적화)
├── style.css         # 메인 디자인 및 반응형 스타일시트 (Pure CSS3)
├── script.js         # 인터랙티브 기능 (Vanilla JS)
├── .nojekyll         # GitHub Pages Jekyll 빌드 방지 파일 (즉시 배포 지원)
├── images/           # 고해상도 이미지 에셋 폴더
│   ├── hero.jpg          # 메인 단지 전경
│   ├── profile.jpg       # 허정미 대표 프로필 포트레이트
│   ├── space_energy.jpg  # 공간 기운 & 전통 티룸 감성
│   └── commercial.jpg    # 상가 및 첨단 공장 단지
├── styles/main.css   # 백업 CSS (동일 내용)
├── scripts/app.js    # 백업 JS (동일 내용)
└── README.md         # 배포 및 설명서
```

---

## 2. GitHub Pages 가장 쉬운 배포 방법 (3단계)

빌드(`npm run build` 등)나 복잡한 설정 없이 브라우저에서 바로 배포할 수 있습니다.

### [방법 1] GitHub 웹사이트에서 드래그 앤 드롭으로 배포하기 (가장 쉬움)

1. **GitHub 로그인 후 새 저장소(Repository) 만들기**:
   - Repository name 입력 (예: `sreal_e` 또는 `samil-realestate`)
   - **Public** 선택 후 **[Create repository]** 클릭
2. **파일 올리기**:
   - 생성된 저장소 화면에서 **"uploading an existing file"** 링크 클릭
   - 내 컴퓨터의 `c:\AI_HJM\sreal_e` 폴더 안에 있는 모든 파일/폴더를 그대로 마우스로 끌어다 놓기 (드래그 앤 드롭)
     - `index.html`, `style.css`, `script.js`, `.nojekyll`, `images` 폴더
   - 아래쪽 녹색 **[Commit changes]** 버튼 클릭
3. **GitHub Pages 켜기**:
   - 저장소 상단 메뉴의 **Settings** 클릭
   - 왼쪽 사이드바에서 **Pages** 클릭
   - **Branch** 항목에서 `None` ➔ `main` (또는 `master`) 선택, 폴더는 `/(root)` 그대로 두고 **[Save]** 클릭
   - 약 1분 후 상단에 표시되는 배포 주소(예: `https://<아이디>.github.io/<저장소이름>/`)로 접속하면 전 세계 어디서든 열람 가능합니다!

---

### [방법 2] Git 명령어로 배포하기

컴퓨터에 Git이 설치되어 있는 경우 터미널에서 다음 명령어로 즉시 푸시할 수 있습니다:

```bash
git init
git add .
git commit -m "삼일단지내부동산 허정미 대표 웹사이트 최초 배포"
git branch -M main
git remote add origin https://github.com/<내_아이디>/<저장소이름>.git
git push -u origin main
```
이후 위 3번(Settings ➔ Pages ➔ Branch 설정)만 해주시면 자동 배포됩니다.

---

## 3. 사업장 및 연락처 정보

- **상호명**: 삼일단지내부동산
- **대표/컨설턴트**: 허정미
- **직통 전화**: 010-8365-4900 (모바일 터치 시 원클릭 전화 연결 및 문자 연결)
- **주요 서비스**:
  - 단지내 아파트 매매·전세·월세
  - 상가·공장·수익형 부동산 권리분석 및 맞춤 중개
  - 동양철학/명리/풍수를 결합한 1:1 맞춤 공간·기운 컨설팅

---

## 4. 내 컴퓨터에서 바로 확인하는 방법

인터넷 연결 여부나 서버 실행 없이, 컴퓨터 탐색기에서 **`index.html` 파일을 더블 클릭**하시면 크롬, 엣지, 웨일 등 모든 웹 브라우저에서 즉시 정상 작동합니다.
