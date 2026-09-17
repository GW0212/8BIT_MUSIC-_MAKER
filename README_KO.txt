8BIT MUSIC MAKER v4.6 FINAL STABLE

실행: index.html을 브라우저에서 여세요.
필수 파일: index.html, styles.css, silent-keepalive.wav, favicon.png

모바일
- PLAY / STOP / 뒤로 / 앞으로 바는 스크롤 시 상단에 고정됩니다.
- SEQUENCER는 8 STEP 페이지 방식입니다. FOLLOW ON 시 재생 위치를 자동 추적합니다.
- iOS에서는 지원 시 playback AudioSession을 사용하고 구형 환경은 silent-keepalive.wav fallback을 사용합니다.
- 모바일 WAV 출력은 메모리 안정성을 위해 기기 조건에 따라 최대 60~120초로 제한될 수 있습니다.

MIDI
- .mid / .midi 파일의 최대 8마디를 Pattern A-D로 가져옵니다.
- Tempo 변화와 Time Signature 변화를 STEP timing map으로 반영합니다.
- 실제 음정 관계를 8개 레인에 가장 가까운 형태로 매핑합니다.

주의
- 휴대폰 미디어 볼륨 자체가 0이면 웹페이지가 시스템 볼륨을 강제로 올릴 수 없습니다.
