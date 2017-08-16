---
title: "장치 추가"
titleSuffix: Intune for Education
description: "교육에 Intune에 대 한 Windows 10 장치를 설정 하는 방법을 알아봅니다."
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: c884df47-61a9-4799-a407-8cd311d376d1
searchScope: IntuneEDU
ms.openlocfilehash: 7b5343d996868ceaf18a58812a4db14d626d2969
ms.sourcegitcommit: 293ad8c775aa37b5d3b6a9e547c80f31ba6a5bdd
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 08/15/2017
---
# <a name="how-do-i-add-devices-to-intune-for-education"></a>교육에 대 한 Intune에 장치를 추가 하려면 어떻게 합니까?

사용자 정보로 교육에 대 한 Intune을 설정 해-학생 레코드, 앱 및 장치에 대 한 설정을 같은-교육에 Intune에 장치를 연결 해야 합니다. 새 Windows 10 장치에 대 한 설치 환경의 일부로이 수행할 수 있습니다.


> [!NOTE]
> 인터넷에 액세스 해야 하는 장치 및 설치를 완료 하려면 사용할 수 있는 교육 장치 라이선스에 대 한 충분 한 Intune 갖고 있어야 합니다. 이에 대 한 자세한 내용을 확인할 수 우리의 [docs 라이선스](https://docs.microsoft.com/intune/get-started/start-with-a-paid-subscription-to-microsoft-intune-step-4)합니다.

## <a name="add-devices-to-intune-for-education"></a>교육에 Intune에 장치 추가

단축 해야는 다음을 수행 하 여 Windows 10 장치를 교육에 대 한 Intune에서 관리 합니다.

1. 새 Windows 10 장치를 켜고 표준 Windows 설치 프로그램을 시작 합니다. 나타나면는 **이 PC를 소유한 사람?** 화면에서 **내 회사 또는 학교 소유**합니다.

  !["소유자는 누구이 PC?"의 스크린 샷 Windows 설치 프로그램에서 화면](./media/devices-001-who-owns-this-pc.png)

2. 에 **연결 하면 선택** 화면에서 **Azure AD 조인**합니다.

  ![Windows 설치 프로그램에서 "연결 방법을 선택" 화면의 스크린 샷](./media/devices-002-how-you-connect-pc.png)

3. 교육 관리를 Intune에 대 한 계정 세부 정보를 입력 또는 **다른 권한이 등록 사용자** 선택 **다음**합니다.

장치는 [Azure AD로 인증](https://docs.microsoft.com/azure/active-directory/active-directory-conditional-access) 설치가 완료 되 면 할당 된 응용 프로그램 및 설정을 받이 됩니다.

다른 방법은 장치를 등록 하는 [무료 __학교 Pc 설정__ 앱](how-should-i-enroll-devices.md) USB 키를 사용 하 여 Pc를 신속 하 게 설정 하 합니다. 

## <a name="find-out-more"></a>자세한 정보
- [에 대 한 자세한 내용을 알아보려면는 **학교 Pc 설정** 응용 프로그램](https://docs.microsoft.com/education/windows/use-set-up-school-pcs-app)
- [Intune에 장치를 추가 하는 전체 환경에 대해 자세히 알아보기](https://docs.microsoft.com/intune/deploy-use/enroll-devices-in-microsoft-intune)
