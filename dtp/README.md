## Dynatrace AppMon 7.0 fastpack for SAP Hybris eCommerce Platform

This fastpack contains a configuration and dashboards for Dynatrace AppMon 7 for monitoring SAP Hybris ECP environments.

This latest version is compatilbe with Dynatrace AppMon 7. 16 of the 23 client dashboards have been converted into Web dashboards. 

To view the webdashboards, go to https://(YourAppMonServer):9911

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
2. Go to Dynatrace Server Settings and select _Plugins_
3. Select _Install Plugin_ and choose the *.dtp file
4. Check the installed Hybris System Profiles (y_Production and y_Staging)

