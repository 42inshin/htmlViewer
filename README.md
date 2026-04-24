# 📽️ HTML & Markdown Viewer

<div align="center">
  <br />
  <img src="assets/logo.svg" width="120" alt="HTML Viewer Logo" />

  <h1 align="center">HTML & MD Viewer</h1>
  <p align="center">GitHub 리포지토리에 업로드된 HTML 발표 자료와 Markdown 문서를 즉시 확인하는 웹 애플리케이션입니다.</p>

  <br />
  <a href="https://42inshin.github.io/htmlViewer/">
    <img src="assets/launch-button.svg" width="300" alt="Launch Viewer" />
  </a>
  <br />
  <br />
  <p>버튼을 클릭하면 즉시 뷰어를 사용할 수 있습니다.</p>
  <br />
</div>

## ✨ 주요 기능

- **실시간 변환 및 렌더링**: 
  - **HTML**: GitHub 소스 주소를 실행 가능한 주소(`Raw.Githack`)로 변환하여 즉시 출력합니다.
  - **Markdown**: `.md` 파일을 실시간으로 읽어와 GitHub 스타일 테마로 깔끔하게 렌더링합니다.
- **다크 & 라이트 모드**: 사용자의 환경에 맞춰 테마를 전환할 수 있으며, 설정은 브라우저에 저장되어 유지됩니다.
- **최근 기록 관리**: 최근에 확인한 항목 리스트를 저장하고 관리합니다. (한글 파일명 복원, URL 복사, 원본 리포지토리 이동 지원)
- **몰입형 프리젠테이션**: UI를 최소화하여 콘텐츠에 집중할 수 있으며, `ESC` 키로 편리하게 홈 화면으로 복귀할 수 있습니다.
- **세련된 디자인**: 글래스모피즘(Glassmorphism) 기반의 현대적인 UI와 CSS로 구현된 애니메이션 로고를 제공합니다.

## 🛠 사용 방법

1. GitHub 리포지토리에서 HTML 또는 Markdown 파일의 주소를 복사합니다.
   - 예: `https://github.com/user/repo/blob/main/index.html` 또는 `README.md`
2. 뷰어 입력창에 주소를 붙여넣고 **[열기]** 버튼을 누릅니다.
3. 뷰어 모드 사용 팁:
   - **왼쪽 상단 구석**: 홈 버튼과 새로고침 버튼이 숨겨져 있습니다. (마우스 호버 시 노출)
   - **ESC 키**: 홈 화면으로 돌아가려면 **ESC** 키를 누르세요.
   - **테마 전환**: 우측 상단의 해/달 아이콘을 클릭하여 다크/라이트 모드를 전환하세요.

## 🌐 직접 배포 및 커스텀

이 프로젝트를 포크(Fork)하여 본인만의 뷰어로 사용할 수 있습니다.

1. 본인의 GitHub 리포지토리 **Settings** -> **Pages**로 이동합니다.
2. **Branch**에서 `main`을 선택하고 **Save**를 누릅니다.
3. 배포된 주소에서 즉시 사용 가능합니다.

---
**Tech Stack**: Tailwind CSS, Lucide Icons, Marked.js, GitHub Markdown CSS  
**Powered by**: [Raw.Githack](https://raw.githack.com/)
