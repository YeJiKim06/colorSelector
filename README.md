# 🎨 Smart LCH Color Generator

> **기준 색상을 바탕으로 인지적 밝기를 유지하며 조화로운 유사색 팔레트를 생성해 주는 스마트 웹 도구입니다.**

이 프로젝트는 단일 HTML 파일로 구성되어 있으며, CSS 변수와 최신 브라우저의 컬러 필터 기능을 활용하여 실시간으로 부드러운 톤 변화를 시각화합니다. 사용자가 선택한 배경색의 밝기를 감지하여 텍스트의 가독성(Dark/Light 모드)을 자동으로 조절하는 스마트한 UI/UX가 특징입니다.

---

## 🚀 주요 기능 (Features)

* **실시간 팔레트 생성:** 기준 색상(Base Color)을 변경하면 실시간으로 주변 유사색 톤이 자동 계산됩니다.
* **개수 맞춤 조절:** 최소 1개부터 최대 10개까지 원하는 만큼 추출 개수를 동적으로 조절할 수 있습니다.
* **랜덤 컬러 추천:** 어떤 색상을 고를지 고민될 때 원클릭으로 감각적인 랜덤 메인 컬러를 제안받을 수 있습니다.
* **지능형 가독성 대비:** 선택한 색상의 밝기(Brightness)를 계산하여, 배경색에 맞춰 텍스트 컬러가 자동으로 흰색 또는 검은색으로 반전됩니다.
* **원클릭 클립보드 복사:** 마음에 드는 컬러 카드를 클릭하면 가상 렌더링 엔진을 통해 실제 계산된 RGB 컬러 값이 클립보드에 자동으로 복사됩니다.

---

## 🛠️ 사용 기술 (Tech Stack)

* **HTML5** - 시맨틱한 웹조직 구조 설계
* **CSS3** - Flexbox/Grid 레이아웃, CSS 변수(`--main-bg`, `--text-color`), Backdrop-filter 디자인 효과
* **JavaScript (Vanilla JS)** - RGB 밝기 계산 알고리즘, 실시간 DOM 조작, 클립보드 API 연동

---

## 💻 설치 및 실행 방법 (Getting Started)

이 프로젝트는 별도의 빌드 과정이나 의존성 패키지(npm 등) 설치가 필요 없는 **순수 웹 페이지**입니다.

1. 이 저장소의 코드를 다운로드하거나 클론합니다.
   ```bash
   git clone [https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git](https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git)
