# Claude Cookbooks

Claude Cookbooks는 개발자들이 Claude를 활용하여 개발할 수 있도록 설계된 코드와 가이드를 제공합니다. 여러분의 프로젝트에 쉽게 통합할 수 있는 복사 가능한 코드 스니펫을 제공합니다.

## 사전 요구사항

이 쿡북의 예제를 최대한 활용하려면 Claude API 키가 필요합니다 ([여기서 무료로 가입](https://www.anthropic.com)).

코드 예제는 주로 Python으로 작성되어 있지만, Claude API와 상호작용을 지원하는 모든 프로그래밍 언어에 적용할 수 있습니다.

Claude API를 처음 사용하시는 분들은 먼저 [Claude API 기초 과정](https://github.com/anthropics/courses/tree/master/anthropic_api_fundamentals)을 통해 기본기를 다지시는 것을 권장합니다.

## 추가 리소스

Claude와 AI 어시스턴트 경험을 향상시킬 수 있는 유용한 링크들입니다:

- [Anthropic 개발자 문서](https://docs.claude.com/claude/docs/guide-to-anthropics-prompt-engineering-resources)
- [Anthropic 지원 문서](https://support.anthropic.com)
- [Anthropic Discord 커뮤니티](https://www.anthropic.com/discord)

## 기여하기

Claude Cookbooks는 개발자 커뮤니티의 기여로 발전합니다. 아이디어 제출, 오타 수정, 새 가이드 추가, 기존 가이드 개선 등 여러분의 모든 기여를 환영합니다. 기여를 통해 이 리소스를 모든 사람에게 더 가치 있게 만들 수 있습니다.

중복 작업을 피하기 위해 기여 전에 기존 이슈와 풀 리퀘스트를 검토해 주세요.

새로운 예제나 가이드에 대한 아이디어가 있으시면 [이슈 페이지](https://github.com/anthropics/anthropic-cookbook/issues)에서 공유해 주세요.

## 레시피 목차

### 핵심 기능 (Capabilities)
- [분류 (Classification)](https://github.com/anthropics/anthropic-cookbook/tree/main/capabilities/classification): Claude를 사용한 텍스트 및 데이터 분류 기법을 탐색합니다.
  - [한국어 가이드](./capabilities/classification/guide_ko.ipynb): 보험 고객 지원 티켓 분류기 구축 (RAG + Chain-of-Thought)
- [검색 증강 생성 (RAG)](https://github.com/anthropics/anthropic-cookbook/tree/main/capabilities/retrieval_augmented_generation): 외부 지식으로 Claude의 응답을 향상시키는 방법을 배웁니다.
- [요약 (Summarization)](https://github.com/anthropics/anthropic-cookbook/tree/main/capabilities/summarization): Claude를 활용한 효과적인 텍스트 요약 기법을 알아봅니다.

### 도구 사용 및 통합 (Tool Use)
- [도구 사용](https://github.com/anthropics/anthropic-cookbook/tree/main/tool_use): Claude를 외부 도구 및 함수와 통합하여 기능을 확장하는 방법을 배웁니다.
  - [고객 서비스 에이전트](https://github.com/anthropics/anthropic-cookbook/blob/main/tool_use/customer_service_agent.ipynb)
  - [계산기 통합](https://github.com/anthropics/anthropic-cookbook/blob/main/tool_use/calculator_tool.ipynb)
  - [SQL 쿼리](https://github.com/anthropics/anthropic-cookbook/blob/main/misc/how_to_make_sql_queries.ipynb)

### 서드파티 통합
- [검색 증강 생성](https://github.com/anthropics/anthropic-cookbook/tree/main/third_party): 외부 데이터 소스로 Claude의 지식을 보완합니다.
  - [벡터 데이터베이스 (Pinecone)](https://github.com/anthropics/anthropic-cookbook/blob/main/third_party/Pinecone/rag_using_pinecone.ipynb)
  - [위키피디아](https://github.com/anthropics/anthropic-cookbook/blob/main/third_party/Wikipedia/wikipedia-search-cookbook.ipynb/)
  - [웹 페이지](https://github.com/anthropics/anthropic-cookbook/blob/main/misc/read_web_pages_with_haiku.ipynb)
- [Voyage AI를 활용한 임베딩](https://github.com/anthropics/anthropic-cookbook/blob/main/third_party/VoyageAI/how_to_create_embeddings.md)

### 멀티모달 기능
- [Claude 비전](https://github.com/anthropics/anthropic-cookbook/tree/main/multimodal):
  - [이미지 시작하기](https://github.com/anthropics/anthropic-cookbook/blob/main/multimodal/getting_started_with_vision.ipynb)
  - [비전 모범 사례](https://github.com/anthropics/anthropic-cookbook/blob/main/multimodal/best_practices_for_vision.ipynb)
  - [차트 및 그래프 해석](https://github.com/anthropics/anthropic-cookbook/blob/main/multimodal/reading_charts_graphs_powerpoints.ipynb)
  - [양식에서 콘텐츠 추출](https://github.com/anthropics/anthropic-cookbook/blob/main/multimodal/how_to_transcribe_text.ipynb)
- [Claude로 이미지 생성](https://github.com/anthropics/anthropic-cookbook/blob/main/misc/illustrated_responses.ipynb): Claude와 Stable Diffusion을 사용한 이미지 생성.

### 고급 기법
- [서브 에이전트](https://github.com/anthropics/anthropic-cookbook/blob/main/multimodal/using_sub_agents.ipynb): Haiku를 Opus와 결합한 서브 에이전트로 사용하는 방법을 배웁니다.
- [PDF를 Claude에 업로드](https://github.com/anthropics/anthropic-cookbook/blob/main/misc/pdf_upload_summarization.ipynb): PDF를 파싱하여 텍스트로 Claude에 전달합니다.
- [자동화된 평가](https://github.com/anthropics/anthropic-cookbook/blob/main/misc/building_evals.ipynb): Claude를 사용하여 프롬프트 평가 프로세스를 자동화합니다.
- [JSON 모드 활성화](https://github.com/anthropics/anthropic-cookbook/blob/main/misc/how_to_enable_json_mode.ipynb): Claude에서 일관된 JSON 출력을 보장합니다.
- [모더레이션 필터 생성](https://github.com/anthropics/anthropic-cookbook/blob/main/misc/building_moderation_filter.ipynb): Claude를 사용하여 애플리케이션용 콘텐츠 모더레이션 필터를 만듭니다.
- [프롬프트 캐싱](https://github.com/anthropics/anthropic-cookbook/blob/main/misc/prompt_caching.ipynb): Claude에서 효율적인 프롬프트 캐싱 기법을 배웁니다.

## 추가 리소스

- [AWS의 Anthropic](https://github.com/aws-samples/anthropic-on-aws): AWS 인프라에서 Claude를 사용하는 예제와 솔루션을 탐색합니다.
- [AWS 샘플](https://github.com/aws-samples/): Claude와 함께 사용할 수 있도록 조정 가능한 AWS 코드 샘플 모음입니다. 일부 샘플은 Claude와 최적으로 작동하도록 수정이 필요할 수 있습니다.

---

## 한국어 번역 가이드

이 저장소에는 한국어로 번역된 가이드가 포함되어 있습니다:

| 가이드 | 설명 | 경로 |
|--------|------|------|
| 분류 가이드 | 보험 고객 지원 티켓 분류기 (RAG + CoT) | [guide_ko.ipynb](./capabilities/classification/guide_ko.ipynb) |

### 번역된 가이드에서 다루는 내용
- **프롬프트 엔지니어링**: XML 형식, 프리필링, temperature 설정
- **검색 증강 생성 (RAG)**: 유사한 예시를 검색하여 few-shot 학습 구현
- **Chain-of-Thought**: 명시적 추론으로 분류 정확도 향상 (~97%)

### 정확도 개선 결과

| 접근 방식 | 정확도 |
|----------|--------|
| 랜덤 기준선 | ~10% |
| 간단한 분류기 | ~70% |
| RAG 분류기 | ~94% |
| RAG + Chain-of-Thought | **~97%** |
