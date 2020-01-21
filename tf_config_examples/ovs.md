# OVS

#### disk_name

Name of volume.

#### space_capacity (optional)

Volume capacity. Default 5GB.

#### tier_id

|Id|Tier type|
|-|-|
|48|Tier1|
|49|Tier2|
|50|Tier3|
|895|Tier4|
|896|Tier5|

#### is_shared (optional)

Determines if volume can be shared between multiple instances. Default false.
    
#### shared_disk_type_id

Required only if volume is shared. Defines filesystem type.
    
|Id|Type|
|-|-|
|1411|LINUX (OCFS/GFS)|
|1412|Windows (MSCS)|

#### subregion_id

|Id|Subregion|
|-|-|
|1|PL001|
|4|PL002|
|5|PL003|
|6|PL004|
|7|PL005|

#### connections_with_instanceids (optional)

Array of instances ids attached to this volume.

#### isfreemium (optional)

Default false.
