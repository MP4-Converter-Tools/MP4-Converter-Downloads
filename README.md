# MP4-GIF-Conversion 다운로드

MP4를 GIF로 변환하고 GIF를 20MB 미만으로 압축하는 Windows 프로그램입니다.
파일은 PC에서 처리하며 서버에 업로드하지 않습니다.

**현재 정식 파일 공개 전 최종 확인 중입니다.** 공개 후 [Releases](https://github.com/SeokYB47/MP4-GIF-Conversion-Downloads/releases)에서 다운로드할 수 있습니다.

## 주요 기능

- MP4 → GIF, GIF 압축, 20MB / Unlimited 선택
- 해상도와 FPS 선택, MP4 시작·종료 구간 지정
- 드래그 앤 드롭, 진행률·취소·변환 타이머, 마지막 설정 기억
- 최초 결과의 용량·해상도·FPS 알림, 선택적 FPS 상향 보정

원본보다 해상도를 확대하지 않습니다. GIF 뷰어에 따라 높은 FPS 재생이 달라질 수 있습니다.

## 실행 방법

1. 릴리스의 Windows x64 ZIP을 다운로드합니다.
2. 이전 버전 폴더와 합치지 않고 **새 폴더에 전부 압축 해제**합니다.
3. `MP4-to-GIF.exe`를 실행합니다. Python이나 FFmpeg를 별도로 설치할 필요가 없습니다.

대상은 Windows 10/11 64비트(x64)입니다. 자세한 사용법과 변경 이력은 ZIP의 `README.md`, `CHANGELOG.md`를 확인하세요.

## 라이선스와 대응 소스

실행 ZIP의 `licenses/`, `source-materials/`, `THIRD_PARTY_NOTICES.md`에 동봉 구성요소의 라이선스·소스·빌드 절차가 포함됩니다. 재배포 시 해당 자료와 원문 고지를 유지해야 합니다.

FFmpeg 등 대응 소스는 실행 ZIP의 `source-materials/`에 있습니다. GitHub가 자동 생성하는 **Source code ZIP**은 이 배포 안내 저장소의 내용이므로 구분해 주세요.

프로그램 자체의 최종 이용 조건은 정식 릴리스에서 안내합니다. 외부 구성요소에는 각각의 라이선스가 별도로 적용됩니다.
