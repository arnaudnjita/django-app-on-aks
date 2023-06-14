# Django and PostgreSQL sample for Azure App Service

This samples is a simple Django app that connects to a PostgreSQL database. The sample is used in the tutorial https://learn.microsoft.com/azure/postgresql/flexible-server/tutorial-django-app-service-postgres](Deploy Django app with App Service and Azure Database for PostgreSQL - Flexible Server).

When deployed to Azure App Service, the database connection information is specified via environment variables `DBHOST`, `DBPASS`, `DBUSER`, and `DBNAME`. This app always uses the default PostgreSQL port. See the tutorials for more information.

