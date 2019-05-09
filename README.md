# Zabbix-Mikrotik-OSPF-JSON

The Zabbix Mikrotik OSPF template for 4.0, which uses LLD, JSON, SSH for connection to Mikrotik router wihout externel scripts.
Discovers OSPF neighbors and monitors STATE and changes.

This template needs changing macroses:
{$MIKROTIK_SSH_PASS}
{$MIKROTIK_SSH_PORT}
{$MIKROTIK_SSH_USER}
