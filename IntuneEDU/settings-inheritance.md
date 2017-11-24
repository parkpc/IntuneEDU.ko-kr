---
title: "설정 상속 이란?"
titleSuffix: Intune for Education
description: "교육에 대 한 Intune로 장치 그룹에 대 한 설정을 관리 하는 방법에 알아봅니다."
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: 4b69b884-bed9-43f4-8507-c802228a8804
searchScope: IntuneEDU
ms.openlocfilehash: 388e4f4468c3184d4dd941c74f8524a6302694f3
ms.sourcegitcommit: 2914b0e879129878ab55f59d288a0739f0e00fb9
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 11/24/2017
---
# <a name="what-is-settings-inheritance"></a>설정 상속 이란?

설정은 그룹에 적용 됩니다. 그룹으로 설정 되어 있으므로 위의 다른, 설정 그룹에 적용 한 그룹 계층, 모든 하위 그룹에 상속 됩니다. 이렇게 하면 보다 쉽게 대규모 그룹을 사용자, 앱 및 장치에 설정을 적용할 수 있습니다.

  ![그룹 및 하위 그룹의 트리입니다.](./media/groups-002-inheritance.png)

이 아래에 있는 하위 그룹 포함 된 그룹에 대 한 하위 그룹이 자동으로 상속 위에 있는 그룹에 수행한 모든 변경 내용을 의미 합니다. 이 라고 _상속_합니다.

## <a name="can-i-configure-subgroups-differently-after-inheriting-settings-from-another-group"></a>구성 하위 그룹 다르게 후 다른 그룹에서 설정을 상속 하는?

하위 그룹 위에 그룹에서 설정을 상속 하는 이러한 경우에 개별적으로 구성할 수 있습니다. 필요한 설정을 구성 하기만 하면 다음 저장 하 여 상속 된 설정을 재정의할 수 있습니다.

## <a name="can-i-ever-end-up-with-settings-that-do-not-work-together"></a>종료 될 수 있습니까 적이 함께 작동 하지 않는 설정을?

동일한 그룹에 적용 된 여러 설정이 교육에 대 한 Intune을 통해 각 설정은 개별적으로 분석 됩니다. 사용자가 장치 설정을 준수 하도록 조치를 강제로 특정 설정은 다른 설정 보다 우선 항상 합니다.

하위 그룹을 고려 *열 두 번째 등급 AP 전산학*, 그룹에 *열 두 번째 등급*합니다. AP 컴퓨터 과학 클래스에서 보안 검사, 필요 하지 않은 일부 JavaScript 파일을 다운로드 해야 하지만 전체 등급은 동일한 작업을 시도 하지 않습니다 확인 하려는 알 수 있습니다. 더 제한적인 설정 상속을 재정의 하지 않는 경우 *열 두 번째 등급* 설정을 사용자에 게 적용 됩니다 *열 두 번째 등급 AP 전산학*합니다.

## <a name="find-out-more"></a>자세한 정보

  - [Intune에서 아웃 환경 전체 그룹에 대 한 자세한 정보 찾기](https://docs.microsoft.com/intune/deploy-use/use-groups-to-manage-users-and-devices-with-microsoft-intune)
