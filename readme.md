# Turbonomic and Envizi Integration - info


## Login

URL : https://sales1.demo.turbonomic.com/api/v3/login?hateoas=true

<img src="images/img01.png">
<img src="images/img02.png">
<img src="images/img03.png">

#### CURL

```
curl --location 'https://sales1.demo.turbonomic.com/api/v3/login?hateoas=true' \
--header 'Cookie: JSESSIONID=node018kipht4j2vt81gsh6k21q42b928661.node0' \
--form 'username="myobserver"' \
--form 'password="xxxxxxx"'

```

## Data Center

URL : https://sales1.demo.turbonomic.com/api/v3/search?types=DataCenter

<img src="images/img11.png">
<img src="images/img12.png">

Output file : <a href="./files/11-datacenter.json">Link</a>

#### CURL

```
curl --location 'https://sales1.demo.turbonomic.com/api/v3/search?types=DataCenter' \
--header 'Cookie: JSESSIONID=node018kipht4j2vt81gsh6k21q42b928661.node0'

```



## Supplychains

URL : https://sales1.demo.turbonomic.com/api/v3/supplychains?environment_type=ONPREM&uuids=75703516241553

<img src="images/img21.png">

Output file : <a href="./files/21-supplychain.json">Link</a>


#### CURL

```
curl --location 'https://sales1.demo.turbonomic.com/api/v3/supplychains?environment_type=ONPREM&uuids=75703516241553' \
--header 'Cookie: JSESSIONID=node018kipht4j2vt81gsh6k21q42b928661.node0'

```



## Entities

URL : https://sales1.demo.turbonomic.com/api/v3/entities/75703516241553/stats

<img src="images/img31.png">

Output file : <a href="./files/31-entities.json">Link</a>


#### CURL

```
curl --location 'https://sales1.demo.turbonomic.com/api/v3/entities/75703516241553/stats' \
--header 'Cookie: JSESSIONID=node018kipht4j2vt81gsh6k21q42b928661.node0'

```
