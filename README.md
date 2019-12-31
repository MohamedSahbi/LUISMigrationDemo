# LUISMigrationDemo
## Description
LUIS application sample used in my blog post "LUIS Migration – False Error Message: Module {..} already exists".
## How to use it?
There are 2 application under Solution folder:
- Import wrongApplication.json to LUIS portal to retrace the error "BadArgument: The models: { BookFlight } already exist in the specified application version.".

- Import correctApplication.json to LUIS portal. Then, go to the build part of the application. Try to add an intent with the a name of an exisitng entity or the other way around. The error message will appear. 
