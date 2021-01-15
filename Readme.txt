=== myCoffee.bat checks if file exists then file is deleted 
@echo off
SET MYFILE="C:\Apps\TOC\myCoffee.html"
IF EXIST %MYFILE% DEL /F %MYFILE%

powershell.exe -ExecutionPolicy Bypass -File C:\Apps\TOC\myCoffee.ps1
echo Your Coffee is Ready :-)
echo Your Coffee is Ready :-)
echo Your Coffee is Ready :-)
exit

=== after myCoffee.ps1 is completed - the newly created myCoffee.html is opened in the default browser.
