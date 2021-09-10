# 74875458
@echo off
set m=%date:~0,4%%date:~5,2%%date:~8,2%

xcopy D:\FFOutput\*.* D:\2345Downloads\%m% /s /e /i /y
