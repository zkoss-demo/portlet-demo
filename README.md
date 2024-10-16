# Overview
A simple portlet example. 
According to [Deploying WARs](https://learn.liferay.com/w/dxp/liferay-development/reference/deploying-wars-wab-generator?p_l_back_url=%2Fsearch%3Fq%3Dliferay-plugin-package.properties&p_l_back_url_title=Search&highlight=liferay-plugin-package.properties), we don't have to deploy an OSGi bundled for making a portlet. This example doesn't use OSGi bundle and include standdard zk jar.

# Liferay Portal
We use 7.4.3.125-ga125 as the target portal.

Download from [here](https://www.liferay.com/downloads-community)

## How to deploy
1. build war with `mvn clean package`
2. copy to [LIFERAY_HOME]/deploy

## Start, Stop

`./liferay-dxp-version/tomcat-version/bin/startup.sh`

`./liferay-dxp-version/tomcat-version/bin/shutdown.sh`

# Reference
* [Liferay 7.4.3.112-ga112 XML DTD Document](https://resources.learn.liferay.com/reference/latest/en/dxp/definitions/index.html)
* [portlet.xml xsd](https://docs.liferay.com/portlet-api/3.0/portlet-app_3_0.xsd)