# tensorflow-variables-edit-script

***내용은 content.pdf 참조하세요***

Tensorflow 모델 저장이 2GB 제한 있음

구글 protocol buffer 자체 스펙 문제 

텐서 내부 OP 들이나 variable 은 lazy 한 모델 생성 구조로 가능

약간의 리버싱과 페이로드를 구성해서 이를 우회해보자

