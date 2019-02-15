# TA_officescan

This TA for Splunk provide fields extractions from Trend Micro OfficeScan logs and mapping to the Malware CIM.

## Trend Micro OfficeScan TA for Splunk. Fields extractions and CIM mapping

## Author Information
Original author: UnderDefense LLC
Version: 1.0.0

## Updates history:
[1.0.0]
- Initial release
- Fields extractions
- CIM Malware mapping

## Configurations: 
- Install this TA from splunkbase or manually on your search heads, indexers and heavy forwarders.
- Configure port listening in Data Inputs or manually in inputs.conf. Set sourcetype to "officescan"
- Go to Settings - Advanced Search - Search macros and change definition of "officescan_index" macros to index with your OfficeScan logs(you can do it making changes in macros.conf
- Go to Search and Reporting. Use `officescan_index` search query to get your data.
- Enjoy!

## Email support during weekday from 08:00 to 16:00 by UTC time

## Contact information: 
dzh@underdefense.com
ds@underdefense.com
