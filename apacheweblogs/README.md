Apache Weblog Analytics
=======================

Author: Ravi Krishnamurthy

This end-to-end solution helps you ingest access logs from your Apache webserver into Solr and provide dashboards. 

I used the search analytics application as an example in the LucidWorks Webinar and an accompanying eBook (http://programs.lucidworks.com/SiLK-introduction_Register.html). This directory contains another use case - Apache weblogs


The included files are:

1. Sample log file: apache\_weblog\_sample.txt
2. LogStash Configuration to grok and index Apache web access Logs: silk\_apachelog\_with\_geoip
3. Collection template for LWS used to create the collection that will hold the indexed log data: apacheaccesslogs.zip. For information on how to use collection templates, please refer to http://docs.lucidworks.com/display/lweug/Using+Collection+Templates
4. Dashboard Configuration: Apache\ Weblog\ Dashboard.json (talks directly to Solr, whether or not it is a part of LWS)



