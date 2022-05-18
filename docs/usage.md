| [Home](https://github.com/fortinet-fortisoar/solution-pack-sunburst-attack/blob/develop/README.md) |
|--------------------------------------------|

# Usage

Refer to [Simulate Scenario documentation](https://github.com/fortinet-fortisoar/solution-pack-soc-simulator/blob/develop/docs/solution-pack-guide.md) to understand how to Simulate and Reset scenarios.

To understand the process FortiSOAR follows to respond to Sunburst attacks, we have included a scenario &mdash; **Sunburst Attack IOC Hunt** with this solution pack. Refer to the section [Phishing Email Scenario](#sunburst-attack-ioc-hunt) to understand how this solution pack's automation addresses your needs.

## Sunburst Attack IOC Hunt

The scenario generates a demo hunt record **Hunt - Sunburst Attack**.

Select **Simulations**.     
On the **Scenario** page, select the checkbox **Sunburst Attack IOC Hunt** and click **Simulate Scenario**.     
Enter a hunt time range when prompted on the **Enter Hunt Time Range** pop-up and click **Submit**.     

Navigate to **Incident Response** > **Hunts** and note the following:
* A demo hunt record &ndash; by the name of **Demo Hunt - Sunburst Attack** &ndash; is created
* This demo hunt record displays a **Hunt Time Range** &ndash; **Hunt Start Date** and **Hunt End Date**
* Launching **Sunburst IOC Hunt** playbook performs the following actions
    - Download IOCs from CSV file
    - Create Indicators
    - Hunt Sunburst Indicators
    - Create an alert of type **Sunburst**