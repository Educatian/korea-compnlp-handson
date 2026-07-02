# 교육학 연구자를 위한 Computational NLP — Colab 실습

고려대학교 특강 참여활동용 노트북입니다. **설치·코딩 경험이 없어도** 됩니다.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Educatian/korea-compnlp-handson/blob/main/Computational_NLP_HandsOn.ipynb)

## 여는 법
1. 위 **Open in Colab** 배지를 클릭
2. 상단 메뉴 **런타임 → 모두 실행**(Runtime → Run all)

GPU도, API 키도, 회원가입도 필요 없습니다. (정적 임베딩 = CPU만으로 동작)

## 무엇을 하나
- 문장을 **의미 좌표**(임베딩)로 바꾸기
- 같은 단어, 다른 의미 — 맥락에 따라 유사도가 갈리는 것 확인
- **의미로 검색**하기(키워드가 아니라 뜻)
- (선택) LLM에게 공감 코딩 시키기

> ⚠️ 실제 학생 데이터는 외부 모델에 넣지 마세요 — 합성·공개 예시만 사용합니다.

핵심 메시지 — **construct-first**: 도구가 아니라 '무엇을, 어떤 증거로, 어디까지'가 먼저입니다.
