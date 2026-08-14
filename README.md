# kimssi-labs 배포 창구

kimssi-labs 도구의 **설치 파일을 내려받는 곳**입니다.
이 저장소에 코드는 없고, [Releases](../../releases)에 첨부된 파일이 전부입니다.

## 내려받기

| 파일 | 설명 |
|---|---|
| `wmx3-eni-viewer-<버전>.vsix` | **WMX3ENIViewer** — WMX3 EtherCAT ENI 파일을 VS Code에서 해석·검증하는 확장 (구문 강조, 호버 디코드, 진단, 요약 뷰). VS Code 1.85 이상 |
| `WMXSwitcher-Setup-<버전>.exe` | **WMX Switcher** — 한 PC에 설치된 WMX3/WMX2/MXR2 버전을 전환하고, 버전 간 파일을 비교·복사하며, 관련 레지스트리 값을 편집하는 유틸리티. Windows 10/11 x64 |

최신 파일은 [Releases](../../releases) 탭의 맨 위 릴리스에 있습니다.

## 설치

**`.exe`** 는 Windows 설치 파일입니다. 내려받아 실행하면 마법사가 안내합니다.
.NET 런타임이 포함되어 있어 따로 설치할 필요가 없고, 제거는 Windows의
`설정 → 앱 → 설치된 앱`에서 합니다.

**`.vsix`** 는 VS Code 확장 설치 파일입니다.

```bash
code --install-extension wmx3-eni-viewer-<버전>.vsix
```

또는 VS Code 확장 뷰(Ctrl+Shift+X) 우측 상단 `···` → `Install from VSIX...` → 파일 선택.

업데이트는 새 파일을 같은 방법으로 설치하면 덮어씁니다. 제거는 확장 뷰에서 `Uninstall`.

## 태그 규칙

여러 제품이 한 저장소에 모이므로 태그는 `<제품>-v<버전>` 형식입니다
(예: `wmx3-eni-viewer-v1.3.0`, `wmx-switcher-v1.8.0`).

## 문의

문제나 요청은 [Issues](../../issues)에 남겨주세요.
