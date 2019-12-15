## Create a splunk external script

user agent like 

```text
"Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/78.0.3904.97 Safari/537.36"
"curl/7.64.1"
``` 

transfer to 
```text
"Chrome/78"
"curl/7.64.1"
```



![Final Result](https://raw.githubusercontent.com/yhjhoo/splunk-script/master/final%20result.png)



```text
user_agents.py http_user_agent ua_os_family ua_os_major ua_os_minor ua_os_patch ua_os_patch_minor ua_family ua_major ua_minor ua_patch ua_device
```
