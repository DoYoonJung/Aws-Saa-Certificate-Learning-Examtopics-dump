# Aws-Saa-Certificate-Learning-Examtopics-dump
<br>
<br>
<br>

## Amazon Machine Image(AMI)란?

> Amazon Machine Image(AMI)는 인스턴스를 시작하는 데 필요한 정보를 제공하는 AWS에서 지원되고 유지 관리되는 이미지입니다. 
>
> 인스턴스를 시작할 때 AMI를 지정해야 합니다. 동일한 구성의 인스턴스가 여러 개 필요할 때는 한 AMI에서 여러 인스턴스를 시작할 수 있습니다. 서로 다른 구성의 인스턴스가 필요할 때는 다양한 AMI를 사용하여 인스턴스를 시작할 수 있습니다.
>
> AMI는 다음을 포함합니다.
>
> 1개 이상의 Amazon Elastic Block Store(Amazon EBS) 스냅샷 또는, 인스턴스 스토어 기반 AMI의 경우, 인스턴스의 루트 볼륨에 대한 템플릿(예: 운영 체제, 애플리케이션 서버, 애플리케이션)
>
> AMI를 사용하여 인스턴스를 시작할 수 있는 AWS 계정을 제어하는 시작 권한
>
> 시작될 때 인스턴스에 연결할 볼륨을 지정하는 블록 디바이스 매핑
<br>

## AWS Lambda란 무엇인가요?

> AWS Lambda은 서버를 프로비저닝하거나 관리하지 않고도 코드를 실행할 수 있게 해주는 컴퓨팅 서비스입니다. 
>
> 서버와 운영 체제 유지 관리, 용량 프로비저닝 및 자동 조정, 코드 및 보안 패치 배포, 로깅 등 모든 컴퓨팅 리소스 관리를 수행
>
> Lambda를 사용하면 거의 모든 유형의 애플리케이션 또는 백엔드 서비스에 대한 코드를 실행
<br>

## 메시지 브로커란?

> 메시지 브로커(message broker), 인터페이스 엔진(interface engine)은 송신자의 메시지 프로토콜 형식으로부터의 메시지를 수신자의 메시지 프로토콜 형식으로 변환하는 중간 컴퓨터 프로그램 모듈이다.
<br>

## EFS(Elastic File System)

> Elastic File System은 AWS 클라우드와 온프레미스에서 사용할 수 있는 클라우드 스토리지 서비스입니다. 파일을 추가하고 제거할 때 자동으로 용량을 확장/축소하여 별도 관리 및 프로비저닝이 필요하지 않습니다.
>
> 탄력적으로 스토리지를 활용할 수 있는 EFS(Elastic File System)의 특징을 더 자세히 살펴보겟습니다.
> 
> 1. EC2에서 확장 사용 가능한 파일 스토리지
> 
> 2. 파일을 추가/제거할 때마다 스토리지 용량이 탄력적으로 자동 확장 및 축소
> 
> 3. Network File System 버전 4.0 및 4.1(NFSv4) 프로토콜 지원
> 
> 4. 한 리전 내 여러 가용 영역에 데이터 및 메타데이터 저장(페타바이트 규모까지 확장 가능)
> 
> 5. 강력한 데이터 일관성 및 파일 잠금 지원
> 
> 6. 파일 시스템 확장에 따라 처리량 및 IOPS가 늘어남
> 
> 7. VPC를 Direct Connect와 연결하면 EFS를 On-Premises 환경과 연결
<br>

## EBS(Elastic Block Store)란 무엇인가?

> AMAZON EBS는 AWS 클라우드의 EC2 인스턴스에 사용할 영구 블록 스토리지 볼륨을 제공, 각 EBS 볼륨은 가용 영역 내에 자동으로 복제되어 구성요소 장애로부터 보호해주고 고가용성 및 내구성을 제공한다.
> 
> AMAZON EBS 볼륨은 워크로드 실행에 필요한 지연시간이 짧고 일관된 성능을 제공합니다.
> 
> AMAZON EBS를 사용하면 단 몇 분 내에 사용량을 많게 또는 적게 확장할 수 있으며, 프로비저닝한 부분에 대해서만 저렴한 비용을 지불합니다.
> 
>흔히 EC2는 메모리, 그래픽카드 등 하드디스크를 제외한 컴퓨터의 모든 부분이라고 생각하면 된다.
EBS는 하드디스크라고 생각하면 된다.
<br>
