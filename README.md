#Sitecore Habitat Project Visual Studio Template
This is the "Project" version of my Sitecore Habitat Feature template (https://github.com/ekapus/SitecoreHabitatFeatureTemplate).

The src folder contains the source project that I used to create the Visual Studio template. The Sitecore Habitat Project (Website) Visual Studio Template.zip file contains the template that can be installed in visual studio.

##Project Template Installation Instructions

1. Download Sitecore Habitat Project (Website) Visual Studio Template.zip from https://github.com/ekapus/SitecoreHabitatProjectTemplate
1. Copy the zip file to to C:\Users\Administrator\Documents\Visual Studio 2015\Templates\ProjectTemplates\Visual C#\ on your local machine.
1. Run the following command from the Visual Studio Command Line (accessed from the start menu at Visual Studio 2015/Developer Command Prompt For Visual Studio 2015:
```
devenv /installvstemplates
```
_Note: this can be done while Visual Studio is running._

For more info about finding, organizing and installing Visual Studio Project Templates: https://msdn.microsoft.com/en-us/library/y3kkate1.aspx

##Project Template Use Instructions

1. Create a new solution folder in your Habitat Solution under "Project" that describes the site you're creating.
1. Right click on the new solution folder, choose add, and select "New Project".
1. Scroll through the project types and select "Sitecore Habitat Project (Website)".
1. Enter a name for your Project. It's best to omit spaces and punctuation.
1. Using windows explorer, create a folder that matches your solution folder name under "Your Habitat Project Root\src\Project"
1. Under the folder you just created, create a "code" and a "serialization" folder.
1. Choose the code folder you just created as the location for the project you're creating.
1. Hit OK
1. Open your new project.
1. Rename /Views/$safeprojectname$ Website to /Views/YourProjectName Website
