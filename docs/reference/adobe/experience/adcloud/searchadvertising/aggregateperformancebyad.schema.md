
# Search Advertising Aggregated Performance Measures By Ad Schema

```
https://ns.adobe.com/experience/adcloud/searchadvertising/aggregateperformancebyad
```

Search Advertising Aggregated Performance Measures By Ad is a collection of aggregated measures pulled from Search Advertising Platforms by Ad/Keyword.

| [Abstract](../../../../../abstract.md) | [Extensible](../../../../../extensions.md) | [Status](../../../../../status.md) | [Identifiable](../../../../../id.md) | [Custom Properties](../../../../../extensions.md) | [Additional Properties](../../../../../extensions.md) | Defined In |
|----------------------------------------|--------------------------------------------|------------------------------------|--------------------------------------|---------------------------------------------------|-------------------------------------------------------|------------|
| Can be instantiated | Yes | Deprecated | No | Forbidden | Permitted | [adobe/experience/adcloud/searchadvertising/aggregateperformancebyad.schema.json](adobe/experience/adcloud/searchadvertising/aggregateperformancebyad.schema.json) |
## Schema Hierarchy

* Search Advertising Aggregated Performance Measures By Ad `https://ns.adobe.com/experience/adcloud/searchadvertising/aggregateperformancebyad`
  * [Time-series Schema](../../../../behaviors/time-series.schema.md) `https://ns.adobe.com/xdm/data/time-series`
  * [Measure](../../../../datatypes/data/measure.schema.md) `https://ns.adobe.com/xdm/data/measure`
  * [Device](../../../../datatypes/device.schema.md) `https://ns.adobe.com/xdm/context/device`


# Search Advertising Aggregated Performance Measures By Ad Properties

| Property | Type | Required | Defined by |
|----------|------|----------|------------|
| [@id](#id) | `string` | Optional | [Time-series Schema](../../../../behaviors/time-series.schema.md#id) |
| [xdm:accountId](#xdmaccountid) | `string` | Optional | Search Advertising Aggregated Performance Measures By Ad (this schema) |
| [xdm:adId](#xdmadid) | `string` | Optional | Search Advertising Aggregated Performance Measures By Ad (this schema) |
| [xdm:adgroupId](#xdmadgroupid) | `string` | Optional | Search Advertising Aggregated Performance Measures By Ad (this schema) |
| [xdm:avgPosition](#xdmavgposition) | Measure | Optional | Search Advertising Aggregated Performance Measures By Ad (this schema) |
| [xdm:campaignId](#xdmcampaignid) | `string` | Optional | Search Advertising Aggregated Performance Measures By Ad (this schema) |
| [xdm:clicks](#xdmclicks) | Measure | Optional | Search Advertising Aggregated Performance Measures By Ad (this schema) |
| [xdm:device](#xdmdevice) | Device | Optional | Search Advertising Aggregated Performance Measures By Ad (this schema) |
| [xdm:eventType](#xdmeventtype) | `string` | Optional | [Time-series Schema](../../../../behaviors/time-series.schema.md#xdmeventtype) |
| [xdm:impressions](#xdmimpressions) | Measure | Optional | Search Advertising Aggregated Performance Measures By Ad (this schema) |
| [xdm:qualityScore](#xdmqualityscore) | Measure | Optional | Search Advertising Aggregated Performance Measures By Ad (this schema) |
| [xdm:searchEngineId](#xdmsearchengineid) | `integer` | Optional | Search Advertising Aggregated Performance Measures By Ad (this schema) |
| [xdm:timestamp](#xdmtimestamp) | `string` | Optional | [Time-series Schema](../../../../behaviors/time-series.schema.md#xdmtimestamp) |
| [xdm:topPageBid](#xdmtoppagebid) | Measure | Optional | Search Advertising Aggregated Performance Measures By Ad (this schema) |
| [xdm:totalCost](#xdmtotalcost) | Measure | Optional | Search Advertising Aggregated Performance Measures By Ad (this schema) |
| `*` | any | Additional | this schema *allows* additional properties |

## @id
### Identifier

A unique identifier for the time-series event.

`@id`
* is optional
* type: `string`
* defined in [Time-series Schema](../../../../behaviors/time-series.schema.md#id)

### @id Type


`string`
* format: `uri-reference` – URI Reference (according to [RFC3986](https://tools.ietf.org/html/rfc3986))






## xdm:accountId
### Account Identifier

Identifier that defines Customer/Client ID setup on the Search Advertising Platform.

`xdm:accountId`
* is optional
* type: `string`
* defined in this schema

### xdm:accountId Type


`string`






## xdm:adId
### Ad Identifier

Ad ID on the search advertising platform.

`xdm:adId`
* is optional
* type: `string`
* defined in this schema

### xdm:adId Type


`string`






## xdm:adgroupId
### Ad Group Identifier

Ad Group ID on the search advertising platform.

`xdm:adgroupId`
* is optional
* type: `string`
* defined in this schema

### xdm:adgroupId Type


`string`






## xdm:avgPosition

Average Position of the Ad displayed on the network.

`xdm:avgPosition`
* is optional
* type: Measure
* defined in this schema

### xdm:avgPosition Type


* [Measure](../../../../datatypes/data/measure.schema.md) – `https://ns.adobe.com/xdm/data/measure`





## xdm:campaignId
### Campaign Identifier

Campaign ID on the search advertising platform..

`xdm:campaignId`
* is optional
* type: `string`
* defined in this schema

### xdm:campaignId Type


`string`






## xdm:clicks

Count of Clicks for a given ad displayed on the network.

`xdm:clicks`
* is optional
* type: Measure
* defined in this schema

### xdm:clicks Type


* [Measure](../../../../datatypes/data/measure.schema.md) – `https://ns.adobe.com/xdm/data/measure`





## xdm:device
### Device

The device from where the ad was displayed.

`xdm:device`
* is optional
* type: Device
* defined in this schema

### xdm:device Type


* [Device](../../../../datatypes/device.schema.md) – `https://ns.adobe.com/xdm/context/device`





## xdm:eventType
### Event Type

The primary event type for this time-series record.

`xdm:eventType`
* is optional
* type: `string`
* defined in [Time-series Schema](../../../../behaviors/time-series.schema.md#xdmeventtype)

### xdm:eventType Type


`string`



### xdm:eventType Known Values
| Value | Description |
|-------|-------------|
| `advertising.completes` | Advertising Completes |
| `advertising.timePlayed` | Advertising Time Played |
| `advertising.federated` | Advertising Federated |
| `advertising.clicks` | Advertising Clicks |
| `advertising.conversions` | Advertising Conversions |
| `advertising.firstQuartiles` | Advertising First Quartiles |
| `advertising.impressions` | Advertising Impressions |
| `advertising.midpoints` | Advertising Midpoints |
| `advertising.starts` | Advertising Starts |
| `advertising.thirdQuartiles` | Advertising Third Quartiles |
| `application.close` | Application Close |
| `application.launch` | Application Launch |
| `web.webpagedetails.pageViews` | Web Webpagedetails Page Views |
| `web.webinteraction.linkClicks` | Web Webinteraction Link Clicks |
| `web.formFilledOut` | Web Form Filled Out |
| `commerce.checkouts` | Commerce Checkouts |
| `commerce.productListAdds` | Commerce Product List (Cart) Adds |
| `commerce.productListOpens` | Commerce Product List (Cart) Opens |
| `commerce.productListRemovals` | Commerce Product List (Cart) Removals |
| `commerce.productListReopens` | Commerce Product List (Cart) Reopens |
| `commerce.productListViews` | Commerce Product List (Cart) Views |
| `commerce.productViews` | Commerce Product (Cart) Views |
| `commerce.purchases` | Commerce Purchases |
| `commerce.saveForLaters` | Commerce Save For Laters |
| `decisioning.propositionDisplay` | Decisioning Proposition Display |
| `decisioning.propositionInteract` | Decisioning Proposition Interact |
| `decisioning.propositionDeliver` | Decisioning Proposition Deliver |
| `delivery.feedback` | Delivery Feedback |
| `message.feedback` | Message Feedback |
| `message.tracking` | Message Tracking |
| `pushTracking.applicationOpened` | Push Tracking Application Opened |
| `pushTracking.customAction` | Push Tracking Custom Action |
| `listOperation.removeFromList` | List Operation Remove From List |
| `listOperation.addToList` | List Operation Add To List |
| `leadOperation.scoreChanged` | Lead Operation Score Changed |
| `leadOperation.revenueStageChanged` | Lead Operation Revenue Stage changed |
| `leadOperation.statusInCampaignProgressionChanged` | Lead Operation Status In Campaign Progression Changed |
| `leadOperation.interestingMoment` | Lead Operation Interesting Moment |
| `leadOperation.newLead` | Lead Operation New Lead |
| `leadOperation.convertLead` | Lead Operation Convert Lead |
| `leadOperation.callWebhook` | Lead Operation Call Webhook |
| `leadOperation.changeEngagementCampaignCadence` | Change Engagement Campaign Cadence |
| `leadOperation.addToCampaign` | Lead Operation Add To Campaign |
| `leadOperation.changeCampaignStream` | Lead Operation Change Campaign Stream |
| `leadOperation.mergeLeads` | Lead Operation Merge Leads |
| `directMarketing.emailBounced` | Direct Marketing Email Bounced |
| `directMarketing.emailBouncedSoft` | Direct Marketing Email Bounced Soft |
| `directMarketing.emailDelivered` | Direct Marketing Email Delivered |
| `directMarketing.emailUnsubscribed` | Direct Marketing Email Unsubscribed |
| `directMarketing.emailOpened` | Direct Marketing Email Opened |
| `directMarketing.emailClicked` | Direct Marketing Email Clicked |
| `directMarketing.emailSent` | Direct Marketing Email Sent |
| `opportunityEvent.removeFromOpportunity` | Opportunity Event Remove From Opportunity |
| `opportunityEvent.addToOpportunity` | Opportunity Event Add To Opportunity |
| `opportunityEvent.opportunityUpdated` | Opportunity Event Opportunity Updated |
| `inappmessageTracking.dismiss` | inapp message was dimissed |
| `inappmessageTracking.display` | inapp message was displayed |
| `inappmessageTracking.interact` | inapp message was interacted with |
| `media.ping` | Media ping |
| `media.sessionStart` | Media sessionStart |
| `media.play` | Media play |
| `media.bufferStart` | Media bufferStart |
| `media.pauseStart` | Media pauseStart |
| `media.chapterStart` | Media chapterStart |
| `media.chapterSkip` | Media chapterSkip |
| `media.chapterComplete` | Media chapterComplete |
| `media.adStart` | Media adStart |
| `media.adSkip` | Media adSkip |
| `media.adComplete` | Media adComplete |
| `media.adBreakStart` | Media adBreakStart |
| `media.adBreakComplete` | Media adBreakComplete |
| `media.bitrateChange` | Media bitrateChange |
| `media.error` | Media error |
| `media.sessionComplete` | Media sessionComplete |
| `media.sessionEnd` | Media sessionEnd |
| `media.stateStart` | Media stateStart |
| `media.stateEnd` | Media stateEnd |




## xdm:impressions

Count of impressions for a given ad displayed on the network.

`xdm:impressions`
* is optional
* type: Measure
* defined in this schema

### xdm:impressions Type


* [Measure](../../../../datatypes/data/measure.schema.md) – `https://ns.adobe.com/xdm/data/measure`





## xdm:qualityScore

Quality Score of the Keyword assigned by the network - range 1 to 10. This is not an additive measure.

`xdm:qualityScore`
* is optional
* type: Measure
* defined in this schema

### xdm:qualityScore Type


* [Measure](../../../../datatypes/data/measure.schema.md) – `https://ns.adobe.com/xdm/data/measure`





## xdm:searchEngineId
### Search Engine Identifier

The application-specified identifier used to identify the Search Advertising Platform Name.

`xdm:searchEngineId`
* is optional
* type: `integer`
* defined in this schema

### xdm:searchEngineId Type


`integer`






## xdm:timestamp
### Timestamp

The time when an event or observation occurred.

`xdm:timestamp`
* is optional
* type: `string`
* defined in [Time-series Schema](../../../../behaviors/time-series.schema.md#xdmtimestamp)

### xdm:timestamp Type


`string`
* format: `date-time` – date and time (according to [RFC 3339, section 5.6](http://tools.ietf.org/html/rfc3339))






## xdm:topPageBid

Top of the Page Bid Estimator. The measure is computed by the network and is not an additive measure.

`xdm:topPageBid`
* is optional
* type: Measure
* defined in this schema

### xdm:topPageBid Type


* [Measure](../../../../datatypes/data/measure.schema.md) – `https://ns.adobe.com/xdm/data/measure`





## xdm:totalCost

Total Advertising Spend for a given ad displayed on the network. The spend is in the account currency configured on the network.

`xdm:totalCost`
* is optional
* type: Measure
* defined in this schema

### xdm:totalCost Type


* [Measure](../../../../datatypes/data/measure.schema.md) – `https://ns.adobe.com/xdm/data/measure`




