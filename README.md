Convert PDF survey to ISO19139
==============================


# How to install ?

* Download https://github.com/titellus/workspace-pdfsurvey-to-iso19139/archive/master.zip
* Download Talend Open Studio 5.4.1 for Data Integration http://www.talend.com/download/data-integration
* Download Talend Spatial http://sourceforge.net/projects/sdispatialetl/files/sdispatialetl/
* Install TDI
* Unzip tAdvancedFileOutputXML components (from the Spatial module ZIP) in the TDI folder plugins/org.talend.designer.components.localprovider_5.4.1/components (as far as https://jira.talendforge.org/browse/TDI-26630 is not added to TDI source code).
* Launch TDI
* Import the workspace



# How to run ?


* Configure the context:
 * the folder where CSV file are
 * the folder where metadata record should be generated
 * the CSW server URL, username and password
