# Anomaly-Detection

반갑습니다!
2022년도 2학기 광운대학교 정보융합학부 인공지능응용 과목에서 팀 프로젝트 하였던 "실제 은행 데이터를 통한 기계학습 이상탐지 성능 비교 및 평가" 를 깃허브에 올립니다.



-지금까지 올린 파일들-  

## Anomaly-Detection 폴더   
  
  > **data**  
  
      * bank 폴더  = raw 데이터셋(bank-full.csv 로 EDA 및 preprocessing 진행)  
  
      * bank-additional 폴더   
  
      * train_set.csv  = preprocessing 끝낸 train 데이터셋  
  
      * test_set.csv  = preprocessing 끝낸 test 데이터셋
  
      * preprocessing_modify.csv  = preprocessing 끝낸 전체 데이터셋(train 데이터셋 + test 데이터셋)  

  > **EDA**
  
      * BankMarketing_EDA.ipynb = bank-full.csv 로 EDA 진행, EDA 후 인사이트는 data - bank 폴더의 "데이터셋 설명과 eda 후 인사이트.txt"에 기입  

  > **preprocessing**
  
      * Preprocessing_detail.ipynb = 전처리 상세한 과정  
      
      * Preprocessing_arrange.ipynb = Preprocessing_detail.ipynb 에서 코드 정리  

  > **model** = 이상탐지 알고리즘 적용  

      * A1A_LOF_PW.ipynb = 밀도 기반 방법 LOF(Local Outlier Factor)

