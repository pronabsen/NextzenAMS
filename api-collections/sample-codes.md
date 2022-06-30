---
description: >-
  All API calls can be made using the POST or GET method to
  "https://amsapi.nextzen.com.bd/api/v1/data"! Please see the sample code for
  more details.
---

# Sample Codes

Following [https://amsapi.nextzen.com.bd/api/v1/data](https://amsapi.nextzen.com.bd/api/v1/data).  See Below for Sample Codes:&#x20;

{% code title="Python:" %}
```python
import requests

url = "https://amsapi.nextzen.com.bd/data?request_type=log&api_key=M5biUBjMt1cvXeayCizIqY4pAl41YA&date_from=2022-06-01&date_to=2022-07-10&time_from=07:00:00&time_to=21:00:00"

payload={}
headers = {}

response = requests.request("GET", url, headers=headers, data=payload)

print(response.text)

```
{% endcode %}

{% code title="JavaScript: " %}
```javascript
var settings = {
  "url": "https://amsapi.nextzen.com.bd/data?request_type=log&api_key=M5biUBjMt1cvXeayCizIqY4pAl41YA&date_from=2022-06-01&date_to=2022-07-10&time_from=07:00:00&time_to=21:00:00",
  "method": "GET",
  "timeout": 0,
};

$.ajax(settings).done(function (response) {
  console.log(response);
});
```
{% endcode %}

{% code title="PHP - cURL: " %}
```php
<?php

$curl = curl_init();

curl_setopt_array($curl, array(
		CURLOPT_URL => 'https://amsapi.nextzen.com.bd/data?request_type=log&api_key=M5biUBjMt1cvXeayCizIqY4pAl41YA&date_from=2022-06-01&date_to=2022-07-10&time_from=07:00:00&time_to=21:00:00',
		CURLOPT_RETURNTRANSFER => true,
		CURLOPT_ENCODING => '',
		CURLOPT_MAXREDIRS => 10,
		CURLOPT_TIMEOUT => 0,
		CURLOPT_FOLLOWLOCATION => true,
		CURLOPT_HTTP_VERSION => CURL_HTTP_VERSION_1_1,
		CURLOPT_CUSTOMREQUEST => 'GET',
));

$response = curl_exec($curl);

curl_close($curl);
echo $response
```
{% endcode %}

{% code title="C#: " %}
```csharp
var client = new RestClient("https://amsapi.nextzen.com.bd/data?request_type=log&api_key=M5biUBjMt1cvXeayCizIqY4pAl41YA&date_from=2022-06-01&date_to=2022-07-10&time_from=07:00:00&time_to=21:00:00");
client.Timeout = -1;
var request = new RestRequest(Method.GET);
IRestResponse response = client.Execute(request);
Console.WriteLine(response.Content);
```
{% endcode %}

af

{% code title="Java: " %}
```java
import java.io.*;
import okhttp3.*;
public class main {
		public static void main(String []args) throws IOException{
				OkHttpClient client = new OkHttpClient().newBuilder()
						.build();
				Request request = new Request.Builder()
						.url("https://amsapi.nextzen.com.bd/data?request_type=log&api_key=M5biUBjMt1cvXeayCizIqY4pAl41YA&date_from=2022-06-01&date_to=2022-07-10&time_from=07:00:00&time_to=21:00:00")
						.method("GET", null)
						.build();
				Response response = client.newCall(request).execute();
				System.out.println(response.body().string());
		}
}

```
{% endcode %}

{% code title="Dart: " %}
```dart
var request = http.Request('GET', Uri.parse('https://amsapi.nextzen.com.bd/data?request_type=log&api_key=M5biUBjMt1cvXeayCizIqY4pAl41YA&date_from=2022-06-01&date_to=2022-07-10&time_from=07:00:00&time_to=21:00:00'));


http.StreamedResponse response = await request.send();

if (response.statusCode == 200) {
  print(await response.stream.bytesToString());
}
else {
  print(response.reasonPhrase);
}
```
{% endcode %}
