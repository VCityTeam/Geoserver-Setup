# Geoserver-Setup
A tool used to upload data in a running geoserver. Currently shapefiles only

## How to run

- setup environment variables
   - GEOSERVER_SOCKET_HOST=geoserver
   - GEOSERVER_SOCKET_PORT=8080
   - GEOSERVER_WORKSPACE=cite
   - GEOSERVER_MAX_CONNECTION_ATTEMPTS=20
   - GEOSERVER_TIME_CONNECTION_ATTEMPTS=5
   - GEOSERVER_CATALOG_ADDRESS=http://geoserver:8080/geoserver/rest
   - DATA_IMPORT_DIR=<Your_Data_Folder>

 - either create a folder and store your data in it or give the path to an existing folder on your computer.

```
pip install --no-cache-dir -r requirements.txt
```

```
python -u python_setup.py
```
