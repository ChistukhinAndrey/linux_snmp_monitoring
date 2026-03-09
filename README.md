# Linux Server Monitoring via SNMP (Zabbix + Grafana)

## Description

This project implements a Linux server monitoring system using:

- Zabbix
- Grafana
- SNMP protocol

The monitoring stack is deployed using Docker containers.

## Technologies

- Debian Linux
- Docker
- Zabbix
- Grafana
- SNMP

## Architecture

Target server (Debian) runs SNMP agent.

Zabbix server polls SNMP metrics.

Grafana visualizes the metrics.

## Services

Zabbix Web:
http://localhost:8080

Grafana:
http://localhost:3000

Default credentials

Zabbix
Admin / zabbix

Grafana
admin / admin

## Run project

Clone repository
