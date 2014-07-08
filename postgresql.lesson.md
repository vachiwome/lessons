#Dealing with errors while installing postgresql :

## Error :  
django.core.exceptions.ImproperlyConfigured: Cannot determine PostGIS version for database "postgres".     
GeoDjango requires at least PostGIS version 1.3. Was the database created from a spatial database template?   

## Solution:    
Add the following line to your settings.py file : "POSTGIS_VERSION = (2, 0, 3)"
