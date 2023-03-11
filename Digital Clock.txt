@echo off
Title Colck
@mode con cols=35 lines=7
color 0f
:main
cls
echo.
echo Time: %Time%
echo.
Echo Date: %Date%
echo.
ping -n 2 0.0.0.0 >nul
goto Main