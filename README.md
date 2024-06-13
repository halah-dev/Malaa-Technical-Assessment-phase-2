
# Investor Bulletin Project

![Welcome](./imgs/hello-welcome.gif)

* Run the Code:
  `docker-compose -f dev_setup/docker-compose.yml up --build`
* Start publisher
  `docker exec -it api-container bash`
  `python core/messaging.py`
* Start subscriber
  `docker exec -it api-container bash`
  `python event_subscriber/main.py`
