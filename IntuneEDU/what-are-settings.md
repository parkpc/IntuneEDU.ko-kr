---
title: "설정 이란?"
titleSuffix: Intune for Education
description: "Intune 통해 교육 정책에 대 한 설정을 관리 하는 방법에 알아봅니다."
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: 91d004c0-8d06-4307-8868-46ac7b119101
searchScope: IntuneEDU
ms.openlocfilehash: c7308ab88970c335a0c43d20f4558a54c9143fd9
ms.sourcegitcommit: 293ad8c775aa37b5d3b6a9e547c80f31ba6a5bdd
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/15/2017
---
# <a name="what-are-settings"></a>설정 이란?

_설정_ 사용 하 여 사용자가 자신의 장치 함께 사용 하는 방법을 정의 됩니다. 장치 작업을 수행 하는 사용자 또는 장치에서 작업을 수행할에서 사용자를 중지 하는 단순히 응답 하는 방법을 수정 하거나이 합니다. 교육 설정에 대 한 Intune을 사용 하면 학교 장치에서 기능을 관리할 수 있도록 합니다.

설정은 그룹에 적용 됩니다. 그룹 설정, 위에 한 개 그룹에 계층으로 모든 이후 [그룹에 적용 된 설정을 모든 하위 그룹에 상속 됩니다](settings-inheritance.md)합니다. 이렇게 하면 보다 쉽게 대규모 그룹을 사용자, 앱 및 장치에 설정을 적용할 수 있습니다.

## <a name="manage-settings"></a>설정을관리

교육에 Intune에서 설정을 관리할 수는 다음과 같은 세 가지가 있습니다.

* __구성 express__: 가장 일반적으로 사용 되는 school 설정의 선택에 사용할 수 있습니다 [Express 구성](how-do-i-manage-settings.md#manage-settings-with-express-configuration) 학생 안전 하 고 학교에서 장치를 사용 하 여 생산성을 유지 될 수 있도록 합니다.

* __그룹__: 모든 개별 그룹에 대 한 모든 설정을 관리할 수 있습니다. Express 구성에서 사용 가능한 프로필과에 비해 설정의 한 확장 된 목록입니다. 작업을 수행할 [여기에 사용할 수 있는 설정은](available-settings.md)합니다.

* __테 넌 트 설정__: 테 넌 트 설정을 모든 사용자 및 장치 관리에 영향을 줍니다. 이러한 설정은 특정 관리자와만 관리할 수는 [테 넌 트에 대 한 액세스의 수준을 적절 한](what-are-tenants.md)합니다.

설정은를 설정할 수 있으며 사용자 및 그룹을 통해 장치에 할당 합니다. 사용자 그룹에 게 할당 된 설정을 사용 하는 어떤 장치에 관계 없이 사용자와 대해서만 합니다. 설정 그룹의 장치에 할당 된 장치에 로그온 하는 사용자에 관계 없이 장치에 적용 됩니다.

## <a name="find-out-more"></a>자세한 정보

- [앱 및 Intune에서 전체 관리 경험을 사용 하 여 데이터를 보호 하는 방법에 대해 자세히 알아보기](https://docs.microsoft.com/intune/deploy-use/protect-apps-and-data-with-microsoft-intune)
