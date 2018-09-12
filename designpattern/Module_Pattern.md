# 모듈 패턴
자바스크립트의 소스를 모듈 단위로 관리하거나 라이브러리 등을 만들 때 사용
> 일반적인 자바스크립트 프로젝트에서는 잘 안 쓰이지만 서버 개발을 하거나 라이브러리, 또는 API 등을 개발할 때 유용하게 사용

모듈 패턴은 파일 단위로 관리할 수 있도록 자바스크립트를 모듈화해주고, 단위 테스트를 모듈 단위로 실행할 수 있도록 하여 test 계획에도 도움이 된다. 또한, 글로벌 변수나 함수들을 최소화함으로써, 다른 자바스크립트 라이브러리나 소스를 가져다 쓸 때 충돌이 일어날 확률을 최소화 한다. </br>
또한, 모듈 단위로 소스를 개발하면 각 모듈 간의 의존성을 최소화하거나 의존성을 파악하기 쉽다. 따라서 장기적이고 규모가 큰 자바스크립트 프로젝트를 관리하기가 좋다.</br>
더 나아가 만약 자바스크립트 라이브러리나 API 등을 개발하여 다른 개발자들에게 제공할 때, 이를 활용하는 개발자들이 모듈 단위로 함수나 변수들의 활용을 예측할 수 있는 네임스페이스로도 활용할 수 있다.