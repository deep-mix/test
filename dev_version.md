# Dev Version



#### Available methods

* DEL - /targets/:id
* DEL - /themes/:id
* Get all currencys
* GET - /targets
* Toolbar GET
* CONFIRM AUTH
* HTML AUTH
* Test PAY
* POST - /targets/
* GET - /targets/:id
* GET -  /themes
* GET - /themes/:id
* Toolbar POST
* Test PAY index

## [DELETE] DEL - /targets/:id

Delete specific target and all of it relathionships

#### Description

* **Method:** DELETE
* **URL:** /api/v2/targets/%7B%7Btarget_id%7D%7D

#### Query parameters

*No query parameters accepted.*

#### Body payload

*No body parameters accepted.*

#### Example responses

*No example responses saved.*

## [DELETE] DEL - /themes/:id

Delete a specific theme

#### Description

* **Method:** DELETE
* **URL:** /api/v2/themes/%7B%7Btheme_id%7D%7D

#### Query parameters

*No query parameters accepted.*

#### Body payload

*No body parameters accepted.*

#### Example responses

*No example responses saved.*

## [GET] Get all currencys



#### Description

* **Method:** GET
* **URL:** /api/v2/currency

#### Query parameters

*No query parameters accepted.*

#### Body payload

*No body parameters accepted.*

#### Example responses

*No example responses saved.*

## [GET] GET - /targets

List all targets

#### Description

* **Method:** GET
* **URL:** /api/v2/targets

#### Query parameters

*No query parameters accepted.*

#### Body payload

*No body parameters accepted.*

#### Example responses

*No example responses saved.*

## [GET] Toolbar GET

require domain name

#### Description

* **Method:** GET
* **URL:** /api/v2/toolbar/json

#### Query parameters

* **url:** https://github.com/chrisbjr/api-guard/tree/v1.0

#### Body payload

*No body parameters accepted.*

#### Example responses

*No example responses saved.*

## [GET] CONFIRM AUTH



#### Description

* **Method:** GET
* **URL:** /api/v1/self-user

#### Query parameters

*No query parameters accepted.*

#### Body payload

*No body parameters accepted.*

#### Example responses

*No example responses saved.*

## [POST] HTML AUTH

Login to Tarzan

#### Description

* **Method:** POST
* **URL:** /authentication/store

#### Query parameters

* **email:** arman.arojan@caliberi.com
,* **email:** arman.arojan@caliberi.com
* **password:** password

#### Body payload

*No body parameters accepted.*

#### Example responses

*No example responses saved.*

## [POST] Test PAY



#### Description

* **Method:** POST
* **URL:** /api/v2/paypal

#### Query parameters

* **action:** classic

#### Body payload

*No body parameters accepted.*

#### Example responses

*No example responses saved.*

## [POST] POST - /targets/

Create new targets

#### Description

* **Method:** POST
* **URL:** /api/v2/targets

#### Query parameters

*No query parameters accepted.*

#### Body payload

```json
{
    "campaignBudget": "10000",
    "campaign_id": 1,
    "category_id": 1,
    "contentBudget": 2500,
    "linkDevBudget": 7500,
    "date_start": "2016-03-01",
    "date_end": "2016-06-30",
    "objects": [
        {
            "cqs": "1",
            "priority_id": 1,
            "target_url": "target url 1",
            "theme_id": 649,
            "topic": "topic 1"
        },
        {
            "cqs": "1",
            "priority_id": 1,
            "target_url": "target url 2",
            "theme_id": 649,
            "topic": "topic 2"
        },
        {
            "cqs": "1",
            "priority_id": 1,
            "target_url": "target url 3",
            "theme_id": 649,
            "topic": "topic 3"
        },
        {
            "cqs": "1",
            "priority_id": 1,
            "target_url": "target url 4",
            "theme_id": 804,
            "topic": "topic 4"
        },
        {
            "cqs": "1",
            "priority_id": 1,
            "target_url": "target url 5",
            "theme_id": 804,
            "topic": "topic 5"
        },
        {
            "cqs": "1",
            "priority_id": 1,
            "target_url": "target url 6",
            "theme_id": 615,
            "topic": "topic 5"
        },
        {
            "cqs": "1",
            "priority_id": 1,
            "target_url": "target url 7",
            "theme_id": 615,
            "topic": "topic 8"
        },
        {
            "cqs": "1",
            "priority_id": 1,
            "target_url": "target url 8",
            "theme_id": 615,
            "topic": "topic 8"
        }
    ],
    "themes": [
        {
            "id": 649,
            "theme_budget": "2500.00",
            "theme_title": "theme 1"
        },
        {
            "id": 804,
            "theme_budget": "2500.00",
            "theme_title": "theme 2"
        },
        {
            "id": 615,
            "theme_budget": "2500.00",
            "theme_title": "theme 3"
        }
    ],
    "guidelines": "test text for guidelinessss"
}
```

#### Example responses

*No example responses saved.*

## [GET] GET - /targets/:id

View details of a specific target

#### Description

* **Method:** GET
* **URL:** /api/v2/targets/%7B%7Btarget_id%7D%7D

#### Query parameters

*No query parameters accepted.*

#### Body payload

*No body parameters accepted.*

#### Example responses

*No example responses saved.*

## [GET] GET -  /themes

List all themes

#### Description

* **Method:** GET
* **URL:** /api/v2/themes

#### Query parameters

*No query parameters accepted.*

#### Body payload

*No body parameters accepted.*

#### Example responses

*No example responses saved.*

## [GET] GET - /themes/:id

Get details for a specific theme

#### Description

* **Method:** GET
* **URL:** /api/v2/themes/%7B%7Btheme_id%7D%7D

#### Query parameters

*No query parameters accepted.*

#### Body payload

*No body parameters accepted.*

#### Example responses

*No example responses saved.*

## [POST] Toolbar POST

require domain name

#### Description

* **Method:** POST
* **URL:** /api/v2/toolbar/json

#### Query parameters

* **url:** https://github.com/chrisbjr/api-guard/tree/v1.0

#### Body payload

*No body parameters accepted.*

#### Example responses

*No example responses saved.*

## [GET] Test PAY index



#### Description

* **Method:** GET
* **URL:** /api/v2/paypal

#### Query parameters

*No query parameters accepted.*

#### Body payload

*No body parameters accepted.*

#### Example responses

##### paypal 589009

```json
[
    {
        "payment_id": 13217,
        "response": {
            "responseEnvelope": {
                "timestamp": "2015-10-12T04:42:36.831-07:00",
                "ack": "Failure",
                "correlationId": "acacc4b2bdf01",
                "build": "17820627"
            },
            "payKey": null,
            "paymentExecStatus": null,
            "payErrorList": null,
            "paymentInfoList": null,
            "sender": null,
            "defaultFundingPlan": null,
            "warningDataList": null,
            "error": [
                {
                    "errorId": "589009",
                    "domain": "PLATFORM",
                    "subdomain": "Application",
                    "severity": "Error",
                    "category": "Application",
                    "message": "The payment can not be processed because no payment source is available",
                    "exceptionId": null,
                    "parameter": [
                        {
                            "name": null,
                            "value": "GetSplitFundingPlan did not return a funding plan"
                        }
                    ]
                }
            ]
        }
    }
]
```
##### paypal 589009

```json
[
    {
        "payment_id": 13217,
        "response": {
            "responseEnvelope": {
                "timestamp": "2015-10-12T04:42:36.831-07:00",
                "ack": "Failure",
                "correlationId": "acacc4b2bdf01",
                "build": "17820627"
            },
            "payKey": null,
            "paymentExecStatus": null,
            "payErrorList": null,
            "paymentInfoList": null,
            "sender": null,
            "defaultFundingPlan": null,
            "warningDataList": null,
            "error": [
                {
                    "errorId": "589009",
                    "domain": "PLATFORM",
                    "subdomain": "Application",
                    "severity": "Error",
                    "category": "Application",
                    "message": "The payment can not be processed because no payment source is available",
                    "exceptionId": null,
                    "parameter": [
                        {
                            "name": null,
                            "value": "GetSplitFundingPlan did not return a funding plan"
                        }
                    ]
                }
            ]
        }
    }
]
```

