THE NEXT STAR — Vertical Slice Demo
====================================

■ 실행 방법
index.html 파일을 브라우저에서 열면 바로 실행됩니다.

■ 폴더 구조
TheNextStar/
  ├ index.html          ← 게임 메인 파일
  ├ 📁 bg/              ← 배경 이미지 (1280x720px)
  │   ├ bg_dormitory.png   (훈련동 입소)
  │   ├ bg_corridor.png    (첫 만남 - 복도)
  │   └ bg_interview.png   (블라인드 인터뷰)
  ├ 📁 characters/      ← 캐릭터 이미지 (PNG 투명배경, 600x900px)
  │   ├ char_player.png
  │   ├ char_sehan.png
  │   ├ char_minu.png
  │   ├ char_hajun.png
  │   ├ char_pd.png
  │   └ char_staff.png
  ├ 📁 audio/           ← BGM/효과음 (나중에)
  └ 📁 data/            ← CSV 데이터 파일

■ 이미지 추가 방법
파일 이름을 위에 맞게 맞춰서 해당 폴더에 넣으면 자동 적용됩니다.
코드 수정 불필요!

■ 구현된 씬
- SCENE 01: 훈련동 입소
- SCENE 02: 첫 만남 (윤세한, 강민우, 이하준)
- SCENE 03: 블라인드 인터뷰 (선택지 3개)

■ 스탯 시스템
노력 / 실력 / 인기 / 방송 (각 0~10)
선택지 클릭 시 해당 스탯 +3 적용

■ 조작 방법
- 클릭 또는 스페이스/엔터 → 대사 진행
- 타이핑 중 클릭 → 전체 텍스트 즉시 표시
