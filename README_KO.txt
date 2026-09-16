8BIT MUSIC MAKER · v3.5 EXPANDED GENERATE
==========================================

실행
- ZIP 압축을 풀면 index.html과 favicon, 문서 파일들이 바로 나옵니다.
- index.html을 최신 Chrome / Edge / Safari에서 열면 됩니다.
- 별도 서버, 설치, 회원가입 없이 로컬에서 동작합니다.

v3.5 GENERATE 멜로디 확장
- 기존 단순 확률형 노트 배치를 전용 멜로디 생성기로 교체했습니다.
- 현재 선택한 Key / Scale / Octave를 유지하면서 서로 다른 구조의 멜로디를 생성합니다.
- 12가지 Melody Style:
  CHIP POP / ARPEGGIO / CALL & RESPONSE / STEPWISE / WIDE LEAPS / SYNCOPATED
  OSTINATO / AMBIENT / BASS DRIVEN / COUNTERPOINT / SEQUENCE / MINIMAL
- 리드 악기는 SQUARE에만 고정되지 않고 SQUARE / PULSE / SAW 사이에서 선택됩니다.
- TRIANGLE은 Bass 역할을 중심으로 8종 Progression과 리듬 변형을 사용합니다.
- Arrangement도 DUO / ARP / COUNTER / FULL / ECHO로 바뀝니다.
- 1마디와 2마디는 Transpose / Invert / Answer / Sequence 변형을 사용해 같은 복사본이 되지 않도록 구성합니다.
- 리듬도 Straight 8th / Syncopated / Sparse / Offbeat / Drive / Dotted / Minimal 계열에서 변형됩니다.
- 직전 생성 결과와 지나치게 비슷한 멜로디는 자동 재생성합니다.
- DRUM / NOISE의 v3.4 Smart Groove Generator도 그대로 유지됩니다.

DRUM / NOISE GENERATE
- STRAIGHT / BREAKBEAT / FOUR ON FLOOR / HALF-TIME
- SYNCOPATED / SPARSE / TOM DRIVE / DOUBLE-TIME
- Bar 1 / Bar 2 Variation, Ending Fill, Clap / Crash / Open HH / Tom 변형
- Open HH와 Closed HH가 같은 Step에서 동시에 켜지지 않도록 처리

모바일 / 태블릿 UI
- 1024px 미만은 Compact Touch Layout을 사용합니다.
- SEQUENCER는 32 STEP을 한 번에 억지로 표시하지 않고 8 STEP씩 전환합니다.
  · 1–8
  · 9–16
  · 17–24
  · 25–32
- 스마트폰부터 태블릿까지 화면 밖 잘림 없이 현재 8 STEP이 완전히 표시됩니다.
- 560px 미만: Instrument 2열 / Mixer 1열
- 560~1023px: Instrument 5열 / Mixer 2열
- 낮은 높이의 모바일 가로 화면에서는 하단 고정 Dock을 숨겨 작업 영역을 가리지 않습니다.
- 일반 세로 모바일에서는 하단 Dock으로 Play / Stop / Undo / Redo를 빠르게 사용할 수 있습니다.
- iPhone Safe Area 및 16px Form 입력 크기를 적용했습니다.

PC UI
- 1024px 이상에서는 32 STEP 전체 시퀀서를 사용합니다.
- 마우스 Drag Paint 입력을 지원합니다.
- Space: Play / Stop
- Esc: Stop
- Ctrl+Z: Undo
- Ctrl+Y: Redo
- 1~5: 악기 선택
- A~D: 패턴 선택

기존 주요 기능
- 화이트 모드 기본 / 다크 모드 전환
- Web Audio currentTime 기반 Look-ahead Scheduler
- 32 STEP = 16분음표 2마디
- Pulse Duty Cycle 12.5% / 25% / 50%
- 8종 합성 드럼
- Pattern A/B/C/D + Song Chain
- Undo / Redo / 16 STEP 복사·교환
- Key / Scale / Octave / Swing
- 악기별 Volume / Pan / Mute / Solo
- 자동복구 Autosave
- JSON 저장 / 불러오기
- 사용자 프리셋 / 내장 프리셋 7종
- WAV / MIDI Export
- 외부 폰트·라이브러리 의존 없음

저장 호환성
- 자동복구 키 8bit_music_maker_autosave_v3를 유지합니다.
- v3.x 작업 데이터가 브라우저 localStorage에 있으면 v3.5에서도 복원됩니다.
- 다른 기기로 옮길 때는 JSON 저장 기능을 사용하세요.

권장 환경
- PC: 최신 Chrome / Edge / Safari
- Android: 최신 Chrome
- iPhone/iPad: 최신 Safari 또는 Chromium 계열 브라우저
- 모바일 브라우저 정책상 최초 오디오 재생에는 사용자 직접 터치가 필요할 수 있습니다.
