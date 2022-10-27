# chis-tools
Tools used at Channel Islands National Park that are universal enough to share on github for anyone that uses ArcGIS Pro software.


## Backup AGOL Services Tool

To use this tool, copy the item ID from AGOL for the service you want to back up.  The tool will package the service defaulted to a zipped file geodatabase, but it can also export as a shp or geojson file. The file is temporarily staged on your AGOL contents but is removed once downloaded. 

The URL of your service in AGOL will look something like this <br>
https://nps.maps.arcgis.com/home/item.html?id=b115ada92f0c4b7cb91ee166a6165ca2

Use the item ID (b115ada92f0c4b7cb91ee166a6165ca2) for the tool as input. The tool accepts multiple item IDs. Each service entered will have its own zip file generated in the output folder. <br>
![Backup Tool Screenshot](img/backup_tool_screenshot.png?raw=true "Backup Tool Screenshot")

You must be signed into AGOL (or Portal) through Pro to have access to the Item IDs entered into the tool. 

If you regularly enter the same item IDs and output folder, you can enter them as defaults.  To do that, right click on the tool in the Catalog Pane in Pro and go to the tool Properties. Under the Parameters section, enter item IDs separated by a semicolon with no spaces in between. Paste in the catalog path into the Output Folder default. <br>

Example default parameters:<br>
![Default params screenshot](img/backup_defaults.png?raw=true "Backup Tool Defaults")

Example tool output messages:<br>
![Messages screenshot](img/backup_output_messages.png?raw=true "Backup Tool Defaults")

Example tool file output:<br>
![File output](img/backup_output_files.png?raw=true "Backup Tool File Output")
