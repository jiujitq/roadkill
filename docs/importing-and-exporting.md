# Importing and Exporting

## Importing
Roadkill currently has one option for importing existing content, which is from a Screwturn 2/3 installation. Future versions of Roadkill will include a REST API for importing data, but for now this is the only import option.

To import from a Screwturn database, you need to login as an administrator and head to the site settings->tools page. From here, enter your Screwturn database connection string (non-database installations aren't supported) and the tool will import the content including page history and categories into your Roadkill instance.

## Exporting
Roadkill supports 4 types of exporting:

- Exporting all content as a SQL file
- Exporting pages and content as an XML file
- Exporting all image/media uploads
- Exporting each page as text (.wiki) file.

You need to login as an administrator and head to the site settings->tools page to export. The last three export types will supply you with the content in .zip format, the .wiki text file export will include the page tags at the top of the file and then the content itself.