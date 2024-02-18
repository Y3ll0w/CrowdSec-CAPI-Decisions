# CrowdSec CAPI Decisions

**This repository always provides up-to-date lists of malicious IPv4 and IPv6 addresses from the CrowdSec CAPI which collects incident data from its users to create community-fueled block lists.**

---

➤ Automatically updates once every 2 hours ([Recommended minimum by CrowdSec](https://doc.crowdsec.net/docs/getting_started/install_softagent/#php-remediation-engine))  
➤ Maximum of 3000 unique IPs per file    
➤ It contains a mix of mostly IPv4 addresses with some IPv6 addresses    
➤ Can be used as import source for Fail2Ban or CrowdSec (without participating in the information sharing)   

---

| **Scenario** |  **JSON**    | **TXT** |
|:-|:--|:-|
| [crowdsecurity/nginx-req-limit-exceeded](https://app.crowdsec.net/hub/author/crowdsecurity/configurations/nginx-req-limit-exceeded) | [JSON](https://raw.githubusercontent.com/Y3ll0w/CrowdSec-CAPI-Decisions/main/nginx-req-limit-exceeded.json)  | [TXT](https://raw.githubusercontent.com/Y3ll0w/CrowdSec-CAPI-Decisions/main/nginx-req-limit-exceeded.json.txt)  |
| [crowdsecurity/http-generic-bf](https://app.crowdsec.net/hub/author/crowdsecurity/configurations/http-generic-bf) | [JSON](https://raw.githubusercontent.com/Y3ll0w/CrowdSec-CAPI-Decisions/main/http-generic-bf.json)  | [TXT](https://raw.githubusercontent.com/Y3ll0w/CrowdSec-CAPI-Decisions/main/http-generic-bf.json.txt)  |
| [crowdsecurity/mysql-bf](https://app.crowdsec.net/hub/author/crowdsecurity/configurations/mysql-bf) | [JSON](https://raw.githubusercontent.com/Y3ll0w/CrowdSec-CAPI-Decisions/main/mysql-bf.json)  | [TXT](https://raw.githubusercontent.com/Y3ll0w/CrowdSec-CAPI-Decisions/main/mysql-bf.json.txt)  |
| [crowdsecurity/ssh-bf](https://app.crowdsec.net/hub/author/crowdsecurity/configurations/ssh-bf) | [JSON](https://raw.githubusercontent.com/Y3ll0w/CrowdSec-CAPI-Decisions/main/ssh-bf.json)  | [TXT](https://raw.githubusercontent.com/Y3ll0w/CrowdSec-CAPI-Decisions/main/ssh-bf.json.txt)  |

---

Formats:
- JSON (raw output from the CAPI Endpoint)
- TXT (IPv4 & IPv6 list, no decision metadata)

