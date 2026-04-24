<div align="center">
  <br />
  <img src="assets/logo.svg" width="100" alt="HTML Viewer Logo" />

  <h1>HTML & Markdown Viewer</h1>
  <p>GitHub의 HTML 발표 자료와 Markdown 문서를 주소 입력만으로 즉시 확인합니다.</p>

  <br />
  <a href="https://42inshin.github.io/htmlViewer/">
    <img src="assets/launch-button.svg" width="240" alt="Launch Viewer" />
  </a>
  <br />
  <br />
</div>

## 🛠 주요 기능

- **주소 변환 및 렌더링**:
  - **HTML**: GitHub 소스 주소를 실행 가능한 주소로 변환하여 출력
  - **Markdown**: `.md` 파일을 읽어 GitHub 테마로 렌더링
- **URL 파라미터 공유**: 주소 뒤에 `?url=전체주소`를 붙여 특정 항목을 즉시 열 수 있는 공유 링크 지원
- **테마 전환**: 라이트/다크 모드 지원 (브라우저 저장)
- **최근 기록**: 확인한 항목 리스트 관리 (한글 파일명 지원, URL 복사, 원본 링크)
- **전체 화면 뷰어**: UI를 최소화한 콘텐츠 중심 화면

## 📖 사용 방법

1. GitHub 리포지토리에서 HTML 또는 Markdown 파일 주소 복사
2. 입력창에 주소 붙여넣고 **[열기]** 클릭
3. 조작 안내:
   - **ESC**: 홈 화면으로 복귀
   - **왼쪽 상단 구석**: 홈/새로고침 버튼 (마우스 오버 시 노출)
   - **테마 전환**: 우측 상단 해/달 아이콘 (Markdown 전용)

---
**Tech Stack**: Tailwind CSS, Marked.js, GitHub Markdown CSS<br>
**Powered by**: [Raw.Githack](https://raw.githack.com/)
