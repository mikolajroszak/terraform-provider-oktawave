# Load balancer

#### group_id

Instances group id.

#### port_number (optional)

Internal port number.

#### ssl_enabled (optional)

Boolean value. Enables SSL on load balancer.

#### service_type_id (optional)

|Id|Service type|
|-|-|
|43|HTTP (80) - default|
|44|HTTPS (443)|
|45|SMTP (25)|
|155|Specified port|

#### target_port_number (optional)

Service port number. Required if service_type_id is set to 155.

#### session_persistence_type_id (optional)

|Id|Session persistence type|
|-|-|
|46|Persistance by source IP - default|
|280|Persistance by Cookie|
|47|None persistance|
	
#### load_balancer_algorithm_id (optional)

|Id|Load balancer algorithm|
|-|-|
|281|Least Connection|
|282|Least Response Time|
|288|Source IP Hash|
|612|Round Robin - default|
	
#### ip_version_id (optional)

|Id|Ip version|
|-|-|
|115|IPv4 - default|
|116|IPv6|
	
#### health_check_enabled (optional)

Boolean value, dafault: true. Enables healthcheck for this LB.

#### common_persistence_for_http_and_https_enabled (optional)

Boolean value, default: true.

