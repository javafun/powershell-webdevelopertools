PowerShell modules and few scripts to help your life as a .NET web developer

You can set the modules to certain directory and use the example profile file to load them or you can install modules with Ed Wilson's great copy_modules.ps1 script, which can be found here:
http://arcanecode.com/2014/02/20/installing-windows-powershell-modules-on-multiple-users-computersupdated/

Functionalities that can be found at this repository

### General:
- Chocolatey installation script for new machine
- Load visualstudio tools to PowerShell runtime 

### IIS Specific:
- List all IIS websites on current machine
- Create a new IIS website, application pool and bindings
- Install certificates for website usage
- Test that machine is ready to run website in IIS
- Installing stuff with WebPI

### server specific:
- Enabling windows features
- Installing stuff silently with exe and msi files