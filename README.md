# nosql-challenge

Before running this code, you need to import the JSON from located in the resources folder.

Use the command below in your git bash or powershell while in the folder with the JSON file.


mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json


Also make sure to active conda dev