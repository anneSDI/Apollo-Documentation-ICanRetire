# Page Load Started

### Page Load Started is part of the page load sequence, including virtual page loads in the case of single page apps, and must be the first event pushed in the page load event sequence.

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Page Load Started",
    "page": {
        "advisorId": "<advisorId>",
        "baseURL": "<baseURL>",
        "channel": "<channel>",
        "pageLevel5": "<pageLevel5>",
        "pageName": "<pageName>",
        "siteAudience": "<siteAudience>",
        "siteCountry": "<siteCountry>",
        "siteLanguage": "<siteLanguage>",
        "siteSection": "<siteSection>",
        "siteSubsection": "<siteSubsection>",
        "subSubSection": "<subSubSection>"
    },
    "user": {
        "investorId": "<investorId>",
        "personaSegment": "<personaSegment>",
        "planParticipantId": "<planParticipantId>",
        "tracSponsorId": "<tracSponsorId>",
        "visionId": "<visionId>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|page.advisorId|string|Captures the Advisor ID asssociated with user activity||||||||
|page.baseURL|string|Captures the URL of the page after removing any parameters||||||||
|page.channel|string|Custom value for s.channel||||||||
|page.pageLevel5|string|Level below sub-subsection of the given page||||||||
|page.pageName|string|Describes the page and its content specifically. |product - XYZ123, Mens - Tops - Sweaters, Order Confirmation|||||||
|page.siteAudience|string|Audience portion of the site name \(audience\/country\/language\)||||||||
|page.siteCountry|string|Indicates the primary country served by the site. ISO 3166 \(alpha-2\) Uppercase.|US, CA, FR, UK|^[a-zA-Z]{2}$||||||
|page.siteLanguage|string|Language in which the site is presented ISO 639-1 code. |en-us, en-gb, ch-cn, fr-ca, fr-fr, da|^[a-z]{2}([-]{1}[a-z]{2}){0,1}$||||||
|page.siteSection|string|The site section portion of the page details||||||||
|page.siteSubsection|string|Subsection of the page being viewed||||||||
|page.subSubSection|string|Sub-subsection level for the given page||||||||
|user.investorId|string|Captures the unique ID that the investor used to access the site||||||||
|user.personaSegment|string|User persona from the quiz if applicable, else an empty string||||||||
|user.planParticipantId|string|The plan participant ID of the user accessing the site||||||||
|user.tracSponsorId|string|Captures the sponsor ID associated with the user accessing the site||||||||
|user.visionId|string|Captures the Vision ID of the user accessing the site||||||||




