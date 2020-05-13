# tmos_azure_api_host_routes
A list of TMSH management-route commands for reaching Azure Public API IP addresses (IPv4)

If you have a default route on an F5 BIG-IP in Microsoft's Azure cloud platform, management traffic will use that route. In some configurations, the data plane interfaces may not have access to the Azure API public IP addresses, which will break the F5 Cloud Failover Extension. 

To install, simply cut/paste the commands list in the file into the Traffic Management SHell (TMSH) on the BIG-IP's CLI.

F5 Management routing: https://support.f5.com/csp/article/K13284
Source of Azure routes: https://www.microsoft.com/en-us/download/details.aspx?id=56519

Currently updated as of 5/11/2020 - this list will not be automatically or routinely updated, so be sure to download the latest list from the link above before pasting.
