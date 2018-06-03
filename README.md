This is a very first version of Sample Application for ASD Data Center API

#DOCUMENTATION


##Installation

Right click on your project and select "Open Module Settings".

* Right click on your project and select "Open Module Settings".
* Click the "+" button in the top left corner of window to add a new module.
* Select "Import .JAR or .AAR Package" and click the "Next" button.
* Find the AAR file using the ellipsis button "..." beside the "File name" field.
* Keep the app's module selected and click on the Dependencies pane to add the new module as a dependency.
* Use the "+" button of the dependencies screen and select "Module dependency".
* Select the module and click "OK".


##Objects

There are a few class that are created for the purpose of storing data from API

* Child
* Examination
* Question
* CareerType
* Domain
* Extra Info


##Download/Upload and parsing data

* JsonDownloader

###Some functions:

*public static Examination parseSingleExamination(String url)

The url is defined in Domain class (static variable)


