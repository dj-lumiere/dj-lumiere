## Hi there 👋

C#으로 밑바닥까지 파고들며 직접 만드는 걸 좋아하는 개발자입니다.
게임, 로봇 시뮬레이터, 그리고 프로그래밍 언어까지 — 도메인은 달라도 "직접 설계하고 만드는 즐거움"을 좇아왔습니다.

- 🔨 **직접 만드는 사람**: C# 객체 시각화 라이브러리부터 LLVM 백엔드 컴파일러까지 혼자서 설계
- 🧩 **알고리즘**: [solved.ac Ruby V](https://solved.ac/djeleanor2) (상위 0.13%), 최장 455일 연속 문제 풀이
- 🔍 **저수준까지 궁금한 사람**: 문법이 IR로 어떻게 낮춰지는지 직접 뜯어보는 걸 좋아합니다
- 🎮 서브컬처 게임과 버추얼 유튜버를 즐기는, 좋아하는 걸 직접 만들어보고 싶은 덕후

### 🛠️ Tech
`C#` `.NET` `Unity` `LLVM` `C` `Python` `Algorithm`

### 📌 Featured Projects

**<img src="assets/razorforge.svg" width="18" alt=""> [RazorForge](https://github.com/dj-lumiere/RazorForge)** — 정밀함을 앞세워 직접 설계한 네이티브 컴파일 언어
> GC도 수명 표기도 없는 단일 소유권, 실패는 기본적으로 크게 터지고 키워드 하나(`try`/`grab`/`lookup`)로 복구하는 에러 모델, 오버플로 동작을 직접 고르는 수치 타입, 코루틴과 OS 스레드를 `Agent[T]` 하나로 묶은 동시성. [📖 Docs](https://razorforge.lumi-dev.xyz)

**<img src="assets/suflae.svg" width="18" alt=""> [Suflae](https://github.com/dj-lumiere/Suflae)** — 공유 상태를 가볍게 다루는 RazorForge의 자매 언어
> 엔티티는 참조 카운트 핸들이고, 스레드를 건너가면 스스로 잠금을 겁니다. 실패 모델과 표준 라이브러리를 RazorForge와 공유하고, REPL을 중심으로 설계. [📖 Docs](https://suflae.lumi-dev.xyz)

> 두 언어는 C# 빌더 코어 **[Anvila](https://github.com/dj-lumiere/Anvila)**(파싱 · 의미 검증 · 단형화 · LLVM IR 생성, 빌드 데몬과 JIT 개발 루프)와 C 네이티브 런타임 **[Ingrid](https://github.com/dj-lumiere/Ingrid)**(코어별 워커 스레드 위의 코루틴, libuv 비동기 I/O, 스택 트레이스가 담긴 크래시 리포트)를 함께 씁니다.

**<img src="https://raw.githubusercontent.com/dj-lumiere/Tessera/master/assets/logo.svg" width="18" alt=""> [Tessera](https://github.com/dj-lumiere/Tessera)** — 연산을 한 단계씩 명시적으로 쓰는 구조적 SSA 언어 & 컴파일러
> 연산자 없이 operation → block → routine → module로 쌓아 올리는 언어. SSA 값, φ 대신 블록 파라미터, 명시적 메모리. 표준 라이브러리는 Tessera로 직접 작성하고, C# 컴파일러가 LLVM IR로 낮춤. [📖 Docs](https://tessera.lumi-dev.xyz/docs/)

**[DebugUtils](https://github.com/dj-lumiere/DebugUtils-CSharp)** — C# 객체 상태 자동 시각화 디버깅 라이브러리
> Reflection/Attribute 기반으로 50+ 타입 자동 지원. 스택 할당 기반 고성능 IEEE 754 변환.

[![Solved.ac](http://mazassumnida.wtf/api/v2/generate_badge?boj=djeleanor2)](https://solved.ac/djeleanor2)
