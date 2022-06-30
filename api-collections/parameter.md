---
description: >-
  All API calls can be made using the POST or GET method to
  "https://amsapi.nextzen.com.bd/api/v1/data"! Please see the sample code for
  more details.
---

# Parameter Details

Following [https://amsapi.nextzen.com.bd/api/v1/data](https://amsapi.nextzen.com.bd/api/v1/data) to run perfectly, need some Parameter.  See Below for Parameter Details:&#x20;

| Parameter       | Details                                                                                                       |
| --------------- | ------------------------------------------------------------------------------------------------------------- |
| request\_type   | Type of Request Method                                                                                        |
| api\_key        | Contact the Nextzen AMS system to get yours Auth API Key                                                      |
| date\_from      | <p>Date since which user logs are to be obtained. </p><p>Example: YYYY-mm-dd ( Need Only for log method )</p> |
| date\_to        | <p>Date until which user logs are to be obtained.</p><p>Example: YYYY-mm-dd ( Need Only for log method )</p>  |
| access\_id      | Unique access log ID till that user logs are already obtained. Example: 777333 ( Need Only for log method )   |
| username        | Unique username of the employee to add/delete ( for add\_employee & remove\_employee\_from\_device )          |
| signature       | Unique signature of the employee which is to be added / removed / updated ( for add\_employee )               |
| signature\_type | Always cards                                                                                                  |
