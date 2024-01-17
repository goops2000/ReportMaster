# 📝 ReportMaster

ReportMaster는 AI 기반의 보고서 작성 도구로, 사용자가 빠르고 효율적으로 보고서를 작성할 수 있도록 지원합니다.


ReportMaster의 개발은 학생들이 Chat GPT를 사용하여 과제를 제출하는 과정에서 영감을 받았습니다. 여러 번 수정하고 질문하는 번거로움을 줄이고자, 자동화를 통해 보다 효율적인 방식을 모색하게 되었습니다.


LangChain과 Chat GPT를 결합하여 사용자가 보고서 틀을 쉽게 생성하고, 사용자의 요구에 맞춘 보고서 초안과 정확한 프롬프트를 제공함으로써, 보고서 작성 과정을 간소화하고 향상시키도록 설계되었습니다. 



<br>

## 작동과정


1. 사용자는 Streamlit 기반의 웹 인터페이스를 통해 필요한 정보를 입력합니다.

   
2. 입력된 데이터는 LangChain 을 통해 처리되고, Chat GPT-3.5-turbo  모델이 이를 바탕으로 보고서를 작성합니다.

<br>

## 기능


- **📝 맞춤형 프롬프트 입력**: 사용자의 연령대, 주제, 분량, 강조할 내용 및 언어 선택을 통한 맞춤형 프롬프트 생성.
- **🔍 보고서 자동 생성**: **LangChain** 및 **OpenAI GPT-3.5-turbo**를 활용한 보고서 자동 작성.
- **💬 실시간 AI 상호작용**: 사용자 질문에 대한 실시간 응답을 제공하여 효율적인 보고서 작성을 지원합니다.

<br>
  
## 보고서 생성을 위한 과정


1. 사용자는 왼쪽 사이드 하단에 위치한 Open API Key를 입력합니다.<br>

2. 사용자는 필요한 정보(연령대, 주제 등)를 입력합니다.<br>

3. 입력된 정보는 AI 모델에 전달됩니다.<br>

4. AI 모델이 정보를 기반으로 보고서 초안을 생성합니다.<br>

5. 생성된 보고서 초안은 사용자에게 제공됩니다.<br>
