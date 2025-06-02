# ■ 데이콘 대회 준비 
![image](https://github.com/user-attachments/assets/fa67248f-6ae2-4398-b23c-8b6c3b7b9212)

- 제목 : 기업 성공 확률 예측 해커톤: 미래의 성공기업을 발굴하라!
- 기간 :  2025.04.01 ~ 2025.05.30 09:59
- 사용 모델 : TabNetPretrainer
- 출처 관련 링크 : [https://dacon.io/competitions/official/236439/overview/description](https://dacon.io/competitions/official/236475/leaderboard)

- 데이터  : <br> 1) Dataset Info / train.csv [파일]
                   ID : 샘플별 고유 ID, 설립연도, 국가, 분야, 투자단계, 직원 수, 인수여부, 상장여부, 고객수(백만명), 총 투자금(억원)
                   연매출(억원), SNS 팔로워 수(백만명), 기업가치(백억원), 성공확률 <br>
                2) test.csv [파일]
                   ID : 샘플별 고유 ID, 설립연도, 국가, 분야, 투자단계, 직원 수, 인수여부, 상장여부, 고객수(백만명), 총 투자금(억원)
                   연매출(억원), SNS 팔로워 수(백만명), 기업가치(백억원)

 <br>
 <br>

- 제출 로그 :
  ![image](https://github.com/user-attachments/assets/341e0a6b-4407-4a6c-b757-604846e5021b)

<br>

- 결과 :<br>
  ![image](https://github.com/user-attachments/assets/8f72eec3-3c5c-4ad4-9c50-f61e01192afc)


  <br>

-  데이터에 대한 이해도가 결과에 있어 큰 영향을 준다는 것을 깨달았고, 현실적 기준을 담은 파생 변수들이 실제 허위 매물을
   판단함에 있어 중요한 부분인 점을 다시 한번 알게된 기회였습니다. XGBoost라는 모델도 처음엔 단순히 성능이 좋다는 이유로 선택했지만,
   결과적으로 해석 가능성과 실전 활용성 측면에서 용이했고, 혼합형 데이터 처리에 효과적인 것을 확인했습니다.
   이후, 더 많은 대회에 참가하고 싶고 문제점에 대해 항상 본질적인 내용과 데이터의 특성을 정확하게 파악하고 논리적인 해결책을 설계하는 과정을
   더욱 더 경험하여 성장해 나가고 싶습니다. 
  
