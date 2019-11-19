## Welcome to My Site!

I do cool stuff in batch and love retro tech.

I mod a lot of different retro consoles - Mostly Gameboy's and PSP's

### Stuff im working on!

[Karla - A simple BATch Assistant](https://github.com/LiamVoid/Karla) - Includes Games, Calculator + More


Gameboy Modding Service - Contact me for more info
willrocks07@gmail.com


### A bit of Code from Karla
```markdown
:choice
set /p Name="Hi there! Im Karla a BATch assistant, Whats Your Name? "
goto:Guest

:Guest
set /P c=Hey %Name%! Are you having a good day[Y/N]?
if /I "%c%" EQU "Y" goto :Good_Day
if /I "%c%" EQU "N" goto :Bad_Day
if /I "%c%" EQU "Z" goto :Request
goto :Guest

:Bad_Day
set mytime=%time%
set /P c=Thats a shame, Hopefully I can Cheer you up! Can I tell you a joke[Y/N]?
if /I "%c%" EQU "Y" goto :Joke1
if /I "%c%" EQU "N" goto :Convo1
if /I "%c%" EQU "Z" goto :Request
goto :Bad_Day

:Convo1
set /P c=Im hungry how bout you[Y/N]?
if /I "%c%" EQU "Y" goto :Convo1EndY
if /I "%c%" EQU "N" goto :Convo1EndY
if /I "%c%" EQU "Z" goto :Request
goto :Convo1
```


<script src="https://gist.github.com/LiamVoid/42ce885968ab72d48685a5932ca45e37.js"></script>


### Support or Contact

Contact me here:
Willrocks07@gmail.com
