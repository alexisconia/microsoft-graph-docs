---
description: "Automatically generated file. DO NOT MODIFY"
---

```powershell

Import-Module Microsoft.Graph.Identity.SignIns

$params = @{
	PhoneNumber = "+1 2065555555"
	PhoneType = "mobile"
}

New-MgUserAuthenticationPhoneMethod -UserId $userId -BodyParameter $params

```