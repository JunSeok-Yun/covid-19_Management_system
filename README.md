# covid-19_Management_system
covid-19 관리 시스템


php, mysql을 이용하여 covid-19 에 대한 종합관리 시스템 구현
종합 관리 시스템은 다음과 같이 3종류 6기관으로 구성함.

(a) 정부
- 종합적인 정보를 제공하여야 하며 국민들의 접종 여부, 백신 보유 상태, 확진자 통계 현황등을 제공하여 종합 관리를 할 수 있어야 한다. 
- 따라서 일반 국민들이 보는 사이트가 아니다 라는 가정.
- 또한 모든 DB를 정부에서 제공한다고 가정. 즉 제약사나, 병원도 모두 정부의 DB를 사용함.


(b) 제약사
- 모더나와 화이자 두 업체, 각각 백신 재고량, 백신 과거 및 미래 생산 계획, 현재 주문량 등을 제공한다.


(c) 병원
- 영남대병원, 경북대병원, 대구병원 세곳. covid-19 환자에 대한 입원일, 퇴원일, 사망일, 코로나 검사받은 사람들에 대한 검사일, 확진여부 등
- 따라서 최소 각 기관별 총 6개의 웹페이지를 제공하여야 한다. 
- 각 기관 사이트는 한 페이지로 구성되도 무관.
