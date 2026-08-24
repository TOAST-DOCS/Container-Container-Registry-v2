<a id="container-nhn-container-registry-ncr-release-notes"></a>
## Container > NHN Container Registry(NCR)  > 릴리스 노트 { #container-nhn-container-registry-ncr-release-notes }

<a id="august-26-2025"></a>
### 2025. 08. 26. { #august-26-2025 }

<a id="august-26-2025-feature-updates"></a>
#### 기능 개선

* 복제 대상 NCR에서 소스 레지스트리에 존재하는 이미지와 동일한 이미지를 식별하여 삭제할 수 있는 기능이 추가되었습니다.

<a id="december-3-2024"></a>
### 2024. 12. 03. { #december-3-2024 }

<a id="december-3-2024-feature-updates"></a>
#### 기능 개선

* NCR 콘솔에서 멀티 플랫폼 이미지를 사용할 수 있습니다.

<a id="september-5-2024"></a>
### 2024. 09. 05. { #september-5-2024 }

<a id="september-5-2024-added-features"></a>
#### 기능 추가

* NCR 서비스를 위한 Public API가 공개되었습니다.
    * Public API에 대한 내용은 [API 가이드](/Container/NCR/ko/public-api-gov)를 참고하세요.
* Resource Watcher 서비스를 통해 레지스트리에서 발생하는 이벤트에 대한 알림을 받을 수 있습니다.
    * 자세한 내용은 [Resource Watcher](/Governance%20&%20Audit/Resource%20Watcher/ko/overview-gov)를 참고하세요.
* 이미지 서명 목록을 조회할 수 있습니다.

<a id="september-5-2024-feature-updates"></a>
#### 기능 개선

* 프로젝트 간 복제 기능이 추가되었습니다.

<a id="june-4-2024"></a>
### 2024. 06. 04. { #june-4-2024 }

<a id="june-4-2024-added-features"></a>
#### 기능 추가
* 미서명 이미지 배포 차단 기능이 추가되었습니다.

<a id="june-4-2024-feature-updates"></a>
#### 기능 개선
* 이미지 정리/보호 정책에서 `/`이 포함된 이미지도 식별할 수 있도록 수정하였습니다.
* 아티팩트 조회 항목을 확장하였습니다.
* 이미지 정리 정책의 개수 제한이 없도록 수정하였습니다.

<a id="march-5-2024"></a>
### 2024. 03 .05. { #march-5-2024 }

<a id="march-5-2024-added-features"></a>
#### 기능 추가
* NCR 콘솔에서 발생한 이벤트를 CloudTrail에서 확인할 수 있습니다.
* 이미지 복제 기능에 덮어쓰기 옵션을 추가하였습니다.

<a id="march-5-2024-feature-updates"></a>
#### 기능 개선
* 이미지 키워드 검색이 가능하도록 수정하였습니다.

<a id="november-30-2023"></a>
### 2023. 11. 30. { #november-30-2023 }

<a id="november-30-2023-added-features"></a>
#### 기능 추가
* Public URI 사용 여부를 설정할 수 있는 기능을 추가하였습니다.
* 이미지 업로드만 할 수 있는 `Image Uploader` 권한이 추가되었습니다.

<a id="august-31-2023"></a>
### 2023. 08. 31. { #august-31-2023 }

<a id="august-31-2023-added-features"></a>
#### 기능 추가

* Private URI 기능 추가
    * 인터넷 게이트웨이에 연결되지 않은 인스턴스에서 NCR 서비스를 이용할 수 있는 Private URI 기능을 추가하였습니다.
    * 자세한 내용은 [Private URI 사용 가이드](./user-guide-gov/#private-uri)를 참고하십시오.
* 리전 간 복제 기능을 추가하였습니다.

<a id="august-31-2023-feature-updates"></a>
#### 기능 개선

* OCI 아티팩트를 관리할 수 있는 기능이 추가되었습니다.
* Quota 기능이 추가되었습니다.

<a id="april-4-2023"></a>
### 2023. 04. 04. { #april-4-2023 }

<a id="april-4-2023-added-features"></a>
#### 기능 추가

* 이미지의 신뢰 기능을 추가하였습니다.

<a id="february-7-2023"></a>
### 2023. 02. 07. { #february-7-2023 }

<a id="february-7-2023-added-features"></a>
#### 기능 추가

* 이미지의 취약점 스캐닝 기능을 추가하였습니다.

<a id="december-6-2022"></a>
### 2022. 12. 06. { #december-6-2022 }

<a id="december-6-2022-added-features"></a>
#### 기능 추가

* 이미지 캐시 기능을 추가하였습니다.

<a id="august-2-2022"></a>
### 2022. 08. 02. { #august-2-2022 }

<a id="august-2-2022-added-features"></a>
#### 기능 추가

* 이미지 정리, 이미지 보호 기능을 추가하였습니다.

<a id="may-31-2022"></a>
### 2022. 05. 31. { #may-31-2022 }

* 레지스트리 도메인으로 nhncloud.com을 사용하도록 수정했습니다.

<a id="may-3-2022"></a>
### 2022. 05. 03. { #may-3-2022 }

<a id="may-3-2022-feature-updates"></a>
#### 기능 개선

* Garbage Collection 기능을 사용자에게 노출하지 않도록 수정했습니다.

<a id="april-5-2022"></a>
### 2022. 04. 05. { #april-5-2022 }

<a id="april-5-2022-feature-updates"></a>
#### 기능 개선

* Container Registry 서비스의 이름이 NHN Container Registry(NCR)로 변경되었습니다.

<a id="february-22-2022"></a>
### 2022. 02. 22. { #february-22-2022 }
<a id="february-22-2022-new-service-release"></a>
#### 신규 서비스 출시
* 컨테이너 이미지를 저장할 수 있는 컨테이너 레지스트리 서비스입니다.
* Docker 명령줄 도구를 통해 컨테이너 이미지를 업로드 또는 다운로드할 수 있습니다.
* 웹 콘솔에서 보관하고 있는 컨테이너 이미지들을 관리할 수 있습니다.

