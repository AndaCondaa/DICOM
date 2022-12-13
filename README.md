<h1>PS3.1</h1>

<h2>소개 및 개요(Introduction and Overview)</h2>



> <h3>Notice and Disclaimer</h3>
>
> - NEMA : The National Electrical Manufacturers Association
> - NEMA에서 본 내용을 준수하도록 감시하거나 강제하지 않습니다.





> <h3>Foreword</h3>
>
> - DICOM 표준 위원회는 의료 영상 정보 및 관련 데이터의 표준화에 관심을 갖는 조직입니다.
> - DICOM 표준 위원회의 사무국은 NEMA와 그 곳의 의료 영상 기술 동맹 부서입니다.
> - DICOM 표준은 위원회의 주요 제품입니다.
> - 본 표준은 NEMA 표준 PS3로 발행되며, NEMA 간행물(PS3.1, PS3.2 등)의 번호로 식별됩니다.





> <h3>1. 범위 및 분야</h3>
>
> - PS3.1은 전체 DICOM(Digital Imaging and Communications in Medicine) 표준에 대한 개요를 제공합니다.
>
> - PS3.1에서는 이 표준의 각 부분의 내용에 대한 간략한 설명이 포함됩니다.
>
>   
>
>   
>
>   <h4>1.1 DICOM의 범위 </h4>
>
>   - DICOM은 의료 영상 정보 및 관련 데이터의 통신 및 관리를 위한 표준입니다.
>   - DICOM 표준은 다음을 지정하여 의료 영상 장비의 상호 운용성을 향상시킵니다.
>     - 네트워크 통신의 경우, 표준 준수를 주장하는 장치가 따라야 하는 프로토콜 집합
>     - 미디어 통신에서 일련의 미디어 저장 서비스와 저장된 이미지 및 관련 정보에 대한 액세스를 용이하게 하는 파일 형식 및 의료 디렉터리 구조
>     - 표준을 준수하는 구현을 진행할 때, 함께 제공되어야 하는 정보
>   - DICOM 표준은 다음을 지정하지 않습니다.
>     - 표준 기능의 구현 세부사항
>     - 구현된 시스템에서 기대할 수 있는 전체 기능 세트
>     - 적합성 평가를 위한 시험/검증 절차
>
>   
>
>   
>
>   <h4>1.2 적용 분야</h4>
>
>    DICOM 표준은 의료 정보학 분야와 관련하여 의료 영상 장비와 다른 시스템 간의 디지털 정보 교환을 다룹니다. 그러한 장비들은 다른 의료기기 및 정보 시스템과 상호 운용될 가능성이 높기 때문에, 이 표준의 적용범위는 의료정보학의 다른 영역과 중복될 필요가 있습니다. 하지만 DICOM 표준에서는 해당 범위에 대해 직접 다루지 않습니다.
>
>   
>
>    이 표준은 진단 의료 영상과 영상 기반 치료에 중점을 두고 개발되었습니다. 그러나 임상, 연구, 수의학 및 기타 의료 환경에서 교환되는 광범위한 영상 및 비영상 관련 정보에도 적용할 수 있습니다.
>
>   
>
>   
>
>   <h4>1.3 이력</h4>
>
>    1970년대에 CT가 도입되고, 디지털 진단 영상 양식의 도입으로 임상 애플리케이션에서 컴퓨터 사용이 증가하면서 ACR과 NEMA는 표준에 대한 필요성에 대해 인식했습니다.
>
>   
>
>    1983년 ACR과 NEMA는 다음을 위한 표준을 개발하기 위해 공동 위원회를 구성했습니다.
>
>   - 장치 제조업체에 관계없이 원활한 디지털 이미지 정보의 통신 촉진
>   - 다른 병원 정보 시스템과도 상호 작용할 수 있는 사진 보관 및 통신 시스템(PACS)의 개발 및 확장 촉진
>   - 위치적으로 분산된 다양한 장치에서 조회할 수 있는 진단 정보 데이터베이스
>
>   
>
>    1985년에 ACR-NEMA 표준 공개번호 300-1985는 버전 1.0으로 지정되었습니다. 이 표준 간행물들은 하드웨어 인터페이스, 최소 소프트웨어 명령어 집합 및 일관된 데이터 형식 집합을 지정하였습니다.
>
>   
>
>    1988년에 ACR-NEMA 표준 공개번호 300-1988은 버전 2.0으로 지정되었습니다. 버전 1.0, 공개된 개정판, 추가 개정판이 포함되며, 디스플레이 장치에 대한 명령을 지원하고, 이미지를 식별하기 위한 새로운 계층 구조를 도입하고, 이미지를 설명할 때 데이터 요소를 추가하기 위한 새로운 자료를 포함합니다.
>
>   
>
>    1933년 ACR-NEMA 표준 300이 실질적으로 개선되어 이 표준으로 대체되었습니다. 이전 버전에 대한 몇 가지 주요 개선 사항입니다.
>
>   - 네트워크 환경에 적용할 수 있습니다. DICOM은 업계 표준 네트워킹 프로토콜 TCP/IP를 사용하여 네트워크 환경에서 작동할 수 있도록 지원합니다.
>   - ACR-NEMA 표준은 파일 형식이나 물리적 미디어 또는 논리적 파일 시스템의 선택을 지정하지 않았습니다. DICOM은 CD-R, USB와 같은 업계 표준 미디어와 공통 파일 시스템을 사용한 오프라인 미디어 환경에서의 작동을 지원합니다.
>   - 이것은 서비스 지향 프로토콜로, 명령어와 관련 데이터의 의미와 표준 준수를 주장하는 장치가 교환되는 명령어와 데이터에 어떻게 반응하는지를 명시한다. 지정된 서비스에는 이미징 부서의 워크플로우 관리 지원이 포함됩니다. ACR-NEMA 표준은 암묵적인 서비스 요구사항만을 가진 데이터 전송으로 제한되었습니다.
>   - 준수해야하는 수준을 지정합니다. DICOM은 특정 옵션을 선택하기 위해 구현자가  준수에 대한 보고서를 구성하는 방법을 명시적으로 설명합니다.
>
>   
>
>    1995년, ACR-NEMA 공동 위원회는 모든 의료 영상 전문 분야에 걸쳐 이해 관계자들의 광범위한 협력인 DICOM 표준 위원회로 개편되었습니다.
>
>   
>
>   
>
>   <h4>1.4 Principles</h4>
>
>   <h5>1.4.1 글로벌 적용 가능성 및 현지화</h5>
>
>    DICOM은 모든 로케일에서 사용할 수 있는 전 세계 표준입니다.  다양한 종류의 데이터를 처리하는 메커니즘을 제공합니다.  여러 분야의 의학적 이미징에 사용되는 다양한 워크플로우, 프로세스 및 정책을 지원합니다.
>
>     국가 또는 지역 보건 및 워크플로우 정책의 요구사항을 충족하기 위한 현지화는 표준을 벗어나지 않고 수행할 수 있습니다. 
>
>     현지화 및 프로파일링은 DICOM 표준의 범위 밖에 있는 여러 메커니즘에서 지정할 수 있습니다. 이러한 메커니즘 중 하나는 IHE(Integrating the Healthcare Enterprise) 조직의 통합 프로필입니다.  프로파일링은 모순되지 않는 개념을 고수하는 것이 중요합니다. 프로파일은 요구 사항을 추가할 수 있지만 DICOM 요구 사항과 모순되지 않아야 합니다. 모순되면, DICOM과 프로파일을 모두 준수할 수 없습니다.
>
>   
>
>   
>
>   <h5>1.4.2 지속적인 유지보수</h5>
>
>    DICOM 표준은 DICOM 표준 위원회의 절차에 따라 유지 관리됩니다. 개선을 위한 제안은 이 표준의 모든 사용자로부터 환영을 받고, 사무국에 제출될 수 있습니다.
>
>    기준서를 업데이트할 때 요구사항은 이전판과의 효과적인 호환성을 유지하는 것입니다.
>
>    
>
>   
>
>    <h5>1.4.3 정보 객체 및 고유 객체 식별</h5>
>
>    대부분의 DICOM 서비스에는 이미지와 같은 영구 Information Object의 교환이 포합됩니다. 이러한 정보 객체의 인스턴스는 많은 시스템과 많은 조직 컨텍스트에서 시간이 지남에 따라 교환될 수 있습니다. 특정 조직 내에서 처리를 용이하게 하기 위해 인스턴스의 속성을 약간 변경할 수 있지만(예: 로컬 컨텍스트에서 사용되는 값으로 환자 ID를 강제함으로써) 인스턴스의 의미론적 내용은 변경되지 않는다.
>
>    각 인스턴스는 전체적으로 고유한 개체 식별자로 식별되며, 이 식별자는 모든 교환에서 인스턴스에 지속됩니다. 인스턴스의 의미론적 내용에 대한 변경사항은 새 인스턴스를 생성하도록 정의되며, 이 인스턴스는 전역적으로 고유한 새 개체 식별자가 할당됩니다.
>
>   
>
>   
>
>    <h5>1.4.4 적합성</h5>
>
>    DICOM 표준 준수는 Information Object의 유형(CT or MR 이미지)에서 작동하는 서비스(네트워크, 미디어 또는 웹을 사용하는 스토리지 등)를 나타내는 SOP(Service-Object Pair) 클래스로 명시됩니다. 
>
>     DICOM 표준의 SOP 클래스 사양은 모든 버전의 표준에 대해 이전 버전과 이전 버전이 호환되도록 설계된 방식으로만 변경됩니다. 따라서 적합성 요구사항 및 적합성 클레임은 SOP 등급의 식별자를 참조하며, 표준에디션을 참조하지 않습니다.
>
>    <u>각 구현은 일관된 형식 구조에 따라 상호운용성을 위한 제품 비교를 용이하게 하는 적합성 설명서를 제공해야 합니다.</u>
>
>   
>
>   
>
>   <h5>1.4.5 정보 모델의 일관성</h5>
>
>    DICOM 표준에 정의된 많은 Information Object는 환자, 스터디, 영상 시리즈, 장비, 기준 프레임 및 특정 인스턴스 데이터 유형을 나타내는 정보 엔티티와 함께 일반적인 복합 정보 모델을 따릅니다. <u>이 정보 모델은 의료 영상의 실제 개념과 활동을 단순화한 것입니다.</u> 
>
>    <u>DICOM에 정의된 새 Information Object는 일반적으로 이 기존의 공통 정보 모델을 준수하므로 새 개체를 지원하기 위해 최소한의 변경 사항으로 구현을 재사용할 수 있습니다. -> 공통 정보 모델 준수의 필요성</u>
>
>   





><h3>2. 표준 참조</h3>
>
>--생략
>
>





><h3>3. 정의</h3>
>
>- Attribute - Information Object의 속성입니다. 속성에는 인코딩 체계와 독립적인 이름과 값이 있습니다.
>
>- Command - 네트워크를 통한 정보에 대한 작업 요청.
>
>- Command Element - An encoding of a parameter of a command that conveys this parameter's value
>
>- Command Stream - DICOM 인코딩 체계를 사용하여, DICOM Command Elements의 집합을 인코딩한 결과
>
>- Conformance Statement - DICOM 표준의 특정 구현을 설명하는 공식 statement.  해당 구현에서 지원하는 서비스 클래스들, Information Object, 통신 프로토콜, 보안 개요 및 미디어 저장 어플리케이션 개요를 설명합니다.
>
>- Data Dictionary - 각 데이터 요소에 대한 고유 태그, 이름, 값 특성 및 의미를 지정하는 DICOM 데이터 요소의 저장. 
>
>- Data Element - Data Dictionary안에 단일 항목으로 정의된 정보 단위.
>
>- Data Set - 구조화된 속성 집합으로 구성된 교환된 정보. Data Set의 각 속성 값은 Data Element로 표시.
>
>- Data Stream - DICOM 인코딩 체계(Data Dictionary에 지정된 Data Element의 번호 및 표현)를 사용하여 Data Set을 인코딩한 결과.
>
>- Information Object - 하나 이상의 DICOM Commands에 의해 동작되는 실제 정보 엔티티(예: CT Image, Structured Report 등)의 an abstraction.     (참고: 이 용어는 주로 PS3.1에서 사용되며, PS3.3에서 몇 번 참조됩니다. PS3.3에 도입된 공식 용어에 상응하는 비공식 용어입니다. DICOM 표준의 다른 모든 부분에서는 이 용어를 Information Object Definition이라고 합니다.)
>
>- Information Object Class - Information Object에 대한 정규 표현으로, Information Object의 목적과 Information Object가 소유한 속성에 대한 설명을 포함. 이 속성에 대한 값은 포함되지 않습니다.     (참고: 이 용어는 PS3.1에서만 사용됩니다. PS3.4에 도입된 공식 용어에 해당하는 비공식 용어입니다. 이 용어는 Service-Object Pair Class 또는 더 일반적으로 SOP Class로 알려져 있습니다. )
>
>- Information Object Instance - 실제 엔터티가 속한 Information Object Class의 속성 값을 포함하는 실제 엔터티의 표현.    (참고: 위의 항목과 비슷하게, 해당 항목은 PS3.4에 도입된 공식용어에 해당하는 비공식 용어이며, SOP Instance로 더 일반적으로 알려져 있습니다.)
>
>- Message - 함께 동작하는 두 DICOM 어플리케이션 간에 교환된 Message Exchange Protocol의 데이터 단위.  Message는 Command Stream과 optional Data Stream으로 구성.
>
>- Part - 관련 주제 자료를 다루는 DICOM 표준의 하위 절.
>
>- Service Class - 특정 클래스의 Information Object에 작용하는 특정 DICOM Commands를 사용하여, DICOM 어플리케이션과 협력하여 지원되는 서비스에 대한 구조체.
>
>- Service-Object Pair Class (SOP Class) - Information Object, DIMSE(DICOM Message Service Element) Service Group, a Media Storage Service, Web Service의 쌍.
>
>- Essence -  소스의 비디오, 오디오 또는 데이터 타입.
>
>- Flow - 소스로부터의 A sequence of Grains;  소스로부터 리턴되는 내용의 구체적인 표현입니다.
>
>- Grain - Essence 요소 또는 특정 시간과 관련된 기타 데이터(프레임, 연속 오디오 샘플 그룹 또는 캡션)를 나타냅니다.
>
>- Rendition - 동시 표현(simultaneous presentation)을 위한 time-synchronized Flows의 모음,  a complete experience of a Source Group을 제공합니다.
>
>- Source - Flow 또는 Flow 집합의 기본 근원을 나타내는 추상 개념.
>
>  





> <h3>4. 기호 및 약어</h3>
>
> - <b>ACSE</b> - Association Control Service Element
> - <b>API</b> - Application Programming Interface
> - <b>CT</b> - Computed Tomography
> - <b>DICOM</b> - Digital Imaging and Communications in Medicine
> - <b>DICOM-RTV</b> - DICOM Real-Time Video
> - <b>DIMSE</b> - DICOM Message Service Element
> - <b>HIS</b> - Hospital Information System
> - <b>HTTP</b> - Hyper-Text Transfer Protocol
> - <b>HTTPS</b> - Hyper-Text Transfer Protocol Secure
> - <b>JIRA</b> - Japan Medical Imaging and Radiological Systems Industries Association
> - <b>OSI</b> - Open Systems Interconnection
> - <b>PACS</b> - Picture Archiving and Communication Systems
> - <b>PTP</b> - Precision Time Protocol
> - <b>REST</b> - Representational State Transfer
> - <b>RESTful</b> - A RESTful Web service is a Web service implemented using REST architecture and HTTP (see http://www.ics.uci.edu/ ~fielding/pubs/dissertation/fielding_dissertation.pdf)
> - <b>RIS</b> - Radiology Information System
> - <b>RTP</b> - Real-Time Transport Protocol
> - <b>SMPTE</b> - Society of Motion Picture and Television Engineers
> - <b>STOW-RS</b> - STore Over the Web by RESTful Services
> - <b>TCP/IP</b> - Transmission Control Protocol/Internet Protocol
> - <b>WADO-RS</b> - Web Access to DICOM Objects by RESTful Services
> - <b>WADO-URI</b> - Web Access to DICOM Objects by URI







> <h3>5. DICOM 통신 모델</h3>
>
>  DICOM 표준은 호환성을 주장하는 장치의 상호 운용성을 용이하게 합니다. 특히 다음과 같습니다.
>
> - 명령 및 관련 데이터의 의미를 설명합니다. 장치가 상호 작용하려면 장치 간에 이동해야 하는 정보뿐만 아니라 명령 및 관련 데이터에 장치가 어떻게 반응할 것으로 예상되는지에 대한 표준이 있어야 합니다.
> - 오프라인 통신에 필요한 파일 서비스, 파일 포맷, 정보 디렉터리의 의미를 다룹니다.
> - 명시적으로 표준 구현의 적합성 요구사항을 정의합니다. 특히, 적합성을 주장하는 다른 장치와의 상호 운용성이 기대될 수 있는 기능을 결정하기 위해 a conformance statement는 충분한 정보를 지정해야 합니다.
> - 

