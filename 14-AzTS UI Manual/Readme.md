# Azure Tenant Security UI Guidance

## AzTS UI
### Contents
- [Introduction of AzTS UI](Readme.md#Introduction-of-AzTS-UI)
- [How to remediate a failed control?](Readme.md#how-to-remediate-a-failed-control)
- [How to scan your subscription manually?](Readme.md#How-to-scan-your-subscription-manually)
- [How to Add By Design Exception?](Readme.md#How-to-Add-By-Design-Exception)
- [How to Renew By Design Exception?](Readme.md#How-to-Renew-By-Design-Exception)
- [How to Clear By Design Exception?](Readme.md#How-to-Clear-By-Design-Exception)
- [How to export scan logs CSV?](Readme.md#How-to-export-scan-logs-CSV?)
- [Feedback](Readme.md#Feedback)

-----------------------------------------------------------------
## Introduction of AzTS UI 
The Azure Tenant Security (AzTS) UI tool is used to:
 * See compliance summary against each subscription.
 * Scan your subscription(s) manually.
 * Add/Renew exception.
 * Clear exception.
 * Export control scan result in CSV.
 
 To see basic introduction about AzTS UI, how it works and what are the functionality it is having, please refer the video below:

 https://msit.microsoftstream.com/video/ff03a1ff-0400-85a8-04aa-f1eb80965daa?list=studio


https://github.com/azsk/DevOpsKit-docs/blob/users/v-adisha/AzTSUIContent/Videos/14_Introduction_of_AzTS_UI.mp4?raw=true

[Back to top…](Readme.md#contents)


## How to remediate a failed control?

![Internals](../Videos/14_Remediate_Failed_Control.mp4)

[Back to top…](Readme.md#contents)

## How to scan your subscription manually?
In general, your subscription(s) will get scanned automatically in every 24 hrs. But if you are interested to see latest updated control scan result, you can go for manual scan of your subscription(s).

![Internals](../Videos/14_Scan_Subscription_Manually.mp4)

**Note:** You can only request for manual scan of subscription 10 times (maximum) in a day.

[Back to top…](Readme.md#contents)

## How to Add By Design Exception?
### What is By Design Exception?
Applicable for scenerios where there is no security risk dur to current control failure. For example, the team mitigated the risk through code implementation or the security control is expected to fail due to by design of application. 

Only following controls are allowed for By Design exception:

 * Azure_AppService_Config_Disable_Web_Sockets
 * Azure_CDN_DP_Enable_Https
 * Azure_HDInsight_Deploy_Supported_Cluster_Version
 * Azure_SQLDatabase_AuthZ_Use_AAD_Admin
 * Azure_Storage_AuthN_Dont_Allow_Anonymous

**Note:** Video will be coming soon..!!

[Back to top…](Readme.md#contents)

## How to Renew By Design Exception?
### Why Renew Exception?
If the requirement due to which the control was attested earlier still exist, you can request for an extension of attestation using this feature.

**Note:** Video will be coming soon..!!

**Note:** You can only request for Renew Exception, if the attestation expiry period is less than 30 days.

[Back to top…](Readme.md#contents)

## How to Clear By Design Exception?

**Note:** Video will be coming soon..!!

[Back to top…](Readme.md#contents)

## How to export scan logs CSV?
If you want to export control scan logs for your subscription in your local machine then you can export with the help of AzTS UI.

![Internals](../Videos/14_export_to_CSV.mp4)

[Back to top…](Readme.md#contents)

## Feedback

For any feedback contact us at: tdengteam@microsoft.com


