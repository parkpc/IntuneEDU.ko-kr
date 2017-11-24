---
title: "그룹은 무엇입니까?"
titleSuffix: Intune for Education
description: "교육에 대 한 Intune로 장치 그룹을 관리 하는 방법에 알아봅니다."
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 10/17/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: 4b570196-a640-4d13-8e01-8e8553ce1468
searchScope: IntuneEDU
ms.openlocfilehash: 5a31632a63b2f8c63ebbd72b83427204b48e9341
ms.sourcegitcommit: 2914b0e879129878ab55f59d288a0739f0e00fb9
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 11/24/2017
---
# <a name="what-are-groups"></a>그룹은 무엇입니까?

사용 하면 _그룹_ 사용자, 앱 및 교육에 대 한 Intune에서 장치를 관리할 수 있습니다. 각 장치를 개별적으로 관리할 필요 없이 사용자 또는 장치를 그룹화할 수 있습니다. 이렇게 하면 다수의 사용자 및 장치에 앱과 설정을 쉽게 할당할 수 있습니다.

그룹을 만들 때 적용 하는 방법을 설정 및 앱 사용자 및 장치에는 것이 좋습니다. 예를 들어 모든 장치에 대 한 위치 서비스를 사용 하 여 앱을 차단 해야 합니다. 이 하는 대신 특정 그룹은 라인 학생을 제공 하는 등의 특정 작업을 할 수 [AP 전산학](https://www.tealsk12.org) 앱의 코드를 편집 합니다.

설정은 그룹에 적용 됩니다. 그룹 위에 다른 한 개 그룹에 계층으로 설정 되어 있으므로 [그룹에 적용 된 모든 설정은 모든 하위 그룹에 상속 됩니다](settings-inheritance.md)합니다. 이렇게 하면 보다 쉽게 대규모 그룹을 사용자, 앱 및 장치에 설정을 적용할 수 있습니다.

교육에 Intune을 자동으로 만듭니다는 __모든 장치__ 및 __모든 사용자에 게__ 테 넌 트를 만들 때 그룹화 합니다. 이러한 기본 그룹의 사용자와 장치 학교 또는 학교 구역에 광범위 한 범주를 나타내도록 및 [변경할 수 없는](what-are-groups.md#why-cant-i-change-the-all-devices-all-users-all-students-or-all-teachers-groups)합니다.

## <a name="group-types"></a>그룹 종류

사용자 및 교육에 대 한 Intune에서 장치를 구성 하는 데 사용할 수 있는 그룹의 두 가지: **Assigned** 그룹 및 **동적** 그룹입니다. 

### <a name="assigned-groups"></a>할당 된 그룹

할당 된 그룹을 수동으로 그룹 구성원으로 사용자 또는 장치를 추가할 때 사용 됩니다. 같은 폴더를 함께 구성에 참여: 적절 한 파일을 해당 폴더에 선택한를 확인할 수에 해당 파일을 할 때입니다. 폴더와 마찬가지로 추가 그룹을 구성 하 여 더 큰 더 짧은 함수로 작동 하는 하위 그룹을 만들 수 있습니다. 

### <a name="dynamic-groups"></a>동적 그룹

동적 그룹에 수동으로 사용자가 직접 추가 하는 대신 그룹 구성원을 추가 하는 프로세스를 건너뛸 수 있습니다. 학생 또는 장치 무엇이 든 기준을 만족 하는 테 넌 트를 검색 하는 규칙을 사용 하 여 생성 됩니다. 예를 들어 올해의 끝에 graduating 학생의 모든 표시 하는 동적 그룹을 만들 수 있습니다. 학생, 에서도 예기치 않게 수 없는 경우 수동으로이 동적 그룹에서 제거 수 없습니다. 대신 그룹에서 제거는 졸업 연도, 해당 학생의 변경 해야 합니다. 

동적 그룹의 규칙의 정의 포함할만 수 있으므로 별로 하위 그룹을 만들 수 없습니다. 

## <a name="managing-groups-and-subgroups"></a>그룹 및 하위 그룹 관리

로 이동 하 여 그룹을 만들 수 있습니다 **그룹**, 다음을 선택 하 **그룹 만들기** 그룹 목록 맨 위부터 합니다. 만들어 그룹을 추가로 구성할 수 있습니다 *하위 그룹* 모든 그룹을 제외 하 고 __모든 장치__ 또는 __모든 사용자에 게__합니다.

  ![하위 그룹 만들기에 대 한 두 위치를 사용 하 여 만들기 하위 그룹 페이지-그룹 이름 및 사이드바 맨 위에 있는-빨간색에서 원이](./media/groups-007-create-subgroup.png)

1. 에 [교육 콘솔에 대 한 Intune](https://intuneeducation.portal.azure.com)선택, **사용자 및 장치 그룹을 관리**합니다.
2. 하위 그룹을 만들려고 한다고 위에 그룹을 선택 합니다.
3. 클릭 **하위 그룹을 만들**, 다음을 입력에서 **그룹 이름**합니다.

## <a name="making-changes-to-groups"></a>그룹 변경

된 그룹을 만든 후에 해당 구성원 자격을 편집 해야 있습니다-장치에 있어야 하는 경우 다른 풍부한 참조 리소스 프로그램 구역에 전송 하는 예를 들어 있습니다.

  ![장치 그룹의 편집](./media/groups-008-edit-group-membership.png)

1. 그룹 멤버를 편집 하려면 선택 합니다.
2. 선택 된 **장치** 탭 합니다.
3. 선택 된 **장치 편집** 단추를 선택 합니다 **장치 추가** 목록에서 더 많은 장치를 추가 하려면 또는 **X** 삭제 하는 장치 옆에 있는 합니다.

그룹 이름을 변경 해야 하는 경우 이름을 변경 하는 그룹을 선택 하면 **이름 바꾸기** 이름을 편집 하려면 단추입니다.

## <a name="move-a-group"></a>그룹 이동

그룹 구조를 내에서 그룹을 이동할 수 또는 **계층**합니다.

  ![빨간색에서 원이 그룹 단추 이동](./media/groups-010-move-groups.png)

1.  에 [교육 포털에 대 한 Intune](https://intuneeducation.portal.azure.com), 선택 **그룹 관리**합니다.
2. 이동 해야 하는 그룹을 선택 합니다.
3.  클릭 **그룹 이동** 또는 메뉴 목록에서 선택 하 여는 **그룹 이동** 단추입니다.
4.  그룹 이름을 검색 하거나 계층 구조에서 선택 하 여 그룹을 이동 하려는 그룹의 위치를 선택 합니다.
5.  선택 **확인** 변경 내용을 저장 합니다.

## <a name="why-cant-i-change-the-all-devices-all-users-all-students-or-all-teachers-groups"></a>"모든 장치", "모든 사용자", "모든 학생" 또는 "모든 교사" 그룹을 변경할 수 없는 이유는 무엇입니까?

<!--These are tenant level groups and therefore they can't be modified-->

교육에 대 한 Intune 기본적 집합이 제공 [테 넌 트 수준 그룹](what-are-tenants.md) 학교 계정이 만들어질 때 만들어집니다. 이러한 그룹 **모든 사용자에 게** 및 **모든 장치**를 변경할 수 없습니다. **모든 교사** 및 **모든 학생** 학교 데이터 동기화가 교육에 대 한 Intune에 학생과 교사 데이터를 가져온 후에 마찬가지로 그룹이 만들어집니다. 

이 두 그룹 아래 하위 그룹으로 끝날 수도 있습니다는 여기서 문제를 인해 거의 수 있습니다.

  <!--![Subgroup under multiple groups error message appears](./media/groups-012-subgroup-is-under-two-groups-warning.png)-->

이 경우이 하위 그룹 위에 배치 하는 단일 그룹을 선택 해야 합니다.

## <a name="why-cant-i-edit-this-group"></a>이 그룹을 편집할 수 없는 이유 

교육에 Intune은 Intune에서 사용할 수 있는 모든 동적 특성의 하위 집합을 표시 합니다. 동적 특성을 교육 콘솔에 대 한 Intune에서 사용할 수 없는 경우에 편집 하려면 Intune 또는 Azure Active Directory로 이동 해야 합니다. 

Intune에 대 한 교육 프로그램 학교에서 장치를 관리 하는 간단한 방법일 수 하도록 설계 되었습니다. 사용 하 여 [Intune](https://docs.microsoft.com/intune/what-is-intune), 앱 및 그룹을 관리 하는 엔터프라이즈 제품입니다. 특정 관리자 조직에는 특수 한 그룹을 만드는 전체 Intune 콘솔 및 교육 콘솔에 대 한 Intune 모두 사용 합니다. 그룹을 편집할 수 없습니다 경우 이러한 그룹을 수정 하려면 전체 Intune 콘솔에 액세스할 수 없는 것입니다. 

## <a name="delete-a-group"></a>그룹 삭제

그룹을 삭제 하면 교육에 대 한 Intune 앱 및 해당 그룹의 구성원 인 모든 장치에서 설정의 컬렉션을 제거 합니다. 그룹을 삭제 하면 제거 되지 않습니다 해당 사용자 또는 장치 관리에서.

  ![Delete에 빨간색에서 원이 단추 그룹화](./media/groups-011-delete-groups.png)

1.  에 [교육 포털에 대 한 Intune](https://intuneeducation.portal.azure.com), 선택 **그룹 관리**합니다.
2. 삭제 하려는 그룹을 선택 합니다.
3.  클릭 **그룹 삭제** 작업 목록에 있습니다.

## <a name="find-out-more"></a>자세한 정보

- [Intune에서 관리 경험 하는 전체 그룹에 대해 자세히 알아보기](https://docs.microsoft.com/intune/deploy-use/use-groups-to-manage-users-and-devices-with-microsoft-intune)
