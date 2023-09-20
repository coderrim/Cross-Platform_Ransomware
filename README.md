# Cross-Platform_Ransomware

 서비스형 랜섬웨어(RaaS)의 확산이 별다른 자금이나 기술을 필요로 하지 않고도 수익을 얻을 수 있게 하여금 랜섬웨어 범죄로의 진입장벽을 낮추고 랜섬웨어 유통량의 폭발적인 증가에 기여하였다면 Cross-Platform 랜섬웨어의 등장은 Windows 운영체제뿐만 아니라 Linux 역시 공격 대상이 됨을 시사하며 이것이 자율주행 차량을 향한 위협으로 이어질 수도 있지 않을까 하는 발상에서 시작한 것입니다. 
 차량에는 암호화할 정보가 없다고 생각할 수도 있지만 전기차와 자율주행 기능의 도입으로 차량 내 소프트웨어가 탑재된다면 컴퓨터의 가격의 몇배를 상회하는 차량을 억류하거나, 교통사고로 위장하여 누군가를 살해하거나 테러에 이용하는 등 인간의 생명을 위협할 수도 있기에 기술의 발전을 악용한 기상천외한 범죄에 경각심을 갖자는 의도로 칼럼을 집필하였습니다. 
 Cross-Platform 랜섬웨어를 작성할 수 있는 Rust 언어와 Go 언어에 초점을 두었는데 두 언어의 특징을 알아보고 대표적으로 IDA pro와 Redress 툴을 활용하여 Hive 랜섬웨어와 DeabBolt, Agenda 랜섬웨어의 샘플을 분석하였습니다. 
 또한 Go 언어로 직접 랜섬웨어 코드를 작성하여 Windows와 Linux 두 운영체제에 맞추어 크로스컴파일하여 모두 파일을 암호화하고 확장자를 변경하며 랜섬노트를 띄우는데 성공하였습니다.
 그리고 해당 랜섬웨어를 자율주행 시뮬레이션에 익스플로잇하는 실습을 진행하였습니다.
