fifo_lager
=====

A lager 'template' that includes graylog, logstash, and the required config for cuttlefish.

The following overlays are used:

* `service` - name of the service of thise node
* `log_path` - path of the log file root

Build
-----

    $ rebar3 compile
