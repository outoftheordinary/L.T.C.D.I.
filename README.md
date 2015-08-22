@echo off
color 0a
title L.T.C.D.I

:main 
cls
echo   *********
echo //Main Menu\\
echo   *********
echo 1. Roblox
echo 2. computer drawing
echo.
echo -----------
set/p menu=))
if not defined menu goto main
if %menu%==1 (
set menu=
start http://www.roblox.com/
goto main
)
if %menu%==2 (
set menu=
start D:\Vishesh\
call the chose one.py
goto main 
)


