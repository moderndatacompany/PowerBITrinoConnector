# DataOS Connector for Power BI

## **Power BI Trino**

---

A Microsoft Power BI Custom Connector for importing DataOS data into Power BI to interactively transform, visualize and analyze data. 

The connector communicates directly with the DataOS client REST API powered by [Trino](https://trino.io/docs/current/develop/client-protocol.html) to retrieve data and provides some parameters to configure.

## **Usage: Power BI Desktop with DataOS authentication**

---
Please use this installer to use DataOS PowerBI Connector- [installer](https://github.com/moderndatacompany/PowerBITrinoConnector/blob/d08e3fa26a124d1a16147aa46ff3ddf4ef1fa7be/Installer/DataOS%20Connector%20For%20PowerBI.msi)


The .mez file generated by the compiling the code has been used to self-sign and generate the .pqx file and further creating the msi installer.
Please find more details on how to self-sign and generate the .pqx file here- https://learn.microsoft.com/en-us/power-query/handling-connector-signing.

This will allow user to to keep the Security settings on PBI Desktop app for allowing only Microsoft certified and other trusted connectors.


Now, in order for Users' PC to know that our connector is trusted, certificate thumbprint is needed. This thumbprint has to be added to windows registry on the user's PC.  Please find more details here - https://learn.microsoft.com/bs-latn-ba/power-bi/connect-data/desktop-trusted-third-party-connectors
