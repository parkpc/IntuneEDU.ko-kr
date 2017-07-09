---
title: "앱 추가"
titleSuffix: Intune for Education
description: "교육에 대 한 Intune에 앱을 추가 하는 방법을 알아봅니다."
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: 24ab6547-aa65-428a-b184-06b806e95bd1
searchScope:
- IntuneEDU
ms.translationtype: Machine Translation
ms.sourcegitcommit: f76a24da64ea7688f385c5ea15a368c76e982951
ms.openlocfilehash: 7a2298d4a1b55d8a1355ca9e828d92c0a561eac8
ms.contentlocale: ko-kr
ms.lasthandoff: 07/05/2017


---

# <a name="how-do-i-add-apps-to-intune-for-education"></a>교육에 대 한 Intune에 앱을 추가 하려면 어떻게 해야 합니까?

교육을 위해 Intune 사용한 학교 장치에서 앱을 설치할 수 있습니다, 전에 그러한 응용 프로그램 교육 계정에 대 한 Intune에 추가 해야 합니다.

Intune 교육에 대 한 다음과 같은 유형의 앱을 지원합니다.
- 와 같은 웹 앱, [온라인 Microsoft Word](https://office.live.com/start/Word.aspx)
- 중인 교육 응용 프로그램에 대 한 Microsoft 저장소 [스토어를 통해 배포 되는 유니버설 앱](https://technet.microsoft.com/itpro/windows/manage/apps-in-windows-store-for-business)
- 데스크톱 앱의 경우와 같은 [독립 실행형 Microsoft Office](https://products.office.com/products)

앱을 추가한 후 다음을 할 수 있습니다 [에서 앱 설치](install-apps.md) 장치 그룹에 있습니다.

설정 앱의 그룹을 포함 하 여 그룹에 적용 됩니다. 그룹 위에 다른 한 개 그룹에 계층으로 설정 되어 있으므로 [그룹에 할당 된 모든 앱은 모든 하위 그룹에 상속 됩니다](settings-inheritance.md)합니다.

## <a name="add-web-apps"></a>웹 앱 추가

A _웹 앱_ 은 사용자가 브라우저에서 배타적으로 액세스 되는 앱입니다. 하기 쉽기 때문 사용자에 게 보내야 하는 모든 장치에 설치 파일을 전송 하는 것이 아니라 웹 사이트에 대 한 링크를 되기 때문에 할당 합니다.

웹 응용 프로그램 교육에 대 한 Intune을 사용 하 여 Windows 10 장치의 시작 메뉴에서 링크로 지정할 수 있습니다. 응용 프로그램에 할당 하려면 먼저 추가 해야 Intune에 대 한 교육을 하는 **앱 관리** 섹션.

  ![다음 절차에 설명 된 정보에 대 한 사용자가 입력 하 라는 새 웹 응용 프로그램 페이지를 추가 합니다.](./media/apps-001-add-webapp.png)

1. 에 [교육에 대 한 Intune](https://intuneeducation.portal.azure.com) 콘솔에서 선택 **앱**합니다.

2. 아래 **웹 앱**선택, **+ 새 앱**, 다음 정보를 입력 합니다:
 * **URL** -할당 하려는 앱의 URL
 * **응용 프로그램 이름** -장치에서 시작 메뉴에 표시 되는 앱의 이름을
 * **아이콘** -응용 프로그램에 대 한 아이콘으로 사용할 컴퓨터에서 PNG 또는 JPG 업로드

3. **저장**을 선택합니다. 웹 앱 준비 되었습니다.

4. 이제 수 [장치에 앱을 설치](install-apps.md)합니다.

선택 하 여 언제 든 지 앱을 편집할 수 있습니다 **편집**, 해당 세부 정보 페이지 다시 열립니다.

## <a name="add-desktop-apps"></a>데스크톱 앱 추가

동일한 인터페이스를 통해 데스크톱 앱을 설치할 수는 **앱** 페이지. 이 프로세스는 웹 앱을 설치 유사 하지만 웹 앱 필요 하지 않은 설치 파일을 포함 합니다.

![새 데스크톱 응용 프로그램 화면입니다.](./media/apps-003-add-desktop-app.png)

1. 에 [교육에 대 한 Intune](https://intuneeducation.portal.azure.com) 콘솔에서 선택 **앱**합니다.

2. 아래 **데스크톱 앱**선택, **+ 새 앱**합니다. 열립니다는 **데스크톱 응용 프로그램을 새** 다음 세부 정보를 입력 한 다음 화면에서:
 * **응용 프로그램 파일** -응용 프로그램에 대 한 MSI 설치 관리자를 업로드 합니다.
 * **응용 프로그램 이름** -장치에 앱의 이름
 * **설명** -는 어떤 앱을 신속 하 게 식별 된 응용 프로그램에 대 한 설명을
 * **게시자** -어디서 응용 프로그램 개발을 신속 하 게 식별 된 응용 프로그램 게시자의 이름
 * **아이콘** -응용 프로그램에 대 한 아이콘으로 사용할 컴퓨터에서 PNG 또는 JPG 업로드

3. 선택 **저장 하 고 파일을 업로드**합니다.

  ![샘플 응용 프로그램을 evernote에 대 한 추가 새 데스크톱 응용 프로그램 화면, 모든 필드와 함께 입력합니다.](./media/apps-004-filled-out-desktop-app.png)

4. 응용 프로그램 교육에 대 한 Intune에 업로드 한 다음 합니다. 업로드가 완료 되 면 다음을 할 수 있습니다 [장치에 앱을 설치](install-apps.md)합니다.

> [!NOTE]
> 경우에 따라 "앱에 없는 설치 파일" 또는 "응용 프로그램 설치 파일에 없는 추가 되었습니다." 라는 오류가 발생할 수 있습니다. 즉, 파일이 올바르게 업로드 되지 않았습니다. 저장 하 고이 오류를 해결 하는 다시 파일을 업로드 하려고 합니다.

## <a name="add-popular-apps"></a>인기 앱 추가

또한 신속 하 게 교육에 대 한 Microsoft 저장소에서 인기 있는 교육 앱을 설치할 수 있습니다. 이러한 목표를 쉽게 찾고 사용자를 위해 즐겨 찾는 앱을 설치 하는 합니다. 자주 교육자에 게 유용 하므로 이러한 앱을 좋습니다. Express 구성 또는에서 이러한 앱을 찾을 수 있습니다는 **앱 관리** 바둑판식으로 배열입니다.

  ![인기 있는 앱의 추가 응용 프로그램의 프로세스 중에 Express 구성을 선택 합니다.](./media/apps-005-popular-apps.png)

교육 포털에 대 한 Intune 상위 표시 12 교육 웹 앱, 아래에 추가 하지 않은 교육 앱에 대 한 12 개까지 교육 Microsoft 저장소 상단 **앱** 관리 합니다.

> [!TIP]
> 교육 계정에 대 한 교육에 대 한 Intune에 앱을 추가 하 여 Microsoft 저장소를 설정 하지 않은 경우에 작업을 수행 하는 방법을 알아볼 수 있습니다 [여기](acquire-store-apps.md)합니다.

1. 에 [교육에 대 한 Intune](https://intuneeducation.portal.azure.com) 콘솔에서 선택 **앱 관리** > **앱 추가** > **빠른 인기 앱 추가**합니다. 목록이 **웹 앱** 및 **Microsoft 스토어 앱** 표시 됩니다.

  ![빠른 인기 앱 화면을 추가 합니다.](./media/apps-006-add-popular-apps.png)

2. 앱을 추가한 다음 선택 하려는 선택 **앱 추가**합니다.

  ![포털에 추가 하는 여러 인기 있는 앱을 선택 하면 됩니다.](./media/apps-007-select-multiple-popular-apps.png)

3. 앱은 백그라운드에서 추가 하 고 준비가 되 면 왼쪽 세로 막대에 표시 됩니다.

  ![앱 화면을 추가 되 고 있습니다.](./media/apps-008-your-popular-apps-are-being-added.png)

## <a name="find-out-more"></a>자세한 정보

- [Intune을 사용 하 여 앱을 관리 하는 전체 경험에 대 한 자세한 내용을 알아보려면](https://docs.microsoft.com/intune/deploy-use/add-apps)

