# chis-tools
Tools used at Channel Islands National Park that are universal enough to share on github for anyone that uses ArcGIS Pro software.


## Backup AGOL Services Tool

To use this tool, copy the item ID from AGOL for the service you want to back up.  The tool will package the service defaulted to a zipped file geodatabase, but it can also export as a shp or geojson file. 

The URL of your service in AGOL will look something like this
https://nps.maps.arcgis.com/home/item.html?id=b115ada92f0c4b7cb91ee166a6165ca2

Use the item ID for the tool as input. The tool accepts multiple item IDs. Each service entered will have its own zip file generated in the output folder.
(img/backup_tool_screenshot.png)
![Backup Tool Screenshot](img/backup_tool_screenshot.png?raw=true "Backup Tool Screenshot")