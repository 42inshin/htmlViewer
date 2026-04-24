# 📽️ HTML Slide Viewer

<div align="center">
  <!-- README용 SVG 로고 -->
  <svg width="120" height="90" viewBox="0 0 120 90" fill="none" xmlns="http://www.w3.org/2000/svg">
    <rect x="10" y="10" width="100" height="70" rx="15" fill="#1E293B" stroke="#334155" stroke-width="2"/>
    <rect x="10" y="10" width="100" height="70" rx="15" fill="url(#paint0_linear)" fill-opacity="0.2"/>
    <path d="M52 35L72 45L52 55V35Z" fill="#60A5FA">
      <animate attributeName="opacity" values="1;0.7;1" dur="2s" repeatCount="indefinite" />
    </path>
    <circle cx="22" cy="22" r="3" fill="#EF4444" fill-opacity="0.6"/>
    <circle cx="32" cy="22" r="3" fill="#F59E0B" fill-opacity="0.6"/>
    <circle cx="42" cy="22" r="3" fill="#10B981" fill-opacity="0.6"/>
    <defs>
      <linearGradient id="paint0_linear" x1="10" y1="10" x2="110" y2="80" gradientUnits="userSpaceOnUse">
        <stop stop-color="#60A5FA"/>
        <stop offset="1" stop-color="#34D399"/>
      </linearGradient>
    </defs>
  </svg>

  <h1 align="center">HTML Viewer</h1>
  <p align="center">GitHub 리포지토리에 업로드된 HTML 발표 자료를 URL 입력만으로 즉시 렌더링하여 보여주는 웹 애플리케이션입니다.</p>

  <br />
  <a href="https://42inshin.github.io/htmlViewer/">
    <img src="https://img.shields.io/badge/Launch%20Viewer-blue?style=for-the-badge&logo=github&logoColor=white" height="40" />
  </a>
  <br />
  <h3>👉 [https://42inshin.github.io/htmlViewer/](https://42inshin.github.io/htmlViewer/)</h3>
  <p>링크를 클릭하면 즉시 뷰어를 사용할 수 있습니다.</p>
  <br />
</div>

## ✨ 주요 기능

- **실시간 변환**: GitHub 소스 주소를 실행 가능한 HTML 렌더링 주소(`Raw.Githack`)로 자동 변환합니다.
- **최근 기록 관리**: 브라우저의 `localStorage`를 이용해 최근에 본 발표 리스트를 저장하고 관리합니다. (한글 파일명 지원, URL 복사, 원본 이동 가능)
- **몰입형 뷰어**: 발표에 집중할 수 있도록 UI를 최소화하고 전체 화면을 활용하며, `ESC` 키로 홈 화면 복귀를 지원합니다.
- **다크 모드 디자인**: 세련된 글래스모피즘(Glassmorphism) 기반의 UI와 CSS 로고를 제공합니다.

## 🛠 사용 방법

1. GitHub 리포지토리에서 HTML 파일의 주소를 복사합니다.
   - 예: `https://github.com/user/repo/blob/main/index.html`
2. HTML Viewer 입력창에 주소를 붙여넣고 **[발표 시작]**을 누릅니다.
3. 발표 모드에서:
   - **왼쪽 상단 구석**: 홈 버튼과 새로고침 버튼이 숨겨져 있습니다. (마우스 호버 시 노출)
   - **ESC 키**: 홈 화면으로 돌아가려면 ESC 키를 누르세요. (슬라이드 클릭 후에는 포커스 문제로 작동하지 않을 수 있습니다.)

## 🌐 GitHub Pages 배포 방법

이 프로젝트를 본인의 GitHub 리포지토리에 올린 후 다음과 같이 설정하세요.

1. GitHub 리포지토리 **Settings** -> **Pages**로 이동합니다.
2. **Branch**에서 `main`을 선택하고 **Save**를 누릅니다.
3. 배포된 주소에서 바로 사용 가능합니다.

---
**Powered by** [Raw.Githack](https://raw.githack.com/) & Tailwind CSS
