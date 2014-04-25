Search Analytics
============

This end-to-end solution helps you build dashboards on your user search logs--generated from your search application powered by Solr or by LucidWorks' commercial product LucidWorks Search (LWS).

A full description of the how to set up your search analytics dashboards is available through a LucidWorks Webinar (http://programs.lucidworks.com/SiLK-introduction_Register.html) and an accompanying document.

Our users may be running Solr or LWS for their existing search application. The logs may be indexed into Solr or LWS in order to power the search analytics dashboard. We have provided configurations for all permutations of the above possibilities.

The included files are:

1. LogStash Configuration to grok and index Solr Logs: silk\_solrlogs.conf (use if our search application is on Solr and does not use LWS)
2. LogStash Configuration to grok and index LWS logs: silk\_lwslogs.conf (use if our search application uses LWS)
3. Solr schema and config for the collection that will hold the indexed log data: solrsearchlogs directory (use if your search analytics dashboard is powered by Solr but not LWS)
4. Collection template for LWS used to create the collection that will hold the indexed log data: lwsearchlogs.zip (use if your search analytics dashboard is powered by Solr within LWS)
5. Dashboard Configuration: SearchAnalyticsDashboard.json (talks directly to Solr, whether or not it is a part of LWS)



