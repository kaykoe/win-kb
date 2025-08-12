# This repo contains polish programmers keyboard layout, as well as a ColemakDHk layout with polish letters, both without a dead key on '~'

to install:
```ps
cd "%userprofile%\Downloads" && curl.exe -fSsL -o win-kb.zip https://github.com/kaykoe/win-kb/archive/refs/heads/main.zip && powershell.exe -Command "Expand-Archive win-kb.zip .; Remove-Item win-kb.zip; Rename-Item win-kb-main win-kb"
```

run the setup.exe file in the desired layout's directory
