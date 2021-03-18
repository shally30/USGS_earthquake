# USGS_earthquake
# Step 1: Download the JSON data from USGS
## 1.1 install "wget" in terminal(mac), just google how to install it
## 1.2 put the code below in the terminal in mac to get the JSON file
wget -O earthquake-all.json https://earthquake.usgs.gov/fdsnws/event/1/query\?format\=geojson\&starttime\=1900-01-01\&endtime\=2021-03-18\&minmagnitude\=6

# Step 2: Using the HW.ipynb to change the JSON file into CSV.
## 2.1 Guideline: https://github.com/hupili/python-for-data-and-media-communication-gitbook/blob/master/notes-week-06.md#use-api-via-http-request-response
## 2.2 Check the features what you want via JSONView: https://earthquake.usgs.gov/fdsnws/event/1/query?format=geojson&starttime=1900-01-01&endtime=2021-03-17&minmagnitude=6
