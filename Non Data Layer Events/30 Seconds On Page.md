# 30 Seconds On Page

### 

## Variable Definitions

| Attribute Name|Data Source Type|Data Source|Description|
| --- | --- | --- | --- |
|30 Seconds On Page|Static|1|Description not provided|
|Adobe Experience Cloud ID|Custom Code|getMarketingCloudVisitorID();
return mcid;|Captures the Adobe Experience Cloud ID associated with user activity|
|Site Name|Custom Code|getVar('Page | SiteLanguage | [APL]');
var sitename = aud + ":" + sitecountry + ":" + sitelang;
return sitename;|Common language used within the business to refer to the website. May be specific County Sites.|
|URL (Full)|Custom Code|href;|Description not provided|



