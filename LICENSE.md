# Otomata 최종 사용자 라이선스 계약 (EULA)

**© 2026 새온 (Saeon). All rights reserved.** · 시행 2026년 10월 16일 · 개정 시행 2026년 11월 23일(제3조 LGPL 구성요소 예외 · 제5조 구성요소 목록)

본 소프트웨어(Otomata, 이하 "프로그램")는 오픈소스가 아닌 **독점(proprietary) 소프트웨어**입니다.
프로그램을 설치하거나 사용하면 아래 조건과 **[이용약관](https://otomata.app/terms.html)** 에 동의한 것으로 간주됩니다.
라이선스 키 · 결제 · 환불 · 책임 제한 등 이 문서에 없는 사항과, 이 문서와 이용약관이 다를 때는 **이용약관이 우선**합니다.

## 1. 무료 기능과 라이선스 키

- 프로그램은 무료로 설치 · 사용할 수 있습니다(개인 · 상업 목적 모두). 음원 불러오기 · 보기 · 재생 · 직접 편집 · oto.ini 내보내기 · LAB 편집은 키 없이 됩니다.
- **자동 원음설정(AI 추론)** 은 유료 **라이선스 키**가 있어야 합니다. 라이선스는 1회 구매이며, 키 하나로 구매자가 쓰는 **PC 3대**까지 활성화할 수 있습니다.
- 키는 구매자 본인에게만 주어지며 공유 · 재판매 · 공개 · 양도할 수 없습니다. 환불 · 결제 취소되었거나 공유가 확인된 키는 비활성화될 수 있습니다.
- 처음 활성화할 때 한 번 인터넷 연결이 필요하며, 이후 인터넷에 연결되면 약 7일마다 키를 다시 확인합니다.
- 구매한 판의 업데이트는 평생 무료입니다(별도로 판매하는 판 · 추가 기능 제외).
- 환불: 구매 후 7일 이내 이유와 관계없이, 14일 이내 키 미활성 시, 설명대로 작동하지 않는 경우 — 자세한 기준은 이용약관 제7조.

## 2. 결과물

프로그램으로 만든 결과물(oto.ini, .lab, oto.omt 등)의 권리는 **사용자에게 있으며**, 이를 활용해 만든 음원 등은 **상업적으로 이용 · 판매할 수 있습니다.** 다른 사람이 만든 음원에 대한 권리는 부여하지 않습니다.

## 3. 금지되는 것

- 프로그램의 **수정, 개작, 2차적 저작물 제작**
- **역설계, 디컴파일, 디스어셈블**, 소스 코드 추출 시도 (관련 법이 명시적으로 허용하는 범위 제외)
- 프로그램 전체 또는 일부 파일의 **재배포, 재판매, 대여, 임대, 공유** (공식 다운로드 페이지 링크 공유는 괜찮습니다)
- 라이선스 확인 · 보호 장치(난독화 등)의 우회 또는 제거
- 내장 모델 · 데이터를 프로그램 외부에서 추출 · 사용하는 행위

**LGPL 구성요소 예외:** 프로그램에 들어 있는 LGPL 구성요소(Qt / PySide6 / shiboken6, libsndfile, libsoxr)에는 이 조의 제한이 적용되지 않습니다. 사용자는 이 라이브러리 파일들을 자신이 쓰려고 수정하거나 다른 버전으로 바꿀 수 있고, 그 수정을 디버깅하는 데 필요한 범위에서 프로그램을 역설계할 수 있습니다. 이 구성요소들 자체의 재배포는 각 라이선스(LGPL)를 따릅니다. 이 예외는 그 밖의 부분(Otomata 자체 코드 · 내장 모델 · NVIDIA CUDA · cuDNN 런타임)에는 적용되지 않습니다.

## 4. 보증 부인과 책임 제한

프로그램은 **"있는 그대로(AS IS)" 제공**되며, 자동 원음설정 결과는 AI 가 만든 초안입니다. 법이 허용하는 범위에서 저작권자의 책임은 사용자가 라이선스에 지불한 금액을 한도로 합니다. 자세한 내용은 [면책 고지](https://otomata.app/disclaimer.html)와 이용약관 제9조를 따릅니다.

## 5. 제3자 구성요소

프로그램은 오픈소스 · 제3자 구성요소를 포함하며, 각 구성요소에는 해당 라이선스가 적용됩니다.
본 계약은 해당 라이선스가 부여하는 권리를 제한하지 않습니다.

**전체 목록과 라이선스 전문은 설치 폴더의 `THIRD_PARTY_NOTICES.txt` 에 있습니다.** 주요 구성요소는 다음과 같습니다.

- PySide6 / Qt — LGPL-3.0
- libsndfile — LGPL-2.1 · libsoxr — LGPL-2.1 이상
- ONNX Runtime — MIT
- librosa — ISC
- NumPy / SciPy — BSD-3-Clause
- Numba — BSD-2-Clause
- matplotlib — PSF 기반 라이선스
- cryptography — Apache-2.0 / BSD
- Lucide icons — ISC
- Pretendard 글꼴 — SIL Open Font License 1.1
- PyArmor 런타임 — PyArmor 라이선스에 따라 배포
- (GPU 판) NVIDIA CUDA · cuDNN 런타임 — NVIDIA 소프트웨어 라이선스

LGPL 구성요소의 해당 버전 소스 코드는, 그 버전의 마지막 배포일로부터 최소 3년간 사본을 가진 누구에게나 실비 이하로 제공합니다. 요청: contact@otomata.app

---

# Otomata End User License Agreement (Summary)

*Machine-translated from Korean. The Korean text above and the [Terms of Use](https://otomata.app/terms.html) prevail.*

**© 2026 Saeon. All rights reserved.** This is proprietary software, not open source. Effective October 16, 2026; amended effective November 23, 2026 (LGPL exception, component list).

- **Free to use:** you may install and use the program for personal or commercial purposes. Viewing, playback, manual editing, oto.ini export and LAB editing need no key.
- **License key:** AI Auto Otoing requires a paid license key — a one-time purchase that can be activated on up to **3 PCs**. Keys are personal and may not be shared, resold or transferred. One online activation is needed; the key is re-checked about every 7 days when online. Free updates for life for the edition you bought. Refunds: within 7 days for any reason, within 14 days if never activated, or if it does not work as described (Terms of Use, section 7).
- **Your output** (oto.ini, .lab, voicebanks, etc.) belongs to **you** and may be used commercially.
- **You may not** modify, reverse-engineer, decompile, redistribute, resell, rent or share the program or any part of it, bypass license checks or protection measures, or extract the bundled models. **Exception:** you may modify or replace the bundled LGPL libraries (Qt/PySide6/shiboken6, libsndfile, libsoxr) and reverse-engineer the program as needed to debug such modifications; those libraries may be redistributed under their own licenses. This exception does not cover the rest of the program (Otomata's own code, the bundled models, or the NVIDIA CUDA/cuDNN runtime).
- Provided **"AS IS"**; liability is limited to the amount you paid, as far as the law allows. See the [Disclaimer](https://otomata.app/disclaimer.html).
- Third-party components keep their own licenses, which this agreement does not restrict. The full list and license texts are in `THIRD_PARTY_NOTICES.txt` in the installation folder. Main components: PySide6/Qt (LGPL-3.0), libsndfile and libsoxr (LGPL-2.1), ONNX Runtime (MIT), librosa (ISC), NumPy/SciPy (BSD), Numba, matplotlib, cryptography, Lucide, Pretendard (OFL-1.1), the PyArmor runtime, and NVIDIA CUDA/cuDNN in the GPU edition. Source code for the exact LGPL versions included is available on request at contact@otomata.app for at least three years.
