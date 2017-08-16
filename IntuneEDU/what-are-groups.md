---
title: "그룹은 무엇입니까?"
titleSuffix: Intune for Education
description: "교육에 대 한 Intune로 장치 그룹을 관리 하는 방법에 알아봅니다."
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: 4b570196-a640-4d13-8e01-8e8553ce1468
searchScope: IntuneEDU
ms.openlocfilehash: 925fee7b2807a340d2b4d0e1e9aa4ca069875f84
ms.sourcegitcommit: 293ad8c775aa37b5d3b6a9e547c80f31ba6a5bdd
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/15/2017
---
# <a name="what-are-groups"></a>그룹은 무엇입니까?

사용 하면 _그룹_ 사용자, 앱 및 교육에 대 한 Intune에서 장치를 관리할 수 있습니다. 각 장치를 개별적으로 관리할 필요 없이 사용자 또는 장치를 그룹화할 수 있습니다. 이렇게 하면 다수의 사용자 및 장치에 앱과 설정을 쉽게 할당할 수 있습니다.

그룹을 만들 때 적용 하는 방법을 설정 및 앱 사용자 및 장치에는 것이 좋습니다. 예를 들어 모든 장치에 대 한 위치 서비스를 사용 하 여 앱을 차단 해야 합니다. 이 하는 대신 특정 그룹은 라인 학생을 제공 하는 등의 특정 작업을 할 수 [AP 전산학](https://www.tealsk12.org) 앱의 코드를 편집 합니다.

설정은 그룹에 적용 됩니다. 그룹 위에 다른 한 개 그룹에 계층으로 설정 되어 있으므로 [그룹에 적용 된 모든 설정은 모든 하위 그룹에 상속 됩니다](settings-inheritance.md)합니다. 이렇게 하면 보다 쉽게 대규모 그룹을 사용자, 앱 및 장치에 설정을 적용할 수 있습니다.

교육에 Intune을 자동으로 만듭니다는 __모든 장치__ 및 __모든 사용자에 게__ 테 넌 트를 만들 때 그룹화 합니다. 이러한 기본 그룹의 사용자와 장치 학교 또는 학교 구역에 광범위 한 범주를 나타내도록 및 [이동할 수 없는](what-are-groups.md#why-cant-i-move-certain-groups)합니다.


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

## <a name="why-cant-i-move-certain-groups"></a>특정 그룹을 이동할 수 없습니다는 이유

이동할 수 없는 기본 그룹의 집합을 제공 하는 교육에 대 한 Intune **모든 사용자에 게** 및 **모든 장치**때 프로그램 [테 넌 트가 만들어집니다](what-are-tenants.md)합니다. **모든 교사** 및 **모든 학생** 학교 데이터 동기화가 교육에 대 한 Intune에 학생과 교사 데이터를 가져온 다음 생성 된 기본 그룹이 있습니다.

이 두 그룹 아래 하위 그룹으로 끝날 수도 있습니다는 여기서 문제를 인해 거의 수 있습니다.

  ![여러 그룹의 오류 메시지에서 하위 그룹이 나타납니다.](./media/groups-012-subgroup-is-under-two-groups-warning.png)

이 경우이 하위 그룹 위에 배치 하는 단일 그룹을 선택 해야 합니다.

## <a name="delete-a-group"></a>그룹 삭제

그룹을 삭제 하면 교육에 대 한 Intune 앱 및 해당 그룹의 구성원 인 모든 장치에서 설정의 컬렉션을 제거 합니다. 그룹을 삭제 하면 제거 되지 않습니다 해당 사용자 또는 장치 관리에서.

  ![Delete에 빨간색에서 원이 단추 그룹화](./media/groups-011-delete-groups.png)

1.  에 [교육 포털에 대 한 Intune](https://intuneeducation.portal.azure.com), 선택 **그룹 관리**합니다.
2. 삭제 하려는 그룹을 선택 합니다.
3.  클릭 **그룹 삭제** 작업 목록에 있습니다.

## <a name="find-out-more"></a>자세한 정보

- [Intune에서 관리 경험 하는 전체 그룹에 대해 자세히 알아보기](https://docs.microsoft.com/intune/deploy-use/use-groups-to-manage-users-and-devices-with-microsoft-intune)
