# sam-atelier-img

[sam-atelier](https://github.com/polos0117/sam-atelier) 의 그림 저장소. 코드 저장소가 무거워지지 않게 새 그림(장수 여성 의인화)은 여기 둔다 — Pages 로 `https://polos0117.github.io/sam-atelier-img/img/<파일>` 에서 읽는다. 게임의 초상(`sam-atelier/images/`)과는 따로다.

## 자리

```
img/<장수>_<세계>_<화풍>_f.webp           세계 그림. 1024×1536 (2:3). 세계는 samguk · fantasy · mecha
img/<장수>_<세계>_<화풍>_f_casualN.webp   일상컷 N — 그 세계 그림을 참고 그림으로
img/thumb/<같은 이름>                      목록용(긴 변 512). 워크플로가 만든다
records/<장수>/<세계>.<화풍>-ui.json       생성기의 「기록 JSON」 그대로(+ 올릴 때 generation)
records/<장수>/<세계>-casualN.<화풍>-ui.json
records/replacement.json                   바꾼 그림의 앞 sha256
```

장수 열쇠는 코드 저장소 `data/sam-design.json` 의 한글 이름(예: 관우), 화풍은 `data/style.json`(지금은 `game_keyart`). 규칙은 코드 저장소 `IMAGE_RULES.md`.

## 올린 뒤에 할 일

없다. `img/` 에 webp 를 올리면 `썸네일` 워크플로가 `img/thumb/` 를 만들어 되커밋하고, 코드 저장소의 `그림 등록` 을 깨운다 — 이 저장소의 Actions 비밀 `CODE_REPO_TOKEN`(Fine-grained token, 저장소 sam-atelier 하나, Contents: Read and write)이 있을 때. 없으면 코드 저장소가 한 시간마다 스스로 돈다.
