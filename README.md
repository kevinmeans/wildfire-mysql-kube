# wildfire-mysql-kube
Mysql Server deployed via kubernetes.  The image will create a table for the wildfire project.  Data in this database is populated via a DAG of the Airflow Server.  The NodeJS will hit this server to fulfill front end request from the React mapbox server.
