---

copyright:
  years: 2017
lastupdated: "2017-10-10"

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:codeblock: .codeblock}
{:pre: .pre}

# API 제품 대체
**기간**: 15분  
**스킬 레벨**: 초보자  

## 전제조건

1. [{{site.data.keyword.apiconnect_full}} 인스턴스를 설정하십시오](tut_prereq_set_up_apic_instance.html).

2. [API 제품 바꾸기 튜토리얼](tut_manage_replace.html)을 완료하십시오.

---
## 목표
이 튜토리얼에서는 기존 API를 새 API로 대체합니다.

---
## API 제품 대체
1. {{site.data.keyword.Bluemix_short}}에 로그인: [https://console.ng.bluemix.net/login ![외부 링크 아이콘](../../../icons/launch-glyph.svg "외부 링크 아이콘")](https://console.ng.bluemix.net/login){:new_window}.

2. {{site.data.keyword.Bluemix_short}} 대시보드에서 {{site.data.keyword.apiconnect_short}} 서비스를 실행하십시오.
![](images/Bluemix.png)

3. API Manager에서 UI 탐색 분할창을 아직 고정하지 않은 경우 **이동 위치** 아이콘 ![](images/navigate-to.png)을 클릭하십시오. API Manager UI 탐색 분할창이 열립니다. UI 탐색 분할창을 고정하려면 **핀 메뉴** 아이콘 ![](images/pinned.png)을 클릭하십시오.

4. **샌드박스**를 클릭하여 샌드박스 카탈로그를 여십시오. **참고**: 화면에 카탈로그 목록이 아니라 타일이 표시될 수 있습니다.
![](images/del-sandbox-list.png)

4. **초안** > **API**를 클릭하십시오.

5. API 패널에서 **Weather Provider API**를 클릭하여 REST 프록시 API를 여십시오.  
![](images/rep-api-list.png)

6. **버전**을 3.0.0으로 변경하십시오.

7. 디스크 아이콘을 클릭하여 API 변경사항을 저장하십시오.  
![](images/sup-change-version.png)

8. **모든 API**를 클릭하십시오.  
![](images/rep-all-apis.png)

9. **제품**을 클릭하십시오.  
![](images/sup-prods.png)

10.	**Weather Provider API 제품 2.0.0**을 선택하십시오.  
![](images/sup-draft-prod-list.png)

11.	**버전**을 3.0.0으로 변경하십시오. 디스크 아이콘을 클릭하여 변경사항을 저장하십시오. **스테이지** 아이콘을 클릭하십시오.  
![](images/sup-change-prod-vers-3.png)

12.	**>>**를 클릭하여 탐색 분할창을 열고 **대시보드**를 선택하십시오.  
![](images/rep-dashboard.png)

13.	**샌드박스**를 클릭하십시오.

14.	**커뮤니티**를 클릭하십시오.  
![](images/sup-sand-dash.png)

15.	**등록**을 클릭하십시오.  
![](images/sup-comm-orgs.png)

16.	Weather Provider API 제품 2.0.0에 대한 애플리케이션 등록을 기록해 두십시오. **제품**을 클릭하십시오.
![](images/sup-scriptions-200.png)  

17.	**Weather Provider API 제품 3.0.0 스테이징됨** 행에서 세로 생략 기호를 클릭하십시오.  
![](images/sup-stage-prod-3.png)

18.	**기존 제품 대체**를 선택하십시오.  
![](images/sup-super-prod.png)

19.	표시된 제품 목록에서 **Weather Provider API 제품 2.0.0**을 선택하십시오. **다음**을 클릭하십시오.   
![](images/sup-super-dialog-1.png)

20.	**기본 플랜**을 선택하십시오. **대체**를 클릭하십시오.  
![](images/sup-super-dialog-2.png)
    이와 같이 바꾸기를 수행하면 Weather Provider API 제품 2.0.0이 더 이상 사용되지 않고 Weather Provider API 제품 3.0.0이 공개됩니다.   
![](images/sup-dash-prods-3.png) 
 
21.	**커뮤니티 >> 등록**을 클릭하십시오.  
![](images/sup-scriptions-200.png)
 
22.	**Weather Provider API 제품 2.0.0** 행에서 세로 생략 기호를 클릭하십시오. **관리**를 선택하십시오.  
![](images/sup-dots-manage.png) 

23.	Weather Provider API 제품 3.0.0에서 **기본 플랜**을 선택하십시오. **마이그레이션**을 클릭하십시오.  
![](images/sup-migrate-dialog.png)
    이와 같이 마이그레이션하면 Weather Provider API 제품 2.0.0이 Weather Provider API 제품 3.0.0으로 마이그레이션됩니다.  
![](images/sup-migrated.png) 
 

 
## 이 튜토리얼에서 수행한 작업
이 튜토리얼에서 다음 활동을 완료했습니다.

1. API 제품 업데이트.
2. 기존 API를 업데이트된 API 제품으로 대체.
3. 기존 API 제품의 등록을 업데이트된 API 제품으로 마이그레이션.

---












