# XEL9-Z

**Secure. Compress. Protect.**

압축은 빠르게, 보관은 보안 볼트에. XEL9-Z는 zip·7z·rar·알집 같은 압축 파일을 대부분 여는 Windows·macOS·Linux용 압축 프로그램입니다. 중요한 파일은 XEL9 자체 암호화 포맷인 **보안 볼트(`.x9z`)** 에 담으세요. 비밀번호를 모르면 안의 내용은 물론 파일 이름조차 볼 수 없습니다.

이 저장소는 XEL9-Z의 **공식 배포 저장소**입니다. 설치 파일과 앱 안 업데이트 파일만 있고 소스 코드는 없습니다.

![XEL9-Z 압축 풀기 화면](https://raw.githubusercontent.com/wiki/xel9-update/xel9-z/images/z-extract.png)

- 홈페이지: https://www.xel9.com
- 사용법: **[XEL9-Z 위키](../../wiki)**
- 업데이트 내역: [Releases](../../releases)

## 다운로드

아래 링크는 항상 가장 최근에 나온 파일을 받습니다.

| 운영체제 | 바로 받기 |
|---|---|
| Windows 10·11 (64비트) | [설치 프로그램 (.exe)](../../releases/latest/download/XEL9-Z_x64-setup.exe) · [MSI 설치 패키지](../../releases/latest/download/XEL9-Z_x64_en-US.msi) |
| macOS 11 이상 (Apple 칩·Intel 모두) | [설치 파일 (.dmg)](../../releases/latest/download/XEL9-Z_universal.dmg) |
| Linux (64비트) | [AppImage](../../releases/latest/download/XEL9-Z_amd64.AppImage) · [.deb](../../releases/latest/download/XEL9-Z_amd64.deb) · [.rpm](../../releases/latest/download/XEL9-Z.x86_64.rpm) |
| 명령줄 도구만 | [Windows](../../releases/latest/download/xel9-z-cli-windows-x86_64.zip) · [macOS](../../releases/latest/download/xel9-z-cli-macos-universal.zip) · [Linux](../../releases/latest/download/xel9-z-cli-linux-x86_64.tar.gz) |

파일마다 어떤 것을 고르면 되는지, 받은 파일이 온전한지 확인하는 방법은 위키의 [설치와 업데이트](../../wiki/설치와-업데이트)에 있습니다.

## 사용법

프로그램 사용법은 위키에 정리해 두었습니다.

| 위키 페이지 | 내용 |
|---|---|
| [설치와 업데이트](../../wiki/설치와-업데이트) | 운영체제별 설치 파일, 앱 안 업데이트, 직접 덮어 설치하기, 안전하게 받기 |
| [데스크톱 앱 사용법](../../wiki/데스크톱-앱-사용법) | 화면 그림과 함께 보는 압축하기·풀기, 보안 볼트 관리, 설정, 우클릭 메뉴 |
| [명령줄(CLI) 사용법](../../wiki/명령줄-CLI-사용법) | 터미널의 `x9z` 명령과 예시 |

## 특징

- **파일 이름까지 암호화하는 보안 볼트:** 내용뿐 아니라 파일 이름·크기·폴더 구조도 숨깁니다. 비밀번호를 대량으로 넣어 보는 공격이 어렵도록 시도할 때마다 많은 메모리를 쓰게 합니다.
- **받은 압축 파일, 대부분 바로 열림:** zip·7z·rar·알집(alz·egg)·tar 계열, ISO·DMG 같은 디스크 이미지까지. 확장자가 아니라 내용을 보고 종류를 알아냅니다.
- **위험한 압축 파일 차단:** 폴더 밖으로 나가는 경로, 압축 폭탄, 위험한 링크가 든 파일은 풀기 전에 멈춥니다.
- **앱(GUI)과 명령줄(CLI) 모두:** 마우스로 쓰는 데스크톱 앱과, 스크립트·서버 작업에 쓰는 `x9z` 명령을 함께 제공합니다.
- **광고도, 결제 권유도 없음:** 프로그램 안에 광고가 없고, 유료 전환이나 결제를 권하는 창도 뜨지 않습니다.
- **모든 처리는 이 PC 안에서만:** 업데이트 확인을 켜지 않으면 인터넷에 연결하지 않습니다.

## 안전하게 받기

- XEL9-Z는 **이 저장소와 https://www.xel9.com 에서만** 받으세요.
- 앱 안 업데이트는 앱에 들어 있는 공개 키로 서명을 확인하고, 맞지 않으면 설치하지 않습니다.
- 보안 문제를 발견하면 홈페이지의 연락처로 알려 주세요.

## 사용 조건

> 개인은 물론 회사·학교·공공기관에서도 별도 허락 없이 자유롭게 설치하고 사용할 수 있습니다.

> 이 프로그램은 있는 그대로 제공됩니다. 프로그램을 사용하면서 생긴 자료 손실이나 그 밖의 문제에 대해 제작자는 책임지지 않습니다. 중요한 파일은 따로 백업해 두세요.

© 2026 XEL9 by 1Pixel Inc. 사용은 자유롭지만, 1Pixel Inc.의 허락 없이 프로그램을 고치거나 다른 곳에 다시 배포하거나 판매할 수는 없습니다. 앱에 쓰인 오픈소스 구성 요소의 라이선스는 앱의 설정 → 정보 → **서드파티 라이선스**에 있습니다.

---

**English:** XEL9-Z is a file compression app for Windows, macOS and Linux. It opens most archive formats and stores sensitive files in its own encrypted vault format (`.x9z`), which hides even file names. This repository hosts the official installers and update packages only; see the [wiki](../../wiki) for usage (Korean). Free to use for individuals and organizations; provided as is, without warranty. Modifying, redistributing or selling it without permission of 1Pixel Inc. is not allowed.
