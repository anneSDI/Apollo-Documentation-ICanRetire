# Tool Middle Step

### 

## Variable Definitions

| Attribute Name|Data Source Type|Data Source|Description|
| --- | --- | --- | --- |
|Adobe Experience Cloud ID|Custom Code|getMarketingCloudVisitorID();
return mcid;|Captures the Adobe Experience Cloud ID associated with user activity|
|Process Steps|Static|1|Description not provided|
|Site Name|Custom Code|getVar('Page | SiteLanguage | [APL]');
var sitename = aud + ":" + sitecountry + ":" + sitelang;
return sitename;|Common language used within the business to refer to the website. May be specific County Sites.|
|Tool Middle Step|Static|1|Description not provided|
|URL (Full)|Custom Code|href;|Description not provided|



