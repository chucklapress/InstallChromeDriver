# How to use the script

Save this code to a file named 'InstallChromeDriver.ps1' and invoke the script from PowerShell like this:  
```powershell
.\InstallChromeDriver.ps1 -ChromeDriverOutputPath .\chromedriver.exe  
```   
If you want to specify the version of Chrome yourself, add the -ChromeVersion parameter:  
```powershell  
.\InstallChromeDriver.ps1 -ChromeDriverOutputPath .\chromedriver.exe -ChromeVersion 88.0.4324.182  
```   

If you want to force the download of the driver even if the same version is already downloaded at the specified location, add the -ForceDownload parameter:  
```powershell
.\InstallChromeDriver.ps1 -ChromeDriverOutputPath .\chromedriver.exe -ForceDownload  
```



## License
[MIT](https://choosealicense.com/licenses/mit/)
