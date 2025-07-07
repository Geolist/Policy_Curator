# Policy_Curator

🤖 **Policy_Curator**는 대한민국 청년을 위한 정책 정보를 AI 기반으로 탐색해주는 RAG 기반 웹 애플리케이션입니다.

---

## 🚀 Features

- **맞춤형 정책 검색**  
  사용자가 입력한 질문을 기반으로 정책 관련 PDF 문서를 검색해 관련 정보를 제공합니다.

- **관심사 설정**  
  주거, 일자리/창업, 금융/자산, 복지/문화 등 관심 분야를 선택하면 맞춤형 질문을 추천합니다.

- **Re-Ranker 적용**  
  검색 결과의 정밀도를 높이기 위해 CrossEncoder 모델로 문서 순위를 재조정합니다.

- **최신 LLM 지원**  
  OpenAI GPT-3.5-turbo 모델로 자연스러운 한국어 답변을 생성합니다.

  Policy_Curator/
├── app.py
├── requirements.txt
├── packages.txt
├── data/
│   └── [PDF 문서들]
└── README.md


