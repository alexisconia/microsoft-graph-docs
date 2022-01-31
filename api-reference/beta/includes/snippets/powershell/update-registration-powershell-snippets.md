---
description: "Automatically generated file. DO NOT MODIFY"
---

```powershell

Import-Module Microsoft.Graph.CloudCommunications

$params = @{
	Subject = "Microsoft Ignite: Day 1"
	StartDateTime = [System.DateTime]::Parse("2021-11-02T08:00:00-08:00")
	EndDateTime = [System.DateTime]::Parse("2021-11-02T15:45:00-08:00")
	Speakers = @(
		@{
			DisplayName = "Henry Ross"
			Bio = "Chairman and Chief Executive Officer"
		}
		@{
			DisplayName = "Fred Ryan"
			Bio = "CVP"
		}
	)
}

Update-MgUserOnlineMeetingRegistration -UserId $userId -OnlineMeetingId $onlineMeetingId -BodyParameter $params

```