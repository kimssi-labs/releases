# kimssi-labs 배포 창구

kimssi-labs에서 만든 도구의 **설치 파일을 공개적으로 내려받는 곳**입니다.
소스 코드는 비공개이며, 이 저장소에는 코드가 없습니다 — [Releases](../../releases) 탭의 첨부 파일이 전부입니다.

## 제품

| 제품 | 설명 | 다운로드 |
|---|---|---|
| **WMX3ENIViewer** | WMX3 EtherCAT ENI 파일을 VS Code에서 해석·검증하는 확장 (구문 강조, 호버 디코드, 진단, 요약 뷰) | [최신 릴리스](../../releases?q=wmx3-eni-viewer&expanded=true) |

## 설치 방법

### `.vsix` — VS Code 확장

```bash
code --install-extension <내려받은 파일>.vsix
```

또는 VS Code 확장 뷰(Ctrl+Shift+X) 우측 상단 `···` → `Install from VSIX...` → 파일 선택.

업데이트도 같은 방법으로 새 파일을 설치하면 덮어씁니다. 제거는 확장 뷰에서 `Uninstall`.

## 릴리스 태그 규칙

한 저장소에 여러 제품이 모이므로 태그는 `<제품>-v<버전>` 형식입니다 (예: `wmx3-eni-viewer-v1.2.0`).
각 릴리스는 해당 제품의 비공개 저장소 CI가 태그 푸시 시 자동으로 올립니다.

## 문의

문제나 요청은 [Issues](../../issues)에 남겨주세요.
