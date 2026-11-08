# 숲 탐험 인벤토리 에셋

실제 사용자 계정에 설치한 Codex 플러그인 0.2.1을 이 프로젝트에서 스킬로 선택해 24×24 황동 열쇠 아이콘을 생성했다.

![황동 열쇠 확대본](acorn-key/preview.png)

[게임용 PNG](acorn-key/asset.png) · [생성 요청](key.request.json) · [검증 결과](acorn-key/validation.json) · [설치·실행 기록](codex-skill-check.json)

이 폴더에서 독립 검증을 다시 실행할 수 있다.

```sh
pixel-asset validate --request key.request.json acorn-key/asset.png
```

같은 요청으로 새 초안을 생성할 때는 `pixel-asset build --request key.request.json --codex --out acorn-key-v2`처럼 새 출력 경로를 지정한다. 생성에는 이 PC의 Codex 내장 이미지 기능을 사용한다.
