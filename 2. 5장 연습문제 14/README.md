### 문제
##### * 작은 도시에 위치한 소규모 신문사에서 각종 사진과 기사들을 관리하기 위해서 데이터베이스 시스템을 설치하려고 결정하였다. 데이터베이스에 어떤 정보를 저장할 것인가에 관한 요구사항이 아래와 같다.
######  1. 사진은 고유한 번호와 촬영한 날짜, 사진의 가로와 세로 크기를 갖는다.

###### 2. 신문사 소속 사진사가 찍은 사진과 외부에서 구입한 사진들을 구분하려고 한다. 신문사 소속 사진사가 찍은 사진에 대해서는 사진사의 이름을 나타내고, 외부에서 구입한 사진 에 대해서는 구입처와 사진의 가격을 나타내려고 한다.


###### 3. 기사 또는 사진에 등장하는 인물에 대한 정보를 별도로 저장하려 한다. 인물에 대해서 이름, 생년월일, 영역(정치,경제, 사회, 스포츠 등)을 저장한다.
###### 4. 사진마다 그 사진에 어떤 사람들이 등장하는가를 저장한다.
###### 5. 기사마다 기사의 제목, 기사 작성자의 이름(들), 기사가 등장한 신문의 발간호를 저장한 다. 또한 각 기사에 대해서 그 기사에 어떤 인물들이 등장했는지, 그 기사에 어떤 사진들 이 포함되었는가를 나타내려 한다.
###### 6. 이와 같은 요구사항들을 바탕으로 다음과 같은 작업들을 수행하라.
> * (1) 위의 요구사항들을 ER 다이어 그램으로 그려라. 기본 키 애트리뷰트뿐만 아니라 관계 타입들의 카디날리티 제약조건들도 ER 다이어그램에 나타내라.
> * (2) ER 다이어그램에 나타내지 못한 무결성 제약조건이 있으면 자연어로 서술하라.
> * (3) (1)에서 작성한 ER다이어그램을 관계 데이터베이스 스키마로 변환하라. 기본 키와 외래 키 애트리뷰트들을 모두 명시하라.