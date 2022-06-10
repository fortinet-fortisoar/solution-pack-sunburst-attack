| [Home](https://github.com/fortinet-fortisoar/solution-pack-sunburst-attack/blob/develop/README.md) |
|--------------------------------------------|

# Installation

To install a solution pack, click **Content Hub** > **Discover**.   
From the list of solution pack that appears, search for and select **Sunburst Attack**.    
Click the **Sunburst Attack** solution pack card.   
Click **Install** on the bottom to begin installation.

> All [dependencies](#prerequisites), if not already installed, are installed automatically.

## Prerequisites

The **Sunburst Attack** solution pack depends on the following solution packs.

| **Solution Pack Name** | **Purpose**   |
| :--------------------- | :--------------------------------------- |
| SOAR Framework | Required for Incident Response modules   |
| SOC Simulator  | Required for Scenario Module and SOC Simulator connector |

# Configuration

For optimal performance of **Sunburst Attack** solution pack, you must configure a data ingestion module such as:

* An EDR solution
    * To configure and use the FortiEDR connector as a source of data ingestion, refer to [Configuring Fortinet FortiEDR](https://docs.fortinet.com/document/fortisoar/1.3.0/fortinet-fortiedr/161/fortinet-fortiedr-v1-3-0)
* A SIEM solution
    * To configure and use the Fortinet FortiSIEM connector as a source of data ingestion, refer to [Configuring Fortinet FortiSIEM](https://docs.fortinet.com/document/fortisoar/4.3.2/fortinet-fortisiem/278/fortinet-fortisiem-v4-3-2)