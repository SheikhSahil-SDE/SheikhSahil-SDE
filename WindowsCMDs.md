
<br>-**To check the system architecture in Windows 11 via Command Prompt, run:** ```$ wmic os get osarchitecture```
<br>-**Alternatively, use:** ```$ echo %PROCESSOR_ARCHITECTURE%```
<br>-**To check the applications installed in the system, run Win + R**: ```shell:AppsFolder```

**sfc /scannow**
<br>-Function: ```Scans and repairs corrupted or missing Windows system files.```
<br>-Details: ```Uses System File Checker (SFC) to verify the integrity of protected system files and replaces incorrect```<br>
          ```versions with correct Microsoft versions from a cached copy (typically in %WinDir%\System32\dllcache).```
<br>-Outcome: ```Fixes issues causing system instability, crashes, or errors by restoring original system files.```
<br>-Requirement: ```Must be run as an administrator in Command Prompt.```
<br>
