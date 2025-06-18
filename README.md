# Airacle - 앱스토어 등록용 웹사이트

이 웹사이트는 Airacle 앱의 구글 플레이스토어 및 애플 앱스토어 등록을 위해 필요한 페이지들을 제공합니다.

## 📋 포함된 페이지들

- **메인 페이지** (`index.html`): 앱 소개 및 마케팅 페이지
- **개인정보처리방침** (`privacy.html`): 플레이스토어/앱스토어 필수 요구사항
- **고객지원** (`support.html`): 앱스토어 지원 URL 요구사항
- **이용약관** (`terms.html`): 서비스 이용약관

## 🚀 GitHub Pages 설정 방법

### 1. GitHub 저장소 설정
1. GitHub에서 새 저장소 생성 (예: `airacle-website`)
2. 이 `docs` 폴더의 모든 파일을 저장소에 업로드

### 2. GitHub Pages 활성화
1. 저장소 → Settings → Pages
2. Source: "Deploy from a branch" 선택
3. Branch: `main` (또는 `master`) 선택
4. Folder: `/ (root)` 선택 (docs 폴더 내용을 루트에 올린 경우)
   또는 Folder: `/docs` 선택 (docs 폴더를 그대로 올린 경우)
5. Save 클릭

### 3. 커스텀 도메인 (선택사항)
- 본인 도메인이 있는 경우 Settings → Pages → Custom domain에서 설정 가능
- 예: `airacle.com` 또는 `www.airacle.com`

## 🔗 생성되는 URL들

GitHub Pages 활성화 후 다음과 같은 URL들이 생성됩니다:

### 기본 GitHub Pages URL (무료)
- 메인 페이지: `https://[username].github.io/[repository-name]/`
- 개인정보처리방침: `https://[username].github.io/[repository-name]/privacy.html`
- 고객지원: `https://[username].github.io/[repository-name]/support.html`
- 이용약관: `https://[username].github.io/[repository-name]/terms.html`

### 커스텀 도메인 사용시
- 메인 페이지: `https://yourdomain.com/`
- 개인정보처리방침: `https://yourdomain.com/privacy.html`
- 고객지원: `https://yourdomain.com/support.html`
- 이용약관: `https://yourdomain.com/terms.html`

## 📱 앱스토어 등록시 사용할 URL들

### 구글 플레이스토어
- **개인정보처리방침 URL**: `https://[your-domain]/privacy.html`

### 애플 앱스토어
- **지원 URL**: `https://[your-domain]/support.html`
- **마케팅 URL** (선택사항): `https://[your-domain]/`

## ⚙️ 수정 방법

필요에 따라 다음 항목들을 수정하세요:

### 연락처 정보 수정
각 HTML 파일에서 다음 정보들을 실제 정보로 변경:
- `support@airacle.com` → 실제 이메일 주소
- `privacy@airacle.com` → 실제 개인정보 담당자 이메일
- `02-1234-5678` → 실제 전화번호

### 회사 정보 수정
- 회사명이 다른 경우 "Airacle"을 실제 회사명으로 변경
- 서비스 설명 및 기능 설명 수정

### 디자인 수정
- CSS 스타일 변경으로 색상, 레이아웃 등 커스터마이징 가능
- 로고 이미지 추가 가능

## 🔄 업데이트

파일 수정 후 GitHub에 push하면 자동으로 웹사이트가 업데이트됩니다. (1-10분 소요)

## ✅ 확인 사항

배포 후 다음 사항들을 확인하세요:
- [ ] 모든 페이지가 정상적으로 로드되는지
- [ ] 모바일에서도 잘 보이는지 (반응형 디자인)
- [ ] 연락처 정보가 정확한지
- [ ] 앱스토어 등록시 URL이 제대로 접근되는지

---

**참고**: GitHub Pages는 완전 무료이며, HTTPS를 자동으로 지원합니다. 별도의 호스팅 비용이 들지 않아 앱스토어 등록용으로 최적입니다. 