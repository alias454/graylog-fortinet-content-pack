================
graylog-fortinet-content-pack
================

Fortigate UTM content pack contains extractors, a stream, a dashboard displaying the last 24 hours of activity, and a syslog tcp input. This was heavily inspired by another fortigate content pack created by juiceman84, which is located here https://github.com/juiceman84/Fortigate_Content_Pack

note

    See the full `Graylog content pack instructions
    <http://docs.graylog.org/en/2.1/pages/sending_data.html#content-packs>`_.

Known Issues
================
Graylog started processing Fortinet and Cisco logs when using the syslog input type so an alternate content pack was added.
Support using the RawExtractor trying to fix a bug with creation of new sources was submitted by @SmartIdeas01

Provided Content
================

A Dashboard: FortiGate Network and System Activity - Last 24 Hours
A Stream: Networking - Fortinet FW
An Input: fortinet-tcp-input on port 11514
Alternate Input: FortiGate RawExtractor on port 11512
And many extractors 

Setup Notes
================

FortiGate Firewall with SYSLOG configured.

1.  Import the Content Pack
2.  Update the stream rule with your device name
3.  Point FortiGate syslog to Graylog
