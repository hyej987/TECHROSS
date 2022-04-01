 # DATA_BASIC_STAT
  
  - 데이터 정제에서 기초통계에 대한 모든 작업(BOXPLOT, SCATTERPLOT,...)

- [ ] ECU_CONTROL_TREE : ECU 테이블 안에있는 CONTROL이 호선 별로 어떤 기준으로 판별되는지를 알기위해 의사결정나무를 사용한 것. <BR>
                         FEATURE 데이터 셋 : ECU의 CONTROL 변수를 제외한 모든 변수(ID, INDEX 제외)<BR>
                         TARGET DATA SET : ECU의 CONTROL 변수
 
- [ ] ECU_PCA : ECU 테이블의 열의 개수로 인한 차원의 저주를 방지하고자, PCA를 이용한 차원축소를 진행. 이 때, ID,INDEX는 차원축소 대상에서 제외시킴. 전체 테이블에 대한 차원축소.

- [ ] (DATA)_AND_(DATA_DEVICE)_SCATTER : DATA테이블과 DATA_DEVICE 테이블 간의 상관성을 파악하기 위해 HEATMAP을 사용하여 분석하였다. 이 때, DATA LEFT JOIN DATA_DEVICE 테이블과 DATA_DEVICE LEFT JOIN DATA 테이블 각각의 HEATMAP을 제작하였으므로, 큰 그림을 볼 때 참고만 하는 용도.
