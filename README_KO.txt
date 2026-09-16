8BIT MUSIC MAKER · FINAL v3.2
================================

실행
- index.html을 Chrome / Edge / Safari 등 최신 브라우저에서 엽니다.
- 별도 서버, 설치, 회원가입 없이 로컬에서 동작합니다.
- PC와 모바일에서 동일한 프로젝트/기능 구조를 사용합니다.

v3.2 PC / MOBILE RESPONSIVE
- PC 레이아웃은 기존 Studio 구조를 유지하면서 모바일 전용 배치를 추가했습니다.
- 760px 이하: 모바일 전용 1열 작업 흐름으로 전환합니다.
- 480px 이하: 작은 스마트폰용 간격/버튼/시퀀서 크기를 추가 보정합니다.
- 360px 이하: 초소형 화면에서도 헤더와 하단 컨트롤이 넘치지 않도록 압축합니다.
- 가로 모드/낮은 화면 높이에 별도 레이아웃을 적용합니다.
- iPhone Safe Area를 상하좌우 모두 반영합니다.

모바일 조작
- 시퀀서 셀: 탭하면 입력/삭제합니다.
- 시퀀서: 좌우 스와이프로 32 STEP을 이동합니다.
- PC: 기존처럼 마우스 드래그 연속 입력/삭제가 유지됩니다.
- 음표/드럼 레이블은 시퀀서를 좌우로 이동해도 왼쪽에 고정됩니다.
- STEP 번호줄과 시퀀서 본체가 하나의 스크롤 영역을 사용해 정렬이 어긋나지 않습니다.
- 악기 목록은 가로 스와이프 카드 방식입니다.
- Mixer는 채널 단위로 스냅되는 가로 스크롤 방식입니다.
- 화면 아래 모바일 전용 Dock에서 재생 / 정지 / Undo / Redo를 바로 실행할 수 있습니다.
- 현재 Pattern, BPM, 재생 상태를 하단 Dock에서 확인할 수 있습니다.

모바일 UX 세부 개선
- 버튼과 주요 컨트롤의 터치 영역을 확대했습니다.
- 입력창/Select는 모바일에서 16px을 사용해 iOS 자동 확대 현상을 방지합니다.
- 확인 Modal은 모바일에서 하단 Sheet 형태로 표시됩니다.
- Toast는 하단 Dock 위에 표시되어 겹치지 않습니다.
- Preset / Project / Export 영역을 모바일에서 1열 또는 2열 버튼 구조로 재배치했습니다.
- 키보드 단축키 안내는 모바일에서 터치 조작 안내로 자동 전환됩니다.
- Visualizer Canvas는 실제 표시 크기에 맞춰 리사이즈하며 DPR을 1.5로 제한해 모바일 렌더 부하를 줄입니다.

v3.1 기능 유지
- 기본 테마: 화이트 모드
- 화이트/다크 모드 전환 및 localStorage 기억
- Web Audio currentTime 기반 Look-ahead Scheduler
- 32 STEP = 16분음표 2마디
- Pulse Duty Cycle 12.5% / 25% / 50%
- 8종 합성 드럼(Kick/Snare/HH/Tom/Clap/Crash)
- Pattern A/B/C/D + Song Chain
- Undo/Redo, 16스텝 복사/교환
- Key / Scale / Octave / Swing
- 악기별 Volume / Pan / Mute / Solo Mixer
- 프로젝트 자동복구, JSON 저장/불러오기, 사용자 프리셋
- 내장 프리셋 7종
- WAV Export / MIDI Export
- 외부 폰트/라이브러리 의존 없음

PC 키보드
- Space: Play / Stop
- Esc: Stop
- Ctrl+Z: Undo
- Ctrl+Y: Redo
- 1~5: 악기 선택
- A~D: 패턴 선택

저장 호환성
- v3.0/v3.1에서 사용하던 자동복구 키(8bit_music_maker_autosave_v3)를 그대로 유지합니다.
- 기존 v3 프로젝트가 브라우저 localStorage에 남아 있으면 v3.2에서도 복원됩니다.
- 프로젝트를 다른 기기로 옮길 때는 JSON 저장 기능을 사용하세요.

권장 환경
- PC: 최신 Chrome / Edge / Safari
- Android: 최신 Chrome
- iPhone/iPad: 최신 Safari 또는 Chromium 계열 브라우저
- 모바일에서는 브라우저의 오디오 정책상 최초 재생 시 사용자의 직접 터치가 필요할 수 있습니다.
