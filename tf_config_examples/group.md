# Group

#### group_name

Name of OCI group.

#### affinity_rule_type_id

|Id|Affinity type|
|-|-|
|1403|No separation (default)|
|1404|Minimize separation|
|1405|Maximize separation|

#### group_instance_ip_ids

Map of instances ids as keys and IP addresses as values. If value is 0, dafault instance IP address is used.

```
group_instance_ip_ids = {
    "12345":0
}
```
