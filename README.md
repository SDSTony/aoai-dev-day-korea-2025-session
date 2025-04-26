# Azure OpenAI Dev Day Korea 2025 세션 발표 - RAG 구현을 간단하게 해주는 Azure OpenAI On Your Data 뜯어보기

- [AOAI Dev Day Korea 2025](https://www.aoai-devday.kr/session1-6)에서 진행한 발표 세션에서 사용된 자료입니다. 
- "01. Naive RAG with Azure AI.ipynb"를 실행한 후 "02. Advanced RAG with Azure AI.ipynb"를 실행하시면 됩니다. 
- Azure 스토리지 계정의 blob storage 컨테이너 액세스 수준을 익명 액세스가 가능하게 "컨테이너"로 설정해주셔야 합니다. 그렇게 해야 현재 코드가 정상적으로 작동됩니다. 현재 코드는 Identity 관련 보안을 고려하지 않고 작성된 코드이기 때문입니다. 
- blob storage 컨테이너에는 data폴더에 있는 pdf 파일들을 올려주시면 됩니다.