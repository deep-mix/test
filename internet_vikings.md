# Internet Vikings



#### Available methods

* Crawl 5 kewords
* /serp/crawl
* /keywords/:id
* List Campaigns
* /campaigns/
* /campaigns/:campaign_id/keywords 
* Serp
* /campaigns/:campaign_id/keywords/:keyword_id 
* Rank
* AUTH
* /campaigns/:campaign_id/keywords 
* /campaigns/:campaign_id
* /campaigns/:campaign_id/keywords/count 
* /campaigns
* /keywords/:keyword
* /searchengines
* /keywords/
* /keywords/count 
* /searchengines/:id
* /keywords/ 

## [POST] Crawl 5 kewords



#### Description

* **Method:** POST
* **URL:** /serp/crawl

#### Query parameters

*No query parameters accepted.*

#### Body payload

```json
[
    {
        "custom_id": "caliber-interactive",
        "searchengine": "google",
        "language": "en",
        "country": "GB",
        "keyword": "cheap+holidays",
        "device": "DESKTOP-CHROME",
        "normal_pages": 10,
        "pad_pages": 1,
        "result_format": [
            "json"
        ]
    },
    {
        "custom_id": "caliber-interactive",
        "searchengine": "google",
        "language": "en",
        "country": "GB",
        "keyword": "holidays",
        "device": "DESKTOP-CHROME",
        "normal_pages": 10,
        "pad_pages": 1,
        "result_format": [
            "json"
        ]
    },
    {
        "custom_id": "caliber-interactive",
        "searchengine": "google",
        "language": "en",
        "country": "GB",
        "keyword": "all+inclusive+holidays",
        "device": "DESKTOP-CHROME",
        "normal_pages": 10,
        "pad_pages": 1,
        "result_format": [
            "json"
        ]
    },
    {
        "custom_id": "caliber-interactive",
        "searchengine": "google",
        "language": "en",
        "country": "GB",
        "keyword": "villa+holidays",
        "device": "DESKTOP-CHROME",
        "normal_pages": 10,
        "pad_pages": 1,
        "result_format": [
            "json"
        ]
    },
    {
        "custom_id": "caliber-interactive",
        "searchengine": "google",
        "language": "en",
        "country": "GB",
        "keyword": "package+holidays",
        "device": "DESKTOP-CHROME",
        "normal_pages": 10,
        "pad_pages": 1,
        "result_format": [
            "json"
        ]
    }
]
```

#### Example responses

*No example responses saved.*

## [POST] /serp/crawl



#### Description

* **Method:** POST
* **URL:** /serp/crawl

#### Query parameters

*No query parameters accepted.*

#### Body payload

```json
[
    {
        "custom_id": "caliber-interactive",
        "searchengine": "google",
        "language": "en",
        "country": "GB",
        "keyword": "cheap+holidays",
        "device": "DESKTOP-CHROME",
        "normal_pages": 10,
        "pad_pages": 1,
        "result_format": [
            "json"
        ]
    }
]
```

#### Example responses

*No example responses saved.*

## [GET] /keywords/:id

Gets information about a specific keyword 

#### Description

* **Method:** GET
* **URL:** /v2/%7B%7Biv_keyword%7D%7D/49700214

#### Query parameters

* **api_username:** {{iv_username}}
,* **api_username:** {{iv_username}}
* **api_key:** {{iv_password}}

#### Body payload

*No body parameters accepted.*

#### Example responses

*No example responses saved.*

## [GET] List Campaigns



#### Description

* **Method:** GET
* **URL:** /v2/campaigns

#### Query parameters

* **api_username:** nick.barratt@caliberi.com
,* **api_username:** nick.barratt@caliberi.com
* **api_key:** 75043448-db10-11e5-866a-8bae884efff9

#### Body payload

*No body parameters accepted.*

#### Example responses

*No example responses saved.*

## [POST] /campaigns/

Parameters: 
● name 
● searchengine_id 
 
Creates a new campaign for the specified search engine. 

#### Description

* **Method:** POST
* **URL:** /v2/%7B%7Biv_campaign%7D%7D

#### Query parameters

* **api_username:** {{iv_username}}
,* **api_username:** {{iv_username}}
* **api_key:** {{iv_password}}
,* **api_username:** {{iv_username}}
* **api_key:** {{iv_password}}
* **name:** MTR - local
,* **api_username:** {{iv_username}}
* **api_key:** {{iv_password}}
* **name:** MTR - local
* **searchengine_id:** {{iv_default_searchengine_id}}

#### Body payload

*No body parameters accepted.*

#### Example responses

*No example responses saved.*

## [POST] /campaigns/:campaign_id/keywords 

Parameters: 
● keyword 
● interval (daily, weekly, monthly) 
 
Adds a keyword to a campaign 

#### Description

* **Method:** POST
* **URL:** /v2/%7B%7Biv_campaign%7D%7D/10299/keywords

#### Query parameters

* **api_username:** {{iv_username}}
,* **api_username:** {{iv_username}}
* **api_key:** {{iv_password}}
,* **api_username:** {{iv_username}}
* **api_key:** {{iv_password}}
* **keyword:** used wolverhampton
,* **api_username:** {{iv_username}}
* **api_key:** {{iv_password}}
* **keyword:** used wolverhampton
* **interval:** daily

#### Body payload

*No body parameters accepted.*

#### Example responses

*No example responses saved.*

## [GET] Serp



#### Description

* **Method:** GET
* **URL:** /v2/serp

#### Query parameters

* **api_username:** nick.barratt@caliberi.com
,* **api_username:** nick.barratt@caliberi.com
* **api_key:** 75043448-db10-11e5-866a-8bae884efff9
,* **api_username:** nick.barratt@caliberi.com
* **api_key:** 75043448-db10-11e5-866a-8bae884efff9
* **keyword:** laptops
,* **api_username:** nick.barratt@caliberi.com
* **api_key:** 75043448-db10-11e5-866a-8bae884efff9
* **keyword:** laptops
* **searchengine_id:** 11
,* **api_username:** nick.barratt@caliberi.com
* **api_key:** 75043448-db10-11e5-866a-8bae884efff9
* **keyword:** laptops
* **searchengine_id:** 11
* **date:** 2016-03-01

#### Body payload

*No body parameters accepted.*

#### Example responses

*No example responses saved.*

## [GET] /campaigns/:campaign_id/keywords/:keyword_id 

Gets information about a specific keyword connected to a campaign 

#### Description

* **Method:** GET
* **URL:** /v2/%7B%7Biv_campaign%7D%7D/10299/keywords/138019492

#### Query parameters

* **api_username:** {{iv_username}}
,* **api_username:** {{iv_username}}
* **api_key:** {{iv_password}}

#### Body payload

*No body parameters accepted.*

#### Example responses

*No example responses saved.*

## [GET] Rank



#### Description

* **Method:** GET
* **URL:** /v2/rank

#### Query parameters

* **api_username:** nick.barratt@caliberi.com
,* **api_username:** nick.barratt@caliberi.com
* **api_key:** 75043448-db10-11e5-866a-8bae884efff9
,* **api_username:** nick.barratt@caliberi.com
* **api_key:** 75043448-db10-11e5-866a-8bae884efff9
* **domain:** http://www.tesco.com
,* **api_username:** nick.barratt@caliberi.com
* **api_key:** 75043448-db10-11e5-866a-8bae884efff9
* **domain:** http://www.tesco.com
* **keyword:** laptops
,* **api_username:** nick.barratt@caliberi.com
* **api_key:** 75043448-db10-11e5-866a-8bae884efff9
* **domain:** http://www.tesco.com
* **keyword:** laptops
* **searchengine_id:** 11
,* **api_username:** nick.barratt@caliberi.com
* **api_key:** 75043448-db10-11e5-866a-8bae884efff9
* **domain:** http://www.tesco.com
* **keyword:** laptops
* **searchengine_id:** 11
* **only_organic:** true
,* **api_username:** nick.barratt@caliberi.com
* **api_key:** 75043448-db10-11e5-866a-8bae884efff9
* **domain:** http://www.tesco.com
* **keyword:** laptops
* **searchengine_id:** 11
* **only_organic:** true
* **include_href:** true

#### Body payload

*No body parameters accepted.*

#### Example responses

*No example responses saved.*

## [GET] AUTH



#### Description

* **Method:** GET
* **URL:** /

#### Query parameters

*No query parameters accepted.*

#### Body payload

*No body parameters accepted.*

#### Example responses

*No example responses saved.*

## [GET] /campaigns/:campaign_id/keywords 

Parameters: 
● updated_at_min 
● updated_at_max 
Supports pagination. 
Gets all keywords connected to the specified campaign 

#### Description

* **Method:** GET
* **URL:** /v2/%7B%7Biv_campaign%7D%7D/10300/keywords

#### Query parameters

* **api_username:** {{iv_username}}
,* **api_username:** {{iv_username}}
* **api_key:** {{iv_password}}

#### Body payload

*No body parameters accepted.*

#### Example responses

*No example responses saved.*

## [GET] /campaigns/:campaign_id

Gets information about a specific campaign 

#### Description

* **Method:** GET
* **URL:** /v2/%7B%7Biv_campaign%7D%7D/10299

#### Query parameters

* **api_username:** {{iv_username}}
,* **api_username:** {{iv_username}}
* **api_key:** {{iv_password}}

#### Body payload

*No body parameters accepted.*

#### Example responses

*No example responses saved.*

## [GET] /campaigns/:campaign_id/keywords/count 

Returns a count of all keywords connected to the specified campaign 

#### Description

* **Method:** GET
* **URL:** /v2/%7B%7Biv_campaign%7D%7D/10299/keywords/count

#### Query parameters

* **api_username:** {{iv_username}}
,* **api_username:** {{iv_username}}
* **api_key:** {{iv_password}}

#### Body payload

*No body parameters accepted.*

#### Example responses

*No example responses saved.*

## [GET] /campaigns



#### Description

* **Method:** GET
* **URL:** /v2/%7B%7Biv_campaign%7D%7D

#### Query parameters

* **api_username:** {{iv_username}}
,* **api_username:** {{iv_username}}
* **api_key:** {{iv_password}}

#### Body payload

*No body parameters accepted.*

#### Example responses

*No example responses saved.*

## [GET] /keywords/:keyword

Parameters: 
● searchengine_id 
Searches for a keyword in all campaigns and returns a single result if found.

#### Description

* **Method:** GET
* **URL:** /v2/%7B%7Biv_keyword%7D%7D/49700214

#### Query parameters

* **api_username:** {{iv_username}}
,* **api_username:** {{iv_username}}
* **api_key:** {{iv_password}}

#### Body payload

*No body parameters accepted.*

#### Example responses

*No example responses saved.*

## [GET] /searchengines

Lists all available search engines 
 
The result returns a key called “device” which indicates which sort of device to identify as when 
crawling. 

#### Description

* **Method:** GET
* **URL:** /v2/%7B%7Biv_search%7D%7D

#### Query parameters

* **api_username:** {{iv_username}}
,* **api_username:** {{iv_username}}
* **api_key:** {{iv_password}}

#### Body payload

*No body parameters accepted.*

#### Example responses

*No example responses saved.*

## [POST] /keywords/

Parameters: 
● keyword 
● campaign_id 
 
Adds a keyword to a campaign 

#### Description

* **Method:** POST
* **URL:** /v2/%7B%7Biv_keyword%7D%7D

#### Query parameters

* **api_username:** {{iv_username}}
,* **api_username:** {{iv_username}}
* **api_key:** {{iv_password}}
,* **api_username:** {{iv_username}}
* **api_key:** {{iv_password}}
* **keyword:** ford fiesta
,* **api_username:** {{iv_username}}
* **api_key:** {{iv_password}}
* **keyword:** ford fiesta
* **campaign_id:** 10300

#### Body payload

*No body parameters accepted.*

#### Example responses

*No example responses saved.*

## [GET] /keywords/count 

Returns a count of all keywords connected to your campaigns 

#### Description

* **Method:** GET
* **URL:** /v2/%7B%7Biv_keyword%7D%7D/count

#### Query parameters

* **api_username:** {{iv_username}}
,* **api_username:** {{iv_username}}
* **api_key:** {{iv_password}}

#### Body payload

*No body parameters accepted.*

#### Example responses

*No example responses saved.*

## [GET] /searchengines/:id

Gets a search engine with a specific id 

#### Description

* **Method:** GET
* **URL:** /v2/%7B%7Biv_search%7D%7D/11

#### Query parameters

* **api_username:** {{iv_username}}
,* **api_username:** {{iv_username}}
* **api_key:** {{iv_password}}

#### Body payload

*No body parameters accepted.*

#### Example responses

*No example responses saved.*

## [GET] /keywords/ 

Parameters: 
● updated_at_min 
● updated_at_max 
Supports pagination.
Lists all keywords currently connected to your campaigns 

#### Description

* **Method:** GET
* **URL:** /v2/%7B%7Biv_keyword%7D%7D

#### Query parameters

* **api_username:** {{iv_username}}
,* **api_username:** {{iv_username}}
* **api_key:** {{iv_password}}

#### Body payload

*No body parameters accepted.*

#### Example responses

*No example responses saved.*

