# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 양기택
- 리뷰어 : 유지희


# PRT(Peer Review Template)
- [X]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
          
프로젝트 1은 완료 ![image](https://github.com/user-attachments/assets/9e94ee01-20a1-4cb8-90f7-1d631c1a33f7)

프로젝트 2는 시각화만 미완료, 나머지 굿 ![image](https://github.com/user-attachments/assets/ec95b1c5-742c-439c-a437-f7e594b7b57c)

    
- [X]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부

전체적으로 주석을 잘 달아주신게 인상깊었음  
추가로 프로젝트에서 요구하는 지시사항을 주석으로 남긴 것은 나중에 코드 리뷰 시 듣는사람에게 도움이 되었음  
pred += X[:, i] * W[i] 코드에 대한 주석은 코드 이해를 도와줌 ![image](https://github.com/user-attachments/assets/841eef01-df15-41fd-b433-ae8dfd11d93c)

        
- [ ]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부

추가 시도는 아니지만, 코드를 작성하며 생겼던 문제점을 기록해놓은 부분이 인상적임
![image](https://github.com/user-attachments/assets/099fcd62-7b12-4b80-91b7-6086136ff09e)


- [ ]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부

기록은 하지 않았으나 코드 리뷰 시 발생한 문제점에 대해 아쉬운 점을 나누고 수정하는 시간을 가짐  
다음부터는 회고 또한 주석으로 남겨주면 더 좋을 것 같음!
        
- [X]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부

전체적으로 코드가 간결하고, 선형회귀분석에 대해 완전히 이해하고 있다는 생각이 들었음  
더 나아가 데이터 칼럼을 빼는 코드에서 drop을 사용하여 코드를 간결하게 사용한것이 인상깊었음
![image](https://github.com/user-attachments/assets/549f9fc0-16a5-4156-9c9a-b40b4a281e5b)

# 회고(참고 링크 및 코드 개선)
```
오늘 정말 수고 많으셨습니다~! 시간이 많이 촉박하셨을텐데 꼼꼼한 각주와 코드가 인상적이였고, 많이 배우고 갑니다!  
지금 생각해보니 프로젝트 1에서 입력 데이터 개수에 맞는 가중치 W와 b를 준비할때, W의 랜덤값이 너무 큰건 아닌가? 라는 생각이 들었습니다. 좀 더 작은 값으로 설정하거나, 정규분포에서 샘플링 한 값으로 초기화해보는건 어떠실까요?  
고생하셨습니다!  
```
