# Mymove 배포

Mymove(Windows 창 이동·크기 조절 도구)의 설치 파일을 올리는 공개 저장소입니다. 소스는 비공개 저장소에 있습니다.

- 최신 설치 파일: [Releases](https://github.com/artchijun/mymove-releases/releases/latest)에서 `MyMove-setup.exe`를 받습니다.
- 앱의 자동 업데이트는 이 저장소의 릴리스를 확인합니다.

## 릴리스 규칙

- 태그: `win-<버전>` (예: `win-2.4.0`)
- 첨부 파일 이름: `MyMove-setup.exe`
- 릴리스 설명 끝에 `SHA256: <해시>` 한 줄을 넣습니다. 앱은 받은 파일의 해시가 다르면 설치하지 않습니다.
- 초안(draft)과 사전 릴리스(pre-release)는 자동 업데이트 대상에서 빠집니다.
