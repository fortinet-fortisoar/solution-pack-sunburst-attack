| [Home](https://github.com/fortinet-fortisoar/solution-pack-sunburst-attack/blob/develop/README.md) |
|--------------------------------------------|

# Contents

## Connector(s)

|Connector Name|Description|
| :- | :- |
|Fortinet FortiEDR| This connector facilitates the automated operations related to events, forensics and collectors. |
|Fortinet FortiGate| Fortinet FortiGate enterprise firewall provide high performance, consolidated advanced security and granular visibility for broad protection across the entire digital attack surface. |
|Splunk| Splunk connector allows users to invoke search, fetch events to related search, invoke alert actions, update notables, sync splunk users to FortiSOAR etc. |

> **Warning:** After deployment, this Solution Pack installs or upgrades the stated list of connectors.

## Global Variable(s)

|Global Variable|Description|
| :- | :- |
|`Demo_mode`| Enables playbook to execute a mock output |
|`QRadarTimeZone`| Gets local time zone while executing the Splunk query|

## Record Set

|Record Set| Description|
|:-|:-|
|Scenario: Sunburst Attack IOC Hunt| The scenario generates a demo hunt record and, as part of this use case, initiates a hunt of IOCs within a user-specified time range. |

## Playbook Collection

|05 - Hunt - Sunburst (3)|
| :- |

**Playbook Name**|**Description**|
 :- | :- |
Hunt Sunburst IOCs|Downloads IOCs from the threat intelligence feeds and hunts them|
Hunt Sunburst Indicator|Performs a hunt on the specified Sunburst indicators using Splunk and FortiEDR|
Block Sunburst Indicators|Blocks Sunburst indicators on Fortinet FortiGate and Fortinet FortiEDR|
Generate Demo Hunt Record|Generates Demo Hunt Record for Sunburst Attack IOC Hunt|

> **Warning:** It is recommended to clone these Playbooks before any customizations to avoid loss of information while upgrading the Solution Pack.
