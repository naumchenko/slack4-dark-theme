# slack4 dark theme with green like terminal/matrix colors. 
(hack and edit colors with find/replace all)

Theme Name: youWantItDarker




```
Works for Slack 4.0.2
!!! On every update pushed by Slack, "local-settings.json" and "lato.less", i.e on everyupdate repeat the 2 steps.
```

For MacOS open Terminal and execute commands:

1) Edit file, change bootsonic value ("bootSonic":"never").

``` open ~/Library/Application\ Support/Slack/local-settings.json ```

2) Get the modified lato.less file.

``` curl https://raw.githubusercontent.com/naumchenko/slack4-dark-theme/master/lato.less | tee /Applications/Slack.app/Contents/Resources/app.asar.unpacked/dist/static/lato.less ```
