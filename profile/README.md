# VideRAG

> YouTube 영상을 선택하고, 자막 기반으로 질문하고 답을 얻는 RAG 서비스입니다.

여러 YouTube 채널과 재생목록의 메타데이터를 먼저 수집하고,  
사용자가 선택한 영상만 분석합니다.

## What we do

- **Folder-first** — 주제별 폴더로 영상을 관리합니다.
- **Selective Analysis** — 필요한 영상만 자막·임베딩을 분석합니다.
- **RAG Q&A** — 영상 내용을 검색하고 직접 질문할 수 있습니다.
- **Evidence-based** — 답변과 함께 영상의 타임스탬프 근거를 제공합니다.

### [video-rag-mvp](https://github.com/VideRAG/video-rag-mvp)

`FastAPI` · `React` · `Vite` · `TanStack Query` · `shadcn/ui` · `Docker` · `PostgreSQL` · `pgvector`

---
