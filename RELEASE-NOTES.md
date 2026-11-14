# MP4 Converter v3.0

Windows 10/11 x64용 MP4 변환·GIF/WebP 압축 프로그램입니다. 파일은 서버 업로드 없이 PC에서 처리합니다.

- **MP4 → GIF / WebP:** 20MB / Unlimited 선택
- **GIF / WebP 압축:** 같은 형식으로 전체 구간을 20MB 미만으로 저장
- **재생 배속:** 0.5x · 0.75x · 1x(기본) · 1.25x · 1.5x · 2x
- **WebP 시작 품질:** 자동·빈칸은 100, 수동은 1~100. 20MB 이상이면 **품질을 3씩 → FPS → 해상도** 순서로 낮춥니다. Unlimited는 시작 품질을 유지합니다.
- 원본 비율 유지, 긴 변 64~4096px 설정(원본보다 확대하지 않음), 최대 60FPS·MP4 구간 설정
- 드래그 앤 드롭, 마지막 설정 기억, 진행률·취소·타이머, 최초 결과 알림·최종 완료 팝업
- 선택적 FPS 상향 보정: 기본 ‘아니요’. 해상도를 유지해 1FPS씩 높이다 처음 20MB 이상이 되면 멈추며, 확인한 제한 미만 후보 중 가장 가까운 결과를 저장합니다(최대 60FPS).

**Assets의 `MP4-Converter.exe`를 다운로드해 바로 실행하세요.** ZIP 압축 해제나 Python·FFmpeg 별도 설치는 필요하지 않습니다. 시작 시 내장 구성요소를 임시 폴더에 준비합니다.

20MB는 **20,000,000바이트 미만**입니다. WebP 품질 조절 하한은 35이며, 35 미만을 직접 설정하면 그 값이 하한입니다. 품질 100도 손실 압축입니다. `SHA256SUMS`로 실행파일의 SHA256을 검증할 수 있습니다.

[사용 매뉴얼](https://github.com/MP4-Converter-Tools/MP4-Converter-Downloads/blob/main/README.md) · [변경 이력](https://github.com/MP4-Converter-Tools/MP4-Converter-Downloads/blob/main/CHANGELOG.md)

개인·업무 무료 사용이며 앱 재배포는 별도 승인입니다. 외부 구성요소에는 각각의 라이선스가 적용됩니다. 내장 문서·라이선스·외부 소스 자료는 비어 있는 폴더에 내보낼 수 있습니다.

```powershell
.\MP4-Converter.exe --export-support-files ".\MP4-Converter-docs"
```

자동 생성되는 **Source code (zip/tar.gz)**는 배포 안내 저장소의 내용이며 실행파일이 아닙니다.
