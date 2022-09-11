```powershell
reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\YandexBrowser" /v BackgroundModeEnabled /t REG_DWORD /d 0 /f
reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\YandexBrowser" /v CrashesReporting /t REG_DWORD /d 0 /f
reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\YandexBrowser" /v DefaultBrowserSettingEnabled /t REG_DWORD /d 0 /f
reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\YandexBrowser" /v DisableScreenshots /t REG_DWORD /d 1 /f
reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\YandexBrowser" /v DistrStatisticsReporting /t REG_DWORD /d 0 /f
reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\YandexBrowser" /v NtpAdsDisabled /t REG_DWORD /d 1 /f
reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\YandexBrowser" /v NtpContentDisabled /t REG_DWORD /d 1 /f
reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\YandexBrowser" /v StatisticsReporting /t REG_DWORD /d 0 /f
reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\YandexBrowser" /v SyncDisabled /t REG_DWORD /d 1 /f
reg add "HKEY_LOCAL_MACHINE\SOFTWARE\Policies\YandexBrowser" /v UpdateAllowed /t REG_DWORD /d 0 /f
```
