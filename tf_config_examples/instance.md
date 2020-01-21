# OCI

#### authorization_method_id (optional)

|Id|Authorization method|
|-|-|
|1398|ssh keys|
|1399|login&password (default)|

#### ssh_keys_ids (optional)

Shh keys ids array. Required if authorization_method_id is ssh keys.


#### disk_class

|Id|Tier type|
|-|-|
|48|Tier1|
|49|Tier2|
|50|Tier3|
|895|Tier4|
|896|Tier5|


#### ip_address_id (optional)

Ip address that would be attached to instance as main address. If value is not set, new random IP address is created.

#### init_disk_size
        
Disk capacity(in GB).

#### instance_name
        
Name of instance.

#### subregion_id

|Id|Subregion|
|-|-|
|1|PL001|
|4|PL002|
|5|PL003|
|6|PL004|
|7|PL005|


#### template_id

|Id|Tempalte|
|-|-|
|1|Mongo DB|
|58|OpenSUSE|
|63|Ruby on Rails|
|64|Django OCI|
|69|Zimbra|
|80|MS SQL 2012 Standard|
|81|MS SQL 2012 Web|
|82|MS SQL 2012 Express|
|96|FreeBSD 10|
|97|MS SQL 2014 Standard|
|98|Windows Server 2012 R2|
|99|MS SQL 2014 Web|
|101|MS SQL 2014 Express|
|304|Debian 8|
|392|Red Hat Enterprise Linux 6|
|396|Red Hat Enterprise Linux 7|
|514|FreeBSD 11.0|
|624|Windows Server 2016|
|643|MS SQL 2016 Express|
|644|MS SQL 2016 Standard|
|645|MS SQL 2016 Web|
|670|Fedora Server 26|
|678|FreeBSD 11.1|
|764|Ubuntu Server 16.04 LTS|
|765|Debian 9|
|767|CentOS 7|
|771|Fedora Server 27|
|772|OpenSUSE Leap|
|775|pfSense|
|776|Ubuntu Server 18.04 LTS|
|910|Debian 10|
|911|Red Hat Enterprise Linux 8 +|
|926|CentOS 8|
|936|CentOS 6|

#### type_id

Determines instance hardware parameters(CPU & RAM).

|Id|Instance type|
|-|-|
|1047|v1.standard-1.05|
|289|v1.standard-1.09|
|1048|v1.standard-16.16|
|34|v1.standard-2.2|
|1766|v1.standard-24.24|
|35|v1.standard-4.4|
|36|v1.standard-8.8|
|1271|v1.highcpu-16.8|
|1268|v1.highcpu-2.09|
|1269|v1.highcpu-4.2|
|1270|v1.highcpu-8.4|
|1769|v1.highmemory.16.48|
|1770|v1.highmemory.24.48|
|1767|v1.highmemory.4.48|
|1768|v1.highmemory.8.48|
|1263|v1.highmemory-1.4|
|1757|v1.highmemory-16.24|
|1049|v1.highmemory-16.32|
|1050|v1.highmemory-16.64|
|1267|v1.highmemory-16.96|
|1428|v1.highmemory-2.4|
|1264|v1.highmemory-2.8|
|1765|v1.highmemory-24.32|
|1759|v1.highmemory-24.64|
|1265|v1.highmemory-4.16|
|1420|v1.highmemory-4.32|
|1421|v1.highmemory-4.64|
|1423|v1.highmemory-4.8|
|1424|v1.highmemory-8.16|
|1266|v1.highmemory-8.32|
|1422|v1.highmemory-8.64|
|1574|v1.highmemory-8.96|

        
#### init_ip_address_id

Main IP address for this instance.
		

#### isfreemium (optional)

Default value - false. 

#### opn_ids (optional)

Array of OPN ids for this instance.
        
#### ip_address_ids

Array of IP addresses ids to be attached to this instance.