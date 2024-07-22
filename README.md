# WeHolic MIXTURE

WeHolic MIXTURE는 디바이스의 운영체제에 따라 사용자를 적절한 저장소로 리다이렉트하는 기술입니다. 또한, Android 또는 iOS가 아닌 디바이스에서 접속 시 QR 코드를 통해 웹사이트 접속을 제안하며, 안내 메시지를 보여줍니다.

![WeHolic Logo]([https://private-user-images.githubusercontent.com/157635626/350888136-1ee1aa44-431d-4cf8-a61a-512b82fec0da.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjE2MzYyMTMsIm5iZiI6MTcyMTYzNTkxMywicGF0aCI6Ii8xNTc2MzU2MjYvMzUwODg4MTM2LTFlZTFhYTQ0LTQzMWQtNGNmOC1hNjFhLTUxMmI4MmZlYzBkYS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNzIyJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDcyMlQwODExNTNaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0xODIxZmJjYWI3YWQwN2VmNjA4ODcxYmJkOWRmNzRiNmY0M2EyNDY2YTljMTg5ZWU0YTZjZjA4NmJjOTkzYWI2JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.qj_DsA5UQGhR3UuqBPg47M9Jfo4oHFMBlYIhiTDi6rs](https://private-user-images.githubusercontent.com/157635626/350888148-dd5c5f92-c81f-481f-a58f-83afcba344ef.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjE2MzYyMTMsIm5iZiI6MTcyMTYzNTkxMywicGF0aCI6Ii8xNTc2MzU2MjYvMzUwODg4MTQ4LWRkNWM1ZjkyLWM4MWYtNDgxZi1hNThmLTgzYWZjYmEzNDRlZi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwNzIyJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDcyMlQwODExNTNaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT00ZTQ1OTQyOTEyNTc1ZDRkZTcyMGMyZGM1ZDQ2MWU5MGFmNmJlZmJkZjNjOGRlZjM0ODVkMzRhNzJiZDQ5YzkwJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9._0pLKtC6_KTXfEi0CixoPMmpXQHMABmc13bBle3TbGU))

## 기능

- **운영체제에 따라 리다이렉션**:
  - Android 디바이스에서는 Google Play 스토어로 리다이렉트됩니다.
  - iOS 디바이스에서는 Apple App Store로 리다이렉트됩니다.
  - Android 또는 iOS가 아닌 디바이스에서는 QR 코드를 생성하여 사용자가 모바일 디바이스로 링크를 접속할 수 있도록 안내합니다.

- **QR 코드 생성**:
  - 서비스 저장소 링크를 QR 코드로 생성하여, 사용자가 스캔하여 쉽게 접근할 수 있도록 합니다.

## 사용 방법

**브라우저에서 열기**:
   - 로컬 서버에서 실행 중인 페이지를 브라우저에서 열면, 사용자의 디바이스 유형에 따라 적절한 리다이렉션 또는 메시지가 표시됩니다.

## 코드 설명

- **HTML 파일**:
  - `<style>` 태그 내 CSS는 페이지의 스타일을 정의합니다. `LINESeedKR-Bd` 폰트를 사용하여 모든 텍스트의 폰트를 설정합니다.
  - `<script>` 태그 내 JavaScript는 사용자 에이전트를 검사하여 디바이스 유형에 따라 리다이렉션을 처리합니다. Android 또는 iOS가 아닌 경우 QR 코드를 생성하고 메시지를 표시합니다.

- **로고**:
  - `<footer>` 태그 내에 로고 이미지를 추가하여, 화면의 가로 너비의 20% 크기로 설정합니다.

## 기술 스택

- **HTML**: 기본 웹 페이지 구조와 콘텐츠를 정의합니다.
- **CSS**: 페이지 스타일링을 담당합니다.
- **JavaScript**: 디바이스에 따라 리다이렉션과 QR 코드 생성을 처리합니다.
- **QRCode.js**: QR 코드 생성을 위한 외부 라이브러리입니다.

## 기여

기여는 언제든지 환영합니다! 버그 수정, 기능 추가 또는 개선 사항이 있으면 Pull Request를 제출해 주세요.

## 라이센스

이 프로젝트는 [MIT 라이센스](LICENSE) 하에 제공됩니다.

이 html 스크립트를 복사하여 자유롭게 변형 및 서비스를 제공하는 것을 환영합니다.

-- WeHolic Corp. --
