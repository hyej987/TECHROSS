# DATA_JOIN

 - 데이터병합, 분할에 대한 모든 작업 

- [ ] EVENT_JOIN_OPTIME_EVENT : EVENT테이블과 OPTIME_EVENT테이블과의 결합.

- [ ] EVENT_JOIN_OPTIME : EVENT_JOIN_OPTIME테이블과 OPTIME테이블과의 결합. 결론적으로 EVENT테이블과 OPTIME테이블을 OPTIME_EVENT 테이블을 이용하여 결합한 결과와 같음.

- [ ] DATA_JOIN_OPTIME : DATA테이블과 OPTIME테이블과의 결합. 

- [ ] DATA_INDEX_BY_OPTIME : OPTIME별 DATA테이블의 DATA_INDEX의 분포를 나타내는 테이블. SHIP_ID, SECTION, OP_INDEX별로 DATA_INDEX가 어떻게 분포하는지를 확인할 수 있다. 

- [ ] EVENT_INDEX_BY_OPTIME : OPTIME별 DATA테이블의 EVENT_INDEX의 분포를 나타내는 테이블. SHIP_ID, SECTION, OP_INDEX별로 DATA_INDEX가 어떻게 분포하는지를 확인할 수 있다. 

- [ ] DATA_JOIN_DATA_DEVICE : DATA테이블을 기준으로 DATA_DEVICE 테이블을 LEFT JOIN 시킨 테이블. 이 때, DATA_DEVICE테이블의 D_INDEX를 제외하고 중복되는 값들은 모두 삭제 처리해야                               DATA테이블과 DATA_DEVICE테이블을 LEFT JOIN 시킬 수 있다. 

- [ ] DATA_DEVICE_JOIN_DATA : DATA_DEVICE 테이블을 기준으로 DATA 테이블을 LEFT JOIN 시킨 테이블. 이 때, DATA_DEVICE 테이블의 행의 갯수가 더 많으므로, DATA 테이블의 행이 LEFT                                 JOIN이 될 때, 중복되어서 들어간다.

- [ ] DATA_DEVICE_JOIN_DATA_JOIN_OPTIME : DATA_DEVICE 테이블을 기준으로 DATA 테이블을 LEFT JOIN 시킨 테이블인 DATA_DEVICE_JOIN_DATA 테이블에서, OPTIME 테이블을           
DATA_DEVICE_JOIN_DATA 테이블을 기준으로 LEFT JOIN 시킨 테이블.

![ERD 최종정리](https://user-images.githubusercontent.com/89781598/160510295-f3e4dba6-8d75-46ca-9afd-8444b0889021.png)
