## Dynatrace fastpack for SAP Hybris eCommerce Platform

This fastpack contains a configuration and dashboards for Dynatrace AppMon for monitoring SAP Hybris ECP environments.

Visit [the Dynatrace Community page](http://bit.ly/hybrisapm) for more details and howto use the fastpack

It provides following capabilities:
* automatic detection of different page types
* automatic detection and monitoring of CronJobs
* detection of external webservices and webrequests
* impact analysis of external systems
* database usage and impact of individual page types
* end-user experience monitoring
* loadbalancing validation and system monitoring
* business dashboards for orders and revenue in multi-currencies

### How to Install the Binary Fastpack (*.dtp)

1. Open the Dynatrace Client and connect to a Dynatrace Server
2. Go to Dyantrace Server Settings and select _Plugins_
3. Select _Install Plugin_ and choose the *.dtp file
4. Check the installed Hybris System Profiles (y_Production and y_Staging)

### Customizing the Fastpack

1. Download the source package
2. Get Apache Ant
3. Edit _fastpack.properties_ and change settings (alternatively you can use -Dproperty.name on the ant command)
4. run ant
5. either install the generated fastpack (in the _dist_ directory) manually or use the deploy target in the build script

