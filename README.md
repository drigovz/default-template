## Default .NET Core Template

Default template to create new .NET Core projects by CLI or Visual Studio IDE, based on Clen Architecture principles.

## Install Template
Clone this repository, and go to path **CleanArchitectureSolution** inside **TemplateDefault\working\templates\** directory. Now, you need to run the following command on terminal:

`dotnet new --install .\`

To uninstall this template, go to path **CleanArchitectureSolution** inside **TemplateDefault\working\templates\** directory, and run this command:

`dotnet new --uninstall .\`

#### CLI
To create projects with CLI, run this command:

`dotnet new cleanarchi -n <<name-of-your-project>>`

### Visual Studio IDE
To install this template on Visual Studio 2022, after you install, you need to go on menu **Tools >> Options >> Environment >> Preview Features** and check the option **Enable Previews of .NET SDK**.
