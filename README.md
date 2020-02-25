# 2019-national-A5
2019년 전국대회 A과제 (try 5, 3시간 30분~ 4시간 컷)

해당 프로젝트는 기능대회를 준비하기 위해 작업한 것입니다. 
모든 문제는 마이스터넷(https://meister.hrdkorea.or.kr:1443/main/main.do)에서 확인하실 수 있습니다.
-----
부산국제영화제 사이트를 리디자인해 보았습니다. 소요시간은 3시간 30분 ~ 4시간정도 소모 되었으며 실제 대회에서는
4시간 내에 만들어야 하기 떄문에 최대한 빠르게 디자인할 수 있도록 요소들을 간소화 시켰습니다.

#### 반성해야 할 점
##### 작업 속도가 너무 느리다.
실제 기능대회에서는 A과제를 2~3시간 내에 끝내고 C과제의 프레임워크를 어느정도 구성해 두어야합니다. 
하지만, 퍼블리싱의 속도나 구현하기 어려운 몇가지의 디자인 때문인지 속도가 많이 느립니다.
따라서 좀 더 간결한 디자인이 요구될 것으로 보입니다.

##### W3C CSS 검사 실패
custom property를 사용한 속성 변수가 가장 영향이 컸습니다. 좀 더 편리하고 빠른 디자인을 위해 custom property를 사용하였으나,
W3C CSS 검사에서 모두 warning를 기록하여 앞으로는 색상 코드를 외우거나 자동완성을 통해 구현할 필요가 있어보입니다.
