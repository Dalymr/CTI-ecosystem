My Cybersecurity internship

This Project allows the user to deploy a docker compose of a cyberthreat intelligence ecosystem and response composed of :

- SIEM : Wazuh

- Automation Platform : Shuffle

- CTI DB & Sharing : Opencti and MISP

- Case Managment : TheHive

- Case analysis : Cortex

- CTI Data Feed : Alienvault and MittreAtt&ck


To Deploy simply pull both branches ( main-sec-auto / main-sec-dev ) and use " runcompose.sh " to allow compose to create the containers.

NOTE THAT IN THIS VERSION THE DEPLOYED CONTAINERS HAS A PROXY CONFIG, BE ADVICED TO REMOVE THE HTTP_PROXY ENV VARIABLES IN THE COMPOSE CONFIG FILES .
