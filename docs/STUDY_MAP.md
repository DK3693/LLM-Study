# LLM 학습 지도

| 영역 | 원자료에서 확인한 실습 | 연결되는 개념 |
|---|---|---|
| 모델 로딩 | Transformers, DeepSeek 계열 모델 로딩 | 토크나이저와 모델, device_map, dtype |
| 로컬 추론 | Ollama 서버·클라이언트, 코딩 모델 | 모델 실행과 애플리케이션 호출 분리 |
| 프롬프트 | prompt engineering, prompt enhance | 질문 형식, 역할과 출력 구조 |
| 체인 | LangChain 예제 | 프롬프트·모델·파서 연결 |
| 기본 RAG | PDF 챗봇, 뉴스 검색 | 로딩·청크·임베딩·검색·답변 |
| 검색 확장 | Multi-query, Adaptive RAG | 질문 변형, 문서 라우팅, 검색 개수 |
| 그래프 | LangGraph 판정·협업·supervisor | 상태, 노드, 조건부 전이 |
| 도구 | MCP, 날씨, 멀티 도구 | 도구 정의와 호출 경계 |
| 관찰 | LangSmith 예제 | 실행 단계와 추적 정보 |
| 미세조정 | LoRA·DoRA 예제 | PEFT 설정과 어댑터 |
| 자동화 | n8n 연계 예제 | 외부 워크플로와 모델 호출 |
| 멀티모달 | LLaVA 관련 예제 | 이미지 정보와 문서 검색 결합 |

위 표는 제공된 학습 자료의 범위를 나타냅니다. 각 항목에 해당하는 강사용 원본 전체는 공개본에 포함하지 않았습니다.

## 공개 노트북

`notebooks/01_model_loading.ipynb`는 모델과 토크나이저를 로딩하는 짧은 실습입니다. 학습·평가·서비스 배포 코드는 포함하지 않습니다.

## 심화 정리

학습 매뉴얼에는 Adaptive RAG의 각 노드를 개별적으로 확인하는 과정과 기본 RAG와의 비교가 설명되어 있습니다. 공개 문서는 그 흐름을 [ADAPTIVE_RAG.md](ADAPTIVE_RAG.md)와 [MANUAL_NOTES.md](MANUAL_NOTES.md)에 요약했습니다.
