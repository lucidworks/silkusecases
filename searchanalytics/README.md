Search Analytics
============

This end-to-end solution helps you build dashboards on your user search logs--generated from your search application powered by Solr.

The following files are included:

1. LogStash Configuration to grok and index Solr Logs: silk\_solrlogs.conf 
3. Solr schema and config for the collection that will hold the indexed log data: solrsearchlogs directory
5. Dashboard Configuration: SearchAnalyticsDashboard.json (talks directly to Solr, could go through Fusion as well)



