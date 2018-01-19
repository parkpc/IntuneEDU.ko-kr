---
title: "설정을 관리 하려면 어떻게 해야 합니까?"
titleSuffix: Intune for Education
description: "Intune 통해 교육 정책에 대 한 설정을 관리 하려면 다음이 단계를 수행 합니다."
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 01/17/2018
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: 20c0f6c9-f1de-4048-aa96-5b0a068c1b75
searchScope: IntuneEDU
.md#ms.tgt_pltfrm: 
ms.openlocfilehash: 9ce70aedf1dfcd054225f879ff11e0fbe3195552
ms.sourcegitcommit: eec0d728af6e8404c08b4b71fb557a5b946b2853
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/19/2018
---
# <a name="how-do-i-manage-settings"></a>설정을 관리 하려면 어떻게 해야 합니까?

다양 한 사용자, 앱 및 Intune로 장치에 대 한 설정 관리할 수 있습니다. 장치 사용자 작업에 응답할 수는 어떻게 변경 되는 방식을 이며합니다

장치 그룹에 설정을 적용 되 면 해당 그룹에서 장치에 액세스할 때 사용자가 영향을 받습니다. 사용자 그룹에는 설정이 적용 되 면

장치 설정 그룹의 모든 장치에 적용 됩니다. 설정을 **구성 되어 있지** 사용자가 장치 자체에서 해당 설정을 정의할 수 있도록 합니다.

## <a name="manage-settings-for-groups"></a>그룹에 대 한 설정 관리

교육에 대 한 Intune의 설정의 전체 목록을 관리 하려면 다음 단계를 따르십시오.
1. 에 [교육에 대 한 Intune](https://intuneeducation.portal.azure.com) 콘솔의 왼쪽 탐색 메뉴에서 선택 **그룹**합니다.
2. 그룹 관리 하려는 설정을 선택 합니다. 전체 목록을 보려면를 참조 하십시오. [사용 가능한 설정](what-are-settings.md)합니다.
3. 클릭 **설정을** 를 사용할 수 있는 설정의 전체 목록을 보려면 페이지 맨 위에 있는 합니다.
4. 범주를 확장 하 고 선택한 그룹에 대해 개별 설정을 수정 합니다.
5. 클릭 **저장** 를 해당 그룹에 대 한 변경 내용을 저장 합니다. 설정은 해당 그룹의 장치에 자동으로 전송 됩니다.

## <a name="manage-settings-with-express-configuration"></a>Express 구성으로 설정 관리

Express 구성을 손쉽게 신속 하 게 시작할 수 있습니다 하지만 사용자 장치에 대 한 빠른 변경 유용할 수 있습니다.

  ![Express 구성 설정 수정](./media/express-config-006-choose-settings.png)

1. 에 [교육에 대 한 Intune](https://intuneeducation.portal.azure.com) 콘솔에서 선택 **Express 구성 시작**합니다. 검토는 **시작** 페이지를 선택 하 고 **시작**합니다.
2. 검토는 **학교 정보를 가져올** 페이지. 학교 정보를 이미 추가한 경우 선택 **다음**합니다.
3. 설정을 관리 하 고 다음 선택 그룹 선택 **다음**합니다.
4. 앱의 목록을 검토 한 다음 선택 **다음**합니다.
5. 에 **설정** 페이지를 사용할 수 있는 설정의 범주를 확장 합니다.
  * [기본 장치 설정](available-settings.md#basic-device-settings)
  * [Microsoft Edge 설정](available-settings.md#microsoft-edge-settings)
  * [장치 업데이트 설정](available-settings.md#device-update-settings)
  * [무선 설정](available-settings.md#wireless-settings)
  * [앱 설정](available-settings.md#app-settings)
  * [로그인 설정](available-settings.md#sign-in-settings)

  범주를 확장 하 고 설정을 수정 하 고 다음 선택할 컨트롤 설정/해제 **다음**합니다.

6. 선택 사항을 확인 한 다음 선택 **마침** 저장 하 여 변경 내용을 업데이트 선택한 그룹의 장치에 있습니다.

## <a name="can-i-ever-have-settings-that-dont-work-together"></a>현재까지 함께 작동 하지 않는 설정을 할 수 있습니까?

같은 그룹에 적용 될 호환 되지 않는 설정에 대 한 것 같습니다. 이러한 inconsistences 사용자 또는 장치를 되 고 설정할 때 다른 설정으로 여러 위치에서 오류를 발생 합니다. 이 사용자 또는 장치를 여러 그룹의 구성원으로 인해 발생 합니다.

예를 들어 Esperanza의 멤버인는 *6 학년* 그룹화 하 고 호출 하는 그룹의 구성원 이기도 *지구 과학*합니다. 홈 페이지 설정을 구성 하 고를 할당 하는 경우 *6 학년*, 서로 다른 홈 페이지 설정을 구성에 할당 하 고 *지구 과학*, 이제 그녀의 사용자에 게 할당 하는 두 개의 충돌 하는 홈 페이지 설정을 갖는. 일치 하지 않는 설정 할당 오류를 발생 합니다. 어떤 장치 및 사용자가 사용 하 여 설정 오류를 찾을 수 있습니다는 [설정 오류 보고서](what-are-reports.md)합니다.

## <a name="find-out-more"></a>자세한 정보

- [Intune에서 관리 환경이 전체 정책에 대해 자세히 알아보기](https://docs.microsoft.com/intune/deploy-use/manage-settings-and-features-on-your-devices-with-microsoft-intune-policies)
