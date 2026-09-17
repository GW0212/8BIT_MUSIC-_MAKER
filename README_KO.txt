8BIT MUSIC MAKER · Studio v4.0 FINAL STABLE
================================================

실행
- index.html을 Chrome / Edge 등 최신 브라우저에서 엽니다.
- 별도 서버나 설치 없이 로컬에서 동작합니다.
- 최초 테마는 화이트이며 선택한 테마는 브라우저에 저장됩니다.

주요 기능
- 32 STEP / Pattern A~D / Song Chain
- SQUARE / PULSE / SAW / TRIANGLE / DRUM·NOISE
- Web Audio Look-ahead Scheduler + 무한 반복
- Master Limiter / 악기별 Volume·Pan·Mute·Solo
- 100개 OST 구성 프로필 + 검색·카테고리·최근·즐겨찾기
- MIDI Import: 최대 A~D 4패턴(2마디×4), 박자표/Tempo/Drum 해석
- JSON Project Import/Export
- WAV / MIDI Export
- Undo / Redo / Autosave
- White / Dark mode
- PC 32 STEP 전체 편집 / 모바일·태블릿 8 STEP 페이지 편집
- 모바일 Playhead FOLLOW ON/OFF

MIDI Import 안내
- .mid / .midi 파일의 앞쪽 최대 8마디를 Pattern A~D에 자동 분할합니다.
- Tempo와 Time Signature를 읽고, 멜로디 음정은 실제 MIDI pitch 관계를 최대한 유지한 채 8개 레인에 매핑합니다.
- MIDI Channel 10(인덱스 9)은 DRUM / NOISE 8종으로 변환합니다.
- 복잡한 원곡 전체를 DAW처럼 완전 재현하는 기능은 아니며, 본 프로그램의 8레인·32STEP 구조에 맞춰 양자화됩니다.

모바일
- 1023px 이하에서는 Compact Touch UI가 적용됩니다.
- SEQUENCER는 1–8 / 9–16 / 17–24 / 25–32 페이지 방식입니다.
- FOLLOW ON이면 재생 위치에 맞춰 페이지가 자동 이동합니다.
- 사용자가 STEP 페이지를 수동으로 바꾸면 FOLLOW가 자동 OFF되어 편집 화면이 갑자기 이동하지 않습니다.

저장
- Autosave와 User Preset은 압축 Grid 포맷을 사용해 localStorage 사용량을 줄였습니다.
- 브라우저 저장 공간이 부족하면 오류 메시지가 표시되므로 JSON Export로 백업하세요.

단축키
- Space: 재생 / 정지
- Esc: 정지
- Ctrl/Cmd + Z: Undo
- Ctrl/Cmd + Y: Redo
- 1~5: 악기 선택
- A~D: 패턴 선택
