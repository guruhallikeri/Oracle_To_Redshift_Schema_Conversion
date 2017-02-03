# Oracle_To_Redshift_Schema_Conversion
This .SQL script will convert the DDLs of oracle schema to Redshift
Even though there are multiple tools available out there for convertion, this will be option for POC or Test environments;

#Steps to execute
1. Replace the {Schema Name} with your Oracle schema
2. Replace the {Table1, Table2 etc} with actual table names
3. Select all and execute

This will generate the create statements for Redshift datastore, same can be executed on the Redshift cluster.
