# MandG-WeatherApplication

Development:
Developed an application which consists of following projects.
Web App: Created WeatherInformation controller to read the data of the uploaded file.
Middleware: To handle the city list. Get & read the city identifiers from the dummy file 'city.list.json' available in 'Input' folder & generate the new file once weather is received from the external API. 
External Resources: To get the weather from the http://api.openweathermap.org/

Assumption: 
List of cities file received by the application will be text file(.txt). 
Cities will be listed on each row one below the another (Please refer to the sample file which is available in SampleInput\Cities.txt)
Please use Cities.txt file while executing 'WeatherInformation' action method.

Execution: 
Once the swagger page is loaded, please upload Cities.txt file available in 'SampleInput' folder
Application will read cities from the Cities.txt file and will get the identifiers for those cities from dummy master file 'city.list.json'.
It will further call the http://api.openweathermap.org (external API) and get the weather information.
Once the weather information is received, application creates new file for each city with todays date appended in the file name (eg Dublin_12-12-2024) and it's stored in 'Output' folder.
