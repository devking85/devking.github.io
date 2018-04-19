---
layout: posts
title: Differences between Visual Studio Community Edition and Express Editions. 
---

# Visual Studio Express, Community 버전 차이.

## Express Edition.
일종의 상업프로그램의 경량 프리웨어 버전입니다. 주요 특징으로는...
- 경량 버전으로 지원하지 않는 기능이 있음. (C++ 의 MFC 처럼)
- 기업에서도 상업적으로 이용가능 (라이센스 제한이 없음)
- 배포 패키지를 생성할 수 없음.(설치 파일)
이름에서 유추해보면 visual studio 를 알리기 위해 IDE 를 쉽게 간소화 시켜 출시한 것으로 보입니다.
원래 목적이 현업 개발자가 아닌 사용자를 위한 학습용으로 출시했습니다.

## Community Edition.
이 역시 프리웨어지만, Express 와는 다르게 일반 판매용(professional)과 기능적 차이가 거의 없습니다.
[공식 홈페이지 비교 표](https://www.visualstudio.com/ko/vs/compare/)
- 개인개발자, 교육기관(조직내 교육기관도 포함), 학술연구, 비영리단체, OSI 인정받은 오픈소스 커뮤니티 등 에서는 무료로 사용이 가능합니다.
- 무료로 사용 가능한 대상은 상업 프로그램 개발에도 사용할 수 있음.
- 소규모 조직(250 유저 이하 / 연 매출 10억 이하) 에서는 최대 5인까지 사용가능.
- 위 조건에 해당되지 않으면 구매해야 함.

## Why have they been separating?
과거사는 자세히 알지 못하지만...
교육용/학습용을 위한 free-of-charge 경량화 버전 IDE 로 2005 버전이 처음 출시되었습니다.
근런데 출시는 했는데 무료 라이선스 내의 사용자라도 축소된 기능으로는 비쥬얼 스튜디오의 메이저 기능을 사용하지 못하는 한계가 있습니다. MFC를 배우고 싶어도 Express Edition 으로는 배울수가 없었죠.
그래서 아예 라이선스 방침을 무료사용자를 확실하게 정의하고, 기능축소가 없는 Community 버전을 배포하기로 한게 아닐까 싶습니다.
*express 2017 버전이 마지막으로 더이상 배포하지 않는다고 하네요*
