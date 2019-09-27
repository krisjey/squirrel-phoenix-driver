# Phoenix thick driver for squirrel client
This driver is used for Squirrel Sql client for Thick driver.

## Create phoenix thick driver jar package for SQuirreL SQL Client.
The driver version is depends on version of Phoenix query server and Hbase version.

So, If you want to use it before, check your HBase version and then change dependencies in build.gradle file.

### After that add jars to "Extra Class Path" and then use below zookeeper URL.
<pre>
jdbc:phoenix:youserver1,youserver2,youserver3:2181:/hbase-unsecure
</pre>

## Tested product versions.
HDP 3.1<br/>
HBase 2.0.2<br/>
phoenix-5.0.0.3.1.0.0-78<br/>
