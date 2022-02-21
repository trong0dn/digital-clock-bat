# digital-clock-bat
Short bash script for a digital clock on a batch executable.

```
:: MyDigitalClock.bat
@echo off
Title Digital Clock
@mode con cols=30 lines=7
color 00
:main
cls
echo.
echo Time: %time%
echo.
echo Date: %date%
echo.
ping -n 2.0.0.0 > nul
goto main
```

## Display

![digital_clock](https://user-images.githubusercontent.com/55768917/154993741-8a95a26f-d400-4883-ad8b-82f364e3304d.png)
