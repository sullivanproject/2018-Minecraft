# 기여 가이드

* 설리번 프로젝트의 '마인크래프트로 미니 게임 코딩하기'의 강의계획서 저장소입니다.
* 최소 5명이 협업하여 계획서를 작성하기 때문에 본 저장소에 기여할 때에는 사전에 협의한 아래의 규칙에 따라야 합니다.

## 문서 작성 컨벤션

* 본 저장소는 기본적으로  [markdownlint](https://github.com/markdownlint/markdownlint)의
* `default` 규칙을 사용하며, 일부 수정된 규칙은 `.markdownlint.json` 에 명시되어 있습니다.
* 또한 markdownlint를 보조하는 `editorconfig` 규칙도 본 저장소에 포함되어 있습니다.
  마지막 줄에서 줄바꿈을 강제하는 `insert_final_newline` 옵션은 `markdownlint`에서는 제공하지 않으니
  후술하는 [적용법](#적용법)에서 `markdownlint`와 함께 규칙을 지켜주셔야 합니다.

## 적용법

* 위 컨벤션을 따르는 가장 쉽고 빠른 방법은, 평소에 사용하는 에디터의 확장프로그램으로 제공되는
  `markdownlint`와 `editorconfig` 패키지를 설치하는 것입니다.
    * VSCode
        * [editorconfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
        * [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)
    * Atom
        * [editorconfig](https://atom.io/packages/editorconfig)
        * [markdownlint](https://atom.io/packages/linter-markdownlint)
    * Sublime Text(Package Control)
        * [editorconfig](https://packagecontrol.io/packages/EditorConfig)
        * [markdownlint](https://packagecontrol.io/packages/SublimeLinter-contrib-markdownlint)
    * IntelliJ
        * [editorconfig(기본 설치)](https://plugins.jetbrains.com/plugin/7294-editorconfig)
        * ~~markdownlint~~
* 그 외에 패키지를 제공하지 않는 에디터나 CLI 환경에서는 [markdownlint](https://github.com/markdownlint/markdownlint/blob/master/README.md#installation)와
  [eclint](https://github.com/jedmao/eclint)를 사용하면 됩니다. 그러나 추천하지 않습니다.
