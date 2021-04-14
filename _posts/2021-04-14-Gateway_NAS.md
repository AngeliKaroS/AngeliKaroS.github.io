---
title:      "NAS 정리"
date:       2021-04-14
author:     김 성은(plumno1@naver.com)
tags:       [NAS, Gateway]
---

## NAS 

Network Attached Storage  
Unified NAS, Gateway NAS, Scaleout NAS로 나뉨  

#### Unified NAS

통합 NAS라고도 함  
블록 레벨 데이터 액세스와 파일 데이터 저장을 통합하여 서비스 제공  
파일 액세스를 위한 CIFS와 NFS 블록 레벨 액세스를 위한 iSCSI와 FC 지원  
  
즉 NAS와 SAN을 통합한 것  
  
한 시스템에 1개 이상의 NAS 헤드와 스토리지를 가짐  
NAS 헤드는 스토리지 컨트롤러(SC)에 연결됨  
SC는 스토리지에 대한 액세스를 제공하며 iSCSI와 FC액세스도 지원  
  
![Unified](/assets/Unified.png)
  
&nbsp;

#### Gateway NAS

1개 이상의 NAS 헤드로 구성되고 외부에서 독립적으로 관리되는 스토리지를 사용  
NAS 헤드와 스토리지를 서로 독립적으로 확장시킬 수 있음  

통합 NAS와는 다르게 따로 스토리지를 내장하고 있지는 않음  
  
![Gateway](/assets/Gateway.png)
  
&nbsp;
