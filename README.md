## 1. 개인 과제 안내

- 구글 제출 링크
    - ipynb 파일로 제출
    - (매니저님 구글 서베이 삽입해주세요)
- Github 제출 방법
    - 준비
        - 사전에 github 아이디를 slack 스레드에 작성(매니저님 공지)
        - 이후 github 가입 이메일로 온 collaborator 승인
        - 깃허브 특강을 참조하여 sparta_ml 의 [깃허브](https://github.com/bellepoque7/sparta_ml) 를 로컬 리포지토리에 clone
        - {조}_{이름} 형식으로 ipynb 파일 제출
        - (주의) 남의 파일 디렉토리나 파일을 가공하지 마세요
        - (주의2) 로컬코드 저장소에서 작업하다가 동기화로 날라갈 수 있으니 백업 해놓으세요!
    
- 제출 마감: 2024. 2. 4. (일) 23:59 까지
- 과제 해설: 2024. 2. 5. (월) 10:00

## 2. 과제 목표 및 진행 안내


📌 **과제 목표**
1. 머신러닝 모델링을 하기 위한 데이터 수집, 정제, 시각화, 성능평가까지 전체 프로세스를 익혀봅니다.

📌 **진행 방식**

1. Jupyter notebook의 코드 행간의 의미를 파악하고 적절한 방법을 구현해 넣으세요.
2. Python IDE는 vscode, google-colab, anacondea  등 본인이 편한 환경으로 설정하여 진행하시되 ipynb 확장자의 jupyter notebook으로 전달해주세요.
3. 문제의 배경, 목표, 데이터, 요구사항을 숙지하여 진행해주세요.
4. 제출방법
    1. 구글 서베이 링크로 들어가서 ipynb 확장 파일업로드

# 3. 과제 설명

- 시나리오
    - 여러분은 S모 금융회사에 입사하였습니다. 올해 프로젝트로 회사의 주 수입원인 이자 매출 증대를 위해서 대출 권유 텔레마케팅을 진행할 예정입니다. 하지만 회사 고객이 1000만명이 넘는 대기업이기 때문에 모든 고객에게 텔레마케팅을 진행하는 것은 비용(돈, 시간)적인 방면에서 효율적이지 못합니다.
    - 데이터 분석그룹 소속인 여러분은 마케팅을 효율적으로 수행하기 위한 방안으로  “대출 할 것 같은” 고객을 사전에 선별하라는 지시를 받았습니다. 입사 후 첫 프로젝트이기 때문에 직접 회사 내 데이터로 예측모델링을 수행하기 전에 앞서 포르투칼 은행 데이터 기반으로 파일럿 프로젝트를 수행하여 고객 정보를 바탕으로 대출 실행 예측을 하려 합니다.
    - 운 좋게도 레퍼런스를 찾다가 이쁘게 구성된 jupyter notebook을 찾았지만 일부가 누락되어서 보완이 필요합니다.
- 데이터 설명
    - 해당 데이터는 포르투칼 은행이 진행한 전화마케팅 콜을 시행하고 대출 유무 여부를 기록한 데이터 입니다. 총 16개의 변수와 45,211의 관측치를 가지고 있습니다.
    - 부트캠프의 과제가 아니라 실제로 파일럿 프로젝트를 시작하려고 서치한 자료이기 때문에 변수 설명이나 맥락과 설명은 공개된 정보가 다입니다.
        - UCI 데이터 저장소: https://archive.ics.uci.edu/dataset/222/bank+marketing
        - Github: https://github.com/uci-ml-repo/ucimlrepo

## 2. 수준별 학습 권고

- 챌린지
    - (선택) 사전에 제공된 Jupyter notebook없이 예측모델링을 수행하기
    - **(필수)** Jupyter notebook 빈칸 채워 구글 서베이 & 깃허브 제출하기
    - (선택) 더 생각해볼 점을 고민해보기
- 스탠다드
    - **(필수)**  Jupyter notebook 빈칸 채워 구글 서베이 & 깃허브 제출하기
    - (선택) 더 생각해볼 점을 고민해보기
- 베이직
    - **(필수)** Jupyter notebook 빈칸 채워보기

## 3. 문제 내용

- 문제 출처
    - 깃허브: https://github.com/bellepoque7/sparta_ml
    - 파일: 

- 문제 파일
    - 문제는 skeleton code를 제공하며, 문제 코드블록은 다음과 같이 Markdown 셀 바로 밑 코드 셀입니다.
        

- 문제1: 라이브러리를 이용해 데이터 불러오기
- 문제2: Y 변수 인코딩 적용하기
- 문제3: 모델링 & 평가함수 생성하기
- 문제4: 전체 모델링 수행하기
- (선택, 서술형): 더 개선할 수 있는 점 생각해보기
    - ex1) 왜 balance 음수 값을 보정해야 했을까요?
    - ex2) 보정하고 왜 1을 더했을까요?
    - ex3) `get_category` 함수는 모든 범주형 변수에 적용했는데 더 나은 방법이 있을까요?
