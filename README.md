[Uploading README.md…]()
# 맥 사진 자동 분류 (Mac Photo Auto Sort)

`PhotoInbox` 폴더에 사진/동영상을 넣으면 촬영일(EXIF) 기준으로
`PhotoSorted/연도/월/일` 폴더에 자동으로 정리해주는 macOS 설정 가이드입니다.

macOS 기본 기능(Automator Folder Action)과 무료 오픈소스 도구(exiftool)만 사용하며,
별도 유료 앱 없이 동작합니다.

## 사용 방법

전체 설치 과정, 스크립트 전문, 트러블슈팅은 아래 문서를 참고하세요.

👉 [맥_사진_자동분류_설정_가이드.md](./맥_사진_자동분류_설정_가이드.md)

## 요약

1. Homebrew + exiftool 설치
2. `~/Scripts/organize_photos.sh` 스크립트 저장
3. Automator로 Folder Action 생성 → `PhotoInbox` 폴더에 연결
4. `PhotoInbox`에 사진을 넣으면 자동으로 `PhotoSorted/연도/월/일`에 정리됨

## 맥 초기화 후 재설정할 때

이 저장소를 클론(또는 `맥_사진_자동분류_설정_가이드.md` 다운로드) 한 뒤,
가이드 문서에 있는 단계를 순서대로 따라 하면 그대로 다시 세팅할 수 있습니다.
