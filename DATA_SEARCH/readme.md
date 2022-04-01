# DATA_SEARCH     

- 데이터 써칭 작업에 대한 모든 것
- 테이터를 하나하나 뜯어보면서 특징을 추출한 결과를 정리함

- [ ] ECU,ANU,TSU,PMU_RELATION_FORM : ECU, ANU, TSU, PMU 테이블 각각의 내부에 있는 변수간의 관계를 측정하기 위한 형식
- [ ] OCCUR_TIME_BETWEEN_START_TIME_END_TIME : EVENT테이블의 OCCUR_TIME이 OPTIME 테이블의 START_TIME과 END_TIME 사이에 존재하는지 파악
- [ ] OPTIME + DATA + DATADEVICE Ballast, Deballast : DATA_DEVICE를 기준으로 DATA, OPTIME을 순차적으로 LEFT_JOIN 시킨 테이블에서 BALLAST, DEBALLAST를 분류
- [ ] PMU_PSUM : PMU 테이블의 PSUM변수에 대한 파악
- [ ] PMU_SHIP_ID, SECTION, LINE_SPLIT : PMU 테이블에서 SHIP_ID, SECTION, LINE이 같은 관측치 끼리 군집화시켜 분리시킴(각각의 테이블을 변수에 할당)
