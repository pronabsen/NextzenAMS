---
description: >-
  All API calls can be made using the POST or GET method to
  "https://amsapi.nextzen.com.bd/api/v1/data"! Please see the sample code for
  more details.
---

# Example Parameter

Following [https://amsapi.nextzen.com.bd/api/v1/data](https://amsapi.nextzen.com.bd/api/v1/data).  See Below for an Example Parameter:&#x20;

{% code title="Method - add_employee" %}
```json
{
    "request_type":"add_employee", 
    "api_key":"ZHdfv6GYuNq0sezBpQob9vbGqVtZWZ",
    "signature_type":"card", 
    "username":"example_username", 
    "signature":"1234abcd", 
    "device_id":["EM111111","EM101010"] 
}
```
{% endcode %}

{% code title="Method - remove_employee_from_device" %}
```json
{
    "request_type":"remove_user_from_device", 
    "api_key":"ZHdfv6GYuNq0sezBpQob9vbGqVtZWZ",
    "username":"example_username",
    "device_id":"EM111111" 
}
```
{% endcode %}

{% code title="Method - delete_employee_permanently" %}
```json
{
    "request_type":"delete_employee_permanently", 
    "api_key":"ZHdfv6GYuNq0sezBpQob9vbGqVtZWZ",
    "username":"example_username"
}
```
{% endcode %}

{% code title="Method - employees_list" %}
```json
{
    "request_type":"employees_list", 
    "api_key":"ZHdfv6GYuNq0sezBpQob9vbGqVtZWZ"
}
```
{% endcode %}

{% code title="Method - employees_in_device_list" %}
```json
{
    "request_type":"employees_in_device_list", 
    "api_key":"ZHdfv6GYuNq0sezBpQob9vbGqVtZWZ"
}
```
{% endcode %}

{% code title="Method - device_detail" %}
```json
{
    "request_type":"device_detail", 
    "api_key":"ZHdfv6GYuNq0sezBpQob9vbGqVtZWZ"
}
```
{% endcode %}

{% code title="Method - unsent_log" %}
```json
{
    "request_type":"unsent_log", 
    "api_key":"ZHdfv6GYuNq0sezBpQob9vbGqVtZWZ"
}
```
{% endcode %}

{% code title="Method - set_employee_registration_mode" %}
```json
{
    "request_type":"set_employee_registration_mode", 
    "api_key":"ZHdfv6GYuNq0sezBpQob9vbGqVtZWZ",
    "device_id":"EM111111"
}
```
{% endcode %}

{% code title="Method - log" %}
```json
{
    "request_type":"log", 
    "api_key":"ZHdfv6GYuNq0sezBpQob9vbGqVtZWZ",
    "start_date":"2022-04-04",
    "end_date":"2022-8-29",
    "start_time":"05:49:09",
    "end_time":"05:49:09",
    "access_id":"11301000"
}
```
{% endcode %}
