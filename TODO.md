### TODO

* create default /etc/sensu/config.json
* check changes sensu before restart
* refactor sensu "sensu-server" and common "sensu-client" roles
* send sensu check logs to fluentd
* configure fluentd with elasticsearch
+ send emails when errors logs
* install kibana
* add checks redis, rabbitmq, process, system, sensu, security
* enable by default start sensu
* set EMBEDDED_RUBY=true into /etc/default/sensu
* reduce times to do apt update_cache=yes
* check update sensu plugins
* create submodules for each role
