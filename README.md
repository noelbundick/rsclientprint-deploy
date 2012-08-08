SSRS Client Print Control Installer
====================

This Visual Studio Setup Project produces an .msi that can be used to deploy the SQL Server Reporting Services Client Print Control to computers without the need for administrative permissions.

The .dll files to be deployed will need to be extracted from the .cab on the server and added to the project.

Instructions
--------------------
Extract RSClientPrint-x86.cab into the project folder

By default located at:

    C:\Program Files\Microsoft SQL Server\MSRS11.MSSQLSERVER\Reporting Services\ReportServer\\bin\RSClientPrint-x86.cab

Build the solution

Presto! An .msi that can be deployed using Group Policy, SCCM, etc.