# ConentProviderExample
Creating custom content provider which to access database and share between other apps; 

AppProvider - custom content provider, managing basic crud operations.

AppDatabase - singleton class to create database, table... and upgrade it to new version.

XxxContract - a class for containing static constants and static methods for the content provider.

Don't forget to define the provider configurations on the Manifest.xml file.
