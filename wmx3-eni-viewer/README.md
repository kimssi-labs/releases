# wmx3-eni-viewer

WMX3ENIViewer 확장 상세 페이지(VS Code Extensions 탭)에 실리는 **스크린샷 호스팅 폴더**입니다.
설치 파일은 이 폴더가 아니라 [Releases](../../releases) 탭의 `wmx3-eni-viewer-v*` 태그에 있습니다.

VS Code는 확장 README의 이미지를 **https 절대 URL로만** 렌더링합니다 — `.vsix` 안에 파일을 넣어
상대 경로로 참조해도 표시되지 않습니다. WMX3ENIViewer의 소스 저장소는 비공개라 그쪽 raw URL은
누구도 열 수 없으므로, 공개된 이 저장소가 이미지의 유일한 주소입니다.

`vsce package --baseImagesUrl https://raw.githubusercontent.com/kimssi-labs/releases/main/wmx3-eni-viewer`
가 패키지 사본의 상대 경로 앞에 이 주소를 붙입니다. 따라서 **`docs/images/` 아래의 파일 이름과
경로는 소스 저장소와 정확히 같아야 합니다** — 이름을 바꾸거나 옮기면 확장 페이지의 이미지가
깨집니다.
