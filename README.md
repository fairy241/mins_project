# mins_project

## 소개
이 프로젝트는 OpenAI Codex 모델을 활용하여 자연어로 작성된 요구사항을 분석하고, 이를 바탕으로 코드 스니펫을 자동 생성 및 리뷰해 주는 오픈소스 도구입니다. 개발자의 코딩 생산성을 높이고 접근성을 향상시키기 위한 목적으로 제작되었으며, OpenAI Codex 오픈소스 지원 프로그램(OpenAI Codex Open Source Support Program)의 일환으로 개발되었습니다.

## 주요 기능
- 사용자가 입력한 자연어 프롬프트를 기반으로 한 코드 자동 생성 및 번역
- 기존 코드의 문맥을 파악하여 버그 분석 및 수정안(리팩토링) 제안
- 터미널 환경에서 즉각적인 사용이 가능한 직관적인 명령줄 인터페이스(CLI) 제공

## 사용 방법

### 1. 다운로드 및 설치
```bash
# 저장소 클론 및 폴더 이동
git clone [https://github.com/](https://github.com/)[GitHub-사용자명]/mins_project.git
cd mins_project

# 필요한 패키지 설치
pip install -r requirements.txt

# OpenAI API 키 환경 변수 설정
export OPENAI_API_KEY="당신의-openai-api-키"

# 프로그램 실행 예시
python main.py "1부터 10까지 출력하는 파이썬 코드 작성해 줘"





# 라이선스
MIT License

Copyright (c) [2026] [minseong kang]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
