# MVC_Start
Created starting point for MVC project

This is a usable starting template for an MVC core web application project that Microsoft should have provided with Visual Studio. Tested with Visual Studio 15.5.4.

This updates the empty MVC core web application template with the following changes:

Added folder hierarchy to wwwroot folder - css, img, js, lib
Added Controllers, Models, Views folders
  - and added basic content
    - copied the ViewStart and Layout cshtml files from the MVC template  
    - simplified Layout.cshtml by removing references to bootstrap etc
Added appsettings and bundleconfig files
  - copied from the MVC template
Updated Startup.cs class
  - to include MVC services
    - using the MVC template as the reference
