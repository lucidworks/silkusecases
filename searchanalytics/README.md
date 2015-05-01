Search Analytics
============

This end-to-end solution helps you build dashboards on your user search logs--generated from your search application powered by Solr.

The following files are included:

1. LogStash Configuration to grok and index Solr Logs: silk\_solrlogs.conf (use if our search application is on Solr and does not use LWS)
3. Solr schema and config for the collection that will hold the indexed log data: solrsearchlogs directory (use if your search analytics dashboard is powered by Solr but not LWS)
5. Dashboard Configuration: SearchAnalyticsDashboard.json (talks directly to Solr, whether or not it is a part of LWS)



