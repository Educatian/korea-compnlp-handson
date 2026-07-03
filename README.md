# 교육학 연구자를 위한 Computational NLP — Colab 실습

고려대학교 특강 참여활동용 노트북입니다. **설치·코딩 경험이 없어도** 됩니다.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Educatian/korea-compnlp-handson/blob/main/Computational_NLP_HandsOn.ipynb)

## 여는 법
1. 위 **Open in Colab** 배지를 클릭
2. 상단 메뉴 **런타임 → 모두 실행**(Runtime → Run all)

API 키도, 회원가입도 필요 없습니다. (1~7단계는 CPU만으로 즉시 동작)

## 손으로 해보는 10단계
1. 문장을 **의미 좌표**(임베딩)로 바꾸기
2. 같은 단어, 다른 의미 — 맥락에 따라 유사도가 갈리는 것 확인
3. **의미로 검색**하기(키워드가 아니라 뜻)
4. **LIWC식 단어 세기**와 비교 — 부정어·맥락의 한계 보기
5. 문장들을 **2D 지도**에 그려보기(PCA)
6. 감정은 점수가 아니라 **궤적**으로 보기
7. 라벨 없이 **주제 묶기**(군집화 · BERTopic 축소판)
8. **진짜 BERT** ① — 맥락으로 빈칸 채우기(`klue/bert-base`)
9. **진짜 BERT** ② — 같은 단어도 맥락 따라 다른 벡터(정적 임베딩은 못 하는 것)
10. 직접 내 문장으로 바꿔보기 ✍️ · (선택) LLM에게 공감 코딩 시키기

> 8~9단계(BERT)는 첫 실행 때 한국어 BERT 모델(~430MB)을 내려받아 20~40초 걸릴 수 있습니다. 여전히 API 키는 불필요.
>
> ⚠️ 실제 학생 데이터는 외부 모델에 넣지 마세요 — 합성·공개 예시만 사용합니다.

핵심 메시지 — **construct-first**: 도구가 아니라 '무엇을, 어떤 증거로, 어디까지'가 먼저입니다.
