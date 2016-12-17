================
graylog-fortinet-content-pack
================

Fortigate UTM content pack contains extractors, a stream, a dashboard displaying the last 24 hours of activity, and a syslog tcp input.

.. note::

    See the full `Graylog content pack instructions
    <http://docs.graylog.org/en/2.1/pages/sending_data.html#content-packs>`_.

This content pack provides
================

A Dashboard: FortiGate Network and System Activity - Last 24 Hours
A Stream: Networking - Fortinet FW
An Input: fortinet-tcp-input on port 11514
And many extractors

Requirements
================

FortiGate Firewall with SYSLOG configured.

1.  Import the Content Pack
2.  Point FortiGate syslog to Graylog

.. contents::
    :local:
