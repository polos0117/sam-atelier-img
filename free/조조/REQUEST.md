# 조조 — GPT 설계 지시문 부탁(그림은 그리지 않는다)

polos0117/sam-atelier-img 저장소의 `free/조조/` 폴더에 있는 설계 주문(`*-brief.txt`)을 하나씩 읽고, 주문 끝의 지시대로 **그림 지시문 글만** 써서 같은 폴더에 아래 이름으로 올려줘(main 에 일반 push). 그림은 그리지 마 — 그림은 내가 API 로 그린다.

- `samguk.api25-brief.txt` → 서로 확실히 다른 두 설계를 `samguk.api25-gpt1.txt` · `samguk.api25-gpt2.txt`
- `fantasy.api25-brief.txt` → 서로 확실히 다른 두 설계를 `fantasy.api25-gpt1.txt` · `fantasy.api25-gpt2.txt`
- `mecha.api25-brief.txt` → 서로 확실히 다른 두 설계를 `mecha.api25-gpt1.txt` · `mecha.api25-gpt2.txt`

규칙
- 주문에 「fixed」 라고 적힌 것(의상 실루엣 목록 · 무기 · 색 · 노출 · 얼굴 비율 · 구도)은 그대로 지킨다. 자유인 것만 새로 짓는다.
- 일상컷 옷 자유는 `free/outfit-catalog.md` 에 없는 옷으로. Outfit 줄 말고는 한 글자도 바꾸지 않는다.
- 파일에는 지시문 글만(설명 · 머리말 없이, 영어).
- 이미 있는 `-gpt*.txt` 는 덮지 않는다.
