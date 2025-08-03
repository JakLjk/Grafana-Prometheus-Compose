# Grafana-Prometeus-Compose


## General Info
This configuration assumes that initial prometheus config is in the local /etc/prometheus/prometheus.yaml path. 

## Initial setup 
Initial setup has pre-configured exporters for cadvisor (for gathering docker image's information) and node_exporter for monitoring system health

## How to add new exporters
In order to add new exporters, the prometeus config has to be extended with the new job names.

## Caveats
External port for prometheus was changed to 9091 to avoid conflicts.
