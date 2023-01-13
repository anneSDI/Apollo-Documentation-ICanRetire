# Page Load Started

### 

## Variable Definitions

| Attribute Name|Data Source Type|Data Source|Description|
| --- | --- | --- | --- |
|Ad ID|Query String|ad_id|Provides the value of the ad\_id parameter if it is present in the URL|
|Adobe Experience Cloud ID|Custom Code|getMarketingCloudVisitorID();
return mcid;|Captures the Adobe Experience Cloud ID associated with user activity|
|Campaign Tracking (s.campaign)|Query String|cid|Description not provided|
|Google Click ID|Query String|gclid|Captures the value of the gclid parameter when present|
|Google Click Source|Query String|gclsrc|Captures the value of the gclsrc parameter|
|Salesforce Marketing ID|Query String|sfid|Captures the value of the sfid parameter if present in the URL|
|Site Name|Custom Code|getVar('Page | SiteLanguage | [APL]');
var sitename = aud + ":" + sitecountry + ":" + sitelang;
return sitename;|Common language used within the business to refer to the website. May be specific County Sites.|
|Site Name|Custom Code|getVar('Page | SiteLanguage | [APL]');
var sitename = aud + ":" + sitecountry + ":" + sitelang;
return sitename;|Common language used within the business to refer to the website. May be specific County Sites.|
|UID|Query String|uid|Participant ID value from the URL, if present \(UID parameter\)|
|URL (Full)|Custom Code|href;|Description not provided|
|URL (full) (prop)|Custom Code|href;|Description not provided|
|URL Advisor ID|Query String|aeid|Captures the advsior ID \(AEID\) provided in the URL that trafficked the user to the site|



