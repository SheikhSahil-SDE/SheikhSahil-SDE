
# Terminal CMDs

- **To check the system architecture in Windows 11 via Command Prompt, run:** $ ```wmic os get osarchitecture```

- **Alternatively, use:** $ ```echo %PROCESSOR_ARCHITECTURE%```

- **To check the applications installed in the system, run Win + R**: ```shell:AppsFolder```

# **sfc /scannow**

- Function: ```Scans and repairs corrupted or missing Windows system files.```
- Details: ```Uses System File Checker (SFC) to verify the integrity of protected system files and replaces incorrect versions with correct Microsoft versions from a cached copy (typically in %WinDir%\System32\dllcache).```
- Outcome: ```Fixes issues causing system instability, crashes, or errors by restoring original system files.```
- Requirement: ```Must be run as an administrator in Command Prompt.```

# Yt-dlp

- **yt-dlp is a feature-rich, command-line audio/video downloader that supports thousands of websites, including YouTube and Vimeo**
- **Usage:** $ ```yt-dlp [OPTIONS] URL [URL...]```
- **For example, users can download audio only with** ```--extract-audio --audio-format mp3.```
- **It also supports downloading playlists with options like** ```--ignore-errors --continue --no-overwrites``` **to resume interrupted downloads.**

