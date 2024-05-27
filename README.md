# News_RAG

## 개요
- 네이버 뉴스기사의 내용을 질의-응답할 수 있는 환경을 RAG를 통해 구축합니다.

## Tools
- OpenAI(GPT-4-Turbo, embedding model)
- Faiss
- LangChain, LangChain Hub


## 활용방안
- 구축된 환경을 통해 뉴스의 내용에서 원하는 내용만 검색하여 확인할 수 있습니다.

## RAG 고도화
- Multi Query Retriever 활용
  고급 프롬프트 기법인 MQR을 활용하여 query의 품질을 높여 RAG의 정확도를 높힙니다.


  <img width="1161" alt="image" src="https://github.com/seunghyeon98/News_RAG/assets/111716640/cc7ed3ec-3da1-4b0d-8ec2-f2dcf853b26f">
  (단일 쿼리 검색 결과와 멀티 쿼리 검색 결과 비교)
  


## Next 고도화 
- Ensemble Retriever 적용해보기
  
