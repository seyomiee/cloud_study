# Module Introduction and Learning Objectives


### Define cloud computing

```

- Describe the essential characteristics of cloud computing

- Briefly recount the history and evolution of cloud computing

- Describe the key considerations that organizations can use as a guide while creating their cloud strategy

- Describe the key cloud service providers and their services

- Create an account on a public cloud platform
```
​

### cloud concepts by NIST's

* NIST defines cloud computing as a model for enabling convenient, on-demand network access to a shared pool of configurable(설정,변경 가능한) computing resources that can be rapidly provisioned(충분히 제공된) and released with minimal management effort or service provider interaction.

##### Examples of computing resources include networks, servers, storage, applications, and services.

#### This cloud model is composed of five essential characteristics, three deployment models, and three service models.

​

클라우드 

5개의 필수적인 특징, 
3개의 배치 모델, 
3개의 서비스 모델

### the five essential characteristics of the cloud—which

include 

1. on-demand self-service, 
###### (이용자의 요구에 따라 네트워크를 통해 필요한 정보를 제공하는 방식)

> the 1st characteristic, means that you get access to cloud resources such as the processing power, storage, and network you need, using a simple interface, without requiring human interaction with each service provider.

​
각 서비스 제공자의 interaction 없이 클라우드 자원에 접근해 얻을 수 있다. 사용자가 서비스 관리자의 개입 없이 원하는 시점에 서비스를 바로 사용할 수 있어야 합니다.

​

1. broad network access, 

> The 2nd characteristic, Broad Network Access, means that cloud computing resources can be accessed via the network through standard mechanisms and platforms such as mobile phones, tablets, laptops, and workstations.

​

핸드폰, 타블렛, 노트북, 워크스테이션 등의 플랫폼이나 표준형 메카니즘을 통해 네트워크에 접근 할 수 있다.

클라우드 서비스 제공자는 네트워크 기반으로 서비스에 접속할 수 있게 해야 합니다. 그리고 다양한 클라이언트에 의해 접속 가능해야 합니다.

​

3. resource pooling, 

> The 3rd characteristic, Resource Pooling, is what gives cloud providers economies of scale (규모의경제) , which they pass on to their customers, making cloud cost-efficient. Using a multi-tenant model, computing resources are pooled to serve multiple consumers; cloud resources are dynamically assigned and reassigned, according to demand, without customers needing to concern themselves with the physical location of these resources.

​
물리적인 자원이나 가상화된 자원은 풀(Pool)로 관리되며, 사용자의 요청에 의해 사용자에게 할당되거나 다시 풀로 반환되어야 합니다. 자원의 물리적인 위치, 크기 등에 대해서는 모르고 자원을 추상화시켜 제공합니다.

​

4. rapid elasticity,

> Rapid Elasticity, the 4th characteristic, implies that you can access more resources when you need them, and scale back when you don’t—because resources are elastically provisioned and released.

​

클라우드 컴퓨팅 서비스를 사용하는 사용자는 자원을 무한대로 확장할 수 있거나 필요한 만큼의 수준으로 마음대로 줄일 수 있어야 합니다. 이러한 작업은 수분 이내로 작업을 할 수 있어야 합니다.

​

5. measured service.

> And the 5th characteristic, Measured Service, means that you only pay for what you use or reserve as you go; if you’re not using resources, you’re not paying. Resource usage is monitored, measured, and reported transparently based on utilization.

​

자원의 사용량이 실시간으로 수집되고 모니터링 되어야 합니다. 사용량에 따른 과금을 할 수 있으며, 지원의 부족에 따른 자원 추가 요청 등의 작업을 할 수 있어야 합니다.

​

> It is a revolution in that it has changed the way the world consumes compute services by making them more cost-efficient while also making organizations more agile in responding to changes in their markets.

​

### There are three types of cloud deployment models—

## Public, Private, and Hybrid.

1. Public cloud is

 when you leverage cloud services over the open internet on hardware owned by the cloud provider, but its usage is shared by other companies.
 
 특정 기업이나 사용자를 위한 서비스가 아닌 인터넷에 접속 가능한 모든 사용자를 위한 클라우드 서비스 모델. 데이터나 기능, 서버 같은 자원은 각 서비스에서 사용자 별로 권한 관리가 되거나 격리 되어, 서비스 사용자 간에는 전혀 간섭이 없다는 장점이 있습니다.

2. Private cloud 
> means that the cloud infrastructure is provisioned for exclusive use by a single organization. It could run on-premises or it could be owned, managed, and operated by a service provider.
 
 제한된 네트워크 상에서 특정 기업이나 특정 사용자만을 대상으로 하는 클라우드 서비스의 자원과 데이터는 기업 내부에 저장됩니다. 또한 기업이 자원의 제어권을 갖고 있습니다. 따라서 보안성이 매우 뛰어나며, 개별 고객의 상황에 맞게 클라우드 기능을 커스터마이징 할 수 있다는 장점이 있습니다.
 
> And when you use a mix of both public and private clouds, working together seamlessly,

3. that is classified as the Hybrid model
   
##### ( 하이브리드 클라우드는 퍼블릭 클라우드와 프라이빗 클라우드를 병행해 사용하는 방식으로 여겨져 왔으나, 최근에는 개념이 모호해진 경향이 있어 가상 서버과 물리 서버를 결합한 형태를 말하기도 합니다. 이럴 경우 퍼블릭 클라우드의 유연성, 경제성, 신속성과 물리 서버의 보안성, 안정성 등을 함께 취할 수 있는 장점이 있다.) 

​

### These cloud computing models are aptly referred to 

1. as Infrastructure as a Service (Iaas),
   
> In an Infrastructure as a Service model,
you get access to infrastructure and physical, computing resources such as servers, networking, storage, and data center space - without the need to manage or operate them.

인프라로서의 서비스를 뜻하며 기존에 물리적인 형태로 사용해왔던 스토리지, 서버 등의 인프라를 가상화된 환경에서 쉽고 신속하게 할당받아 사용할 수 있는 서비스입니다. 아래에서 설명할 PaaS와 SaaS의 기반이 되는 가장 기본적인 클라우드 서비스의 형태입니다.

예) 아마존의 AWS 서비스 중 EC2, S3, 가비아의 g클라우드

​

사용자가 관리할 수 있는 범위가 가장 넓은 클라우드 컴퓨팅 서비스입니다.

인프라 수준의 클라우드 컴퓨팅을 제공해 사용자가 서버 OS부터 미들웨어, 런타임, 그리고 데이터와 어플리케이션까지 직접 구성하고 관리할 수 있습니다.

클라우드 서비스 제공업체(CSP, Cloud Service Provider)는 데이터센터를 구축해 다수의 물리 서버를 가상화해 제공하며, 네트워크, 스토리지, 전력 등 서버 운영에 필요한 모든 것을 CSP가 책임지고 관리합니다.

사용자에게 인프라 수준의 클라우드 컴퓨팅을 제공한다는 점은 기존 서버 호스팅과 유사하나, 서버 호스팅의 경우 자원 확장 및 축소에 긴 시간이 필요하고, 확장한 서버가 활용되지 않아 유휴자원이 발생할 가능성이 있습니다.

반면 IaaS의 경우 가상화 기술 덕분에 수초에서 수분 이내에 리소스를 확장할 수 있고, 사용하지 않을 경우 늘렸던 컴퓨팅 자원을 언제든지 반납할 수 있어 유연하고 탄력적인 인프라 운영이 가능합니다.

비용 또한 사용한 만큼만 지불하는 종량제 형식을 택하고 있어, 자체적으로 인프라를 운영하는 것과 비교했을 때 합리적인 인프라 운영이 가능합니다.

IaaS는 사용자가 많은 부분을 컨트롤하고 관리할 수 있어 다양한 목적에 따라 인프라를 자유롭게 활용할 수 있다는 장점이 있지만, 인프라 운영에 대한 경험과 지식, 담당 인력 등 여건이 준비되지 않은 경우 활용에 어려움을 겪을 수 있습니다.

IaaS는 뒤이어 소개할 PaaS(Platform as a Service)와 SaaS(Software as a Serivce)의 밑바탕이 되는 기술이기도 합니다.

IaaS 서비스에는 Amazon Web Service(AWS)의 EC2와 Google의 Compute Engine(GCE), 그리고 가비아의 g클라우드 등이 있습니다.

​

​

2. Platform as a Service (PaaS), 

> In a Platform as a Service model, you get access to the platform, that is the hardware and software tools, usually those needed to develop and deploy applications to users over the Internet.

​

IaaS 서비스로 제공되는 인프라 위에 사용자가 원하는 서비스를 개발할 수 있는 환경(Platform)을 제공하는 서비스입니다. 여기서 말하는 환경이란 운영체제, 미들웨어, 애플리케이션 실행환경 등이 포함됩니다.

기존의 물리 서버 환경에서는 새로운 서비스를 개발하기 위해서 서버를 구매하고 IDC 센터에 입주한 후 서버에 OS, 미들웨어 등을 설치해야 하는 등 개발에 들어가기까지 필요한 선행작업으로 소비되는 시간과 비용이 많았습니다. 또한, 이런 물리적인 환경은 지속적인 관리가 필요합니다.

하지만 PaaS를 이용한다면 서비스 외적인 부분에 시간과 비용을 들이지 않고 서비스 개발에 집중할 수 있으므로 기존 물리환경에서 서비스를 개발할 때보다 비교적 적은 비용으로 신속하고 간편하게 서비스를 개발하고 운영할 수 있습니다.

예) 구글의 앱엔진

​

3. and Software as a Service (SaaS).

> Software as a Service is a software licensing and delivery model in which software and applications are centrally hosted and licensed on a subscription basis, and sometimes also referred to as "on-demand software."

​

클라우드 기반의 응용프로그램을 서비스 형태로 제공하는 것을 말하며, 일반 사용자들이 가장 많이 접하게 되는 형태입니다.

예) 세일즈포스닷컴의 CRM, 웹기반 개인용 스토리지 서비스(드롭박스, N드라이브 등), 구글 드라이브 (문서, 스프레드시트, 프레젠테이션)



##### 한글부분 출처: https://library.gabia.com/