# AzureOpenAIWorkshop

## Healthcare Innovation Forum

![Untitled](image.png)

GPT(Generative Pre-trained Transformer)는 OpenAI에서 개발한 LLM(Large Language Model)입니다. 트랜스포머 아키텍처 기반의 딥러닝 모델입니다. ChatGPT의 **Function Calling** 기능을 활용하면, 아이언맨의 자비스와 같은 인공지능 비서를 만들 수 있습니다. 약품의 업체명, 제품명 등을 통해 서비스에 질의하면 복약 안내문을 응답하는 챗봇 서비스를 만듭니다.

1. 사용자의 음성은 Microsoft Azure가 제공하는 STT(Speech to Text) 서비스를 이용하여 텍스트로 변환합니다.
2. 텍스트는 ChatGPT가 제공하는 Function Calling 기능을 활용하여 이미 작성되어진 API 또는 코드를 선택적으로 수행합니다.
3. 수행 결과는 다시 Microsoft Azure가 제공하는 TTS(Text to Speech)를 이용하여 대답할 수 있습니다.
